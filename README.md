# React Homework Module 1

## Description

This project was created as part of the GoIT Neoversity React course (Module 1: Components and Styling).

The application consists of three React components:

- `Profile` — displays a user's social network profile.
- `FriendList` — displays a list of friends and their online status.
- `TransactionHistory` — displays a table of transaction history.

All data is stored in separate JSON files and passed to components via props.

## Technologies Used

- React
- Vite
- JavaScript (ES6+)
- CSS Modules

## Project Structure

```text
src/
│
├── components/
│   ├── Profile/
│   │   ├── Profile.jsx
│   │   └── Profile.module.css
│   │
│   ├── FriendList/
│   │   ├── FriendList.jsx
│   │   └── FriendList.module.css
│   │
│   ├── FriendListItem/
│   │   ├── FriendListItem.jsx
│   │   └── FriendListItem.module.css
│   │
│   └── TransactionHistory/
│       ├── TransactionHistory.jsx
│       └── TransactionHistory.module.css
│
├── userData.json
├── friends.json
├── transactions.json
│
├── App.jsx
├── main.jsx
└── index.css
```

## Features

### Profile

Displays:

- User avatar
- User name
- Social media tag
- Location
- Statistics:
  - Followers
  - Views
  - Likes

### Friend List

Displays:

- Friend avatar
- Friend name
- Online/Offline status

Status colors:

- Green — Online
- Red — Offline

### Transaction History

Displays transaction data in a table:

- Type
- Amount
- Currency

## Installation

Clone the repository:

```bash
git clone https://github.com/SwissLana/goit-neo-react-hw-module1.git
```

Navigate to the project folder:

```bash
cd goit-neo-react-hw-module1
```

Install dependencies:

```bash
npm install
```

Run the project locally:

```bash
npm run dev
```

## Links

- GitHub Repository: https://github.com/SwissLana/goit-neo-react-hw-module1.git

## Author

Lana Huerzeler

GoIT Neoversity — React Module 1 Homework