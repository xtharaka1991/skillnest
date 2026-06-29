# SKILLNEST Academy Static Website

This folder contains a single-page static website for the SKILLNEST Academy course catalog.

## Included files

- `index.html` - single-page site with hero, sticky course nav, all 5 courses, and contact footer
- `css/styles.css` - responsive styling and accessibility-focused presentation
- `PLAN.md` - full implementation plan and syllabus source content

## Course coverage

All five courses are included with mandatory fields:

- Course name
- Full 12-week content table
- Duration (12 weeks, ~30 contact hours)
- Price placeholder (`Contact for pricing`)

## Local preview

Open `index.html` directly in your browser.

PowerShell option:

```powershell
Set-Location c:\work\dev\private\skillnest
Start-Process .\index.html
```

## Deploy options

### GitHub Pages

1. Push repository to GitHub.
2. In repository settings, open Pages.
3. Set source branch and folder (root or `/website`, based on your repo setup).
4. Save and wait for publishing.

### Netlify

1. Open Netlify and create a new site from drag-and-drop.
2. Drop the `website/` folder.
3. Use generated URL or attach a custom domain.

## Updating prices

Find each line like:

```html
<p class="price"><strong>Price:</strong> Contact for pricing</p>
```

Replace text with your final fee and optional installment details.
