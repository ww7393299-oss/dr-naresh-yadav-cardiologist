# Dr. Naresh Yadav — Cardiologist Website

A responsive, single-page style landing page (`index.html`) for **Dr. Naresh Yadav**, a cardiologist based in Jaipur, Rajasthan (Mehta Heart Care Clinic). Built with plain HTML, embedded CSS, and a touch of vanilla JavaScript for the mobile nav.

## 📁 File
- `index.html` — Home page of the website

## 🎨 Design & Tech
- **Font:** Poppins (Google Fonts)
- **Styling:** Custom CSS using CSS variables (`:root`) for colors, shadows, radius, and transitions
- **Color theme:** Teal/cyan primary (`#0e7490`), teal-green secondary (`#14b8a6`), orange accent (`#f97316`)
- **Layout:** CSS Grid & Flexbox, fully responsive with a `.container` max-width wrapper
- **JS:** Small inline script to toggle the mobile navigation menu (`menuToggle` / `navMenu`)

## 🧩 Page Sections
1. **Header / Navbar** — Sticky header with logo and nav links, mobile menu toggle
2. **Hero** — Introduction banner with tagline, heading, and quick info cards
3. **Expert Cardiac Care** — Intro highlight with two feature boxes (Personalized Consultation, Modern Cardiac Evaluation)
4. **About Preview** — Doctor's photo and short bio, links to `about.html`
5. **Services** — 6 service cards: Heart Checkup, ECG Testing, Blood Pressure Management, Chest Pain Consultation, Preventive Cardiology, Follow-up Cardiac Care
6. **Why Choose Us** — 4 trust points (12+ Years Experience, Advanced Heart Care, Compassionate Treatment, Trusted in Jaipur)
7. **Stats** — Key numbers (12+ years experience, 5000+ patients, 100% patient-focused care, 2025 award)
8. **Testimonials** — 3 patient reviews
9. **CTA (Call to Action)** — Appointment booking prompt, links to `appointment.html`
10. **Contact Strip** — Phone, email, location, consultation hours
11. **Footer** — About summary, quick links, services list, contact info, copyright

## 🔗 Linked Pages (referenced but not included in this file)
- `about.html`
- `services.html`
- `appointment.html`
- `contact.html`

## 📞 Contact Info (as listed on the page)
- **Phone:** +91 6367824967
- **Email:** ny7976540@gmail.com
- **Location:** Jaipur, Rajasthan
- **Hours:** Mon–Sat, 10 AM – 6 PM

## ⚠️ Known Issues
- A few "why choose" icons show a placeholder `?` instead of an actual icon/number
- Testimonial quote marks and name-prefix bullets show as `�` (broken/garbled character encoding — likely a special character or emoji that didn't save correctly). Recommend re-adding proper `"` quote glyphs and removing the stray character before patient names
- Footer copyright symbol also shows as `�` instead of `©`
- Image path `images/doctor-profile.jpg` must exist in an `images/` folder for the About section photo to display

## 🚀 How to Use
Simply open `index.html` in any modern browser — no build step or server required. To deploy, upload all site files (including the linked `about.html`, `services.html`, etc., and an `images/` folder) to any static hosting service (GitHub Pages, Netlify, Vercel, etc.).
