# FlippedStat

The site is provided as a self-contained HTML page with its content, styles,
and application scripts embedded in `index.html`.

## Run locally

From the repository root, start a local web server:

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000> in a modern browser with JavaScript enabled.
There is no build step or package installation.

The HTML page is intentionally kept intact from the supplied FlippedStat
website. Optional browser features may load their runtime dependencies only
when used.

## Public website

Try the public demo:

<https://michaelkwkan.github.io/TDLEG-FlippedStat/>

The `Deploy to GitHub Pages` workflow publishes updates on every push to
`main`. The repository and its source are public, but visitors only need the
demo link; they do not need Git or a GitHub account.
