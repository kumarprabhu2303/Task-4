# Mobile-Friendly Web Layout Using CSS Media Queries

A responsive landing page project demonstrating how to transform a traditional, fixed desktop layout into a mobile-friendly experience using CSS media queries and modern layout systems like Flexbox.

## 📱 Mobile Transformation Features

When the viewport drops to **768px or smaller**, the layout smoothly adapts through the following changes:
- **Responsive Navbar:** The horizontal navigation menu shifts to a clean, vertically stacked list.
- **Stacked Columns:** The desktop two-column row layout (`Flexbox`) refixes into a single vertical stack.
- **Fluid Images:** Images auto-scale safely up to 100% of their container width to eliminate overflow.
- **Optimized Typography:** Font sizes drop (`48px` to `32px` headings) for readable layouts on narrow viewports.

---

## 🛠️ Prerequisites

No installation or server environments are required. You only need:
- A modern web browser (e.g., Google Chrome, Microsoft Edge, Brave)
- A code editor (like VS Code)

---

## 🚀 How to View and Run

1. Clone or download this project folder to your local machine.
2. Open the directory containing your project.
3. Double-click the **`index.html`** file to open it directly in your web browser.

---

## 🧪 Testing with Chrome DevTools

To observe the responsive breakpoints action live:

1. Open **`index.html`** in Google Chrome.
2. Right-click anywhere on the webpage and select **Inspect** (or press `F12` / `Cmd + Option + I`).
3. Click the **Toggle Device Toolbar** icon at the top-left of the inspection panel (the mobile/tablet icon).
4. Select a virtual device (e.g., *iPhone 14*, *Pixel 7*) from the top dropdown, or manually drag the viewport handles to dynamically watch the layout adapt under `768px`.

---

## 🧠 Key Learnings

- **Meta Viewport Tag:** Included `<meta name="viewport" content="width=device-width, initial-scale=1.0">` to ensure mobile devices scale the site pixel-for-pixel accurately.
- **Fluid Sizing:** Used percentages, `max-width`, and `auto-height` parameters instead of hard-coded pixel configurations to banish horizontal scrolling.
- **Media Queries:** Leveraged `@media (max-width: 768px)` rules to seamlessly inject dynamic breakpoint behavior.
