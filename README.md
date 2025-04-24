# Node CLI Contacts 📒

This command-line application allows you to easily manage your contacts directly from the terminal: add, view, search, and delete contacts.

## 🛠️ Technologies Used

- Node.js
- Commander
- Nanoid
- FS (File System)

## 🚀 Installation & Usage

### Step 1. Clone the repository

```bash
git clone https://github.com/<your-username>/goit-node-cli.git
cd goit-node-cli
```

### Step 2. Install dependencies

```bash
npm install
```

### Step 3. Run commands

#### View all contacts

```bash
node src/index.js --action list
```

#### Get a contact by ID

```bash
node src/index.js --action get --id <contactId>
```

#### Add a new contact

```bash
node src/index.js --action add --name "Mango" --email "mango@gmail.com" --phone "322-22-22"
```

#### Remove a contact

```bash
node src/index.js --action remove --id <contactId>
```

## 📂 Project Structure

```
goit-node-cli
├── package.json
├── src
│   ├── db
│   │   └── contacts.json
│   ├── contacts.js
│   └── index.js
└── README.md
```
