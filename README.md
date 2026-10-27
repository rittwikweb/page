# Rittwik Hajra — Personal Website

Welcome to my personal webpage, bringing together my research, publications, academic background, professional experience, talks, and interests beyond academia.

The website is built as a single `index.html` file, with the styling and JavaScript included in the same file. The different sections are accessible through the navigation menu and have individual URL fragments, making it easy to link directly to a particular section.

## Website Structure

- **Home** — Introduction, research interests, academic profiles, and selected publications.
- **Publications** — Research papers, preprints and thesis.
- **Experience** — Professional and research experience.
- **Education** — Academic background.
- **Talks** — Conference presentations and other talks.
- **Miscellaneous** — Theatre, paintings and other creative interests.
- **Contact** — Contact information and relevant links.

## Deployment

The website is hosted using GitHub Pages.

To deploy the site:

1. Create a public repository named `<username>.github.io`.
2. Upload `index.html` and the associated assets to the repository root.
3. Navigate to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` directory, then save.
6. Once deployment is complete, the website will be available at `https://<username>.github.io`.

No build step or package installation is required.

## Repository Structure

```text
.
├── index.html
├── README.md
├── cover.jpg
├── photo.jpg
├── cv.pdf
├── papers/
│   ├── kummer-asiaccs2026.pdf
│   ├── matse-africacrypt2026.pdf
│   └── mtech-thesis.pdf
└── images/
    ├── theatre/
    │   └── stage.jpg
    ├── paintings/
    └── photography/
