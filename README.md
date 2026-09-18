# Owam-Website
# Velora Motors — Luxury & Performance Automotive Platform

## Student Details
* **Student Name:** Mvumbi Owam
* **Student ID:** ST10526553
* **Module Code:** WEDE5020 (Web Development)
* **Institution:** IIE Rosebank International

---

## Project Overview
Velora Motors is a responsive, multi-page digital showroom designed to showcase high-performance and luxury vehicles. The platform allows automotive enthusiasts, collectors, and prospective buyers to explore vehicle specifications, learn about brand heritage, investigate ownership financing options, and request private viewings.

---

## File & Folder Structure

```text
Owam-Website/
├── css/
│   └── style.css
├── images/
│   ├── ferrari-296.jpg
│   ├── rolls-royce-ghost.jpg
│   ├── bentley-bentayga.jpg
│   ├── aston-martin-db12.jpg
│   ├── lamborghini-huracan.jpg
│   ├── range-rover.jpg
│   └── jaguar-etype.jpg
├── index.html
├── about.html
├── showroom.html
├── heritage.html
├── ownership.html
├── contact.html
└── README.md
---

## 3.4 Test and Iterate

### Testing Process

The Velora Motors website was tested using **Chrome Developer Tools (Device Toolbar)** across desktop, tablet, and mobile screen sizes to verify responsive design and ensure optimal user experience across all devices.

### Testing Observations

**🖥️ Desktop (1440px)**
- Full-width layout with horizontal navigation
- Vehicle images render at full size (600px max-width)
- Contact form spans its maximum width (700px)
- Typography at largest scale

**💻 Tablet (768px)**
- Content narrows gracefully, header padding reduces
- Navigation remains horizontal but tighter
- Vehicle cards maintain readability

**📱 Mobile (375px)**
- Navigation wraps into a stacked layout
- Headings resize appropriately
- All images scale to fit viewport without overflow
- Form fields stretch to full width for easier tapping

### Responsive Breakpoints

| Breakpoint | Target |
|---|---|
| `min-width: 768px` | Tablet and up |
| `min-width: 1024px` | Desktop and up |
| `min-width: 1440px` | Large desktop |

### Screenshot Evidence

**🖥️ Desktop View (1440px)**

![Desktop View](screenshots/desktop.png)

**💻 Tablet View (768px)**

![Tablet View](screenshots/tablet.png)

**📱 Mobile View (375px)**

![Mobile View](screenshots/mobile.png)

### Iteration Notes

Based on testing, the following refinements were made:

1. **Mobile navigation** — Adjusted link padding and reduced font size so all nav items fit
2. **Image scaling** — Applied `max-width: 100%` and `aspect-ratio` to prevent overflow
3. **Form usability** — Set inputs to `width: 100%` for easier touch interaction
4. **Touch targets** — Buttons sized to meet the 44px minimum for touch devices
5. **Contrast** — Verified gold accent colours meet WCAG contrast requirements

---

© 2026 Velora Motors. All Rights Reserved.
