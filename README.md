# Varsha Patil | Portfolio

A personal portfolio website that shows both sides of me: an IT student who builds Android and web apps, ML models and Power BI dashboards, and a creative who makes rangolis, designs on Canva and photographs the sky.

**Live site:** [https://varshptl23-portfolio.vercel.app/]

## What's inside

| Section | What it shows |
| --- | --- |
| Front page | Name, one-line intro, photo with stickers, Resume button |
| About | Short story, education and focus |
| My world | Rangoli, Canva designs, nature photography |
| Rangoli | Four rangolis: pookalam, colour-powder mandala, Gudi Padwa and a portrait rangoli |
| Photography | Auto-scrolling strip of nature photos (pauses on hover or touch, tap to enlarge) |
| Skills | Languages, web, mobile, databases, data, ML, tools and creative skills |
| Projects | 7 projects with screenshots, tools, links and category filters |
| Education | Degree, diploma, SSC and work experience |
| Achievements | Hackathon rank, certificates and coding profiles |
| Contact | Email, GitHub, Resume, LinkedIn, LeetCode, HackerRank, Blog |

## Features

- Fully responsive layout for phones, tablets and desktops
- Automatic light and dark mode that follows the device setting
- Scroll-in animations, gradient headings, floating photo, sticker decorations and a scroll progress bar
- Auto-scrolling photo gallery with pause on hover or touch
- Project filter buttons (All, Mobile, Web, Data & BI, Machine Learning, UI/UX)
- Click or tap any photo, project screenshot or certificate to enlarge it
- Respects the "reduce motion" setting for accessibility
- No frameworks and no build step: one HTML file with inline CSS and JavaScript

## Tech stack

- **HTML5, CSS3 and vanilla JavaScript**
- **Google Fonts:** Instrument Serif, Hanken Grotesk, Caveat
- **Inline SVG** for the stickers, arrows and icons

## Project structure

```
.
├── index.html                 # the whole portfolio (HTML, CSS and JavaScript)
├── README.md
└── images/
    ├── profile/               # front-page photo
    ├── rangoli/               # my rangolis
    ├── photography/           # nature photos
    ├── projects/              # project screenshots
    └── certificates/          # certificates
```

## Run it locally

1. Download or clone this repository.
2. Open `index.html` in any browser. No install needed. Keep the `images` folder next to it.

## Deploy with GitHub Pages

1. Upload `index.html`, `README.md` and the `images` folder to the root of your repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then click **Save**.
4. After a minute, your site is live at `https://varsh23-p.github.io/REPO-NAME/`.

It also works on Vercel and Netlify: import the repository and deploy with no build command.

## Customise it

- **Colours:** edit the variables at the top of the `<style>` block (`--sun`, `--rose`, `--vio`, `--bg`, `--ink`) and the dark-mode set below them.
- **Text:** search `index.html` for the section id (`id="about"`, `id="projects"`, `id="education"`) and edit the text there.
- **Photos:** replace a file inside `images/` with a new photo of the same name, or change the `src="images/..."` path in `index.html`.
- **Projects:** each project is one `<div class="pr" data-c="Category">` row. Copy a row to add a project, and set `data-c` to a filter category.
- **Certificates:** each one is a `<div class="cc">` card in the Achievements section.
- **Links:** update the Resume, GitHub, LinkedIn and project links in the Contact and Projects sections.

## Contact

**Varsha Patil**, B.Tech Information Technology, MPSTME, NMIMS Shirpur

- Email: varshadpatil2309@gmail.com
- [GitHub](https://github.com/varsh23-p) · [LinkedIn](https://www.linkedin.com/in/varsha-patil23) · [LeetCode](https://leetcode.com/u/varshap23/) · [HackerRank](https://www.hackerrank.com/profile/varshadpatil2309)
