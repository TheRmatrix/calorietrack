# CalorieTrack 1.2

CalorieTrack is a local-first, iPhone-friendly nutrition tracker designed for GitHub Pages.

## 1.2 highlights

- Multi-source food lookup using Open Food Facts first and USDA FoodData Central as a secondary source.
- Barcode lookup checks the local CalorieTrack product cache, global/regional Open Food Facts endpoints, then USDA branded/reference data.
- Search combines Open Food Facts and USDA results with duplicate removal.
- Common EAN/UPC barcode representations are normalized before lookup.
- Products manually added after an unsuccessful scan are cached locally for future scans.
- Home weight card is tied to the same dedicated weight history used by Progress.
- Legacy daily weight records are migrated into the dedicated weight history.
- Existing CalorieTrack local data is preserved.

## Data/privacy note

Personal tracking data remains in the browser's local storage. Food lookups require network requests to the selected external food databases. USDA's public `DEMO_KEY` is used only as a best-effort secondary fallback and may be rate limited; the app never depends on it and manual entry remains available.

## Versioning

Release numbering now starts at 1.0 and increments as 1.1, 1.2, 1.3, etc.
