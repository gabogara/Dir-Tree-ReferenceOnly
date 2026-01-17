# Money Mentor

## Front-end

```text
money-mentor-front-end/
├── index.html
├── vite.config.js
├── package.json
├── .env
├── .gitignore
├── public/
└── src/
    ├── assets/
    │   └── logo.svg
    ├── components/
    │   ├── NavBar/
    │   │   └── NavBar.jsx
    │   ├── SignUpForm/
    │   │   └── SignUpForm.jsx
    │   ├── SignInForm/
    │   │   └── SignInForm.jsx
    │   ├── Landing/
    │   │   └── Landing.jsx
    │   ├── Dashboard/
    │   │   └── Dashboard.jsx
    │   ├── TransactionList/
    │   │   └── TransactionList.jsx
    │   ├── TransactionDetails/
    │   │   └── TransactionDetails.jsx
    │   ├── TransactionForm/
    │   │   └── TransactionForm.jsx
    │   └── MonthSummary/
    │       └── MonthSummary.jsx
    ├── contexts/
    │   └── UserContext.jsx
    ├── services/
    │   ├── authService.js
    │   ├── transactionService.js
    │   ├── summaryService.js
    │   └── userService.js
    ├── App.jsx
    ├── main.jsx
    ├── App.css
    └── index.css

```

## Back-end
```text
money-mentor-back-end/
├── server.js
├── package.json
├── package-lock.json
├── .env
├── .gitignore
├── controllers/
│   ├── auth.js
│   ├── test-jwt.js
│   ├── users.js
│   ├── transactions.js
│   └── summary.js
├── middleware/
│   └── verify-token.js
└── models/
    ├── user.js
    ├── transaction.js
    └── category.js
```