edu.inversebits.ai static site

This folder contains the static site to be deployed to GitHub Pages for the subdomain `edu.inversebits.ai`.

How to deploy (locally):

1. Open PowerShell in this folder: `d:\Projects\Web\InverseBit-Web\edu-site`
2. Install dev dependencies: `npm install`
3. Run deploy script: `npm run deploy`

This publishes the current folder to the `gh-pages` branch using the `gh-pages` package. The `CNAME` file maps the site to `edu.inversebits.ai`.
