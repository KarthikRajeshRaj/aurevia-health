# Aurevia Health — Website

[**Live Site →**](https://aureviahealth.ca)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=flat&logo=vercel&logoColor=white)

Production website for **Aurevia Health**, a Toronto-based digital-health nonprofit. Built and maintained solo during a Software Development & QA internship, from first line of code to live deployment on a custom domain.

## About Aurevia Health

Aurevia Health connects emerging digital-health leaders through events and programs focused on authentic connection, mentorship, and knowledge-sharing — for students, early-career professionals, healthcare providers, and community organizations.

## My Role

Software Development & QA Intern, May–Aug 2026. Full ownership of the website: design, development, deployment, and ongoing maintenance, working directly from project manager's direction and iterating through multiple rounds of content and design revisions.

## Tech Stack

**HTML, CSS, and vanilla JavaScript**. Each page is self-contained and fully static.

Notable implementation details:
- Scroll-triggered reveal animations via `IntersectionObserver`
- A custom SVG-based interactive hero visualization, generated at runtime and responsive to viewport size
- A hand-built mobile navigation system (hamburger menu, overlay, responsive breakpoints)
- CSS custom properties for a centralized design/theming system

## Pages

Six pages — Home, Programs, About, Get Involved, Contact, Careers — sharing a consistent design system, navigation, and footer. Visual direction and page structure were designed from PM's requests and written content brief.

## Testing & QA

A significant part of this project was identifying and fixing real-world rendering and layout issues post-launch, including:
- Cross-browser and cross-device (desktop/mobile) layout debugging
- Diagnosing and fixing a CSS specificity bug causing fixed-header content overlap on mobile
- Resolving responsive grid overflow issues on narrow viewports
- Verifying fixes with direct before/after measurement rather than visual inspection alone

## Deployment & Infrastructure

- **Hosting:** Vercel
- **Domain:** Custom domain (`aureviahealth.ca`), registered separately and connected via DNS configuration
- **CI/CD:** Git-based — every push to `main` triggers an automatic production deployment
- **Collaboration:** Repository shared with project stakeholders, who can edit content directly without needing local tooling

## Project Status

Actively maintained. Ongoing work includes content updates, design refinements, and new pages as the organization's needs evolve.

---

Built and maintained by **Karthik Rajesh Raj**
