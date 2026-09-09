#  Pawsitive Hub

> **Capstone Thesis Project**  
> A web-based management platform designed for Tabaco Animal Rescue and Adoption to streamline animal listings, adoption applications, and community outreach.

---

##  Preview & Resources

**Walkthrough Video:** [Watch Video Demo](https://res.cloudinary.com/ilhjqbnt/video/upload/f_auto,q_auto/v1788926576/PAWSITIVEHUB_LITERAL_NAVIA.mp4)
**Capstone Documentation:** [View PDF Document](https://drive.google.com/file/d/1Dd7EyLnvNTeZnYjnIgKbb-rrJeAOGnbm/view?usp=drive_link)
**User Manual:** [View PDF Guide](https://drive.google.com/file/d/1hn3ncs0p82r_C4vkqOjCsTsvhzd5Vmhu/view?usp=drive_link)

---

##  Built With

* **Backend Framework:** [PHP / Laravel](https://laravel.com/)
* **Authentication & Reactive UI:** [Laravel Jetstream](https://jetstream.laravel.com/) + [Livewire](https://livewire.laravel.com/)
* **Styling & UI Components:** [Bootstrap](https://getbootstrap.com/)
* **Database:** MySQL

---

## Key Features

**Pet Management:** Track rescues, medical status, adoption readiness, and animal profile galleries.
**Adoption Workflows:** Digital application forms, applicant processing, and tracking system for adoption statuses.
**Community Outreach:** Event publishing, rescue updates, and adoption awareness.
**User Management:** Secure, role-based access control for rescue organization admins and adopters via Jetstream.

---

##  Local Development Setup

### Prerequisites

* **PHP** >= 8.1
* **Composer**
* **Node.js & NPM**
* **MySQL** (via XAMPP, Laragon, or local MySQL Server)

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/pagongtotherescue/PawsitiveHub.git](https://github.com/pagongtotherescue/PawsitiveHub.git)
   cd PawsitiveHub


   Install PHP Dependencies
   composer install


   Install Frontend Dependencies
   npm install

   Copy the example environment file:
   cp .env.example .env

   Generate the application key:
   php artisan key:generate

   Update your database credentials inside the .env file:
   DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=pawsitive_hub
    DB_USERNAME=root
    DB_PASSWORD=

    Run Migrations and seeders
    php artisan migrate --seed

    Create Storage Link
    php artisan storage:link

    Start Local Development Servers
    In your first terminal window:
    npm run dev
    In a second terminal window:
    php artisan serve

   
