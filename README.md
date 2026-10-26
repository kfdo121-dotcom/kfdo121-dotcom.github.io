Developer Portfolio
A fast, accessible, single-page developer portfolio built with plain HTML, CSS and JavaScript. No build step, no dependencies.
Live site: https://your-username.github.io/portfolio (replace after deploying)
Features
Semantic HTML5 layout: header, hero, about, skills, projects, resume, contact
Mobile-first responsive design using Flexbox and CSS Grid
Dark/light theme toggle that remembers your choice and respects system preference
Smooth-scrolling navigation with a mobile hamburger menu
Project modals built on the native `<dialog>` element (keyboard accessible, closes with Esc)
Respects `prefers-reduced-motion`, visible keyboard focus, ARIA labels
Project structure
```
portfolio/
├── index.html   # markup, styles and scripts in one file
├── resume.pdf   # add your own resume here
└── README.md
```
Customise
Open `index.html` and replace the placeholder name, bio, résumé entries and links.
Edit the `projects` array in the `<script>` block to list your own work.
Change colours in the `:root` and `:root[data-theme="dark"]` blocks.
Add your `resume.pdf` next to `index.html`.
Run locally
Open `index.html` in a browser, or serve the folder:
```bash
npx serve .
```
Deploy
GitHub Pages
Push this folder to a public repo (for example `portfolio`).
Go to Settings → Pages.
Under Build and deployment, choose Deploy from a branch, pick `main` and `/ (root)`, then save.
Your site appears at `https://<username>.github.io/<repo>/` within a minute or two.
Vercel
Import the repo at vercel.com/new.
Leave the framework preset as Other and the build command empty.
Click Deploy.
Netlify
Drag the folder onto app.netlify.com/drop, or connect the repo with no build command and `.` as the publish directory.
Tech
HTML5 · CSS3 (custom properties, Grid, Flexbox) · JavaScript (ES6+) · Google Fonts (Bricolage Grotesque, IBM Plex Sans)
License
MIT
