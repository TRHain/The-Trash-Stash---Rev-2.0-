# Trash Stash Website Deployment

## Files

- `index.html` — complete responsive product landing page.
- `assets/trash-stash-workflow.png` — AI-rendered product/workflow image required by the page.
- `assets/trash-stash-rev2-board.jpeg` — optional Rev 2.0 product board fallback.

## Recommended Echo Werks location

Publish the page at:

`https://echowerks.com/trash-stash`

Add **Trash Stash™** as a primary navigation tab on EchoWerks.com.

If EchoWerks.com is served from a repository, copy `index.html` into the site's `/trash-stash/` route and copy both images into `/trash-stash/assets/`.

## Required image names

Upload the supplied images using these exact names:

1. `assets/trash-stash-workflow.png`
2. `assets/trash-stash-rev2-board.jpeg`

The page automatically falls back to the Rev 2.0 board if the workflow image is missing.

## GoDaddy forwarding

Configure permanent **301 forwarding**:

- `thetrashstash.com` → `https://echowerks.com/trash-stash`
- `www.thetrashstash.com` → `https://echowerks.com/trash-stash`
- `thetrashstash.shop` → `https://echowerks.com/trash-stash`
- `www.thetrashstash.shop` → `https://echowerks.com/trash-stash`

Use **forward only**, not masked forwarding. Masking can interfere with analytics, SEO, accessibility and social sharing.

When online ordering is ready, change the `.shop` domain to forward directly to the store or checkout route.

## Before launch

Update the email address `info@echowerks.com` in `index.html` if Echo Werks uses a different public inbox.

Confirm that Echo Werks owns or has permission to use all product photography, renderings, logos, fonts and trademarked names shown on the page.

## Intellectual-property notice

The footer currently states:

> Trash Stash™ and Hardware Saver™ are trademarks of Echo Werks LLC. Product design, documentation, imagery and associated intellectual property © 2026 Echo Werks LLC. All rights reserved.

The ™ symbol asserts a claimed trademark but is not the same as federal registration. Use ® only after the relevant mark is officially registered in the applicable jurisdiction.
