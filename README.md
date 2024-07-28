# inventory-management
    inventory-management/
    ├── app/
    │   ├── Http/
    │   │   ├── Controllers/
    │   │   │   ├── AdminController.php
    │   │   │   ├── EmployeeController.php
    │   │   │   ├── StockController.php
    │   │   │   ├── PaymentController.php
    │   │   │   └── InvoiceController.php
    │   │   └── Middleware/
    │   │       ├── AdminMiddleware.php
    │   │       └── EmployeeMiddleware.php
    │   └── Models/
    │       ├── User.php
    │       ├── Product.php
    │       ├── Payment.php
    │       └── Invoice.php
    ├── config/
    ├── database/
    │   ├── migrations/
    │   └── seeders/
    ├── public/
    ├── resources/
    │   ├── css/
    │   │   └── app.css
    │   ├── js/
    │   │   ├── app.js
    │   │   ├── router/
    │   │   │   └── index.js
    │   │   └── components/
    │   │       ├── StockManagement.vue
    │   │       ├── PaymentManagement.vue
    │   │       └── InvoiceManagement.vue
    │   ├── views/
    │   │   ├── layouts/
    │   │   │   └── app.blade.php
    │   │   ├── stock/
    │   │   │   ├── index.blade.php
    │   │   │   ├── create.blade.php
    │   │   │   └── edit.blade.php
    │   │   ├── payments/
    │   │   │   ├── index.blade.php
    │   │   │   └── create.blade.php
    │   │   └── invoices/
    │   │       ├── index.blade.php
    │   │       └── create.blade.php
    ├── routes/
    │   └── web.php
    ├── tailwind.config.js
    ├── vite.config.js
    ├── package.json
    └── .env
