# Design rationale

## Reporting objective

Help a business reader identify the highest-selling categories and judge the size of the differences between them.

## Diagnostic observations

### The chart does not match the task

A pie chart emphasizes part-to-whole composition. The stated business question requires ranking and comparison across fifteen categories. Lengths measured from a common baseline support that task more directly than angles and areas.

### The legend increases visual effort

The reader repeatedly moves between a colored slice and a separate legend. Direct labels keep the category name and value with the mark they describe.

### Color carries more weight than meaning

Fifteen unrelated colors imply fifteen distinctions that the reader must remember. A restrained single-color treatment leaves room to use emphasis later for an exception, target, or selected category.

### Precision exceeds the decision need

Cents are valid in the underlying data, but they do not help a reader compare annual category sales at this scale. The redesign displays values in millions to one decimal place and retains exact amounts in the supporting table.

### The title misses the finding

“Annual Sales by Category” identifies the subject. “Electronics and Furniture lead sales; top five contribute 64%” communicates what the chart shows.

## Redesign specification

- Use a horizontal bar chart with a zero baseline.
- Sort categories from highest to lowest annual sales.
- Place category labels to the left of each bar.
- Place rounded values at the end of each bar.
- Use one accessible brand color for all bars.
- Retain all fifteen categories, including the original “Other” category.
- Keep exact values available in a supporting table or accessible data view.
- Use the title to state the principal finding.

## Validation

The top five categories total $18,478,100.56. Total sales are $28,755,378.47. The resulting share is 64.26%, rounded to 64% in the title.

## Implementation note

The same treatment can be implemented in Power BI, Tableau, Excel, or a web reporting layer. Tool choice does not change the underlying reporting decision.
