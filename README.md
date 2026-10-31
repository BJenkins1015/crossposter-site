# crossposter-site

Static pages for CrossPoster, served by GitHub Pages at https://bjenkins1015.github.io/crossposter-site/

- `index.html` — home page
- `privacy.html` — privacy policy (`#delete` has the data-deletion instructions Meta asks for)
- `terms.html` — terms of service
- `oauth/callback.html` — sign-in redirect for Meta and TikTok; forwards `code`/`state`/`error*` to `crossposter://oauth/callback`

Plain HTML and CSS, no build step. `.nojekyll` tells GitHub Pages to serve the files as they are.
