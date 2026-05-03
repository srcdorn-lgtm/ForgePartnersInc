# Forge Partners, Inc. — Website

Official website for [forgepartnersinc.com](https://forgepartnersinc.com)

Built with HTML, CSS, and vanilla JavaScript. No frameworks, no build step required.

## Files

| File | Description |
|------|-------------|
| `index.html` | Main homepage |
| `team.html` | Team bios page |
| `CNAME` | Custom domain configuration for GitHub Pages |

## Deployment

This site is deployed via **GitHub Pages** with a custom domain.

Any commit pushed to the `main` branch is automatically published live.

## To add a new blog post

Open `index.html`, find the `<!-- BLOG MODALS -->` section, and duplicate one of the existing `modal-overlay` blocks with a new `id`. Then add a matching `blog-card` in the `#blog` section pointing to the new modal id.

## To add a team member

Open `team.html`, find the `<!-- CONSULTANT SECTION -->` and duplicate the `consultant-card` block.

## To update contact details

Search for `forgepartnersinc.com` in both files and replace with current information.

---

*The Stress Test™ and Strength Index™ are proprietary trademarks of Forge Partners, Inc.*
