📊 Live Market Visibility Dashboard — Power BI

This project showcases a dynamic Power BI dashboard built to analyze Market Visibility, Retail Performance, and Lost Case Tracking across SPMs and TSMs.
It provides real-time insights for sales managers to identify performance gaps, monitor team productivity, and improve market capture efficiency.

🚀 Project Highlights

📌 SPM & TSM Level Market Analysis

🔄 Total Retail vs Lost Cases Comparison

📈 Market Visibility % and Live Deal Visibility % KPIs

🏆 Top 4 & Bottom 4 TSM Rankings

🎛 Interactive slicers for Product Line, Month, State, and SPM

🎨 Conditional formatting to highlight performance levels

🧩 Hierarchical SPM → TSM structure for detailed team performance

📌 Data Model Summary

The dataset used in the dashboard includes:

Actual TIV (Total Industry Volume)

Total Retail

Lost Cases

TSM / SPM Hierarchy

Filters/Slicers: Product Line, Month, State, SPM

🧠 DAX Measures Used

⭐ 1. Market Visibility
Market Visibility =
DIVIDE(
    SUM(TIV[Total Retail]) + SUM(TIV[Lost Cases]),
    SUM(TIV[Actual Tiv])
)

⭐ 2. Live Deal Visibility (LDV)
Live Deal Visibility =
DIVIDE(
    SUM(TIV[Lost Cases]),
    SUM(TIV[Actual Tiv]) - SUM(TIV[Total Retail])
)

🎨 Visuals Included

📊 SPM → TSM hierarchical matrix

🌡 Conditional formatted bar chart (Green → Yellow → Red scale)

🏅 Top 4 TSM performance panel

⚠️ Bottom 4 TSM performance panel

🔷 KPI tiles for:

Actual TIV

Total Retail

Lost Cases

🧭 Slicers Added

Product Line

Month

State

SPM

These slicers help users analyze market performance from different perspectives.

📊 Dashboard Insights

Provides a complete SPM-wise and TSM-wise breakdown of Actual TIV, Retail, Lost Cases, and KPIs.

Helps identify Top-performing TSMs using the Market Visibility % metric.

Highlights Bottom performers needing attention and corrective action.

Uses color-coded visibility bars for quick performance interpretation.

Includes summary KPI tiles to give a quick snapshot of Total TIV, Total Retail, and Lost Cases.
