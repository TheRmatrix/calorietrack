# CalorieTrack 1.0

CalorieTrack 1.0 is the new stable release line for the CalorieTrack web app.

## Release numbering

This release resets the project to **1.0**. Future releases will use:

- 1.1 — feature/fix update
- 1.2 — feature/fix update
- 1.3 — feature/fix update
- etc.

We will no longer use the old v41/v42-style numbering for normal releases.

## Design and architecture direction

The functionality roadmap is informed by the open-source nutrition tracker OpenNutriTracker, while the CalorieTrack implementation remains a web-first HTML/CSS/JavaScript application and keeps the existing CalorieTrack UI.

OpenNutriTracker: https://github.com/simonoppowa/OpenNutriTracker

CalorieTrack is not copying Flutter source code from OpenNutriTracker. Equivalent functionality is implemented for GitHub Pages/Safari using CalorieTrack's own code.

## Included in 1.0

- Calorie and macro tracking
- Suggested calorie and macro targets
- Cut / bulk / maintain goals
- Goal-weight validation
- Food search
- Open Food Facts barcode lookup
- Live barcode scanner
- Camera Roll barcode scanning
- Manual barcode entry
- Custom foods
- Saved meals
- Recipes
- Portion calculator
- Drink tracking
- Water tracking
- Manual steps tracking
- Weight history and trend
- Workout tracking and PRs
- Female menstrual-cycle tracker
- Supplements
- Dark mode
- Local-first storage
- JSON backup/restore
- CSV food export
- iPhone/Safari-focused UI

## Privacy

Personal tracker data is stored locally in the browser. There is no CalorieTrack account or central diary database.
