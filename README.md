# RestroBot

**RestroBot** is a restaurant automation platform designed to simplify digital ordering and restaurant operations through Telegram-based ordering and a centralized management dashboard.

The platform helps restaurants manage menus, orders, customers, notifications, and cashier operations from one system.

# Features

* Telegram-based ordering
* Restaurant management dashboard
* Cashier dashboard
* Real-time order notifications
* Menu management
* Order management
* Customer management
* Restaurant onboarding system
* Subscription & billing system
* Telegram dynamic synchronization
* Arabic-first and RTL-friendly interface
* Responsive dashboard

# Technologies

* React 19
* TypeScript
* Tailwind CSS 4
* shadcn/ui
* Vite
* Node.js
* Express.js
* tRPC
* MySQL
* Supabase
* Telegram Bot API

# Project Structure

```text
restrobot/
├── client/
│   ├── components/
│   ├── pages/
│   └── ...
├── server/
│   ├── routers/
│   ├── services/
│   └── ...
├── database/
│   └── migrations/
├── public/
├── .env
├── package.json
├── tsconfig.json
└── README.md
```

# Getting Started

## 1. Clone the repository

```bash
git clone <repository-url>
cd restrobot
```

## 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file and add the required configuration:

```env
DATABASE_URL=
TELEGRAM_BOT_TOKEN=
```

Add any additional environment variables required by the project.

### 4. Run the development server

```bash
npm run dev
```

The application will be available on the local development URL shown in the terminal.

## Production Build

```bash
npm run build
```

Then start the production server using the project's configured start command.

## Target Users

RestroBot is built for:

* Restaurants
* Cafés
* Fast-food businesses
* Small and medium-sized food businesses
* Restaurant owners who want to automate ordering and operations

## Project Goal

The goal of RestroBot is to reduce manual restaurant operations by connecting **customers, Telegram ordering, restaurant staff, and management** in one automated platform.

##  License

This project is licensed under the **MIT License**.
