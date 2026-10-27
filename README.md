<p align="center">
  <img src="assets/banner.svg" alt="Dental Landing Page Design" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white" alt="Three.js">
  <img src="https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=black" alt="GSAP">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/sections-21-0C489C?style=flat-square" alt="21 sections">
  <img src="https://img.shields.io/badge/screenshots-25-3CB4B4?style=flat-square" alt="25 screenshots">
  <img src="https://img.shields.io/badge/responsive-320px%20to%202560px-F2C9C2?style=flat-square&labelColor=071E44" alt="Responsive">
  <img src="https://img.shields.io/badge/content-dummy-7A879A?style=flat-square" alt="Dummy content">
</p>

<p align="center">
  <b>A premium, scroll-driven landing page for a family dental clinic.</b><br>
  Calm porcelain neutrals, one navy anchor, teal for anything live, and a real-time 3D implant that builds itself as you scroll.
</p>

<p align="center">
  <a href="#-preview">Preview</a> ·
  <a href="#-highlights">Highlights</a> ·
  <a href="#-design-system">Design system</a> ·
  <a href="#-sections">Sections</a> ·
  <a href="#-mobile">Mobile</a> ·
  <a href="design.md">Full spec →</a>
</p>

---

## 👀 Preview

<p align="center">
  <img src="screenshots/01-hero.png" alt="Hero section" width="100%">
</p>

<table>
  <tr>
    <td width="33%"><img src="screenshots/04-implant-3d-root.png" alt="Implant step 1"></td>
    <td width="33%"><img src="screenshots/05-implant-3d-abutment.png" alt="Implant step 2"></td>
    <td width="33%"><img src="screenshots/06-implant-3d-crown.png" alt="Implant step 3"></td>
  </tr>
  <tr>
    <td align="center"><sub><b>① Root</b> · the 3D scene pins to the screen</sub></td>
    <td align="center"><sub><b>② Post + abutment</b> · threads and labels appear</sub></td>
    <td align="center"><sub><b>③ Crown</b> · the new tooth seats on top</sub></td>
  </tr>
</table>

---

## ✨ Highlights

| | Feature | What it does |
|:-:|---|---|
| 🦷 | **3D implant story** | A Three.js molar, helical titanium post, abutment and ceramic crown assemble across a 300vh sticky scene. The canvas stays clipped to its own section. |
| 🧑‍⚕️ | **Scroll-swapped dentists** | One pinned stage: scrolling wipes from one dentist to the next, with clickable progress tabs. |
| 😁 | **Aligner slider** | Drag or scroll to straighten an illustrated smile from 0% to 100%. |
| 🩺 | **Symptom finder** | Pick what you feel and get pointed to the right treatment. |
| 🎀 | **Moving ribbons** | Crossed marquee bands as section dividers, built as one reusable component. |
| 🖱️ | **Custom cursor** | A ring that snaps onto buttons and links (pointer devices only). |
| 📋 | **Custom dropdowns** | Accessible listbox with search, keyboard support and flip-up when space runs out. |
| 💬 | **Always reachable** | Floating WhatsApp button on desktop; Call / Book / WhatsApp bar on mobile. |

---

## 🎨 Design system

<p align="center">
  <img src="assets/palette.svg" alt="Colour palette" width="100%">
</p>

<table>
  <tr>
    <td width="50%" valign="top">

**Typography**

| Role | Font |
|---|---|
| Display | **Sora** 600–800, tight tracking |
| Body | **DM Sans** 400–600 |
| Labels | 12px uppercase, wide tracking |

  </td>
  <td width="50%" valign="top">

**Motion**

| Library | Used for |
|---|---|
| GSAP + ScrollTrigger | Reveals, pins, scrubbed scenes |
| Lenis | Smooth scrolling |
| Three.js | Implant scene |

  </td>
  </tr>
</table>

> [!TIP]
> Animations respect `prefers-reduced-motion`, and the 3D scene falls back to a static illustration when WebGL isn't available.

---

## 🧩 Sections

<table>
  <tr>
    <td width="50%"><img src="screenshots/03-why-bento.png" alt="Why us"><p align="center"><sub><b>Why us</b> · bento grid</sub></p></td>
    <td width="50%"><img src="screenshots/02-divider-stats.png" alt="Divider and stats"><p align="center"><sub><b>Crossed ribbons</b> · stats</sub></p></td>
  </tr>
  <tr>
    <td><img src="screenshots/07-treatments.png" alt="Treatments"><p align="center"><sub><b>Treatments</b></sub></p></td>
    <td><img src="screenshots/08-aligners.png" alt="Aligners"><p align="center"><sub><b>Aligners</b> · pinned slider</sub></p></td>
  </tr>
  <tr>
    <td><img src="screenshots/09-symptom-finder.png" alt="Symptom finder"><p align="center"><sub><b>Symptom finder</b></sub></p></td>
    <td><img src="screenshots/10-dentists-1.png" alt="Dentists"><p align="center"><sub><b>Dentists</b> · scroll stage</sub></p></td>
  </tr>
  <tr>
    <td><img src="screenshots/12-first-visit.png" alt="First visit"><p align="center"><sub><b>First visit</b></sub></p></td>
    <td><img src="screenshots/13-insurance.png" alt="Insurance"><p align="center"><sub><b>Insurance</b></sub></p></td>
  </tr>
  <tr>
    <td><img src="screenshots/14-emergency.png" alt="Emergency"><p align="center"><sub><b>Emergency</b></sub></p></td>
    <td><img src="screenshots/15-tips.png" alt="Tips"><p align="center"><sub><b>Care tips</b> · pinned</sub></p></td>
  </tr>
  <tr>
    <td><img src="screenshots/16-faq.png" alt="FAQ"><p align="center"><sub><b>FAQ</b></sub></p></td>
    <td><img src="screenshots/17-visit-map.png" alt="Visit"><p align="center"><sub><b>Visit</b> · map + hours</sub></p></td>
  </tr>
  <tr>
    <td><img src="screenshots/18-refer-a-patient.png" alt="Refer a patient"><p align="center"><sub><b>Refer a patient</b></sub></p></td>
    <td><img src="screenshots/19-booking.png" alt="Booking"><p align="center"><sub><b>Booking form</b></sub></p></td>
  </tr>
</table>

<p align="center">
  <img src="screenshots/20-footer.png" alt="Footer" width="100%"><br>
  <sub><b>Footer</b> · CTA card, partner strip, giant wordmark</sub>
</p>

---

## 📱 Mobile

<p align="center">
  <img src="screenshots/m01-hero.png" width="18%" alt="Mobile hero">
  <img src="screenshots/m02-why-bento.png" width="18%" alt="Mobile why us">
  <img src="screenshots/m03-dentists.png" width="18%" alt="Mobile dentists">
  <img src="screenshots/m04-refer.png" width="18%" alt="Mobile refer">
  <img src="screenshots/m05-footer.png" width="18%" alt="Mobile footer">
</p>

<p align="center"><sub>Pinned scenes switch to stacked reveals on small or short screens. No horizontal scroll from 320px up.</sub></p>

---

## 📁 What's inside

```
dental-landing-page-design/
├── README.md          ← you are here
├── design.md          ← full spec: tokens, wireframes, motion, a11y, copy bank
├── assets/            ← banner + palette graphics
└── screenshots/       ← 20 desktop (1440×900) + 5 mobile (390×844)
```

## 🛠️ Using the spec

1. Read **[design.md](design.md)** for each section's layout, with ASCII wireframes.
2. Swap the placeholders (`Clinic Name`, `(555) 010-0000`, `Dr. Jane Doe` …) for the real clinic's details.
3. Follow the asset checklist in the spec for photos, logos and badges.

---

<p align="center">
  <sub>All names, numbers, addresses and logos shown are <b>placeholder content</b>.</sub><br>
  <sub>Made with 🦷 by <a href="https://github.com/rayan-sarfaraz1">Rayan Sarfaraz</a></sub>
</p>
