# Digital-Marketing-Audience-Analytics-Dashboard
Analysis of 132 audience interest segments to find which ones drive revenue, using data cleaning, KPI benchmarks, a segment matrix, and a Power BI dashboard.
Campaigns often have plenty of audience data but no clear way to turn it into decisions, so budget goes to large audiences that don’t pay back. This project analyzes 132 audience interest segments across 12 categories to find which segments deserve more budget, which need testing, and which need fixing. I cleaned the data, defined KPIs with benchmarks, built an interactive Power BI dashboard, and wrote recommendations.

Tools: Power BI, Python/Excel (data cleaning), CSV

What I did:

Cleaned the data: converted numbers stored as text (for example “$3,507.90”, “53.91%”, “18s”), removed an index column, checked for blanks and duplicates (none), and validated logic (for example new users never exceed users)
Split the hierarchy: separated interest paths such as Shoppers / Value Shoppers into Category and Segment
Created KPIs: revenue per user, key events per user, and events per user, benchmarked against portfolio medians
Flagged small samples: 24 segments with under 100 users were flagged rather than deleted
Built a segment matrix (Stars, Hidden Gems, Volume Traps, Low Priority) and a Power BI dashboard with slicers for category, segment type, sample size, users, and hierarchy level

Key findings:

74 of 132 segments (56%) earn no revenue, so choosing the right audience matters more than reaching more people
Technophiles has the largest reach (10,602 users) but earns only $0.33 per user, while Do-It-Yourselfers earns $2.74 per user, over 8 times more
Engagement rate is almost unrelated to revenue (correlation 0.02), so it shouldn’t drive budget alone
Reach has a stronger link to revenue (correlation 0.66), but few segments are both large and high-yielding
The matrix found 13 Stars to scale, 4 Hidden Gems to test, 45 Volume Traps to fix or cap, and 70 Low Priority segments to monitor
