# Macroeconomic Data Lab

Independent student research portfolio by Ege Umut Can (FMV Işık High School, Istanbul).

Live site: https://ege211.github.io/macroeconomic-data-lab/

## What is here

- `index.html`: the whole site in one file. The Data Lab chart compares annual real GDP growth and consumer-price inflation for Turkey, the United States, Germany, the United Kingdom and Japan, 2019 to 2023.
- `papers/`: PDFs of my essays, papers and case studies, and my CV.
- `data/`: monthly data behind the Firm Finance Tools tab: TCMB one-week repo rate changes, TURKSTAT CPI (annual and monthly change), and the real policy rate built from them. Each file has a source column.

The Firm Finance Tools tab has a real interest rate chart (policy rate minus inflation, January 2019 to October 2026) and a factoring cost calculator. Real rate = (1 + policy rate) / (1 + annual CPI inflation) minus 1, using the policy rate in force at the end of each month.

## Data

World Bank Open Data API v2, indicators `NY.GDP.MKTP.KD.ZG` (real GDP growth) and `FP.CPI.TOTL.ZG` (CPI inflation). The page shows saved values first, then requests live values from the API and replaces them. If the request fails, the saved values stay on screen.

## Related repositories

- https://github.com/ege211/strategic-capital-allocation-investment-banking
- https://github.com/ege211/ai-assisted-equity-valuation
- https://github.com/ege211/global-financial-crisis-ews
