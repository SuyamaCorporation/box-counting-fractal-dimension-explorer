# Box-Counting Fractal Dimension Explorer

Draws classic fractals on Canvas and estimates their Hausdorff/Minkowski dimension via the box-counting algorithm, comparing computed values to known theoretical dimensions.

## Key Features

- Three fractals: Koch Snowflake (D≈1.2619), Sierpiński Triangle (D≈1.5850), and 2D Cantor Dust (D≈1.2619)
- Box-counting runs at 4 scales (ε = 8, 16, 32, 64 px), performs log-log linear regression, and displays the slope as the fractal dimension estimate with percentage error
- Toggle a grid overlay on the canvas to visualise the box-counting process at ε=32
- Side panel shows the N(ε) data table (box size, count, log values) and a scatter + fit-line log-log chart
- Adjustable iteration depth (2–6) with live re-computation of dimension and chart
