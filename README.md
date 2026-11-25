# AnranQi.github.io

## Updating the news

The homepage news is in the `#News` section of `index.html`; its styles are scoped
to `#News` at the end of `site.css`. No build step or JavaScript is required.

Add new items at the top of the first `.news-list`, in reverse chronological
order. Keep ten recent entries visible and move older entries into the
`<details class="news-archive">` list. Update the archive's year range as needed.
Use a machine-readable date on `<time>` (`YYYY-MM`, or `YYYY` for a season),
brief announcement text, and public project or conference links.

Use confirmed acceptance or participation dates. Do not include private email
links, review details, travel logistics, or unconfirmed invitations in the page.

To preview locally, run `python3 -m http.server 8000` from this folder and open
`http://localhost:8000/`.
