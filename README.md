# Loan & Compound Interest Calculator

Mortgage, car and personal loan payments with a full amortization schedule and extra-payment what-ifs, plus a compound growth mode. Runs entirely in your browser.

**Live:** <https://loan-calculator.slippylabs.com/>

## What it does

- Mortgage, car and personal loan payments with the full amortization schedule.
- Extra-payment what-ifs: what one more payment a month actually saves in interest and in time.
- A separate compound savings-growth mode.
- Weekly, fortnightly, monthly, quarterly or yearly periods; five currency symbols; CSV export.

## How it works

Every row is rounded to cents as it is computed rather than at the end, so a three-hundred-row schedule still adds up to the stated total instead of drifting. The final payment is the balancing one — it clears exactly what is left rather than overshooting. And if the payment does not cover the interest the schedule says so, instead of looping until it gives up: that debt genuinely never amortizes.

## Run it locally

A static site. No build step, no package manager, no dependencies:

```
git clone git@github.com:slippylabs/loan-calculator.slippylabs.com.git
cd loan-calculator.slippylabs.com
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

---

Part of [Slippy Labs](https://slippylabs.com). Every tool is indexed at
[projects.slippylabs.com](https://projects.slippylabs.com).
