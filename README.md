# 🛒 Basic E-Shop

A simple e-shop website built with **HTML**, **CSS**, **PHP**, and **Bootstrap**.  
This project demonstrates a basic online store structure with product listings, shopping cart functionality, and responsive design.

---

## 📌 Features

- Responsive design using Bootstrap
- Product listing page
- Shopping cart system
- Simple PHP backend
- Clean and modern UI
- Easy to customize

---

## 🛠 Technologies Used

- HTML5
- CSS3
- PHP
- Bootstrap v3.3

---

## 📂 Project Structure

```bash
/basic-eshop
│
├── index.php
├── products.php
├── product-details.php
├── cart.php
├── checkout.php
│
├── /css
│   └── style.css
│
├── /images
│
├── /includes
│   ├── header.php
│   ├── footer.php
│   └── db.php
│
└── README.md
```

---

## 🚀 Installation

1. Clone the repository:

```bash
git clone https://github.com/Chasab86/basic-eshop.git
```

2. Move the project folder to your local server directory:

- For XAMPP: `htdocs`


3. Start Apache from XAMPP/WAMP.

4. Open your browser and visit:

```bash
http://localhost/basic-eshop
```

---

## ⚙️ Configuration

If using a database, edit the database connection file:

```php
<?php
$conn = mysqli_connect("localhost", "root", "", "eshop_db");

if (!$conn) {
    die("Connection failed: " . mysqli_connect_error());
}
?>
```

---

## 🎨 Bootstrap Usage

This project uses Bootstrap via CDN.

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
```

---

## 📱 Responsive Design

The layout is fully responsive and works on:

- Desktop
- Tablet
- Mobile devices

---

## 📷 Future Improvements

- Admin dashboard
- Payment gateway integration
- Product search & filters
- Order history
- Wishlist functionality

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the project
2. Create a new branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## 📄 License

This project is open-source and available under the [GNU GPL v3.0 License](https://github.com/Chasab86/Voting-System---php/blob/main/LICENSE).

---
