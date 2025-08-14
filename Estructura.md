gym-system/
├── public/
│   ├── assets/
│   │   ├── css/
│   │   └── js/
│   ├── index.php        # Redirecciona a login/dashboard
│   └── login.php
│
├── app/
│   ├── config/
│   │   └── database.php
│   ├── controllers/
│   │   ├── AuthController.php
│   │   ├── DashboardController.php
│   │   └── MemberController.php
│   ├── models/
│   │   ├── User.php
│   │   └── Member.php
│   ├── services/
│   │   └── MembershipService.php
│   ├── helpers/
│   │   └── functions.php
│   └── routes.php
│
├── resources/
│   ├── layouts/
│   │   ├── auth.php      # Layout para login/registro
│   │   └── main.php      # Layout principal con navbar, sidebar, footer
│   ├── components/
│   │   ├── navbar.php
│   │   ├── sidebar.php
│   │   ├── dashboard-cards.php
│   │   └── member-card.php
│   ├── pages/
│   │   ├── dashboard.php
│   │   ├── members.php
│   │   └── profile.php
│   └── partials/
│       ├── head.php
│       └── footer.php
│
├── storage/             # para fotos, documentos, extras
├── tests/               # para pruebas automatizadas (PHPUnit)
├── .env
├── composer.json
├── package.json
└── README.md
