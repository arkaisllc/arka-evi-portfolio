# Design rationale: P&L variance report

## Reporting objective

Help an executive reader understand the operating-income gap, its effect on margin, and the financial drivers that warrant follow-up.

## Diagnostic observations

- The monthly table combines executive review and detailed lookup in one view.
- Exact cents create density without improving the variance decision.
- Red is applied to ordinary expense values, weakening its meaning as an exception signal.
- Gross profit and operating income do not receive enough visual hierarchy.
- The reader must calculate which line items explain the operating-income gap.

## Redesign specification

- Preserve the P&L sequence from revenue through operating income.
- Compare H1 actual, budget, and variance in aligned columns.
- Highlight gross profit and operating income as meaningful subtotals.
- Use red only for adverse variance and green for favorable variance.
- Add operating margin because it conveys the combined revenue-and-cost effect.
- Rank the variance drivers by absolute contribution.
- Retain monthly detail as a drill-through or supporting schedule.

## Validation

Operating income is $0.83M against a $1.40M budget, producing a $0.57M adverse variance. Operating margin is 9.9% against 16.0%, a 6.1-point gap after rounding.
