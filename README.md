
# ORIGINOVA — Luxury Travel & Tourism

A flight booking and travel website built as a personal learning project.

**Live demo:** _add your deployed link here_

---

## About

ORIGINOVA is a front-end concept for a premium travel agency. I designed the product —
the pages, the booking journey and the payment experience — and built it using
AI-assisted development, then iterated on it after the first release.

The project is intentionally front-end only: all state is handled in the browser,
so the booking and payment flows are functional demos rather than real transactions.

---

## Features

### Flight booking
- Flight search with autocomplete across **179 airports**
- One-way and round-trip selection
- Interactive **seat selection** with a visual cabin map
- Booking summary and checkout

### Payment
- Egyptian payment methods: **Fawry, Vodafone Cash, Etisalat Cash**
- International methods: **Visa, Mastercard, PayPal, Apple Pay, Google Pay**
- Payment confirmation screen

### Experience
- Animated login page with an interactive lamp that lights the scene
  (driven by CSS custom properties)
- Landing page with destinations, offers, services, testimonials, FAQ and a video modal
- GSAP-powered scroll and entrance animations
- Responsive layout for mobile

---

## Tech stack

| Area | Tools |
| --- | --- |
| Markup & styling | HTML, CSS (~4,600 lines) |
| Logic | Vanilla JavaScript (~2,500 lines) |
| Animation | GSAP |
| Fonts | Playfair Display, Poppins |
| Version control | Git & GitHub |

No frameworks and no build step — the site runs directly from static files.

---

## Project structure

```
index.html            Login page (entry point)
home.html             Landing page
booking-flight.html   Flight search, results and seat selection
payment.html          Checkout and payment methods
payment-success.html  Confirmation screen

script.js             Main application logic
auth.js               Client-side session handling
autocomplete.js       Airport search autocomplete
payment-utils.js      Payment helpers
airports-data.js      179 airports dataset
services-data.js      Services and offers content

styles.css            Global styles
booking-styles.css    Booking and seat-map styles
assets/               Payment provider logos
```

---

## Running locally

Clone the repository and open it with any static server:

```bash
git clone https://github.com/ultimateXD/originova3.git
cd originova3
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

---

## How this was built

This project was built with **AI-assisted development**. My role was defining the
product: deciding the pages and user flows, choosing which payment methods mattered
for the Egyptian market, reviewing the output, and going back to fix what didn't work.

After the first version shipped I returned to improve seat-selection performance,
fix the mobile layout, and add search autocomplete — those changes are in the commit
history.

---

## Author

**Ahmed Taha Mostafa Taha** — first-year Computer Science student,
Egyptian Chinese University, Cairo.

[LinkedIn](https://www.linkedin.com/in/ahmed-taha-soliman) · [GitHub](https://github.com/ultimateXD)
