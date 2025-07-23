# Custom-PC-Builder

An interactive, modern, and responsive web app that lets users design, review, and “order” a custom-built PC—tailored for both AMD and Intel platforms, with seamless routing, stateful component selection, and a delightful visual style.

<img width="1920" height="1080" alt="Screenshot 2025-07-24 001352" src="https://github.com/user-attachments/assets/4768b01c-180c-4454-b644-eb15b073df45" />


## Features

- **Welcome Landing:** Platform selection (AMD/Intel) with modern, split design
- **Smart Build Page:** CPU, Motherboard, RAM, Storage, GPU, Cooler, PSU, Case, and OS—all filtered for compatibility
- **Cart and Checkout:** Visual summary with icons, theme-colored platform badge, and “Cash on Delivery” checkout with delivery notice
- **Persistent State:** Remembers the selection across pages (via localStorage)
- **Responsive:** Works great on desktop and mobile
- **No Backend Required:** All frontend, runs with just HTML/CSS/JS

To run locally:

```bash
git clone https://github.com/your-username/custom-pc-builder.git
cd custom-pc-builder
# Open welcome.html with your browser (or use Live Server or similar tool)
```

Pages:

- `welcome.html` — Entry and platform selection
- `build.html` — Configure the custom PC; options filtered for Intel/AMD compatibility
- `cart.html` — View the selected build and complete checkout

## How It Works

1. **Choose a Platform:**  
   The welcome page lets the user select AMD or Intel.  
2. **Build Your PC:**  
   All component selectors are filtered for only compatible parts.
3. **Add to Cart:**  
   The full build appears on a confirmation-style cart page, with a platform-specific accent and order summary.
4. **Checkout:**  
   checkout acknowledges the order, with a “Delivered in 7 Days” notice.


## Tech Stack

- HTML5, CSS3, and vanilla JavaScript (ES6)
- Google Fonts ([Inter](https://fonts.google.com/specimen/Inter))
- [Emojis & SVG Logos](https://upload.wikimedia.org/) for instant visual cues
- No dependencies, no build step
