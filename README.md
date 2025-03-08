# My-Eshopify Store

This is a simple online electronics store built using **HTML, CSS, and JavaScript**. The website serves as a product catalog with a direct **WhatsApp order system**, allowing customers to inquire about products via WhatsApp instead of completing transactions online.

## Features

- 📌 **Home Page** – Displays a general view of available electronics.
- 📌 **Product Detail Page** – Shows product images, descriptions, and pricing.
- 📌 **WhatsApp Order Integration** – Instead of an online checkout, users can click a button that opens WhatsApp with a pre-filled message.
- 📌 **Responsive Design** – Mobile-friendly for better user experience.

## Tech Stack

- **HTML** – Structure of the website
- **CSS** – Styling using Tailwind CSS / Bootstrap (Optional)
- **JavaScript** – For dynamic interactions (like WhatsApp link generation)
- **Hosting** – Can be deployed on GitHub Pages, Netlify, or Vercel

## Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate to the project folder:
   ```bash
   cd your-repo-name
   ```
3. Open the `index.html` file in a browser to preview.

## How It Works

- Customers browse through the product list.
- Clicking on a product takes them to its detail page.
- Clicking **"Order on WhatsApp"** redirects them to WhatsApp with a pre-filled inquiry message:
  ```html
  <a href="https://wa.me/2547XXXXXXXX?text=Hello!%20I'm%20interested%20in%20[Product%20Name]." target="_blank">Order on WhatsApp</a>
  ```
- You receive the message and finalize the order directly on WhatsApp.

## Future Enhancements

- 🔹 Add a search & filter feature for easier product navigation.
- 🔹 Convert to a **dynamic** store using Django or Firebase.
- 🔹 Integrate a simple admin panel to update products easily.

## License

This project is open-source and free to use. Feel free to modify it to fit your needs.

---
