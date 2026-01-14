# JEZUSPOP

A minimal, bold linktree-style personal website with a monochromatic black and white aesthetic.

## Features

- Single-page linktree design
- Bold typography and clean animations
- Fully responsive
- Black and white color scheme
- Smooth hover interactions

## Deployment

### GitHub Pages

1. Push this repository to GitHub
2. Go to Settings → Pages
3. Set Source to "Deploy from a branch"
4. Select `main` branch and `/ (root)` folder
5. Click Save

Your site will be live at `https://yourusername.github.io/repository-name/`

### Custom Domain

To use with jezuspop.com:

1. Add a `CNAME` file to the root directory containing `jezuspop.com`
2. Configure your DNS settings:
   - Add an A record pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - Or add a CNAME record pointing to `yourusername.github.io`
3. Enable "Enforce HTTPS" in GitHub Pages settings

## Customization

Edit `index.html` to update:
- Tagline text
- Link destinations and labels
- Social media links
- Copyright year

## File Structure

```
jezuspop-site/
├── index.html       # Main website file
├── images/
│   └── logo.png     # Jezuspop logo
└── README.md        # This file
```

## License

© 2026 Jezuspop
