## ✨ SiMonika

Inventory and Vehicle Monitoring Information System.



## 💀 Design Database
![Diagram Class](https://github.com/fajarghifar/simonika/assets/71541409/85bc96af-6266-475e-94b0-6b49594bce09)

## 😎 Features
- Inventory
- Vehicles
  - STNK
  - Tax
- Office
- Brand
- Users

## 🚀 How to Use
1. Clone the Repository: `git clone https://github.com/aslan-asilon31/simonika-laravel10`
2. Navigate to the repository: `cd simonika`
3. Install Packages: `composer install` or Update: `composer update`
4. Copy `.env` file: `cp .env.example .env`
5. Generate app key: `php artisan key:generate`
6. Set up your database credentials in your `.env` file.
7. Seed Database: `php artisan migrate:fresh --seed`
10. Run: `php artisan serve`

Try logging in with:
 - email: `admin@admin.com` and password: `password`
 - email: `user@user.com` and password: `password`

## 🚀 Etc
1. **Theme**
    This theme uses Tabler.
    > For more details, visit this link [Tabler Theme](https://github.com/tabler/tabler).
1. **Fonnte**
    To set up reminders and send messages.
    > For more details, visit this link [Fonnte](https://md.fonnte.com/).
    To set Fonnte API, add this line of code to the end of the `.env` file:
    ```bash
    FONNTE_API="YOUR_FONNTE_API"
    ```
