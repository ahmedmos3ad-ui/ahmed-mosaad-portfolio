# Ahmed Mosaad — Portfolio

Graphic design portfolio built with React and Vite. Includes project galleries, contact links, and CV download.

## Run

Requires Node.js and npm.

```sh
npm ci
npm run dev
```

## Build

```sh
npm run build
npm run preview
```

The built website is in `dist/client`.

## Update content

- Edit `src/content.js` to add projects or change contact links.
- Put project images in `public/assets/`, then add their paths, titles and natural dimensions to the relevant project's images list.
- Replace `public/cv/Ahmed_Mosaad_Professional_CV.pdf` to update the CV.

`src/` contains the page and styles. `public/` contains images and the CV. Root configuration files and `package-lock.json` are needed for installing and building the project consistently.

Selected artwork and the studio hero were generated or refined with AI assistance, as disclosed in project metadata. Fonts: Manrope. Icons: Phosphor React. Artwork and personal assets remain the property of their respective owners; no reuse license is granted.

## GitHub Pages

Enable GitHub Actions as the publishing source in repository Settings > Pages. The included Publish portfolio workflow builds the correct public asset paths for this repository and publishes dist/client. GitHub Pages hosting availability depends on repository visibility and the account plan.

## Client handoff

Send a ZIP of the source repository, or invite the client to the private GitHub repository. The ZIP includes source, images, CV, dependency lockfile and these instructions. Install with npm ci; run with npm run dev. Node.js 22 is used for automated publishing. Do not include node_modules, dist, .git or local credentials in a source delivery.
