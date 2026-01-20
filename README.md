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
    ├── styles/
    │   └── components.css
    ├── components/
    │   ├── NavBar/
    │   │   └── NavBar.jsx
    │   ├── Auth/
    │   │   ├── SignUpForm.jsx
    │   │   └── SignInForm.jsx
    │   ├── Landing/
    │   │   └── Landing.jsx
    │   ├── Dashboard/
    │   │   ├── Dashboard.jsx
    │   │   ├── MonthSelector.jsx
    │   │   ├── MonthSummary.jsx
    │   │   └── TransactionList.jsx
    │   ├── Transactions/
    │   │   ├── TransactionDetails.jsx
    │   │   ├── TransactionForm.jsx
    │   │   └── TransactionRow.jsx
    │   └── Mentor/                      (Stretch)
    │       ├── MentorDashboard.jsx
    │       ├── PointsBadge.jsx
    │       ├── LevelProgress.jsx
    │       ├── MentorMessageCard.jsx
    │       ├── GoalList.jsx
    │       └── GoalCard.jsx
    ├── contexts/
    │   └── UserContext.jsx
    ├── services/
    │   ├── authService.js
    │   ├── transactionService.js
    │   ├── summaryService.js
    │   ├── categoryService.js
    │   └── userService.js
    │   └── mentorService.js             (Stretch)
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
│   ├── users.js
│   ├── transactions.js
│   └── categories.js
│   └── goal.js                    (Stretch)
├── routes/
│   ├── auth.routes.js
│   ├── users.routes.js
│   ├── transactions.routes.js
│   └── categories.routes.js
│   └── goal.routes.js                    (Stretch)
├── middleware/
│   └── verify-token.js
└── models/
    ├── user.js
    ├── transaction.js
    └── category.js
│   └── goal.js                   (Stretch)
```
