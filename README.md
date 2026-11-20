# Model Genealogy Hackathon

Public landing page for the December 5, 2026 hackathon at Constellation 6E,
8:30am–8pm Pacific. Participants identify the teachers behind distilled models.

Live site: <https://llmgenealogy.com/>

This is a static single page using HTML, CSS, and local SVG artwork. It requires no
build step, package installation, JavaScript, or application server.

## Preview locally

From this directory:

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

Open <http://127.0.0.1:8080>.

## GitHub Pages

Publish the root directory of the `main` branch from
`constellation-model-genealogy-hackathon/constellation-model-genealogy-hackathon.github.io`.
The `.nojekyll` file lets GitHub Pages serve the files directly. All page assets
use relative paths.

## Applications

The Apply buttons link to the hosted Google Form. The calendar download reserves
the event hours in Pacific time and retains the original event UID.

## Editing

- `index.html`: public event copy, navigation, and expandable FAQs.
- `style.css`: responsive layout, colors, and print/reduced-motion styles.
- `assets/genealogy.svg`: an illustrative model-lineage diagram, not measured results.
- `assets/mark.svg`: the page icon and wordmark symbol.
- `assets/save-the-date.ics`: the December 5 calendar event, 8:30am–8pm Pacific.

Only approved public event information belongs in this repository. Review page
copy, metadata, assets, and commit contents before publishing updates.
