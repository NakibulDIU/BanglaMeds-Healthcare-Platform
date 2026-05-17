# BanglaMeds - A Comprehensive Online Healthcare Platform

BanglaMeds is a robust, full-featured web-based healthcare ecosystem built to modernize and simplify access to medical services in developing regions. It effectively bridges the communication and service gaps between patients, doctors, pharmacies, and emergency logistics providers through a unified interface.

---

## 🌟 Key Features

### 👤 Role-Based Access Control (RBAC)
The platform securely manages access logic across three distinct user roles:
* **Customer (Patient):** Browse & filter medicines, upload prescriptions for verification, order medicines (with subscription-based refills), schedule teleconsultations, securely access personal medical histories, book lab tests, and request on-demand emergency ambulances.
* **Doctor:** Personalized clinical dashboard to manage patient appointment streams, conduct real-time consultations via secure chat/video, review electronic patient records (EHR) or lab reports, and generate secure digital prescriptions.
* **Admin:** Comprehensive management suite overseeing user roles, prescription validations, inventory/stock thresholds, order fulfillments, secure localized payment processing, and multi-metric analytics reporting (weekly/monthly/yearly logs).

### 🛠️ Advanced Technical Modules
* **Distance-Based Dynamic Fare Calculator:** Powered by the **Google Maps Distance Matrix API** to compute transparent ambulance logistics rates based on real-time distance and estimated travel times.
* **E-Commerce & Prescription Verification:** Secure prescription image/PDF file-handling pipeline requiring Admin/Pharmacist validation before allowing prescription-only medication checkouts.
* **Secure Multi-Channel Authentication:** Built on Laravel Breeze, supporting secure login flows, OTP verifications, and social logins (Google/Facebook).
* **Dynamic Data Filters:** Real-time search, instant inventory check, and responsive catalog browsing utilizing asynchronous AJAX and jQuery actions.

---

## 🛠️ Technology Stack

* **Backend Framework:** PHP (Laravel Framework)
* **Frontend Engine:** Blade Templating Engine & Bootstrap Framework
* **Client-Side Interactivity:** JavaScript, jQuery, AJAX
* **Database Management:** MySQL (Enforced Referential Integrity via migrations)
* **API Integrations:** Google Maps API (Distance Matrix), Local Payment Gateways (bKash, Nagad, SSLCommerz)
* **Security layer:** Laravel Sanctum (Token-based web sessions & CSRF guards), HTTPS encryption pipelines

---

## 📊 System Architecture & Design References

The software development process followed the **Agile Methodology**, structuring progress via incremental sprints. The system's logical dependencies are modeled based on standard software engineering principles:
* **Design Models:** Comprehensive use-case diagrams, Data Flow Diagrams (DFD Level 0 & Level 1), and Entity-Relationship Diagrams (ERD).
* **Database Design:** Normalized relations optimized via precise database indexing on heavy-read query targets (`email`, `order_id`, `medicine_id`).

---
👥 Contributors (Project Team)
Md Nakibul Islam

Oasif Sadik Jisan

Md Roknuzzaman Khandoker

Saiyeda Lamiya Rikti
## 🚀 Installation & Local Setup

### Prerequisites
Make sure your system satisfies the requirements for Laravel and has PHP, Composer, and MySQL installed.

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/BanglaMeds-Healthcare-Platform.git](https://github.com/YOUR_GITHUB_USERNAME/BanglaMeds-Healthcare-Platform.git)
   cd BanglaMeds-Healthcare-Platform

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[WebReinvent](https://webreinvent.com/)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Jump24](https://jump24.co.uk)**
- **[Redberry](https://redberry.international/laravel/)**
- **[Active Logic](https://activelogic.com)**
- **[byte5](https://byte5.de)**
- **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
# BanglaMeds-Healthcare-Platform
