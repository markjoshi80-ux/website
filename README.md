# Faithful Hands & Hope Collective Society Website

Static website for Faithful Hands & Hope Collective Society. It is dependency-free and can be hosted on Azure Static Web Apps, Azure Storage static website hosting, or Azure App Service.

## Files

- `index.html` - site content and page structure
- `styles.css` - responsive visual design
- `script.js` - mobile menu and contact form feedback
- `assets/faithful-hands-hero.png` - generated homepage hero artwork
- `assets/favicon.svg` - browser icon
- `staticwebapp.config.json` - Azure Static Web Apps routing and headers

## Preview locally

From this folder:

```powershell
python -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Deploy to Azure Static Web Apps

1. Push this folder to a GitHub repository.
2. In the Azure portal, create a Static Web App.
3. Choose the repository and branch.
4. Set the app location to `/`.
5. Leave the API location and output location blank.
6. Deploy.

## Before going live

- Confirm the contact details and Zeffy donation link are still current.
- Update programs, sponsors, and impact numbers with confirmed charity information.
