# Green Horizon Landscaping Website

A responsive static website built with HTML, CSS, and vanilla JavaScript. It can be deployed directly to GitHub Pages or imported from GitHub into Vercel.

## Pages

- `index.html` - Home
- `about.html` - About
- `services.html` - Landscaping services
- `gallery.html` - Project gallery
- `contact.html` - Formspree estimate form

## Deploy to GitHub

1. Create a new empty repository on GitHub.
2. Do not add a GitHub README, license, or `.gitignore` during repository creation.
3. Copy the repository URL shown by GitHub.
4. In a terminal opened in this folder, run:

```powershell
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git branch -M main
git push -u origin main
```

## Deploy to Vercel

1. Sign in to Vercel and select **Add New > Project**.
2. Import the GitHub repository.
3. Leave **Framework Preset** as `Other`.
4. Leave the build command and output directory empty.
5. Select **Deploy**.

Future commits pushed to the `main` branch will trigger new Vercel deployments automatically.

## Before Using With A Customer

- Replace the placeholder phone number, email address, and street address.
- Replace the placeholder social links.
- Confirm the Formspree endpoint in `contact.html` belongs to the correct recipient.
- Replace demo photos and testimonial text with approved customer content.

The separate `website-pricing.html` file is an internal sales page and is intentionally not included in the customer deployment ZIP.
