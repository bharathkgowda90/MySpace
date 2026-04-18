# Images Setup Guide

This portfolio site uses local images instead of external CDN links for better performance and reliability.

## Current Status

The HTML references local image paths under `images/`. Add or replace assets in those folders as needed for your deployment.

## SVG Icons Available

The following SVG icons are included:

- **UI Icons**: `images/icons/dropdown-arrow.svg`, `images/icons/arrow-right-circle.svg`, `images/icons/arrow-right-circle-white.svg`
- **Social Icons**: `images/social/youtube.svg`, `images/social/twitter.svg`, `images/social/instagram.svg`
- **Placeholder Logo**: `images/icons/logo-placeholder.svg`

## Image Directory Structure

```
images/
├── icons/           # Favicons, logos, UI icons
├── emojis/          # Emoji images
├── resources/       # Resource card backgrounds
├── work/            # Work section images
└── social/          # Social media icons
```

## Manual assets

If you need to fetch or recreate assets from an external CDN, download them with your browser, `curl`, or another tool and place them at the paths referenced in the HTML.

## Notes

- SVG icons in `images/icons` and `images/social` are already in the repo where listed above.
- Use `src` / `srcset` paths in HTML as the single source of truth for which files each page expects.
