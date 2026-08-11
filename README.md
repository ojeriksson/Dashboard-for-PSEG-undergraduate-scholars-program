# Reconciling ESG Scores with Attention-based Graph Neural Networks

Research Project for PSEG Undergraduate Scholars Program 2026
Mentee: Owen Eriksson, Stevens Institute of Technology
Mentor: Arion Cheong, Stevens Institute of Technology

This is an interactive web dashboard for exploring reconciled ESG scores across three rating providers (Refinitiv, MSCI, Bloomberg), with New Jersey as its focus. Each firm-year's unified score is the mean of our model's predicted Refinitiv, MSCI, and Bloomberg scores. 

What it shows:
- New Jersey map with 184 NJ-headquartered firms plotted by HQ location, colored by their relative unified ESG score (upper / middle / lower third among NJ firms). Click a marker for full details.
- Firm search bar for searching any of the 39,121 firms by name or ticker; opens a dedicated firm page.
- Firm details including providers, our Graph Neural Network model's unified ESG score, HQ state, ISIN, Compustat fundamentals, an ESG score history chart (each provider's overall score plus the unified line), a pillar breakdown table (Overall / Environmental / Social / Governance for each provider and the unified score), and provider category detail (Refinitiv's 10 categories, MSCI's 10 themes and Bloomberg's pillar scores). Hovering the chart drives the breakdown and category detail to any available year with data.
- Industry explorer with average unified score and firm count per GICS sector; click a sector to list its firms.
