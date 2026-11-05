# Satya Sreeja Chalasani Portfolio

Personal portfolio for **Satya Sreeja Chalasani** — AI & Cloud Software Engineer and AWS Certified Solutions Architect. A single-page site built with plain **HTML, CSS, and JavaScript**, with custom CSS variables for **light and dark** themes, hosted on **GitHub Pages**.

## Repository

- **GitHub:** [https://github.com/satyasreejachalasani/Satya_Sreeja_Portfolio](https://github.com/satyasreejachalasani/Satya_Sreeja_Portfolio)
- **Owner:** [satyasreejachalasani](https://github.com/satyasreejachalasani)

```bash
git clone https://github.com/satyasreejachalasani/Satya_Sreeja_Portfolio.git
```

## Live site

[https://satyasreejachalasani.github.io/Satya_Sreeja_Portfolio/](https://satyasreejachalasani.github.io/Satya_Sreeja_Portfolio/)

After the first push, enable GitHub Pages from the repository settings: **Settings → Pages → Deploy from a branch**, with `main` and `/ (root)`.

## What’s on the site

| Section | Content |
|--------|---------|
| **Hero** | Name, AI & Cloud Software Engineer title, photo, Resume / LinkedIn / GitHub |
| **About** | 7+ years across full-stack, cloud, data, and Generative AI (RAG, agentic workflows) |
| **Education** | UNT — M.S. Data Science (coursework and focus areas) |
| **Skills** | Frontend, backend, AI/GenAI, vector search, AWS, Azure & GCP, DevOps, databases, testing |
| **Experience** | CBRE, Salesforce, First Databank, ZF Group |
| **AI Programs & Workshops** | Dallas AI Summer Program (SMU) and Build with AI Workshop Series (UNT The Spark) |
| **Certifications** | Credential cards with issuer badges and verification links |
| **Contact** | Email, LinkedIn, GitHub, Medium — open to full-time AI & Cloud roles |

**AI programs highlighted:** Dallas AI Summer Program (Intelli AI — NLP talent matching and workflow automation) and the Build with AI Workshop Series.

**Certifications featured:** Anthropic (Claude 101, Model Context Protocol, AI Fluency), AWS Solutions Architect – Associate (SAA-C03), Oracle OCI Generative AI Professional, Microsoft Azure Fundamentals (AZ-900).

## Tech stack

- **Markup & style:** HTML5, `style.css` (layout, responsive behavior, theme tokens)
- **Fonts:** [Google Fonts](https://fonts.google.com/) — Fraunces and Outfit
- **Script:** Vanilla JavaScript for theme persistence (`localStorage`), certification modals, Escape-to-close, and scroll reveal (`IntersectionObserver`)
- **Hosting:** GitHub Pages (static assets only; no server-side runtime)

No bundler or framework is required to view or deploy the site. A `package-lock.json` may be present from earlier tooling; there is no `package.json` or npm scripts at the repo root.

## Repository layout

```
Satya_Sreeja_Portfolio/
├── index.html          # Full page content and inline scripts
├── style.css           # Global and component styles, themes
├── README.md
├── images/
│   ├── Profile.png
│   ├── unt.png
│   ├── unt-graduation.png
│   ├── cbre.svg
│   ├── salesforce.svg
│   ├── first-databank.svg
│   ├── zf-group.svg
│   ├── oracle-certificate.png
│   ├── ai-programs/    # AI program and workshop photos
│   ├── certs/          # Certification issuer icons
│   └── certificates/   # Certificate imagery and PDFs
└── resume/
    └── Satya_Sreeja_Chalasani.pdf   # Linked from the hero
```

## Local preview

Open `index.html` in a browser, or serve the folder with any static file server:

```bash
# Python 3
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Contact

- [Email](mailto:satyasreejachalasani@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/satya-sreeja-chalasani/)
- [GitHub](https://github.com/satyasreejachalasani)
- [Medium](https://medium.com/@satyasreejachalasani)
