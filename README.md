# Transparent Formula Reference: Marginal Tax, Paid Leave Caps & Rent Ratios

Documentation of common calculation pitfalls when estimating net take-home pay, statutory parental/medical leave replacement benefits, and housing affordability ratios.

## Core Formula Notes
1. **Piecewise marginal brackets vs. flat effective rate**: Always integrate bracket widths `sum_i max(0, min(income, upper_i) - lower_i) * rate_i` before dividing by gross income for effective rate.
2. **Weekly benefit caps on statutory leave**: Apply wage-tier replacement percentages first, then clamp `min(raw_weekly_benefit, statutory_max_weekly_cap)`.
3. **Gross vs. net rent-to-income**: Distinguish `30%` gross-income rule of thumb from post-tax, post-fixed-debt cashflow coverage.

## Interactive Browser Calculators
- **Live suite (no signup)**: [OneTaskKit — Precision Micro Utilities for Professionals](https://onetaskkit.com/)
