# 🍽️ Food Website — Indian Restaurant Landing Page

A feature-rich, fully animated restaurant website built with HTML, CSS, JavaScript, and multiple premium libraries including GSAP, Swiper, MixItUp, FancyBox, and Parallax. Complete with a filterable menu, chef showcase, testimonials, table booking, gallery slider, and FAQ — deployed live on Vercel.

## 🌐 Live Demo

🔗 **[food-website-blush-ten.vercel.app](https://food-website-blush-ten.vercel.app)**

---

## ✨ Features

- 🏠 **Hero Section** — Parallax floating food images (berry, leaf), restaurant intro with "Welcome to our India restaurant" headline
- 🏢 **Brands Bar** — "Trusted by 70+ companies" logo strip
- 🎬 **About Section** — Restaurant story with video popup (FancyBox) — "Watch The Recipe"
- 🍛 **Filterable Menu** — 6 dishes across Breakfast / Lunch / Dinner tabs (MixItUp filter)
- 🍕 **Feature Dishes** — Two-column spotlight sections for Chicken Pepperoni & Sushi
- 📅 **Book a Table** — Opening hours display with Swiper gallery slider (FancyBox lightbox on click)
- 👨‍🍳 **Meet Our Chefs** — 5-chef Swiper carousel (Nilay, Ravi, Navnit, Pranav, Priyotosh)
- ⭐ **Testimonials** — 4 customer review cards with star ratings
- ❓ **FAQ Section** — 6 frequently asked questions with parallax background
- 📰 **Blog Section** — 3 blog posts with dates and Read More links
- 📧 **Contact / Footer** — Contact form, social links, address & newsletter
- 🛒 **Cart Icon** — Header cart with item count badge
- 🔍 **Search Bar** — Desktop search form in header
- 📱 **Responsive Design** — Mobile hamburger menu, Bootstrap grid layout
- 🎞️ **GSAP Animations** — Smooth scroll-triggered entrance animations throughout

---

## 🍛 Menu Items

| Dish | Category | Type | Price | Rating |
|------|----------|------|-------|--------|
| Fresh Chicken Veggies | Breakfast | Non Veg | Rs. 499 | ⭐ 5.0 |
| Grilled Chicken | Breakfast | Non Veg | Rs. 359 | ⭐ 4.3 |
| Paneer Noodles | Lunch | Veg | Rs. 149 | ⭐ 4.0 |
| Chicken Noodles | Lunch | Non Veg | Rs. 379 | ⭐ 4.5 |
| Bread Boiled Egg | Dinner | Non Veg | Rs. 99 | ⭐ 5.0 |
| Immunity Dish | Dinner | Veg | Rs. 159 | ⭐ 5.0 |

---

## 👨‍🍳 Our Chefs

- Nilay Hirpara
- Ravi Kumawat
- Navnit Kumar
- Pranav Badgal
- Priyotosh Dey

---

## 📅 Restaurant Hours

| Days | Timing |
|------|--------|
| Monday – Thursday | 9:00 AM – 10:00 PM |
| Friday – Sunday | 11:00 AM – 8:00 PM |

---

## 🗂️ Project Structure

```
Food-Website/
│
├── Assets/                       # All images, videos & icons
│   ├── logo.png                  # Brand logo
│   ├── main-b.jpg                # Hero banner image
│   ├── berry.png                 # Hero parallax floating element
│   ├── leaf.png                  # Hero parallax floating element
│   ├── about.jpg                 # About section video thumbnail
│   ├── video.mp4                 # Recipe video (FancyBox popup)
│   ├── menu-1.png → menu-4.png   # Menu tab filter icons
│   ├── 1.png → 6.png             # Dish images
│   ├── pizza.png                 # Feature dish — Chicken Pepperoni
│   ├── sushi.png                 # Feature dish — Sushi
│   ├── bt1.jpg → bt4.jpg         # Book table gallery images
│   ├── c1.jpg → c5.jpg           # Chef photos
│   ├── t1.jpg → t4.jpg           # Testimonial customer photos
│   ├── testimonial-img.png       # Testimonials section illustration
│   ├── b1.png → b5.png           # Brand/partner logos
│   ├── blog1.jpg → blog3.jpg     # Blog post images
│   ├── title-shape.svg           # Decorative underline shape
│   ├── table-leaves-shape.png    # Book table leaf decorations
│   └── faq-bg.png                # FAQ section background
│
├── index.html                    # Main HTML — full single-page site
├── style.css                     # Custom styles on top of Bootstrap
├── script.js                     # Main JS — nav, menu filter, GSAP init
│
├── bootstrap.min.css             # Bootstrap 5 grid & components
├── swiper-bundle.min.css         # Swiper slider styles
├── jquery.fancybox.min.css       # FancyBox lightbox styles
│
├── jquery-3.5.1.min.js           # jQuery core
├── popper.min.js                 # Bootstrap dependency
├── gsap.min.js                   # GSAP animation engine
├── ScrollTrigger.min.js          # GSAP scroll-triggered animations
├── ScrollToPlugin.min.js         # GSAP smooth scroll plugin
├── swiper-bundle.min.js          # Swiper slider
├── jquery.fancybox.min.js        # FancyBox video/image lightbox
├── jquery.mixitup.min.js         # MixItUp menu filter
├── parallax.min.js               # Parallax floating elements (hero)
├── smooth-scroll.js              # Smooth anchor scrolling
└── font-awesome.min.js           # Font Awesome icons
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5** | Semantic page structure |
| **CSS3** | Custom styling, animations, responsive layout |
| **Bootstrap 5** | Grid system, responsive components |
| **jQuery 3.5.1** | DOM manipulation & plugin base |
| **GSAP + ScrollTrigger** | Scroll-triggered entrance animations |
| **Swiper.js** | Chef carousel & gallery slider |
| **MixItUp** | Animated menu filter (All / Breakfast / Lunch / Dinner) |
| **FancyBox** | Video popup & gallery lightbox |
| **Parallax.js** | Floating hero food elements (berry, leaf) |
| **Smooth Scroll** | Smooth anchor link navigation |
| **Unicons** | Line icon set (cart, search, user, star etc.) |
| **Font Awesome** | Additional icons |
| **Vercel** | Deployment & hosting |

---

## 📄 Sections Overview

| Section | Description |
|---------|-------------|
| **Header** | Logo, nav links, search bar, cart (badge count 3), user icon, mobile menu |
| **Hero** | Parallax floating fruits, Indian restaurant tagline, "Check our Menu" CTA |
| **Brands** | 5 partner/brand logos — "Trusted by 70+ companies" |
| **About** | Restaurant story, video popup with FancyBox |
| **Menu** | 6 dishes, filterable by All / Breakfast / Lunch / Dinner (MixItUp) |
| **Feature Dishes** | Two-column Chicken Pepperoni & Sushi spotlight sections |
| **Book a Table** | Opening hours + Swiper gallery with FancyBox lightbox |
| **Our Team** | 5-chef Swiper carousel with social links |
| **Testimonials** | 4 customer star-rating review cards |
| **FAQ** | 6 questions on parallax background |
| **Blog** | 3 blog posts with dates and Read More |
| **Footer** | Contact form, social icons, newsletter, address |

---

## 🚀 Getting Started

### Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/Daniish-Qureshi/Food-Website.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd Food-Website
   ```

3. **Open in browser**
   ```
   Open index.html in your browser
   — use Live Server (VS Code extension) for best experience
   ```

> ✅ All libraries are bundled locally — no internet required after cloning!

---

## 📱 Responsive Design

| Screen | Behavior |
|--------|----------|
| **Mobile** | Hamburger menu, stacked sections, single-column menu grid |
| **Tablet** | 2-column menu cards, side-by-side about layout |
| **Desktop** | 3-column menu grid, parallax effects active, full chef slider |

---

## 👨‍💻 Author

**Danish Qureshi**  
BCA Final Year Student | Full Stack Developer  
📍 Dadri, Uttar Pradesh, India  
🔗 [GitHub — @Daniish-Qureshi](https://github.com/Daniish-Qureshi)  
🌐 [Portfolio](https://danish-qureshi-6ew5.vercel.app)

---

## 📄 License

This project is built for **educational & portfolio purposes**.  
Free to use as reference or inspiration.

---

⭐ If you liked this project, give it a **star** on GitHub!
