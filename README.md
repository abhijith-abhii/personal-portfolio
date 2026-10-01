# Abhijith Viswanathan — Personal Portfolio

**[Open the public portfolio](https://abhijith-viswanathan-portfolio.abhijithabhi3331.chatgpt.site/)**

Thirty projects across software engineering, data science and ML, AI engineering, security and safe access, cloud and DevOps, and data analytics. Field buttons jump to each section; skill filters and search help visitors find relevant work. Each project has a shareable case study with source links, implementation details, AI-assistance disclosure, and limitations.

The website works on phones, tablets, and laptops without signing in. It includes light and dark themes, keyboard-accessible navigation, optimized screenshots, and a downloadable resume. Analytics is disabled.

## Updated resume and professional background

[Download the resume](https://abhijith-viswanathan-portfolio.abhijithabhi3331.chatgpt.site/assets/Abhijith-Viswanathan-Resume.pdf) · [GitHub profile](https://github.com/abhijith-abhii)

The October 1 resume features Global Health Passport, NoteMesh, DocSearch Atlas and Shipyard. The portfolio now includes both internships, Cambridge Institute of Technology cultural leadership with more than 3,000 student participants per event, and AWS Certified Cloud Practitioner as planned professional development. The source archive includes the current resume.

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

The [25-project GitHub catalog](https://github.com/abhijith-abhii/portfolio-index) is included in the website alongside earlier projects. DocSearch and Retention Studio were updated rather than counted twice, producing 30 distinct case studies.

These are AI-assisted learning projects. Case studies distinguish synthetic demonstrations, local or temporary CI execution, and proposed next steps from production use or independently authored work.

Updated October 1, 2026.
