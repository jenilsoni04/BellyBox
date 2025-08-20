# BellyBox

BellyBox is a PHP-based web platform designed to connect home-chefs and women entrepreneurs with customers seeking fresh, homely, and affordable meals. Bringing the warmth of “ghar ka khana” right to your doorstep!

---

## 🌟 Features

- **Marketplace for Home-Chefs:** Platform for home-chefs and women entrepreneurs.
- **Easy Ordering:** Browse, order, and enjoy home-cooked meals delivered to your door.
- **Affordable & Fresh:** Emphasis on affordable pricing and homemade freshness.
- **Personal Touch:** Meals crafted with care and tradition.

---

## 🖥️ Tech Stack

- **Backend:** PHP
- **Frontend:** HTML, CSS, JavaScript
- **Containerization:** Docker
- **Database:** MySQL
- **Version Control:** Git & GitHub

---

## 📁 Project Structure

```
BellyBox/
│
├── assets/             # Static assets like images, CSS, JS
├── src/                # PHP source files
│   ├── controllers/    # Logic controllers
│   ├── models/         # Database models
│   └── views/          # HTML/PHP templates
├── docker/             # Docker-related files
├── .env.example        # Environment configuration sample
├── Dockerfile          # Docker build file
├── README.md           # Project documentation
└── index.php           # Entry point
```

---

## 🏗️ Architecture Overview

1. **Customers** interact with the web platform (PHP, JS, CSS) to browse and place orders.
2. The platform manages order data via the database.
3. **Home Chefs** provide menu and meal details through the platform.
4. The platform notifies home chefs of new orders.
5. Docker is used for easy deployment and containerization.

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/jenilsoni04/BellyBox.git
   ```
2. **Set up environment variables:**
   - Copy `.env.example` to `.env` and fill in the values.

3. **Build and run with Docker:**
   ```sh
   docker build -t bellybox .
   docker run -d -p 8080:80 bellybox
   ```

4. **Or run locally:**
   - Ensure you have PHP and your database installed.
   - Configure your web server to point to `index.php`.

---

## 🤝 Contributing

We welcome contributions! Please open issues or submit pull requests for improvements.

---

## 👤 Author

- [jenilsoni04](https://github.com/jenilsoni04)

---

> Bringing the joy of homemade meals to your doorstep—supporting local talent, one tiffin at a time.
