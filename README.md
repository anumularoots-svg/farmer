# 🌾 BIYAM KRISHNA GARI RICE - Website

Premium e-commerce website for **BIYAM KRISHNA GARI RICE** (బియ్యం కృష్ణ గారి రైస్) - A farm-to-home traditional Telugu food business based in Hyderabad, India.

![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Products](#-products)
- [Tech Stack](#-tech-stack)
- [File Structure](#-file-structure)
- [Setup & Installation](#-setup--installation)
- [WhatsApp Integration](#-whatsapp-integration)
- [Customization](#-customization)
- [Browser Support](#-browser-support)
- [Contact](#-contact)

---

## 🌟 Overview

BIYAM KRISHNA GARI RICE is a premium single-page website designed for a traditional Telugu food business that delivers:

- **Village-grown BPT Sannalu Rice** (Brown, Semi-Polish, Full-Polish)
- **Fresh Urad Dal** (Split & Whole)
- **Homemade Pickles** (24+ varieties - Veg & Non-Veg)
- **Traditional Karam Powders** (10+ varieties)

The website features a modern, elegant design with a green & gold color scheme, bilingual content (English & Telugu), and seamless WhatsApp order integration.

---

## ✨ Features

### Design & UI
- 🎨 **Premium Design** - Elegant green (#1a472a) & gold (#d4a574) color palette
- 📱 **Fully Responsive** - Mobile, tablet, and desktop optimized
- 🌙 **Smooth Animations** - Scroll reveal, hover effects, floating elements
- 🔤 **Bilingual Support** - English & Telugu (తెలుగు) content
- 🖼️ **Process Infographics** - Visual storytelling for each product category

### Functionality
- 📝 **Smart Order Form** - Dropdown selectors with product variants & sizes
- 💬 **WhatsApp Integration** - One-click order submission via WhatsApp
- 🧭 **Smooth Navigation** - Fixed navbar with scroll effects & active states
- 📍 **Delivery Area Display** - 12+ Hyderabad locations listed
- 🔗 **Social Media Links** - Facebook, Instagram, LinkedIn, YouTube

### Performance
- ⚡ **Single HTML File** - No build process required
- 🎯 **Optimized Assets** - Google Fonts & Font Awesome CDN
- 📦 **Lightweight** - Fast loading, minimal dependencies

---

## 🛒 Products

### 🍚 Rice (BPT Sannalu)
| Type | Sizes Available |
|------|-----------------|
| Brown Rice (అన్‌పాలిష్డ్) | 5kg, 25kg, 50kg |
| Semi Polish Rice (సెమీ పాలిష్) | 5kg, 25kg, 50kg |
| Full Polish Rice (ఫుల్ పాలిష్) | 5kg, 25kg, 50kg |

### 🫘 Urad Dal
| Type | Sizes Available |
|------|-----------------|
| Urad Split - Pappu (పప్పు) | 1kg, 2kg, 5kg |
| Urad Whole - Gundram (గుండ్రం) | 1kg, 2kg, 5kg |

### 🥒 Pickles (24+ Varieties)
- **Mango**: Avakaya, Magaya
- **Vegetable**: Lemon, Gooseberry, Tomato, Gongura, Curry Leaves, etc.
- **Non-Veg**: Chicken, Mutton, Fish, Prawn varieties
- **Sizes**: 250gm, 500gm, 1kg

### 🌶️ Karam Powders (10 Varieties)
Kandi Podi, Pappula Podi, Nuvvula Karam, Kobbari Karam, Karivepaku, Munagaku, Gongura, Pudina, Kothimeera, Vepudu Karam

**Sizes**: 100gm, 250gm, 500gm

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure & Content |
| CSS3 | Styling & Animations |
| Vanilla JavaScript | Interactivity & Form Handling |
| Google Fonts | Typography (Cormorant Garamond, Montserrat, Noto Sans Telugu) |
| Font Awesome 6.5 | Icons |
| WhatsApp API | Order Submission |

---

## 📁 File Structure

```
biyam-krishna-gari-rice/
│
├── index.html          # Main website file (all-in-one)
├── README.md           # Project documentation
│
├── rice-process.png    # Rice making process infographic
├── urad-process.png    # Urad dal process infographic
├── pickle-process.png  # Pickle making process infographic
└── karam-process.png   # Karam powder process infographic
```

---

## 🚀 Setup & Installation

### Quick Start

1. **Download** all files to a folder
2. **Open** `index.html` in any web browser
3. **Done!** No server or build process required

### For Web Hosting

Upload all files to your web hosting service:

```bash
# Example using FTP or File Manager
├── index.html
├── rice-process.png
├── urad-process.png
├── pickle-process.png
└── karam-process.png
```

### Using Local Server (Optional)

```bash
# Python 3
python -m http.server 8000

# Node.js (with http-server)
npx http-server

# Then open: http://localhost:8000
```

---

## 💬 WhatsApp Integration

The website includes a smart order form that sends formatted messages to WhatsApp.

### How It Works

1. Customer fills in: Name, Phone, Location
2. Selects products from dropdown menus
3. Clicks "Send Order via WhatsApp"
4. WhatsApp opens with pre-formatted message

### Sample WhatsApp Message

```
🌾 *BIYAM KRISHNA GARI RICE*
━━━━━━━━━━━━━━━━
*📋 NEW ORDER*
━━━━━━━━━━━━━━━━

👤 *Name:* John Doe
📞 *Phone:* 9876543210
📍 *Location:* Kukatpally

🛒 *ORDER ITEMS:*
─────────────────
🍚 *Rice:* Brown Rice - 25kg
🫘 *Urad Dal:* Urad Split - 2kg
🥒 *Pickles:* Avakaya - 500gm
🌶️ *Karam:* Kandi Podi - 250gm

📝 *Notes:* Please deliver on Sunday

━━━━━━━━━━━━━━━━
_Sent from website_
```

### Changing WhatsApp Number

Find and replace `917993822600` with your number in `index.html`:

```javascript
// In the JavaScript section
var whatsappURL = 'https://wa.me/91XXXXXXXXXX?text=' + encodeURIComponent(message);

// In WhatsApp button links
href="https://wa.me/91XXXXXXXXXX"
```

---

## 🎨 Customization

### Colors

Edit CSS variables in `<style>` section:

```css
:root {
    --primary: #1a472a;        /* Main green */
    --primary-light: #2d5a3f;  /* Light green */
    --primary-dark: #0f2d1a;   /* Dark green */
    --gold: #d4a574;           /* Accent gold */
    --gold-light: #e6c9a8;     /* Light gold */
    --cream: #faf8f5;          /* Background */
}
```

### Fonts

Currently using Google Fonts:
- **Headings**: Cormorant Garamond (serif)
- **Body**: Montserrat (sans-serif)
- **Telugu**: Noto Sans Telugu

### Adding Products

1. Add to dropdown in HTML:
```html
<option value="New Product - 1kg">New Product - 1kg</option>
```

2. Add display card in respective section

### Delivery Areas

Edit the areas in both the display grid and dropdown:

```html
<span class="area-tag">New Area</span>
<!-- and -->
<option value="New Area">New Area</option>
```

---

## 🌐 Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Edge | ✅ Full |
| Opera | ✅ Full |
| Mobile Browsers | ✅ Full |

---

## 📞 Contact

**BIYAM KRISHNA GARI RICE**

- 📱 **Phone**: +91 79938 22600
- 💬 **WhatsApp**: +91 79938 22600
- 📍 **Service Area**: Hyderabad & Surrounding Areas

### Social Media

- [Facebook](https://facebook.com/profile.php?id=61584456673929)
- [Instagram](https://instagram.com/biyamkrishnagaririce)
- [LinkedIn](https://www.linkedin.com/company/110548513)
- [YouTube](https://www.youtube.com/@BIYAMKRISHNAGARIRICE)

---

## 📄 License

This project is licensed under the MIT License - feel free to use and modify for your own business.

---

## 🙏 Acknowledgments

- Design inspired by premium food & agriculture websites
- Process infographics showcase traditional Telugu food preparation methods
- Built with ❤️ for pure food lovers

---

**© 2026 BIYAM KRISHNA GARI RICE. All rights reserved.**

*Pure Quality • No Mixing • No Middlemen • Direct from Farm*
