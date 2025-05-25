
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

**Your Name**  
🔗 [GitHub Profile](https://github.com/chaitalidigar)  


---

## 📸 (Optional) Screenshots

You can add screenshots of your dashboard and key pages here.
