

---

# YCBF Charity Django Application

A fully functional Django web application for a charity organization, converted from a premium HTML template. The application features a modern responsive design with proper routing, static file management, and template inheritance.

---

## 🌟 Features

* **Responsive Design**: Mobile-first layout that works on all devices
* **Multiple Pages**: Home, About, Contact, Blog, Donations, Team, Shop, Gallery, FAQ, and more
* **Static File Management**: Properly configured CSS, JS, and image assets
* **Template Inheritance**: Clean Django template structure with base template
* **URL Routing**: SEO-friendly URLs for all pages
* **Navigation**: Dynamic navigation menu with URL reversing
* **Contact Form**: Includes CSRF protection (backend processing required)
* **Modern UI**: Beautiful charity-themed design with animations and effects

---

## 📂 Project Structure

```
ycbf_charity/
├── ycbf_charity/        # Django project settings
├── charity/             # Main Django app
│   ├── views.py         # View functions for all pages
│   ├── urls.py          # URL patterns
│   └── ...
├── templates/           # Django templates
│   └── charity/
│       ├── base.html    # Base template
│       ├── includes/    # Reusable template components
│       │   ├── header.html
│       │   ├── footer.html
│       │   └── mobile_menu.html
│       ├── index.html   # Home page
│       ├── about.html   # About page
│       ├── contact.html # Contact page
│       └── ... (other pages)
├── static/              # Static files
│   └── assets/          # CSS, JS, images
└── manage.py            # Django management script
```

---

## ⚙️ Installation & Setup

### Prerequisites

* Python 3.8+
* pip (Python package manager)

### Steps

1. **Clone or Download**
   If you have this project as a ZIP file, extract it to your desired location.

2. **Install Dependencies**

   ```bash
   cd path/to/ycbf_charity
   pip install -r requirements.txt
   ```

3. **Database Setup**

   ```bash
   python manage.py migrate
   ```

4. **Create Superuser (optional)**

   ```bash
   python manage.py createsuperuser
   ```

5. **Run Development Server**

   ```bash
   python manage.py runserver
   ```

   Access the app at: **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**

---

## 📑 Available Pages

* **Home** (`/`) – Landing page with hero section and key content
* **About Us** (`/about/`) – Information about the charity
* **Contact** (`/contact/`) – Contact form and details
* **Blog** (`/blog/`) – Blog listing page
* **Donations** (`/donations/`) – Donation campaigns
* **Team** (`/team/`) – Team/volunteer info
* **Shop** (`/shop/`) – Merchandise store
* **Gallery** (`/gallery/`) – Photo gallery
* **FAQ** (`/faq/`) – Frequently asked questions

---

## 🎨 Customization

1. **Text Content**: Edit files in `templates/charity/`.
2. **Contact Info**: Update in `templates/charity/includes/header.html` and `footer.html`.
3. **Organization Name**: Replace "YCBF Charity" with your organization’s name.

### Adding New Pages

* Create view in `charity/views.py`
* Add URL in `charity/urls.py`
* Create template in `templates/charity/`

### Static Files

All assets (CSS, JS, images) are under `static/assets/`.

---

## 🚀 Production Deployment

1. Set `DEBUG = False` in `ycbf_charity/settings.py`
2. Configure `ALLOWED_HOSTS` with your domain
3. Use PostgreSQL (recommended)
4. Configure static files (Apache/Nginx)
5. Run with a WSGI server (e.g., Gunicorn)

---

## 🎨 Template Credits

Converted from the **Donat Premium HTML Template**.

---

## ✅ Key Features Implemented

* Django project structure
* URL routing for all pages
* Template inheritance with base template
* Static file configuration
* Responsive navigation menu
* Contact form with CSRF protection
* Organized template system
* Development server ready

---

## 📌 Repository Info

* **Stars**: 0 ⭐
* **Watchers**: 0 👀
* **Forks**: 0 🍴
* **Languages**:

  * Python (76.3%)
  * CSS (16.1%)
  * HTML (4.3%)
  * JavaScript (3.2%)

---
