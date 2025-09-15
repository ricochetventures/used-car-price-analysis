# used-car-price-analysis
CRISP-DM analysis of used car pricing factors for dealer inventory optimization

**Used Car Market Analysis**
The data reveals several clear patterns in used car pricing. The price distribution shows most vehicles concentrated under $50,000, typical for mainstream used car markets. Vehicle age demonstrates a strong positive correlation with price, though the relationship isn't perfectly linear, indicating other factors contribute significantly to final valuations. The mileage versus price relationship shows the expected inverse correlation, but with considerable variation suggesting odometer readings alone don't determine market value.

Brand representation follows predictable patterns, with Ford leading by volume, followed by Chevrolet and Toyota. However, the condition analysis presents an unexpected finding - vehicles rated as "good" condition command higher median prices than those rated "excellent" or "new" or "like new". This suggests either market skepticism toward "excellent" classifications or inconsistent condition reporting across listings.

**Model Performance**
The modeling results show substantial differences between approaches. Random Forest achieved an R-squared of 0.81 with an RMSE of $6,227, while linear regression models performed significantly worse at 0.51 R-squared with nearly $10,000 RMSE. This performance gap indicates that used car pricing involves complex, non-linear relationships between variables that tree-based models capture more effectively than linear approaches.

Link to notebook:
