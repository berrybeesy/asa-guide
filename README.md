# ASA Full Guide

A web version of the **ASA Full Guide** for Adobe Student Ambassadors (ASA) at the University of Utah.

I turned our 30-page PDF handbook into a booklet-style website that new members can open from a QR code on campus posters. It covers everything a new ambassador needs: getting started, running workshops, tabling, event promotion, budget and points, and what to do after an event.

## Highlights

- **Booklet layout:** a fixed sidebar with the table of contents, and full-screen pages that turn sideways with the mouse wheel, trackpad swipe, or arrow keys.
- **Reading progress:** a thin progress bar in the sidebar, and the current chapter is highlighted in the contents.
- **Interactive checklists:** workshop and tabling checklists with progress bars. Checked items are saved in the visitor's browser.
- **One place for links:** every form and social link is defined once in a `LINKS` object at the bottom of `index.html`. An empty value hides that link everywhere.
- **Mobile:** a compact top bar with a menu, and pages still turn sideways with a swipe.
- **No build step:** a single HTML file with inline CSS and JavaScript, set in Pretendard.

## Run locally

Open `index.html` in a browser.

## Deploy

Import this repository into Vercel (or any static host). No framework or build settings are needed.

---

© 2026 All rights reserved. Created by [Teresa Park](https://www.linkedin.com/in/parkteresa/).
University of Utah and Adobe logos belong to their respective owners.
