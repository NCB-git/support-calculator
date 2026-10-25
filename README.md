# Child Support Calculator

A small, browser-based calculator with illustrative child- and spousal-support estimates.

## Try it

The calculator is published on GitHub Pages:

**[Open the Child Support Calculator](https://ncb-git.github.io/support-calculator/)**

## Use

Enter the family's shared information once. Province, number of children, and age at separation are in the collapsed **Advanced inputs** section. All three estimates appear together in the **Compare support scenarios** accordion. Inputs are reflected in the page URL, so the family details can be shared by copying the URL.

### Child support

Enter the payor's province or territory, number of children, and annual gross income. The monthly estimate updates automatically. This simplified estimate does not use official child support tables.

### Spousal support

Enter the higher- and lower-income spouses' annual gross incomes and relationship duration. The spousal-only mode also asks for the lower-income spouse's age at separation, used only for the Rule of 65 duration test; age does not affect the estimated amount. Combined mode does not estimate duration.

The spousal-only estimate illustrates the Spousal Support Advisory Guidelines' basic amount and duration ranges: 1.5%–2% of the gross-income difference per relationship year, capped at 50%, and 0.5–1 year of duration per relationship year. It flags indefinite duration under the 20-year relationship or Rule of 65 tests (the Rule of 65 also requires at least five years together). The combined estimate calculates child support using the higher-income spouse's income and estimates spousal support using a 40%–46% recipient share of disposable income after child support. The combined result shows both estimated amounts and their total range; duration is not estimated in this scenario. All scenarios assume the higher-income spouse pays support.

## Important disclaimer

This calculator is for general information and demonstration purposes only. It does not use official child support tables, determine entitlement to spousal support, or account for all Spousal Support Advisory Guidelines adjustments. The combined mode estimates each spouse's monthly net income using a rough 25% deduction from annual gross income; this is not a tax calculation and does not model individual taxes, benefits, or other adjustments. Actual support may differ based on applicable laws and individual circumstances. Check official resources and consult a qualified family law professional for advice about a specific situation.

## Run locally

No dependencies or build step are required. Open `index.html` in a web browser.

## Deployment

The GitHub Actions workflow in `.github/workflows/pages.yml` publishes the site to GitHub Pages when changes are pushed to the `main` branch, or when the workflow is run manually.
