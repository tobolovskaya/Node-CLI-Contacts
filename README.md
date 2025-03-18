# GoIT Node CLI Contacts 📒

Цей консольний додаток дозволяє легко керувати контактами з командного рядка: додавати, переглядати, шукати і видаляти контакти.

## 🛠️ Технології

- Node.js
- Commander
- Nanoid
- FS (File System)

## 🚀 Встановлення та запуск

### Крок 1. Клонувати репозиторій

```bash
git clone https://github.com/<your-username>/goit-node-cli.git
cd goit-node-cli
```

### Крок 2. Встановити залежності

```bash
npm install
```

### Крок 3. Запуск команд

#### Переглянути всі контакти

```bash
node src/index.js --action list
```

#### Знайти контакт за id

```bash
node src/index.js --action get --id <contactId>
```

#### Додати новий контакт

```bash
node src/index.js --action add --name "Mango" --email "mango@gmail.com" --phone "322-22-22"
```

#### Видалити контакт

```bash
node src/index.js --action remove --id <contactId>
```

## 📂 Структура проєкту

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
