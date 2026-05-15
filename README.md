# Mark Anthony Baltazar — Personal Portfolio & Resume

This repository houses my personal portfolio website, built to showcase my career, projects, and skills. 

Live Website: **[mabsite.netlify.app](https://mabsite.netlify.app)**

---

## 🎨 Credits & Original Template

This website is built using an open-source Astro portfolio template. Massive thanks to the original creator for designing such a high-performance, data-driven foundation!

* **Original Template Credits:** [CareerPortfolio: Data-Driven Astro SSG](https://astro.build/themes/details/career-portfolio-data-driven-astro-ssg/)
* **Key Features Inherited:** Zero-JS by default architecture, JSON-first configuration, built-in theme switching, and optimized performance scores.

---

## 🚀 How I Customized This Project

While the core layout and components are powered by the original template, I have customized the repository to reflect my own professional background:

* **Personalized Data:** Updated all career timelines, skills, project showcases, and profile info via the JSON files in `src/data/`.
* **Theme Configuration:** Tweaked the global site settings within `src/config.ts` to match my professional branding.
* **Production Deployment:** Configured, built, and continuously deployed the site live onto **Netlify**.

---

## 🛠️ Tech Stack & Setup

### Core Technologies
* **Framework:** [Astro v6](https://astro.build/) (Static Site Generation)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/)
* **Icons:** [Iconify](https://iconify.design/) via `astro-icon`
* **Hosting:** [Netlify](https://www.netlify.com)

### Local Development Quickstart

If you want to run my version of this repository locally:

1. Clone the repository:
```bash
git clone <your-repo-url>
```

2. Install the necessary dependencies (Node.js v22.12.0+ required):
```bash
npm install
```

3. Boot up the local development server:
```bash
npm run dev
```

*The local site will be viewable at `http://localhost:4321`.*

---

## 📁 Repository Structure

* `src/data/` — **(Where I made my updates)** Contains the JSON files controlling the text, projects, and experience displayed on the site.
* `src/components/` & `src/layouts/` — The underlying UI components and meta tags provided by the template.
* `src/config.ts` — Global configuration file used for toggling the site's base theme.

---

## 📝 License

The original template is licensed under the [MIT License](https://www.google.com/search?q=LICENSE). Feel free to check out the original creator's repository to use their template for your own project!