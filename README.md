# Solvara Ontario Calculator

An interactive six-year profit model for the Solvara Glass case (Imperium ARB 2026, Case 1). It compares two plants for supplying Northline Motors' Ontario windshield program:

- **Talavane, India**, shipped either entered into the US or in-bond to Canada
- **Harlow Springs, Ohio**, under different learning-curve paths

Move the sliders for freight, US duty, customs route, Indian wage growth and Ohio's yield, output and staffing. The page updates:

- the winner and the six-year profit gap
- each plant's six-year profit, year-4 cost and margin
- a profit-by-year chart
- the freight and duty levels at which the answer flips
- a year-by-year table

Preset buttons recreate the scenarios used in the deck.

## Run it

It is a single static file with no build step and no dependencies apart from Google Fonts.

- **Locally:** open `index.html` in a browser.
- **GitHub Pages:** push this folder to a repository, then go to **Settings → Pages**, set the source to the `main` branch, root folder. The calculator will be live at `https://<your-username>.github.io/<repo-name>/`.

## Model

Costs per set are rebuilt from case Exhibits 2–4 and reconcile to the case totals ($39.45 for Talavane, $60.47 for Harlow Springs). Program volumes and prices come from Exhibit 9, freight from Exhibit 8 and duty from Exhibit 10 (on a $45 declared value).

Assumptions added to the case data:

| Item | Assumption |
|---|---|
| Launch timing | Production starts 3 years after 2026 (adjustable) |
| Indian wages | +11% a year (case trend, adjustable) |
| In-bond cost | $0.30 per set for bond and brokerage (adjustable) |
| Ohio cost scaling | Materials, power and other per gross set; labour and depreciation per shift; SG&A per set |

All companies and figures are from a fictional competition case.
