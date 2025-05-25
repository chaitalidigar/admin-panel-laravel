
# Laravel Admin Panel

A responsive and modular admin dashboard built with **Laravel**, **Laravel Breeze**, and **SB Admin 2**. It includes authentication, user management, and a clean layout ready to be extended for any backend system.

---

## ✨ Features

- 🧑‍💻 User Authentication (Login, Register, Logout)
- 📊 Admin Dashboard Layout (SB Admin 2 integrated)
- 🔐 Profile Management( Admin,Vendor Customer)
- ⚙️ Clean Modular Structure
- 🎨 Tailwind CSS Styling
- 🚀 Ready for Role/Permission (Authorization)

---

## 🚀 Installation

Follow these steps to set up the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/chaitalidigar/admin-panel-laravel.git
cd admin-panel-laravel
```

### 2. Install PHP dependencies

```bash
composer install
```

### 3. Install Node.js dependencies

```bash
npm install
npm run build
```

### 4. Configure environment variables

```bash
cp .env.example .env
php artisan key:generate
```

Then edit your `.env` file with your local DB credentials:

```
DB_DATABASE=your_db_name
DB_USERNAME=your_db_user
DB_PASSWORD=your_db_pass
```

### 5. Run database migrations

```bash
php artisan migrate
```

### 6. Start the development server

```bash
php artisan serve
```

Visit your project at: [http://localhost:8000](http://localhost:8000)

---

## 📦 Modules Included

This admin panel includes the following core modules:

- ✅ **Dashboard** — Overview of users and activities  
- ✅ **User Management** — View, edit, delete users  
- ✅ **Profile** — User profile info & password update  
- ✅ **Authentication** — Login, register, logout using Laravel Breeze  
- 🔒 **Authorization Ready** — (Optional) Add roles/permissions as needed  

---

## 📁 Folder Structure

| Folder/File              | Description                             |
|--------------------------|-----------------------------------------|
| `/routes/web.php`        | Web routes                              |
| `/resources/views/`      | Blade templates (includes SB Admin)     |
| `/resources/css/`        | Tailwind CSS files                      |
| `/app/Http/Controllers/` | Controller logic                         |
| `/database/migrations/`  | Table structure definitions             |
| `/public/`               | Public-facing files (index.php, assets) |

---

## 🛠️ Tools & Technologies

- Laravel 12
- Laravel Breeze (Auth scaffolding)
- SB Admin 2 (Bootstrap 4 Template)
- Tailwind CSS
- Blade Templating Engine
- MySQL (or compatible DB)
- Vite (asset bundler)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👤 Author
 
🔗 [GitHub Profile](https://github.com/chaitalidigar)  
Built with ❤️ by [Chaitali Digar](https://github.com/chaitalidigar)

⚠️ This admin panel is fully built from scratch by me for learning and development purposes. 


---

## 📸 (Optional) Screenshots

You can add screenshots <img width="1457" alt="Screenshot 2025-05-25 at 11 41 30 PM" src="https://github.com/user-attachments/assets/ff5fd07e-15d6-4696-86f4-309a2c636931" />
of your dashboard and key pages here.
<img width="1446" alt="Screenshot 2025-05-25 at 11 40 52 PM" src<img width="1451" alt="Screenshot 2025-05-25 at 11 42 07 PM" src="https://github.com/user-<img widt<img width="1431" alt="Screenshot 2025-05-26 at 12 05 48 AM" src="https://github.com/user-attachments/assets/4dff2bef-7a95-454d-bc80-5d90de85ee8e" />
h="1448" alt="Screenshot 2025-05-26 at 12 05 34 AM" src="https://github.com/user-attachments/assets/7339f330-fa0a-43f9-95b5-40fb56f99e15" />
attachments/assets<img width="1441" alt="Screenshot 2025-05-25 at 11 42 24 PM" src="https://github.com/user-attachments/assets<img width="1436" alt="Screenshot 2025-05-25 at 11 42 39 PM" src="https://github.com/user-attachments/assets/5e7384b5-8ff1-4ae0-be9d-fc7a09dbb764" />
/fbfea43f-6840-4c4f-8339-ba67e9d1c3fd" />
/6f1e5016-dcc1-4a05-b52e-2e8942d9a53a" />
="https://github.com/user-<img width="1450" alt="Screenshot 2025-05-25 at 11 42 14 PM" src="https://github.com/user-attachments/assets/33593a74-79d4-4142-aada-14203cba2e9f" />
attachments/assets/06cc1f93-8731-4153-a979-97c995987295" />


