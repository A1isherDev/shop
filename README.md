# shop

A simple online shop project built with Django — a base e-commerce application that lets you manage products, media, and storefront logic.

## 🧰 Features

- Product catalog management (via `products/` app)  
- Media handling (product images and other uploads)  
- Simple project structure ready to extend  
- Uses SQLite for development (file `db.sqlite3`)  

## 📦 Tech Stack

- Python + Django  
- HTML / CSS / SCSS / JavaScript for frontend  
- SQLite (default DB for development)  
- Django static/media file support  

## 🚀 Getting Started

### Prerequisites

- Python 3.x  
- pip (or another package manager)  

### Installation & Run (development)

```bash
git clone https://github.com/A1isherDev/shop.git
cd shop
# (optional) create and activate virtualenv  
pip install -r requirements.txt   # if you add one  
python manage.py migrate
python manage.py runserver
````

Then open your browser at `http://127.0.0.1:8000/`

### (Optional) Admin & Product Management

You can use Django’s admin to add products, manage media files, and configure the catalogue.

## 🧪 (Future) To-Do / TODOs

* Add user authentication (signup / login / cart)
* Add shopping-cart & checkout functionality
* Switch to production-ready database (e.g. PostgreSQL)
* Add tests & coverage
* Add CI/CD and environment configs (e.g. `.env`, Docker)

## 🤝 Contributing

Feel free to fork, suggest improvements or add features via pull requests. Please follow standard Django coding style and keep code clean.
---
