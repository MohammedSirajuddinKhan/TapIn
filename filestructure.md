club-attendance-app/
│
├── app.js
├── package.json
├── package-lock.json
├── .env
├── .gitignore
├── README.md
│
├── config/
│   ├── db.js
│   └── passport.js
│
├── controllers/
│   ├── authController.js
│   ├── attendanceController.js
│   ├── adminController.js
│   └── dashboardController.js
│
├── models/
│   ├── User.js
│   ├── Session.js
│   ├── Attendance.js
│   └── ClubMember.js
│
├── routes/
│   ├── authRoutes.js
│   ├── attendanceRoutes.js
│   ├── adminRoutes.js
│   └── dashboardRoutes.js
│
├── middleware/
│   ├── authMiddleware.js
│   ├── adminMiddleware.js
│   ├── errorMiddleware.js
│   └── validationMiddleware.js
│
├── services/
│   ├── attendanceService.js
│   └── analyticsService.js
│
├── utils/
│   ├── formatDate.js
│   ├── calculatePercentage.js
│   └── constants.js
│
├── views/
│   ├── layouts/
│   │   └── main.ejs
│   │
│   ├── partials/
│   │   ├── navbar.ejs
│   │   ├── footer.ejs
│   │   └── flashMessages.ejs
│   │
│   ├── auth/
│   │   ├── login.ejs
│   │   └── register.ejs
│   │
│   ├── attendance/
│   │   ├── markAttendance.ejs
│   │   ├── attendanceHistory.ejs
│   │   └── myStats.ejs
│   │
│   ├── admin/
│   │   ├── dashboard.ejs
│   │   ├── createSession.ejs
│   │   ├── manageMembers.ejs
│   │   └── attendanceReport.ejs
│   │
│   ├── errors/
│   │   ├── 404.ejs
│   │   └── 500.ejs
│   │
│   └── index.ejs
│
├── public/
│   ├── css/
│   │   ├── style.css
│   │   ├── auth.css
│   │   ├── attendance.css
│   │   └── admin.css
│   │
│   ├── js/
│   │   ├── main.js
│   │   └── validation.js
│   │
│   └── images/
│
└── tests/
    ├── auth.test.js
    ├── attendance.test.js
    └── dashboard.test.js