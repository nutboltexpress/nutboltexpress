# Nut Bolt Express - Version 1

Static GitHub Pages website for nutboltexpress.com.

## Stack
HTML5, custom CSS, vanilla JavaScript and JSON. No backend or build step.

## Local test
Run `python -m http.server 8000` from this directory and browse to http://localhost:8000.

## GitHub Pages
Publish the repository root from the main branch. The included CNAME targets nutboltexpress.com. Configure DNS and enable HTTPS in GitHub Pages settings.

## Important
The RFQ form creates a WhatsApp message and does not store submissions. Replace or expand legal/privacy pages before production if analytics or third-party forms are added.


## Local preview
The site has been revised so that pages, CSS, JavaScript, logo assets, navigation and the catalogue work when you open `index.html` directly from the extracted folder (`file://`) as well as when deployed to GitHub Pages.

For the closest match to production browser behaviour you can also serve the folder locally with `python -m http.server 8000`, but this is optional.
