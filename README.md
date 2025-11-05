# Portfolio Project - Front-end Style Guide

## Overview
This is a **responsive single-page portfolio** designed to showcase personal projects. The layout adapts to various screen sizes using **Flexbox** and **CSS Grid**.

---

## Layout
- **Responsive design** for desktop, tablet, and mobile.
- **Sections:** Home, About, Services, Projects, Contact, Footer.
- **Flexbox & Grid** used for alignment and spacing.

---

## Colors
| Purpose                     | Variable            | Hex       |
|------------------------------|------------------|-----------|
| Background Color             | --bg-color        | #191f36  |
| Secondary Background Color   | --snd-bg-color    | #262b40  |
| Text Color                   | --text-color      | #fff     |
| Main Accent Color            | --main-color      | #f49818  |

---

## Typography

**Font Family:**  
- Nunito (imported from Google Fonts)

**Font Sizes:**  
- Base HTML font size: 62.5% (1rem = 10px)  
- Logo: 2.5rem  
- Heading 3: 3.2rem (Home), 2.6rem (About)  
- Heading 1: 5.6rem  
- Paragraphs: 1.6rem  
- Navbar links: 1.5rem  
- Icons:  
  - Social media: 2rem  
  - Services box: 7rem  
  - Portfolio layer: 2rem  
  - Footer icon: 2.4rem

**Font Weights:**  
- Logo: 700  
- Navbar links: 700  
- Home Heading 3: 700  
- Home Heading 1: 700  
- Buttons: 600

---

## Icons
- **Font Awesome** and **Bootstrap Icons** used for:  
  - Social media  
  - Menu toggle  
  - Services boxes  
  - Portfolio links  

---

## Animations
| Element                        | Animation / Transition                             | Duration / Effect             |
|--------------------------------|--------------------------------------------------|-------------------------------|
| Hero Image Float               | floatImage                                      | 4s ease-in-out infinite       |
| Social Media Icon Hover        | Color, background, box-shadow transition        | 0.5s ease                    |
| Button Hover                   | Box-shadow transition                            | 0.5s ease                    |
| Services Box Hover             | Border-color & scale transform                  | 0.5s ease, scale(1.02)       |
| Portfolio Image Hover          | Scale & opacity                                  | 0.5s ease, scale(1.1)        |
| Portfolio Layer Animation      | TranslateY on hover                              | 0.5s ease                     |
| Footer Icon Hover (Back to Top)| Box-shadow transition                             | 0.5s ease                     |

---

## Notes
- All measurements use **rem units** based on a 10px root font size.  
- The project uses a **dark theme** with orange accent for highlights.  
- Fully responsive using **media queries** for 1024px, 768px, and 425px breakpoints.  

---

**Technologies Used:**  
- HTML5  
- CSS3 (Flexbox, Grid, Animations)  
- Google Fonts  
- Font Awesome & Bootstrap Icons
