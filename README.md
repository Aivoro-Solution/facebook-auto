# Facebook Privacy Policy Website

Static, GitHub Pages-ready legal website for an application using Facebook Login and n8n authentication workflows.

## Files

- `index.html` — landing page
- `privacy-policy.html` — Privacy Policy
- `data-deletion.html` — Facebook/user data deletion instructions
- `terms.html` — Terms of Service
- `assets/style.css` — shared responsive styling

## Before deploying

Search for and replace these placeholders:

- `[APP NAME]`
- `[YOUR COMPANY / APP NAME]`
- `[YOUR SUPPORT EMAIL]`
- `[YOUR WEBSITE]`

Do not leave placeholders on your production legal pages.

## GitHub Pages deployment

1. Create a new GitHub repository.
2. Upload all files while preserving the directory structure.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select your main branch and `/ (root)`.
6. Save and wait for GitHub Pages to publish the site.

Your pages will normally be available at:

- `/`
- `/privacy-policy.html`
- `/data-deletion.html`
- `/terms.html`

## Meta / Facebook App

Use the public HTTPS URL of `privacy-policy.html` as the Privacy Policy URL in your Meta App configuration.

Use the public HTTPS URL of `data-deletion.html` for the data deletion instructions field when applicable.

Make sure the repository is public if using GitHub Pages in a way that requires public access, and verify every legal page opens in an incognito/private browser window.

## n8n

This website is static. n8n does not need to be hosted in this repository. Keep your Facebook OAuth callback/authentication workflow in n8n and use this site only for the public legal pages.

## Example repository

```text
facebook-privacy-policy/
├── index.html
├── privacy-policy.html
├── data-deletion.html
├── terms.html
├── README.md
├── .gitignore
└── assets/
    └── style.css
```
