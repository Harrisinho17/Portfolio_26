# Alexander Harris — portfolio

A responsive, static portfolio site built with HTML, CSS, and vanilla JavaScript. No build step or dependencies are required.

## Preview locally

Open `index.html` in a browser, or use VS Code's Live Server extension for a local preview.

## Publish with GitHub Pages

1. Push these files to the repository you want to publish.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch containing this site and the `/ (root)` folder, then save.

The published URL will follow `https://<username>.github.io/<repository-name>/` for a project repository (for example, `https://harrisinho17.github.io/Portfolio/` if published from the existing `Portfolio` repository).

## Personalize

- Update the completed project summaries and links in `index.html` as your portfolio evolves.
- Update the email and social profile links in `index.html` if they change.
- Adjust the palette and layout in `styles.css`.

## Project pages

Individual case studies live in `projects/`. Each page is a static HTML file and uses `../styles.css` and `../script.js`, so the folder works directly on GitHub Pages with no build step.

Each case study streams its demo video from the existing portfolio's public GitHub Pages assets. If that older site is retired, copy the MP4s into this repository and update the video source URLs in the corresponding pages.
