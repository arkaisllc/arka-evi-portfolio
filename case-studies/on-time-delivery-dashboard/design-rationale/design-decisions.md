# Design rationale: on-time delivery dashboard

## Reporting objective

Help operations leadership understand the service decline, identify the dominant exception causes, and focus the first corrective review.

## Diagnostic observations

- KPI cards and gauges emphasize current status without showing the sustained decline.
- Up and down arrows omit the comparison period and magnitude.
- OTIF, on-time, and in-full measures repeat related information at equal visual weight.
- The order-detail table supports investigation but does not reveal cause concentration.
- The 95% target is separated from the trend.

## Redesign specification

- Lead with the 4.6-point six-month decline.
- Show June OTIF and its 5.4-point gap to target.
- Plot the monthly trend against a visible 95% target line.
- Rank exception causes by share of recorded exceptions.
- State that the top two causes account for 61% of exceptions.
- Direct the first review toward carrier capacity and picking windows.
- Retain order-level detail for drill-through and ownership assignment.

## Validation

OTIF moves from 94.2% in January to 89.6% in June, a decline of 4.6 percentage points. June is 5.4 points below the 95% target. Carrier capacity and picking delays total 61% of recorded exceptions.
