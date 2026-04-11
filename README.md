# hajj-draw-system
hajj lottery system with user registration, admin control and automated draw process for webdev lab

## file structure
```
hajj-draw-system/
│
├── public/
│   ├── index.php              # landing page
│   ├── login.php
│   ├── signup.php
│   ├── results.php
│
├── pages/
│   ├── user/
│   │   ├── profile.php
│   │   ├── lotteries.php
│   │
│   ├── admin/
│       ├── dashboard.php
│       ├── manage-users.php
│       ├── manage-lotteries.php
│
├── includes/
│   ├── db.php                # database connection
│   ├── auth.php             # login/session checks
│   ├── functions.php        # reusable helpers
│   ├── header.php           # shared UI parts
│   ├── footer.php
│
├── config/
│   ├── config.php
│
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   ├── images/
│
├── database/
│   ├── schema.sql
│
├── docs/
│   ├── identity.png         # brand / ui guide
│
├── README.md
└── .gitignore
```
