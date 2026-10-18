# Abhijith Viswanathan — Personal Portfolio

**[Open the public portfolio](https://abhijith-viswanathan-portfolio.abhijithabhi3331.chatgpt.site/)**

Thirty-two projects across software engineering, data science and ML, AI engineering, security and safe access, cloud and DevOps, and data analytics. Field buttons jump to each section; skill filters and search help visitors find relevant work. Each project has a shareable case study with source links, implementation details, development notes, and limitations.

The website works on phones, tablets, and laptops without signing in. It includes light and dark themes, keyboard-accessible navigation, optimized screenshots, and a downloadable resume. Analytics is disabled.

## Updated resume and professional background

[Download the resume](https://abhijith-viswanathan-portfolio.abhijithabhi3331.chatgpt.site/assets/Abhijith-Viswanathan-Resume.pdf) · [GitHub profile](https://github.com/abhijith-abhii)

The October 18 resume features Global Health Passport, RescueRoute, PropertyPulse, NoteMesh and DocSearch Atlas. The portfolio now includes both internships, Cambridge Institute of Technology cultural leadership with more than 3,000 student participants per event, and the AWS Certified Solutions Architect – Professional certification. The source archive includes the current resume.

## Complete website source

Download **[portfolio-source.zip](portfolio-source.zip)** and extract it. This archive contains the complete editable website, assets, build scripts, and provenance notes, with the original folder structure preserved. It excludes Git history and credentials.

Inside the extracted `portfolio` directory:

```sh
node scripts/build.mjs
node scripts/check.mjs --release
python3 -m http.server 5187 --directory dist
```

Open `http://localhost:5187/` for local development. The public link above is the one to share.

Edit `dist/content.js` for projects and skills, `src/index.html` for the homepage, and `dist/styles.css` for styling. Read the archive's README for detailed maintenance instructions. The existing Sites hosting configuration belongs to this portfolio; use your own hosting configuration if making a separate copy.

## Project collection

The [25-project GitHub catalog](https://github.com/abhijith-abhii/portfolio-index) is included in the website alongside earlier projects. DocSearch and Retention Studio were updated rather than counted twice, producing 30 distinct case studies before the October additions of PropertyPulse and RescueRoute brought the total to 32.

These are my personal projects. Case studies explain implemented features, reproducible results and deployment boundaries. Development notes document the AI-assisted tools used during implementation.

Updated October 18, 2026.

## Reproducible performance comparisons

[RescueRoute](https://github.com/abhijith-abhii/rescue-route) compares exact enumeration and heuristic planning, plus constrained multi-vehicle route improvement. [PropertyPulse](https://github.com/abhijith-abhii/propertypulse-api) compares rental-search queries before and after indexing. The other selected projects have local benchmark reports. Every claim is tied to its synthetic workload and limitations; no production adoption or business uplift is asserted.

## Connect

[LinkedIn — Abhijith Viswanathan](https://www.linkedin.com/in/abhijith-viswanathan-0a7216436/)
