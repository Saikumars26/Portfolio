# Sai Sheri Portfolio

A clean, modern, single-page portfolio website for Sai Sheri, a Data Analyst and Analytics Engineer. Built with plain HTML, CSS, and JavaScript so it can be deployed easily on GitHub Pages.

## Features

- Responsive navigation with mobile menu
- Smooth scrolling sections
- Active section highlighting
- Scroll reveal animations
- Recruiter-focused home, about, skills, projects, experience, education, achievements, and contact sections
- Resume download button pointing to `assets/Sai_Sheri_Resume.pdf`

## Folder Structure

```text
.
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── assets/
    └── Sai_Sheri_Resume.pdf
```

## Setup

Open `index.html` directly in a browser, or run a small local server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Resume

Place the final resume PDF at:

```text
assets/Sai_Sheri_Resume.pdf
```

The download button is already wired to that path.

## Deploy To GitHub Pages

1. Create a GitHub repository.
2. Push these files to the repository.
3. In GitHub, open `Settings` > `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select the `main` branch and `/root` folder.
6. Save. GitHub will publish the portfolio at the Pages URL.

## Customize

- Update contact links in `index.html`.
- Replace project placeholder links with GitHub repositories and dashboard URLs.
- Add the real resume PDF in `assets/`.
