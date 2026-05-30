# Agent Notes

## Project overview
- Static HTML/CSS/JS fitness website with jQuery plugins and Bootstrap.
- No build system or test runner in this repo.
- SCSS sources exist under assets/scss, but compiled CSS lives under assets/css.
- Contact form uses a PHP endpoint at contact_process.php.

## Start here
- README: ../README.md
- Homepage: ../index.html
- Main scripts: ../assets/js/main.js
- Main styles (compiled): ../assets/css/main.css
- SCSS entrypoint: ../assets/scss/style.scss
- Contact form page: ../contact.html
- Contact handler: ../contact_process.php

## Development workflow
- Edit HTML files directly (index.html, about.html, pricing.html, etc.).
- For styles: update SCSS in assets/scss and recompile externally if needed, or edit compiled CSS in assets/css for quick changes.
- For scripts: update assets/js/*.js and ensure dependencies remain in assets/js/vendor.

## Notes and pitfalls
- There is no local build command; open HTML files directly in a browser to preview.
- The PHP contact handler may not work on static hosting providers; changes to contact_process.php should be treated carefully.
