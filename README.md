# Task 2 – Data Visualization and Storytelling

## Objective
Create visualizations from sales data that highlight clear, actionable business insights — not just charts for the sake of charts.

## Tool Used
Power BI Desktop (free, local — no sign-in required)

## Dataset
Sample Superstore dataset (Kaggle) — order-level retail sales data including category, sub-category, region, sales, and profit.

## Dashboard

The dashboard contains 5 visuals on a single page:

1. **Sales Trend (Line Chart)** — Sum of Sales across Order Date, showing how sales fluctuate over time.
2. **Sales by Category (Column Chart)** — Compares total sales across Technology, Furniture, and Office Supplies.
3. **Profit by Sub-Category (Bar Chart)** — Sorted ascending to surface the weakest performers first.
4. **Top 10 Products (Table)** — Ranks the 10 highest-selling individual products by total sales.
5. **Sales by Region (Bar Chart)** — Compares total sales across West, East, Central, and South.

## Key Insights

- **Canon imageCLASS 2200 Advanced Copier** is the single highest-selling product at ₹61,599.82 — more than double the next product on the list (Fellowes PB500 Binding Machine at ₹27,453.38).
- **Tables** is the only sub-category running at a loss (negative profit), while **Chairs** is the most profitable sub-category — despite both belonging to Furniture. This points to a pricing or discounting issue specific to Tables worth investigating further.
- **West** is the top-performing region by sales, with **South** trailing behind the other three regions.

## Files in this Repository
- `Task2_Visualization.pbix` — Power BI source file
- `Task2_Visual_Report.pdf` — Exported visual report (deliverable)
- `Sample_Superstore.csv` — Raw dataset used
- `README.md` — This file

## Interview Questions (Practice Reference)

**1. What is the importance of data visualization?**
It turns raw numbers into visual patterns that are far faster to interpret than tables, surfacing trends and outliers that stay hidden in rows of data.

**2. When do you use a pie chart vs a bar chart?**
Pie charts only work for parts-of-a-whole with very few categories (under 5). Bar charts are better almost everywhere else, since people judge bar length far more accurately than pie-slice angle.

**3. How do you make visualizations more engaging?**
Use color with purpose, remove unnecessary gridlines/borders, sort data logically instead of randomly, and keep titles specific rather than generic.

**4. What is data storytelling?**
Arranging visuals and context in a sequence that leads the viewer toward a specific insight — not disconnected charts, but a narrative the data supports.

**5. How do you avoid misleading visualizations?**
Start bar/column axes at zero, keep scales consistent across comparable charts, avoid cherry-picked date ranges, and label axes clearly.

**6. What are best practices in dashboard design?**
Group related charts together, keep one consistent color scheme, place the most important metric where the eye lands first, and make sure every chart answers a distinct question.

**7. What tools have you used for visualization?**
Power BI Desktop for this task — built column, bar, line, and table visuals on a single report page, then exported to PDF.

