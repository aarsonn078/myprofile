<<<<<<< HEAD
# Personal-Portfolio
Personal portfolio website of Aarson Maharjan, an aspiring full stack developer interested in AI-powered applications. Responsive, mobile-first, with light/dark mode.
=======
# Aarson Maharjan | Portfolio

A personal portfolio website built with plain HTML, CSS and JavaScript (no React, no build step). It has a light/dark mode toggle.

## Folder structure

```
portfolio/
├── index.html     # page structure and content
├── css/
│   └── style.css  # all styles, colors and layout
├── js/
│   └── main.js    # dark mode toggle and contact form
└── README.md
```

## Run locally

Double-click `index.html` to open it in your browser. Or, for a local server:

```
python -m http.server 8000
```

Then visit http://localhost:8000

## Things to edit

1. **Links:** replace `your-username`, `your-profile` and `your.email@example.com` in the Contact section.
2. **Email for the contact form:** change the `TO` value in `js/main.js`.
3. **Projects:** replace the two placeholder cards with your real titles, descriptions, tech tags, GitHub links and live demo links.
4. **Photo:** replace the "AM" block in the About section with an `<img>` tag. Add `alt` text and keep the image small (under 200 KB).
5. **Colors:** change the variables at the top of `css/style.css` (`--bg`, `--accent` and so on).

## Contact form

The form opens the visitor's email app with the message filled in, so it needs no server. For a real backend, you can use a form service such as Formspree or Netlify Forms, or build a small API (Node + Express or Spring Boot) and send the form data to it with `fetch`.

## Deploy

**GitHub Pages**

1. Create a new repository and upload the whole folder contents (`index.html`, `css/`, `js/`, `README.md`).
2. Go to Settings, then Pages.
3. Under Source, choose the `main` branch and the `/ (root)` folder, then save.
4. After a minute, your site is live at `https://your-username.github.io/repo-name/`.

**Netlify:** drag the folder onto app.netlify.com/drop.

**Vercel:** import the repository at vercel.com/new and deploy with the default settings.
>>>>>>> 438bbd7 (Initial commit)
