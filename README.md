# Responsive wireframe website

A static HTML/CSS/JavaScript website based on the supplied wireframe.

## Files
- `index.html`: home page
- `about.html`, `services.html`, `contact.html`: additional pages
- `style.css`: responsive design
- `script.js`: mobile menu and email enquiry

## Test locally
Open `index.html` in a browser, click each navigation link, resize the window and test the mobile menu. For a local development server, run `python -m http.server 8000` in this folder and visit http://localhost:8000.

## Publish to GitHub Pages
1. Create a **new public repository** on GitHub (not the MGT4017 repository).
2. Upload the contents of this folder to the repository root (not the containing folder).
3. Commit the files.
4. Go to Settings > Pages > Build and deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. After deployment, open `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Customise
Replace `LOGO`, hero text, service names, about text, and footer details in the HTML. Change colours in the `:root` section of `style.css`. Replace `hello@example.com` in `script.js` and HTML. Replace the placeholder LinkedIn URL. The contact form uses `mailto:` and **does not send messages through a server**; for reliable contact-form submissions, use a third-party form service. Add a hero image using a local file in `assets/` if desired. All internal links are relative for GitHub Pages project sites.
