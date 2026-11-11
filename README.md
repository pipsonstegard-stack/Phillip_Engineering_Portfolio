# Phillip Sonstegard — Engineering Portfolio

A responsive, dark-themed engineering portfolio built with plain HTML, CSS, and JavaScript. It is designed for GitHub Pages and keeps application source code separate from public portfolio materials.

## Preview locally

Open `index.html` in a browser. No build tools or package installation are required.

## Publish with GitHub Pages

1. Create a **new public repository** for the portfolio (for example, `phillip-engineering-portfolio`).
2. Upload the contents of this folder to the repository root. Do **not** upload your private Solar-Battery-Modeling application repository or its source files.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will provide the published site URL after deployment.

## Before publishing

- Replace the placeholder panels in the project pages with approved screenshots, diagrams, and results.
- Confirm that Powerfully Green has authorized every company-related image, document excerpt, model detail, and result you plan to publish.
- Remove customer information, addresses, credentials, API keys, local file paths, and other sensitive data from screenshots and documents.
- Verify every technical statement and add specific project results only when you can support them.
- Add your LinkedIn and GitHub profile links when ready.
- Consider adding a downloadable PDF resume if desired.

## Structure

```text
.
├── index.html
├── assets/
│   ├── css/styles.css
│   ├── js/main.js
│   └── images/
├── projects/
│   ├── solar-battery-model.html
│   ├── turbojet-analysis.html
│   └── cad-design.html
└── README.md
```

## Customization

- Main content and project cards: `index.html`
- Project case studies: `projects/`
- Colors, spacing, and responsive layout: `assets/css/styles.css`
- Mobile navigation: `assets/js/main.js`

The site uses Google Fonts (Manrope and DM Mono) when a network connection is available, with standard sans-serif and monospace fallbacks.
