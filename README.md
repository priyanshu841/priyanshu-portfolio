# Priyanshu Mishra — 3D Animator & Technical Animator Portfolio

A responsive React + Vite + React Three Fiber portfolio starter with a dark cinematic game-art direction, an animated procedural 3D character placeholder, project filters, a Maya script catalog, technical animation highlights, and contact links.

## Run locally

1. Install Node.js 20 or newer.
2. Open a terminal in this folder.
3. Run:

   ```bash
   npm install
   npm run dev
   ```

4. Open the local URL printed by Vite.
5. Before publishing, run `npm run build` to check the production build.

## Customize before launch

Search `src/main.jsx` for the placeholder data arrays `projects` and `scripts`. Replace titles, dates, descriptions, prices, and categories with your real work.

- **Hero character:** The current character is made from Three.js primitives so the page works without an external model. Replace the `Character` component with your own model when ready. A `.glb` file can be placed in `public/models/` and loaded with Drei's `useGLTF`.
- **Project previews:** Project thumbnails are CSS placeholders. Replace each `.project-visual` content with video embeds, poster images, or links to your animation breakdowns.
- **Contact:** Replace `your.email@example.com` and generic LinkedIn/GitHub links with your own profiles.
- **Script downloads:** Add actual free scripts and documentation. Public files can be placed in `public/downloads/` and linked from the catalog. For paid scripts, use a checkout + secure digital delivery provider; don't commit paid files to a public GitHub repository.
- **Availability wording:** Update the availability label if it doesn't reflect your current status.

## Publish with GitHub Pages

1. Create a GitHub repository named `priyanshu-portfolio` (or your preferred name).
2. Upload/commit all files in this project to the repository's `main` branch.
3. In GitHub, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
4. The workflow in `.github/workflows/deploy.yml` builds the site and deploys it automatically after a push to `main`.
5. After the workflow succeeds, your site will be available at `https://YOUR-USERNAME.github.io/priyanshu-portfolio/` (replace the username and repository name).

The Vite config uses `base: './'` to support relative assets on GitHub Pages project sites.

## Notes

- This is a starter template, not a finished portfolio: all sample project/script descriptions should be replaced with accurate content before going live.
- GitHub Pages is static hosting. It does not process payments or securely gate paid downloads by itself.
