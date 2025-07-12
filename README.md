# 💸 Velza Wallet System

Velza is a scalable full-stack digital wallet platform that allows users to securely transfer money, withdraw funds to their bank accounts, and receive money from banks via webhooks. Built with **Next.js**, **Prisma**, **PostgreSQL**, **TailwindCSS**, and **Turborepo**, it’s a clean and production-ready fintech foundation.

---

## 🚀 Features

- 🔐 Secure wallet-to-wallet money transfers
- 🏦 Withdraw wallet balance to user's linked bank account
- 📥 Handle incoming money via webhook from external banks
- ✅ Transaction-safe wallet updates using Prisma + PostgreSQL
- 💅 Clean, responsive UI powered by TailwindCSS

---

## 🧱 Tech Stack

| Layer        | Technology                                    |
|--------------|-----------------------------------------------|
| Frontend     | **Next.js (App Router)** + TailwindCSS        |
| Backend      | **Next.js API Routes**, **Express.js**        |
| Database     | **PostgreSQL**                                |
| ORM          | **Prisma**                                    |
| Dev Infra    | **Turborepo** (monorepo for FE/BE separation) |

---

## 🔥 Core Flows Handled

| Flow                    | Description                                      |
|-------------------------|--------------------------------------------------|
| 💸 Send Money           | Transfer money between Velza wallet users        |
| 🏦 Withdraw to Bank     | Users withdraw wallet balance to their bank      |
| 📨 Bank Webhooks        | Handle POST webhook from banks to credit wallet  |

---

---

## 🛠 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/velza-wallet.git

cd velza-wallet

npm install

npx prisma migrate dev

npm run dev
```
## made with  ❤️
Engineered by *YashRawatTechnology*
Simplifying complex financial operations with scalable and production-grade code.



