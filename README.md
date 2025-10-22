# ShareVolume App

## How to run
1. Open `index.html` in a web browser.
2. Use `index.html?CIK=<10-digit CIK>` to fetch data for different companies.

## Features
- Fetches share volume data and displays maximum/minimum shares outstanding.
- Dynamically updates content based on the CIK provided in the URL.

## Accessibility
- Includes ARIA roles and semantic structure for assistive technology compatibility.

## Design tokens (CSS variables/palette)
- Main colors used for the application are defined in `style.css`.

## API endpoints used
- SEC API: `https://data.sec.gov/api/xbrl/companyconcept/CIK0000002969/dei/EntityCommonStockSharesOutstanding.json`

## Attachments used
- `uid.txt`

## Keyword coverage
| Keyword/Phrase | Implementation |
|-----------------|----------------|
| Air Products | entityName field in data.json |
| Shares Outstanding | Maximum and Minimum shares data displayed |
| fetch data.json | Fetch data using the SEC endpoint |
| ?CIK= query parameter | supports query to get alternate company data |

## Changelog: Round 1
- Implemented fetching of share volume data from SEC API.
- Structured HTML and CSS for a professional layout.
- Implemented dynamic updates based on the provided CIK in the URL.