# RokFort Website - Complete Package

## Structure

```
rokfort-complete-site/
├── index.html                          # Landing page (black background, two boxes)
├── rokfort-capital-logo.png           # Capital logo (for landing page)
├── advisory-logo.png                   # Advisory logo (construction crane version)
│
├── capital/                            # Search Fund Division
│   ├── index.html                      # English version
│   ├── index-fr.html                   # French version
│   └── 20260206_RokfortCapital.png    # Logo
│
└── advisory/                           # Advisory Division
    └── index.html                      # English only
```

## Deployment to GitHub Pages

1. **Go to:** https://github.com/romancelll/SearchFund2
2. **Delete all current files** (or create a new repository)
3. **Upload ALL files and folders** from this package
4. **Enable GitHub Pages:** Settings → Pages → main branch
5. **Your site will be live at:** https://romancelll.github.io/SearchFund2/

## URLs Structure

- **Landing:** https://romancelll.github.io/SearchFund2/
- **Capital (EN):** https://romancelll.github.io/SearchFund2/capital/
- **Capital (FR):** https://romancelll.github.io/SearchFund2/capital/index-fr.html
- **Advisory:** https://romancelll.github.io/SearchFund2/advisory/

## To Customize

### Advisory Profile Section
Edit `/advisory/index.html`:
- Replace `[Your Photo Here]` placeholder with your actual photo
- Update the bio text in the profile section
- Image should be named something like `roman-profile.jpg` and placed in `/advisory/` folder

### Email
Currently set to: `roman@rokfort.com`
To change, search and replace in all HTML files.

## Custom Domain Setup

When you buy `rokfort.com`:
1. In GitHub: Settings → Pages → Custom domain → Enter `rokfort.com`
2. In your domain registrar (Namecheap/Google): Update nameservers as GitHub instructs
3. Wait 10-60 minutes for DNS propagation

## Notes

- Landing page is intentionally minimal (black background, two elegant boxes)
- Capital section is fully bilingual (English/French)
- Advisory section is English only
- Profile section in Advisory has placeholder for your photo and editable bio text
