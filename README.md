# JaeYoun Park — portfolio

A static, editorial portfolio site built for GitHub Pages.

## Structure

- \`index.html\` — complete responsive portfolio, styles and interaction
- \`RESEARCH.md\` — source provenance, project-credit boundaries and image origins
- \`.github/workflows/pages.yml\` — GitHub Pages deployment workflow
- \`.nojekyll\` — serve the static site without Jekyll processing

## Editorial rule

Project credits are limited to what can be verified publicly. The Asiana case distinguishes the Kumho Asiana Group Wing CI from SodiumPartners’ airline-specific identity work, and does not assign unverified individual responsibilities to JaeYoun Park.

## Deployment

The workflow publishes the repository root to GitHub Pages whenever \`main\` is updated. If Pages has not yet been enabled for this private repository, select **Settings → Pages → Source: GitHub Actions** once; the next workflow run will publish the site.
