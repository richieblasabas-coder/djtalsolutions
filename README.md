# The Rippling Views — PWA Website Starter

## What's included
- Responsive home page, feature stories, and editorial cartooning sections
- The supplied publication logo and blue/pink branding
- Poppins typography
- Demo Admin CMS to add, edit, and delete feature stories and cartoons
- Local browser storage for demo content
- PWA manifest and service worker for installability and basic offline caching

## Run locally
For the best PWA behavior, serve this folder over localhost or HTTPS. For example, if Python is installed:
`python -m http.server 8000`
Then open `http://localhost:8000`.

You can also upload the folder contents to a static host that supports HTTPS.

## Important before real publication use
This is a front-end prototype with placeholder content. The CMS stores edits only in the current browser using localStorage; it does not synchronize between editors or devices and has no login. Before public deployment, connect a secure backend/CMS, implement administrator authentication and role permissions, validate uploads, and review privacy/accessibility/security requirements. Replace sample stories, image URLs, authors, and dates with approved content. Some sample images use remote Unsplash URLs and need an internet connection.
