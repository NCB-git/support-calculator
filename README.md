# Child Support Calculator

A small, browser-based calculator with illustrative child- and spousal-support estimates.

## Try it

The calculator is published on GitHub Pages:

**[Open the Child Support Calculator](https://ncb-git.github.io/support-calculator/)**

## Use

Enter the father's and mother's annual gross incomes, relationship duration, and number of children once. Province, primary residence, and age at separation are in the collapsed **Advanced inputs** section. Estimates appear together in the **Compare support scenarios** accordion. Spousal support only is shown when there are no children. Family inputs stay on the page and are not added to the URL.

### Child support

Enter the father's and mother's annual gross incomes, then select the number of children (choose **No children** for a child-free family). In **Advanced inputs**, select where the children primarily live. For a sole residence, the estimate uses the non-resident parent's income. For shared parenting, it estimates both table amounts and uses a simplified set-off. Shared parenting generally means each parent has at least 40% of parenting time. These are rough estimates and do not use official child support tables.

### Spousal support

Enter the father's and mother's annual gross incomes and relationship duration. The estimate assumes the higher-income spouse is the spousal-support payor. The **Advanced inputs** section asks for the lower-income spouse's age at separation, used only for the Rule of 65 duration test; age does not affect the estimated amount. Spousal support only is shown only when **No children** is selected.

The spousal-only estimate illustrates the Spousal Support Advisory Guidelines' basic amount and duration ranges: 1.5%–2% of the gross-income difference per relationship year, capped at 50%, and 0.5–1 year of duration per relationship year. It flags indefinite duration under the 20-year relationship or Rule of 65 tests (the Rule of 65 also requires at least five years together). The combined estimate shows net support after combining the estimated child- and spousal-support transfers. Positive combined amounts indicate a net transfer from the higher-income parent to the lower-income parent; negative amounts indicate the reverse. With no children, the combined spousal estimate uses the no-child formula.

## Important disclaimer

This calculator is for general information and demonstration purposes only. It does not use official child support tables, determine entitlement to spousal support, or account for all Spousal Support Advisory Guidelines adjustments. Shared parenting uses a simplified set-off and the combined estimate approximates each spouse's monthly net income using a rough 25% deduction from annual gross income; this is not a tax calculation and does not model individual taxes, benefits, or other adjustments. Actual support may differ based on applicable laws and individual circumstances. Check official resources and consult a qualified family law professional for advice about a specific situation.

## Run locally

No dependencies or build step are required. Open `index.html` in a web browser.

## Deployment

The GitHub Actions workflow in `.github/workflows/pages.yml` publishes the site to GitHub Pages when changes are pushed to the `main` branch, or when the workflow is run manually.
