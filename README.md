# Deen Ledger

Debt tracking app using the original Deen Ledger UI. Accounts, people, balances, and history are saved on the server.

## Run

```bash
npm install
copy .env.example .env
npm start
```

Open [http://localhost:3000](http://localhost:3000).

## Features

- Sign up / log in (password is hashed)
- Add people as **Deen** or **I Owe**
- Star people on Home
- Add or settle amounts from a person page
- All transactions list
- English / Somali
- Profile photo upload
- SQLite database in `data/deen-ledger.db`

Data is per account. Log out and log back in to see the same records.
