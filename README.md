# 📰 Newspaper-Style FAQ with White Border for Power BI

A modern, responsive FAQ accordion inspired by the [ProPakistaniTools.com FAQ Accordion](https://propakistanitools.com/faq-accordion-html-css-javascript/), adapted for use in **Power BI** with **100% pure DAX, HTML, and CSS** — no JavaScript required.

This version recreates a classic **newspaper-style FAQ** with a black background and clean white borders. It uses a simple radio-button toggle system for expanding and collapsing answers — fully compatible with the HTML Viewer or HTML Content visuals in Power BI.

---

## 📌 What This Is

✅ A fully customisable FAQ template:
- Main questions and nested answers, styled in a clean accordion.
- Pure HTML5 and CSS — works anywhere Power BI supports HTML.
- SEO-friendly structure using `<div>`, `<article>`, and `<input>` elements.
- Inspired by the ProPakistaniTools.com accordion design.

✅ Lightweight:
- No JavaScript — only radio inputs and CSS for toggling.
- Works offline in Power BI Desktop and online in Power BI Service.

✅ Flexible:
- Easily adjust text, colours, and borders to match any report or brand.
- Good readability with a clear black-and-white newspaper look.

---

## ✨ Why Use This

- A simple way to add interactive FAQs to your reports without extra visuals.
- Keeps FAQs organised — perfect for help sections, data explanations, or guidance.
- Fully responsive design with fallback for mobile.
- Optimised for performance — no external plugins.

---

## ⚙️ How It Works

1️⃣ **Create a DAX Measure**

Write your entire HTML + CSS in a single DAX measure. You can bind dynamic FAQ text from your data model using `CONCATENATEX` if needed.

2️⃣ **Use an HTML Viewer Visual**

Add a certified HTML Content or HTML Viewer visual from AppSource to your report. Place your DAX measure in the visual.

3️⃣ **Radio Button Toggle**

Uses radio inputs and labels to expand/collapse questions — no JavaScript means it renders safely in both Desktop and Service.

---

## 🎨 Customisation Tips

✅ Change background colours, borders, and text directly in your DAX measure’s inline CSS.

✅ If you prefer a light theme, you can toggle the background to white — just adjust the `background-color` style in your DAX to switch between black and white.

✅ Style your fonts, spacing, and borders to match your report theme.

---

## 🔗 Inspiration & Source

This FAQ accordion is based on the open-source [ProPakistaniTools.com FAQ Accordion](https://propakistanitools.com/faq-accordion-html-css-javascript/), recreated for use in **Power BI**.
It uses the standard HTML5 `<details>` and `<summary>` accordion pattern — widely used in modern documentation and open-source README files.

---

## ✅ Example Use Cases

- Help sections for Power BI dashboards
- Data definitions or glossary pages
- Compliance and policy explanations
- Any place you need a simple, clean FAQ

---

## 📄 Licence

Open-source and free to use.  
If you share your version, please include the original inspiration link for reference.

---

**Enjoy building your Newspaper-Style FAQ with White Border for Power BI!** 📰✨
