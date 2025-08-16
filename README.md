# Shopify Custom Marquee Section

A lightweight, customizable **marquee section** for Shopify themes.  
It allows you to display scrolling **text** or **images** with adjustable speed, colors, and padding.

---

## 🚀 Features
- Option to display **text** or **images**
- Unlimited image blocks for scrolling logos/banners
- Adjustable marquee scroll speed
- Customizable background color and text color
- Adjustable top and bottom padding
- Responsive design with auto-duplication for seamless scroll

---

## 📂 File Setup
Create the following file in your theme:

---

## 🛠 Installation

### 1. Create the Section
1. Go to **Shopify Admin > Online Store > Themes > Edit Code**.
2. Under the **Sections** folder, click **Add a new section**.
3. Name it:  custom-marquee.liquid

---

4. Paste the provided section code inside `custom-marquee.liquid`.

---

### 2. Add the Section in Theme Editor
1. Open **Customize** for your theme.
2. Add the **Custom Marquee** section where you want it (header, top of homepage, footer, etc.).
3. Configure settings:
- **Marquee Content** → Text or Image
- **Marquee Text** → Enter scrolling text
- **Add Blocks** → Upload images if using Image mode
- Adjust colors, speed, and padding

---

## ⚙️ Settings

| Setting | Type | Description |
|---------|------|-------------|
| Marquee Content | Select (Text / Image) | Choose between scrolling text or image |
| Marquee Text | Text | Text to display if "Text" mode is selected |
| Marquee Speed | Range (10–40s) | Controls animation speed (lower = faster) |
| Background Color | Color | Background color of marquee |
| Text Color | Color | Text color (only in text mode) |
| Padding Top | Range | Top spacing (px) |
| Padding Bottom | Range | Bottom spacing (px) |

---

## 🧩 Blocks
- **Marquee Image**: Upload one or more images.  
Each block adds an image to the scrolling marquee.

---

## 🎨 Customization
- Adjust scroll speed via **Marquee Speed** (default: 20s).
- Change **background/text colors** from Theme Editor.
- Add multiple **logo images** for partner/client logo carousels.
- Use **text mode** for announcements like "🚀 Free Shipping above ₹999".

---

## 📜 Notes
- The script automatically duplicates content until it fills **2× container width** to ensure seamless scrolling.
- Images are constrained to **50px height** by default (adjustable in CSS).

---

## 📜 License
This project is open-source. Feel free to use and modify in your Shopify projects.

---

## 🐛 Found a Bug?

If you found any bugs in the code, feel free to:

- 📬 Reach out via email: [santhoshkumarb1309@gmail.com](mailto:santhoshkumarb1309@gmail.com)
- 🐙 Open an issue on GitHub: [GitHub Issues](https://github.com/iamsansk/Shopify-Custom-Freebie/issues)

Your feedback is always appreciated!

---
