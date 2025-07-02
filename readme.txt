# Identifying Optimal Locations to Provide Affordable Insurance

---

## Overview

This project analyzes global natural disaster data to identify regions where Union Insurance can expand its offerings with minimal capital risk. By examining correlations between people affected by disasters and insured damages, we recommend target countries in Asia and Europe that present affordable opportunities for profitable insurance policies.

## Methodology

1. **Data Sources**

   * `natural-disasters.csv`: Annual disaster impact and insured damage figures
   * `natural-disasters_peryear_country-csv.csv`: Detailed disaster occurrences by country and year

2. **Correlation Analysis**

   * Computed Pearson correlation between total people affected and insured damages (ρ ≈ 0.369).
   * Fitted a log–log linear regression model to validate relationship and support expansion strategy.

3. **Geospatial Visualization**

   * Mapped disaster-affected population across Asia and Europe using `rnaturalearth` and `sf`.
   * Highlighted countries with consistently low impact.

4. **Susceptibility Assessment**

   * Counted disaster occurrences by region (2000–2015) to gauge susceptibility.
   * Identified Asia and Europe as relatively low-risk regions.

5. **Hypothesis Testing**

   * Null hypothesis (H₀): No relation between disaster-affected population and insured damages.
   * Alternative hypothesis (H₁): Positive relation exists.
   * Performed t-test on correlation; p-value < 2.2e‑16 → Reject H₀.


## Installation & Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/<username>/insurance-expansion-analysis.git
   cd insurance-expansion-analysis
   ```
2. Install dependencies:

   ```r
   install.packages(c("ggplot2", "plotly", "sf", "dplyr", "rnaturalearth", "rnaturalearthdata"))
   ```
3. Run the analysis in Quarto or RStudio:

   ```bash
   quarto render README.qmd
   ```

---

