# Salla Twilight Theme – Custom Minimal UI

A modern, minimalistic, and elegant theme built using Salla's Twilight engine.  
Designed to offer clean UX across all stages of shopping: from product discovery to checkout and tracking.

---

## ✨ Features

- 🔥 Fully compatible with [Salla Twilight](https://docs.salla.dev/)
- 🧱 Modular structure with reusable components
- 🛍 Product listing with filters
- 📦 Product detail view
- 🛒 Shopping cart
- 🧾 Checkout and billing screen
- ✅ Order success and tracking screen
- 📸 Comes with 3 preview screenshots
- 🎨 Clean styling using pure CSS (easy to replace with Tailwind or custom framework)

---

## 🧩 Project Structure

```
salla_theme/
├── twilight.json               # Theme config and metadata
├── layouts/
│   └── default.twig            # Base layout template
├── pages/
│   ├── home.twig               # Homepage
│   ├── all.twig                # All products listing
│   ├── product.twig            # Single product
│   ├── cart.twig               # Cart view
│   ├── checkout.twig           # Checkout page
│   ├── thank_you.twig          # Payment success
│   └── track.twig              # Order tracking
├── components/
│   ├── hero.twig               # Hero banner
│   ├── product-card.twig       # Single product in list
│   └── product-info.twig       # Full product display
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── images/
│       ├── screenshot_1.png
│       ├── screenshot_2.png
│       └── screenshot_3.png
```

---

## 🧪 How to Preview (Local)

### Using Salla CLI:
```bash
# Install CLI if not done yet
npm install -g @salla/cli

# Login
salla login

# Preview the theme
salla theme preview
```

---

## 📤 How to Publish

1. Push this folder to a public GitHub repository.
2. Go to [Salla Partner Portal](https://partners.salla.sa).
3. Choose **Create New Theme** or **Import Theme from GitHub**.
4. Fill out metadata, upload screenshots, and submit for review.

---

## 🖋 Customization Tips

- Modify `twilight.json` to add settings or toggles.
- Use Twig logic like `{% if ... %}` to conditionally show components.
- Customize styling in `assets/css/style.css`.
- Create new components under `components/` and register them in the JSON.

---

## 🧑‍💻 Author

Built with 💛 by ChatGPT + Mohammed

---

## 🧾 License

For personal and commercial use within Salla Platform.