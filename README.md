# ICP Workshop
## **PhoneBook and Message History**

This Motoko project implements an actor to manage a phone book and message history.

#### Features:
- **PhoneBook:** Add and retrieve phone entries (`Name -> Entry`).
- **Message History:** Send and query messages (`Phone -> Message`).

#### Usage:
- **Insert Entry:** `insert(name: Name, entry: Entry)`
- **Get Entry:** `getPhone(name: Name): ?Entry`
- **Send Message:** `sendMessage(senderPhone: Phone, message: Message)`
- **View Sent Messages:** `sentMessages(senderPhone: Phone): ?Message`

#### Data Types:
- `Entry`: `{ desc: Text; phone: Phone }`
- `Message`: `{ receiver: Text; message: Text }`
