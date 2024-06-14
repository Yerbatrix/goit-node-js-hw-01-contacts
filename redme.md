# CLI Contacts Application

This is a CLI application for managing contacts. The application allows you to list, add, get, and remove contacts.

## Installation

1. Clone the repository.
2. Run `npm install` to install dependencies.

## Scripts

- `npm start` - Run the application using Node.js.
- `npm run start:dev` - Run the application using nodemon.

## Usage

### List all contacts

```sh
node index.js --action list
```

Get a contact by ID
node index.js --action get --id <ID>

Add a contact
node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22

Remove a contact
node index.js --action remove --id <ID>

link - https://monosnap.com/file/T5pHTP2xY1PSYQzaHeEUxEaBuaHhF5
