# Dionz Burgers

A modern, responsive web application for a gourmet burger restaurant featuring an interactive menu catalog, order customization, and seamless cart management.

## Features

* **Interactive Menu Catalog:** Browse signature burgers, sides, drinks, and combos with detailed descriptions, high-resolution imagery, and live pricing.
* **Order Customization:** Customize burgers with extra patties, cheese, toppings, and house sauces before adding to the cart.
* **Dynamic Cart & Checkout:** Real-time subtotal, tax, and order total calculations with instant quantity updates and item removal.
* **Responsive Mobile-First Design:** Adapts cleanly across desktop monitors, tablets, and mobile screens.

## Tech Stack

* **Frontend:** HTML5, CSS3 / Tailwind CSS, JavaScript (React / Vite)
* **Icons & Assets:** Lucide Icons / Font Awesome
* **State Management:** Client-side Cart & UI State

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/DeveloperDionz/dionz-burgers.git
cd dionz-burgers
```

### 2. Run Locally

If your project uses **Node.js / Vite**:

```bash
npm install
npm run dev
```

Then open the local development URL shown in your terminal (typically `http://localhost:5173`).

> **Note:** If this is a static HTML/CSS/JS build without a bundler, simply open `index.html` directly in your browser or launch it with the **Live Server** extension in VS Code.

## Project Structure

```text
dionz-burgers/
├── public/              # Static images, logos, and favicon
├── src/
│   ├── components/      # Reusable UI components (Navbar, MenuCard, Cart, Footer)
│   ├── data/            # Menu items, categories, and pricing data
│   ├── styles/          # Stylesheets and theme variables
│   └── main.js          # Application entry point and interactivity
├── index.html           # Main HTML entry file
├── package.json         # Project dependencies and scripts
└── README.md            # Project documentation
```

## Customization

* **Menu Items & Prices:** Update the menu array/JSON inside `src/data/` to add new burgers, adjust prices, or toggle item availability.
* **Branding & Theme:** Modify color variables and typography in your main CSS file to match your brand palette.

## License

This project is open-source and available under the [MIT License](LICENSE).