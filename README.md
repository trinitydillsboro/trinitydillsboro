# Trinity Evangelical Lutheran Church, Dillsboro, Indiana

The church's website. The whole site is one file, `index.html`.

- Sunday times, the Visit, Beliefs, and Watch sections, and the contact details are plain text in `index.html`.
- The "News & Events" section holds announcements and a calendar of services and events. Each calendar item has a `data-date`; items whose date has passed hide themselves, and the box at the top shows the next Sunday service listed. An announcement with a `data-date` hides after that date; one without stays until it is removed.
- The blue "Christmas at Trinity" band under the opening hides each line after its date and hides itself after New Year's Eve. Reuse it for Lent and Easter by changing its dates and lines.
- Photos are in the `images` folder. The sanctuary photo has a wide version for tablets and computers and a narrower crop for phones; the page picks the right one. Following the photo guideline in the website proposal, the building and sanctuary may be shown freely, members only with their permission, and children only with a parent's permission and never with their names. Anything added to this repository stays in its public history, so check a photo before adding it.
- `favicon.svg`, `favicon-32.png`, and `apple-touch-icon.png` are the tab and home-screen icons. `share-card.png` is the picture shown when someone shares a link to the site; when the site moves to trinitydillsboro.org, change the `og:image` address in `index.html` to match.
- GitHub Pages publishes the `main` branch, so a change committed here goes live within a few minutes.
