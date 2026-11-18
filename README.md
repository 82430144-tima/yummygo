# YummyGo 🍔

A modern food delivery web application built with React that lets users
browse restaurants, add items to a cart, save favorites, and track their
order with a live countdown timer.

**Course:** CSCI426 – Advanced Web Programming  
**Team:** Fatima Arar & Nour Hassiry  
**Phase:** 1 (Frontend)

---

## 🌐 Live Demo

🔗 [**yummy-go-web.netlify.app**](https://yummy-go-web.netlify.app)

---

## ✨ Features

- 🏠 **Home** – Landing page with an intro video and quick category chips
- 🍔 **Menu** – Browse categories (Fast Food, Drinks, Sweets) and restaurants
- 🍽️ **Restaurant page** – Dynamic page: dishes are generated from data for the selected restaurant, with Add to Cart and Favorite buttons
- 🛒 **Cart** – Review items, remove items, and see the total
- ❤️ **Favorites** – Save and manage favorite dishes (polaroid-style wall)
- 📦 **Order** – Enter delivery details (with validation) and track the live ETA with a progress bar
- 📞 **Contact** – Contact information cards
- ℹ️ **About** – Project info with stats and features
- 🧭 **404 page** – Friendly error page for unknown URLs
- 📱 **Fully responsive** – Works on desktop, tablet, and mobile

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| React 18 | UI library |
| React Router DOM v6 | Client-side routing |
| Bootstrap 5 | Grid system and utility classes |
| CSS3 | Custom theming and animations |
| Git & GitHub | Version control |
| Netlify | Deployment |

---

## 🚀 Setup

Clone the repository and install the dependencies:

```bash
git clone https://github.com/82430144-tima/yummygo.git
cd yummygo
npm install
npm start
The app runs at http://localhost:3000.

📂 Project Structure
yummygo/
├── public/
│   ├── images/       Restaurant and food images
│   ├── screens/      UI screenshots (for README)
│   ├── logo.png      Favicon and navbar logo
│   └── intro.mp4     Home page video
├── src/
│   ├── components/   Navbar, Footer, RestaurantsMenu
│   ├── pages/        Home, Menu, Cart, Favorites, Order, Contact, About, NotFound
│   ├── styles/       CSS files for each page
│   └── App.js        Routes and global state (cart, favorites)
└── package.json

📸 Screenshots
🏠 Home Page
https://github.com/82430144-tima/yummygo-/raw/main/screens/home.jpeg

🍔 Menu Page
Top View
https://github.com/82430144-tima/yummygo-/raw/main/screens/menu1.jpeg

Bottom View
https://github.com/82430144-tima/yummygo-/raw/main/screens/menu2.jpeg

🛒 Cart Page
Top View
https://github.com/82430144-tima/yummygo-/raw/main/screens/cart.jpeg

Bottom View
https://github.com/82430144-tima/yummygo-/raw/main/screens/cart2.png

❤️ Favorites Page (Empty State)
https://github.com/82430144-tima/yummygo-/raw/main/screens/favorite.jpeg

📦 Order Page
Order Form
https://github.com/82430144-tima/yummygo-/raw/main/screens/order1.jpeg

Order Confirmation with Live Countdown
https://github.com/82430144-tima/yummygo-/raw/main/screens/order2.jpeg

📞 Contact Page
Top View
https://github.com/82430144-tima/yummygo-/raw/main/screens/contact1.jpeg

Bottom View
https://github.com/82430144-tima/yummygo-/raw/main/screens/contact2.jpeg

ℹ️ About Page
https://github.com/82430144-tima/yummygo-/raw/main/screens/about.jpeg


---

---

🎨 Design System
Primary color: #670626 (deep wine)

Background color: #FFBDC5 (soft pink)

Typography: Bootstrap defaults + custom weights

Border radius: 15–20px (soft, friendly feel)

Consistent theme across all pages with per-page unique UI patterns

🙏 Credits
Food and restaurant images: Sourced from publicly available educational resources (Pinterest / Google Images) for educational purposes only

Intro video: Custom-made by Nour Hassiry

Libraries used: React, React Router DOM, Bootstrap (all open source)

Icons: Emoji-based, no external icon library required

👥 Team Contributions
YummyGo was developed as a true partnership, where both team members
contributed equally across all stages of the project — from ideation to
deployment. Every feature was discussed, built, and reviewed together.

👩‍💻 Nour Hassiry
Project concept – Proposed the YummyGo food delivery idea and helped define the feature scope

Home page – Built the landing page with the intro video and welcome content

Menu page – Implemented the categories and restaurant browsing structure

RestaurantsMenu component – Developed the dynamic restaurant page with dish rendering

Design system – Chose the deep wine (#670626) and soft pink (#FFBDC5) palette that defines the brand

Contact page – Designed the contact information cards

Responsive testing – Tested the layout on tablet and mobile breakpoints

Presentation prep – Prepared the demo flow and slides content

👩‍💻 Fatima Arar
Cart page – Implemented item management, deletion, and live total calculation

Favorites page – Designed the polaroid-style favorites wall with hover animations

Order page – Built form validation, live countdown timer, and animated progress bar

About page – Designed the stats section and feature cards

State management – Refactored App.js to centralize cart and favorites logic

Git & GitHub – Set up version control with a structured commit history

Deployment – Deployed the final application on Netlify

Documentation – Wrote the README, captured UI screenshots, and prepared the project report

🤝 Built Together
UI/UX refinement – Both members reviewed and improved every page's layout together

Cross-browser & device testing – Tested on Chrome, Edge, and mobile devices

Bug fixing – Debugged issues collaboratively throughout development

Feature planning – Jointly decided what to build, how to structure it, and how each page should feel

Final polish – Reviewed the complete project together before submission

Report & presentation – Co-authored the project report and prepared the presentation slides

📄 License
This project was developed for CSCI426 – Advanced Web Programming (Phase 1)
at LIU – Lebanese International University.
For educational purposes only.