# FinTrack - Personal Finance Tracker

A full-stack MERN Finance Tracker with Dashboard, Expenses, Split Bills, Lend/Borrow Management, Goals Tracking, and Analytics.

---

##  Tech Stack

### Frontend
- React.js
- React Router
- Recharts
- Axios

### Backend
- Node.js
- Express.js

### Database
- MongoDB (Mongoose)

### Authentication
- JWT
- bcryptjs

---

##  Project Structure

```text
fintrack/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   └── .env
│
└── frontend/
    └── src/
        ├── pages/
        ├── components/
        ├── context/
        └── utils/
```

---


##  Features

| Feature | Description |
|----------|-------------|
| Authentication | Secure Register/Login using JWT |
| Dashboard | Balance Overview, Charts, Recent Transactions |
| Expenses | Add/Delete Income & Expenses |
| Split Bills | Split Bills and Track Payments |
| Lend/Borrow | Manage Lent and Borrowed Money |
| Goals | Create Savings Goals and Track Progress |
| Analytics | Monthly Trends and Category Insights |

---

##  API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | `/api/auth/register` | Register User |
| POST | `/api/auth/login` | Login User |
| GET | `/api/expenses` | Get All Expenses |
| POST | `/api/expenses` | Add Expense |
| DELETE | `/api/expenses/:id` | Delete Expense |
| GET | `/api/splits` | Get All Splits |
| POST | `/api/splits` | Create Split |
| PUT | `/api/splits/:id/member/:mid` | Toggle Member Payment Status |
| GET | `/api/lendborrow` | Get Records |
| POST | `/api/lendborrow` | Add Record |
| PUT | `/api/lendborrow/:id/settle` | Settle Record |
| GET | `/api/goals` | Get Goals |
| POST | `/api/goals` | Create Goal |
| PUT | `/api/goals/:id` | Update Goal |

---

##  Future Improvements

- Dark Mode
- Export Reports
- Budget Alerts
- Recurring Transactions
- Mobile Responsive UI

---

##  Author

Developed  using the MERN Stack.

⭐ If you like this project, consider giving it a star.