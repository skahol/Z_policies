# Game Policies

Privacy Policies and Terms of Service for mobile games, hosted via GitHub Pages.

## Structure

```
Z_policies/
├── _config.yml           # Jekyll configuration
├── index.md              # Landing page
├── sudoku-spark/         # Sudoku Spark game policies
│   ├── index.md
│   ├── privacy-policy.md
│   └── terms-of-service.md
└── [future-game]/        # Add more games as needed
```

## URLs (after GitHub Pages setup)

**Default GitHub Pages URL:**
- Privacy Policy: `https://skahol.github.io/Z_policies/sudoku-spark/privacy-policy`
- Terms of Service: `https://skahol.github.io/Z_policies/sudoku-spark/terms-of-service`

**With Custom Domain (e.g., policies.yourdomain.com):**
- Privacy Policy: `https://policies.yourdomain.com/sudoku-spark/privacy-policy`
- Terms of Service: `https://policies.yourdomain.com/sudoku-spark/terms-of-service`

## Setup GitHub Pages

1. Go to repo **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / **(root)**
4. Click **Save**

## Adding Custom Domain (Optional)

1. In GitHub Pages settings, enter your custom domain
2. Add DNS records with your domain provider:
   - For subdomain (e.g., policies.example.com): Add CNAME record pointing to `skahol.github.io`
   - For apex domain: Add A records pointing to GitHub's IPs
3. Enable "Enforce HTTPS"

## Adding New Games

1. Create a new folder: `[game-name]/`
2. Add `privacy-policy.md` and `terms-of-service.md`
3. Update the root `index.md` with links
4. Commit and push

## Contact

sudoku.spark@gmail.com
