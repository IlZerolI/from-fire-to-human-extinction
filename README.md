# From Fire to Human Extinction

Presentation companion website for an 18-number class roster, exploring innovations that built civilisation and how they could threaten it. Student 18 is excluded, leaving 17 assigned students.

## Project files

- `index.html` — responsive presentation website, timeline, fixed team assignments, and QR code.
- `qrcode-generator.min.js` — locally bundled QR encoder (MIT licensed).
- `qrcode-generator.LICENSE.txt` — QR encoder license.
- `GROUP_ASSIGNMENTS.md` — team topics and assignment instructions.
- `From fire to human extinction.pptx` — the slide deck.

## Teams

The nine timeline topics are arranged into four teams. Student numbers 1–17 are randomly assigned once to balanced teams of four or five; student 18 is excluded. Entering the same number again—on the same or another phone—always returns the same team. The page shows team totals, not names.

| Team | Topics | Students |
|---|---|---:|
| 1 | Agriculture; Nuclear Fission | 5 |
| 2 | Steam Engine; Transistor; Recombinant DNA | 4 |
| 3 | Printing Press; World Wide Web | 4 |
| 4 | Mastery of Fire; Artificial Intelligence | 4 |

This works as a static GitHub Pages site, so no database or backend setup is required.

## Features

- Animated particle background and responsive, dark futuristic design.
- Interactive innovation timeline with detail modals.
- Fixed, balanced assignments that stay the same on every scan.
- Locally generated QR code for the canonical GitHub Pages URL, with PNG download and copy-link actions.
- No build step or external service required.

## Edit and preview

Edit `index.html` to change the timeline or page content. The `teamTopics` array determines the innovation topics, and `studentTeamByNumber` holds the fixed student-to-team mapping. If you change the mapping, assign each number from 1–17 exactly once, leave 18 unassigned, and keep each team at four or five students.

Run a local HTTP server to preview the page, or open `index.html` directly in a browser.

## GitHub Pages

The site is published from the `main` branch and repository root:

- Site: https://ilzeroli.github.io/from-fire-to-human-extinction/
- Repository: https://github.com/IlZerolI/from-fire-to-human-extinction

Push changes to `main` to publish an update.
