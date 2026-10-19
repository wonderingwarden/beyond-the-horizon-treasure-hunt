# Beyond the Horizon — Pirate Treasure Hunt

A map-led, interactive pirate treasure hunt created for **Beyond the Horizon**, a student exhibition exploring materials and creative practice.

Players use two illustrated room maps to navigate the exhibition, follow animated clues, ask location-based questions, and enter answers into the website. Correct answers are recorded in the Captain’s Log, and the final answer stops the timer and celebrates the crew’s finish.

## Features

- **Two illustrated maps:** Map A — Room 1: The Voyage, and Map B — Room 2: Forbidden Zone.
- **Tap-to-enlarge maps** for easier viewing on phones and computers.
- **Animated clue reveal** and a highlighted map to guide players to the relevant room.
- **Running timer** with completion time and split times.
- **Captain’s Log** showing accepted keywords and when each was found.
- **Input feedback** for incorrect and repeated answers.
- **Victory animation** when the hunt is completed.
- **Responsive layout** with reduced-motion support.
- **No backend or build step:** the site is plain HTML, CSS, and JavaScript.

## Preview

Open `index.html` locally in a modern browser, or publish the repository with GitHub Pages.

## Repository structure

```text
beyond-the-horizon-treasure-hunt/
├── index.html
├── assets/
│   ├── room1-map.jpg
│   └── room2-map.jpg
├── README.md
├── CONTRIBUTING.md
├── SECURITY.md
├── .gitignore
├── vercel.json
└── .github/
    └── ISSUE_TEMPLATE/
        ├── bug_report.md
        └── feature_request.md
```

## Run locally

1. Download or clone this repository.
2. Keep `index.html` and the `assets/` folder together.
3. Open `index.html` in a modern browser.

No package installation, framework, server, or build command is required.

## Publish with GitHub Pages

1. Create a GitHub repository named `beyond-the-horizon-treasure-hunt`.
2. Upload the **contents** of this project folder to the repository root. Make sure `index.html` is at the root and `assets/` is beside it.
3. Open **Settings → Pages**.
4. Under the build and deployment settings, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Wait for GitHub Pages to finish deploying. The published URL will appear in the Pages settings.

The included `vercel.json` is optional and only relevant if you choose to deploy through Vercel instead.

## Customise the hunt

Open `index.html` and find the `EDIT YOUR HUNT HERE` section near the end of the file.

- `KEYWORDS` contains the accepted answers for the first five stages.
- `FINAL_KEYWORD` contains the answer that completes the hunt.
- `STAGES` contains the clue text and the map (`'A'` or `'B'`) highlighted for each stage.

When editing, ensure that the keywords match the answers players receive from the location characters, and that every stage and final answer matches the physical exhibition. Test the full hunt from start to finish after making changes.

## Privacy and security

- The game does not send answers, player names, or completion times to a server.
- Progress and timing exist only in the current browser page. Refreshing or leaving the page resets the hunt.
- The page does not require API keys, credentials, or environment variables.
- Google Fonts are loaded from Google’s servers; a visitor’s browser may contact Google to retrieve the fonts. If you want to avoid this third-party request, remove the Google Fonts stylesheet link and use the local fallback fonts defined in the CSS.
- Keep the two map images in `assets/` at their current paths unless you also update the image paths in `index.html`.

## Credits and publishing rights

Created for the **Beyond the Horizon** student exhibition. The interactive website was developed collaboratively; the clue and question writing was contributed by Diya.

Before making this repository public, confirm that every collaborator agrees to publish the code, clue text, and map artwork, and that you have permission to publish any third-party material included in them. This repository intentionally does **not** include an open-source licence: add one only after the relevant contributors have agreed on the licensing terms.

## Known limitations

- There is no shared scoreboard or persistent record; refreshing the page resets the current run.
- The timer runs in the visitor’s browser and is intended for a live, informal exhibition game, not for audited competition timing.
- The site relies on an internet connection to load the selected Google Fonts. The rest of the experience is local static content.

## Suggested GitHub topics

`interactive-experience` · `treasure-hunt` · `student-project` · `html` · `css` · `javascript` · `github-pages`
