# ASIS MUN 2026 Website

This folder contains the complete static website for ASIS Model United Nations 2026. It can be uploaded directly to GitHub and hosted using GitHub Pages, Cloudflare Pages, or the school's existing web server.

## Website files

- `index.html` — Home page
- `about.html` — About page
- `committees.html` — Committee directory and committee details
- `secretariat.html` — Secretariat page
- `resources.html` — Delegate resources and training information
- `faq.html` — Frequently asked questions
- `contact.html` — Contact page
- `register.html` — Registration page
- `styles.css` — Complete desktop and mobile styling
- `script.js` — Navigation, committee data, FAQ data and interactions
- `assets/` — School logo and supplied visual assets

## Preview locally

Open `index.html` in a web browser. For the most reliable preview, open this folder in VS Code and use the Live Server extension.

## Upload to GitHub

1. Create a new repository, for example `asis-mun-website`.
2. Upload everything inside this folder to the root of the repository.
3. Keep `index.html` in the repository root.
4. Commit the files.

## Publish with GitHub Pages

1. Open the repository's **Settings**.
2. Select **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Save and wait for the public link to appear.

## Publish with Cloudflare Pages

1. Sign in to Cloudflare using the school-controlled account.
2. Create a Pages project and connect this GitHub repository.
3. Select **Static HTML** or use no framework preset.
4. Leave the build command blank.
5. Set the output directory to `/` if requested.
6. Deploy, then connect a school subdomain such as `mun.bhavansalain.com`.

## Making changes

- Page text and structure: edit the relevant `.html` file.
- Colours, spacing and mobile layout: edit `styles.css`.
- Navigation, committees, FAQs and interactive behaviour: edit `script.js`.
- Images and logos: place replacements in `assets/` and keep the referenced filenames or update their paths in the code.

Once automatic deployment is connected to GitHub, every committed change to the main branch will update the published website. The team will not need to request new files from the original creator.

## Items still awaiting official information

The current website intentionally contains placeholders for the registration link, registration dates and fees, Secretariat photographs, official contact details, study guides, committee handbooks, training schedule and other final conference information.

## Important note about forms

The contact form is currently a visual demonstration and does not send email. The school's backend team must connect it to an approved form service or backend endpoint before using it to receive enquiries.
