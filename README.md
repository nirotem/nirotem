# Dr. Nir Rotem - Personal Academic Website

Welcome to the repository for the personal academic website of Dr. Nir Rotem, hosted via GitHub Pages and secured through Cloudflare at `nirotem.com`. 

This site is built as a lightweight, lightning-fast static web environment. It is designed to showcase academic research, publications, teaching experience, and professional engagements without the bloated overhead or security vulnerabilities of a traditional Content Management System (CMS) like WordPress or Wix.

---

## 🎨 Design Ethos & Architecture

The website features a custom **Scandinavian Modern Academic Theme** characterized by minimalist aesthetics, a muted earth-toned palette, sophisticated typography (`Inter`), and generous whitespace to ensure maximum readability.

### Key Technical Features:
* **Grid Layout (1100px Desktop):** Optimized layout for modern desktop monitors, utilizing structural flexbox and grid splits to keep text and media perfectly aligned.
* **Full Mobile Responsiveness:** Built natively with fluid CSS layout modifications and viewport constraints. It seamlessly adapts to mobile screens, scaling fonts, stacking cards, and adjusting navigation menus automatically without requiring separate mobile files.
* **Secure and Proxied Architecture:** Operating on a decoupled infrastructure. The domain DNS and SSL handshakes are handled via Cloudflare (Full/Strict Encryption Mode) mapping directly to GitHub Pages' static edge servers over safe HTTPS protocols.

---

## 📂 File Directory & Page Breakdown

The core project consists of five foundational HTML pages, a centralized stylesheet, and an isolated asset folder:

* **`index.html` (About Me):** The digital landing page. It introduces your core research paradigm at the intersection of transnational sociology and political sociology. It highlights your current status as a *David and Rosa Orzen Research Fellow*, presents your targeted research interests in a clean grid of styled UI boxes, and hosts your verified social buttons (Google Scholar, ORCID, HUJI).
* **`projects.html` (Research):** A comprehensive catalog of your ongoing and completed research initiatives. Every research card uses a split text-and-graph layout to cleanly break down projects ranging from *Illiberalism, Higher Education, and Academic Freedom* to machine learning attrition studies.
* **`publications.html` (Selected Publications):** Fully automated page hosting a secure async BibBase integration pipeline connected directly to your public Zotero collection database. Custom style overwrites are embedded in the master CSS to scrub out duplicate outbound icons for a cleaner look.
* **`teaching.html` (Teaching & Engagement):** Displays a structured, chronological timeline of your pedagogical appointments at the Hebrew University of Jerusalem, University of Graz, and University of Minnesota. It also houses an elaborate, categorized overview of your professional memberships (ASA, ISS), peer-review pipelines, and selected awards.
* **`lighter.html` (The Lighter Side):** A curated personal section featuring a customized, narrow landscape hero banner. It displays your personal interests (Expeditions, Film/Cinema, Reading) across a symmetric 4-box layout, alongside a Font-Awesome integrated Spotify badge linking to your profile.
* **`style.css`:** The master engine for the site’s entire visual presentation, governing variables, structural media queries, spacing utilities, and responsive breakpoints.

---

## 🚀 Future Maintenance: How to Add a New Research Project

Because this site is built with clean, static HTML components, you can add a brand-new project to the top of your portfolio at any point directly inside your web browser via GitHub. 

### Step-by-Step Guide:

1. Log into GitHub, open this repository, select **`projects.html`**, and click the **pencil icon (Edit this file)** in the upper right.
2. Scroll down until you find the comment line: ``.
3. Right beneath that line (so it appears as the very first, most recent project), press Enter to create an empty space and paste the following blank structural template:

```html
<div class="project-card">
    <div class="project-text">
        <h4>Name of Your Brilliant New Project Here</h4>
        <p>Type the detailed paragraph describing your new research framework here. Keep it engaging, clear, and written in prose that matches your established tone. Mention methodology, data sources, or key theoretical angles as needed.</p>
    </div>
    <div class="project-image-box">
        <img src="images/project-new-name.jpg" alt="Brief Description of Image">
    </div>
</div>
