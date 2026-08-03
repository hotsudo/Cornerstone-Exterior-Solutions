# Cornerstone Exterior Solutions

Hugo website for Cornerstone Exterior Solutions, configured for Hugo Extended 0.164.0 and Netlify.

## Local development

Run `hugo server` and open the local address shown by Hugo.

## Production build

Run `hugo --gc --minify`. The generated site is written to `public/`.

## Netlify

The repository includes `netlify.toml` with the production build command, publish directory, Hugo version, security headers, and contact-success redirect.

The contact page uses Netlify Forms with a honeypot field. After the first deploy, confirm that the `contact` form appears in Netlify and add an email notification for `info@cornerstoneexteriorsolutions.co` under the site’s form notification settings.

## Site content

- Company contact information is stored in `data/company.yml`.
- Main page content is stored in `content/`.
- Existing images are stored in `static/` and the root site icon remains in place.
