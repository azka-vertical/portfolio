# Muhammad Azka Abbasy — Data Analyst Portfolio

A responsive, static personal portfolio built with HTML, CSS, and vanilla JavaScript. It works locally and can be deployed to GitHub Pages without a build step.

## Files

- `index.html` — page structure and content
- `style.css` — responsive styling
- `script.js` — mobile navigation and dynamic footer year

## Run locally

1. Download and extract the ZIP file.
2. Open the `azka-data-analyst-portfolio` folder.
3. Double-click `index.html` to open it in your browser.

For a better editing workflow, open the folder in Visual Studio Code and use the **Live Server** extension, then choose **Open with Live Server** on `index.html`.

The Google Fonts import uses an internet connection; the site still works without it using fallback fonts.

## Personalize

- Edit the text in `index.html`.
- Add project case studies when you have real projects to showcase.
- Add public credential URLs to the certificates in the Highlights section when available.
- The hero currently uses an `AA` monogram. To use a photo, add an image file (for example, `assets/profile.jpg`) and replace the `.avatar` element in `index.html` with an `<img>` element, then style it in `style.css`.

## Publish with GitHub Pages

1. Create a new repository on GitHub, for example `azka-vertical.github.io` for a user site, or `azka-data-analyst-portfolio` for a project site.
2. Open a terminal in this project folder.
3. Run:

```bash
git init
git add .
git commit -m "Build personal data analyst portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace `YOUR-USERNAME` and `YOUR-REPOSITORY` with your actual GitHub username and repository name.

4. On GitHub, open the repository and go to **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then click **Save**.
7. Wait for the Pages deployment to finish. The published URL will appear in the Pages settings.

For a user site repository named exactly `YOUR-USERNAME.github.io`, the URL is `https://YOUR-USERNAME.github.io/`. For a project site, it is usually `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

## Updating the site

After editing files, run:

```bash
git add .
git commit -m "Update portfolio content"
git push
```

GitHub Pages will publish the update automatically after the deployment completes.
