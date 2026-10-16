# Jordan Crosse Coaching website

Static HTML and CSS website for Jordan Crosse Coaching, deployed from the `main` branch to the connected Netlify site `jordancrossept`.

## Run locally

Run `python3 -m http.server 8000` from the repository root and open http://localhost:8000/ . No build step or JavaScript framework is required.

## Structure

Each page lives in its own directory as `index.html`. Shared styles are in `assets/site.css`. Netlify reads `_headers`, `_redirects` and `netlify.toml` from the repository root.

## Update content

Search for prices `£45`, `£540`, and `£60` in HTML files and structured data before changing offers. Contact details are in the shared header/footer markup repeated on each HTML page. WhatsApp uses `447478743023`, email is `jordancrosse_pt@hotmail.com`, and the booking CTA uses the Setmore URL. Update every occurrence when details change. Review sitemap.xml after adding pages.

## Editorial checks

`TODO` means the detail is not verified. Do not publish invented reviews, rating values, opening hours, parking arrangements, drive times, qualifications or class availability. The original Shopify-hosted photo is not yet self-hosted. The privacy page requires legal review before being relied upon as a complete policy.

## Deployment

Pushing to `main` triggers the existing Git-connected Netlify build (publish directory `.`). Verify the production deploy and mobile experience in Netlify after each push. The Netlify preview does not automatically replace the original domain.
