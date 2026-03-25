# Student Engineer Portfolio

Multi-page static portfolio designed for GitHub Pages. The site uses plain HTML, CSS, and JavaScript with no build step and no framework-specific deployment requirements.

## Structure

- `index.html` redirects visitors to `projects.html`.
- `projects.html` is the landing page with the hero and featured work.
- `about.html`, `skills.html`, `experience.html`, and `contact.html` split the rest of the portfolio into dedicated pages.
- `styles.css` contains the shared visual system and responsive layout.
- `script.js` handles mobile navigation, active-page nav styling, and reveal-on-scroll behavior.
- `assets/` is reserved for optional profile images or project thumbnails.

## GitHub Pages Deployment

1. Push this repository to GitHub.
2. Open the repository settings.
3. Go to `Pages`.
4. Under `Build and deployment`, select `Deploy from a branch`.
5. Choose the default branch and `/ (root)` folder.
6. Save, then wait for the Pages URL to be published.

This site uses relative paths only, so it is safe for a project repository URL such as `https://username.github.io/repository-name/`.

## Replace These Placeholders

- Update `Your Name`, `YN`, and the profile copy across the HTML pages.
- Replace `you@example.com`, `yourusername`, and social links in `contact.html` and the shared footers.
- Add your school, degree details, graduation timeline, and relevant coursework in `experience.html`.
- Replace starter projects in `projects.html` with your real project names, stacks, links, and outcomes.
- If you want a real profile image later, add it inside `assets/` and swap the placeholder panel in `projects.html` or `about.html`.
- If you have a resume file to share, add a download link or keep the current “Resume available on request” line.

## Notes

- The redirect in `index.html` keeps the root URL working while making `projects.html` the main portfolio entry point.
- Every internal link is relative, so navigation works correctly on GitHub Pages project repos.
