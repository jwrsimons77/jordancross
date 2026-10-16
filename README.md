# Jordan Crosse Coaching website

Static HTML and CSS website for Jordan Crosse Coaching, deployed from the `main` branch to the connected Netlify site `jordancrossept`.

## Run locally

Run `python3 -m http.server 8000` from the repository root and open http://localhost:8000/ . No build step or JavaScript framework is required.

## Structure

Each page lives in its own directory as `index.html`. Shared styles are in `assets/site.css`. Netlify reads `_headers`, `_redirects` and `netlify.toml` from the repository root.

## Update content

Search for prices `£45`, `£540`, and `£60` in HTML files and structured data before changing offers. Contact details are in the shared header/footer markup repeated on each HTML page. WhatsApp uses `447478743023`, email is `jordancrosse_pt@hotmail.com`, and booking CTAs use prefilled WhatsApp enquiries (wa.me/447478743023). Update every occurrence when details change. Review sitemap.xml after adding pages.

## Editorial checks

`TODO` means the detail is not verified. Tom's testimonial is an unapproved draft on the reviews page. Do not represent it as verified feedback before written approval. Do not publish invented reviews, rating values, opening hours, parking arrangements, drive times, qualifications or class availability. The original Shopify-hosted photo is not yet self-hosted. The privacy page requires legal review before being relied upon as a complete policy.

## Deployment

Pushing to `main` triggers the existing Git-connected Netlify build (publish directory `.`). Verify the production deploy and mobile experience in Netlify after each push. The Netlify preview does not automatically replace the original domain.

## SEO and launch checklist

The Netlify preview intentionally returns `X-Robots-Tag: noindex, nofollow` in `_headers` to avoid indexing the staging site while the original domain is live. **Remove this header before switching the production domain to this site**, otherwise the new production site will be excluded from search. Check the published HTTP response, not just the file.

The canonical domain and sitemap are set to `https://jordancrosse.co.uk/`. After the domain switch, submit the sitemap in Google Search Console, run Google's Rich Results Test and URL Inspection on the live domain, and check mobile Core Web Vitals. The preview is not a substitute for production validation.

Online coaching now links directly to the Everfit package `https://coach.everfit.io/package/KI143539`. Confirm the price and package terms shown by Everfit before promoting any offer. In-person taster booking enquiries use WhatsApp.

Remaining editorial confirmations: single PT session price; current Everfit package inclusions and billing; indoor cycling venue, timetable and price; parking details; precise venue coordinates and opening hours; Jordan's approved biography and qualification providers; privacy policy legal review; authentic Google rating if any. The Shopify-hosted photo remains a dependency until a properly licensed local copy is available.
