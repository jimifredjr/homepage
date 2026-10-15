# James Davis Portfolio

A static personal portfolio for James Davis, a senior software engineer and AWS Solutions Architect.

**Website:** [https://jimifredjr.github.io/homepage/](https://jimifredjr.github.io/homepage/)

## What's on the Site

- Professional introduction and selected career highlights
- Personal projects: [Advanced Gmail Spam Filter](https://github.com/jimifredjr/gmail-spam-filter) and [GitHub-Jenkins Continuous Integration](https://github.com/jimifredjr/git-jenkins-ci)
- Expandable work history with selected responsibilities and outcomes
- About section with education, certifications, technologies, and leadership approach
- Notes section for future writing
- Email, GitHub, and LinkedIn contact links

## Repository Layout

- `index.html` contains the page content and semantic structure.
- `style.css` contains the visual design, responsive layouts, and reduced-motion support.
- `script.js` controls the responsive navigation menu.
- `.github/workflows/pages.yml` publishes the repository root to GitHub Pages.
- `LICENSE` contains the repository license.

## Run Locally

No build step or package installation is required. From the repository root, run:

```sh
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000). Google Fonts and project imagery are loaded from external services, so those assets require an internet connection.

## Deployment

The Pages workflow runs on pushes to `main` and can also be started manually with `workflow_dispatch`. It uploads the repository root as the Pages artifact and deploys it with GitHub Actions. In repository settings, set **Settings > Pages > Build and deployment > Source** to **GitHub Actions**.

## License

This repository is licensed under Apache-2.0. See [LICENSE](LICENSE).