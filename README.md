# Trinity Evangelical Lutheran Church, Dillsboro, Indiana

The church's website. The whole site is one file, `index.html`.

- Sunday times, the Visit, Beliefs, and Watch sections, and the contact details are plain text in `index.html`.
- The "News & Events" section holds announcements and a calendar of services and events. Each calendar item has a `data-date`; items whose date has passed hide themselves, and the box at the top shows the next Sunday service listed. An announcement with a `data-date` hides after that date; one without stays until it is removed.
- GitHub Pages publishes the `main` branch, so a change committed here goes live within a few minutes.
