# Reindolf Manu — Personal Portfolio Site

A modern, high-performance static portfolio website built for **GitHub Pages** (plain HTML5, CSS3, JavaScript — no build step or framework dependencies needed).

Inspired by modern, top-tier consulting and data engineering portfolios, featuring a **Deep Navy (`#00183B`)**, **Fresh Mint (`#DCF6F1`)**, and **Electric Lime (`#ECFCAC`)** color palette with **Space Grotesk** and **Inter** typography.

---

## 📄 Site Structure & Pages

| File | Status | Description |
|---|---|---|
| [`index.html`](file:///Users/macbookpro/Desktop/GitHub/My%20Portfolio/portfolio-site/index.html) | **Complete** | Home page featuring hero headline, metrics counter, selected case studies, and value proposition. |
| [`about.html`](file:///Users/macbookpro/Desktop/GitHub/My%20Portfolio/portfolio-site/about.html) | **Complete** | Professional bio, career timeline (Cohby Consulting, Clore Social Leadership, AkamaFund), and core competencies matrix. |
| [`education.html`](file:///Users/macbookpro/Desktop/GitHub/My%20Portfolio/portfolio-site/education.html) | **Complete** | Academic degrees (MSc Data Science, Pitman Diploma, BA) and verified certifications (Salesforce Admin, Sales Cloud, PSM I). |
| [`sfdc-projects.html`](file:///Users/macbookpro/Desktop/GitHub/My%20Portfolio/portfolio-site/sfdc-projects.html) | **Complete** | Salesforce CRM case studies, Flows, validation rules, security governance, and multi-system integrations. |
| [`data-science.html`](file:///Users/macbookpro/Desktop/GitHub/My%20Portfolio/portfolio-site/data-science.html) | **Complete** | Machine learning pipelines, biostatistics, n8n AI workflows, CohbyLearn LMS, and software applications. |
| [`contact.html`](file:///Users/macbookpro/Desktop/GitHub/My%20Portfolio/portfolio-site/contact.html) | **Complete** | Dedicated contact touchpoints (+1 343-883-2087, reindolfpratt@gmail.com, Ottawa ON) and contact form. |

---

## 🚀 Publishing on GitHub Pages

To publish as your primary GitHub Pages site (`<your-username>.github.io`):

1. Create a public repository on GitHub named exactly `<your-username>.github.io`.
2. From this folder, run:
   ```bash
   git init
   git add .
   git commit -m "Complete portfolio site redesign"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages → Source**, select **Deploy from a branch**, set branch to `main` and folder `/ (root)`.
4. Your site will be live at `https://<your-username>.github.io` in a minute or two!

---

## 🖼️ Adding Custom Images

To add screenshots or custom diagrams for any project card:
1. Place image files in `assets/images/`.
2. Insert an `<img>` tag inside the appropriate `.card` block in the HTML file:
   ```html
   <img src="assets/images/your-screenshot.png" alt="Project Screenshot" style="width:100%; border-radius:10px; margin-bottom:1rem;">
   ```
