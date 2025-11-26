📊 Live Market Visibility Dashboard (Power BI)

A fully interactive Power BI analytics dashboard designed to monitor Market Visibility, Retail Performance, and Live Deal Tracking across multiple Sales Personnel (SPM & TSM).
This dashboard helps business teams measure real-time performance, identify gaps, and improve sales conversion efficiency.

🚀 Project Overview

The Live Market Visibility Dashboard provides a consolidated view of:

Actual TIV (Total Industry Volume)

Retail Performance

Lost Cases Analysis

Market Visibility %

Live Deal Visibility %

Top & Bottom Performing TSMs

SPM-wise Sales Team Performance Breakdown

This system helps sales managers understand how effectively their teams capture market opportunities and pinpoints improvement areas using meaningful KPIs.

🧠 Key KPIs & Metrics
⭐ Market Visibility (MV)

Measures the team's overall capture of market opportunities.

Market Visibility =
DIVIDE(
    SUM(TIV[Total Retail]) + SUM(TIV[Lost Cases]),
    SUM(TIV[Actual Tiv])
)

⭐ Live Deal Visibility (LDV)

Shows how effectively current live deals are being tracked or closed.

Live Deal Visibility =
DIVIDE(
    SUM(TIV[Lost Cases]),
    SUM(TIV[Actual Tiv]) - SUM(TIV[Total Retail])
)


🧩 Features

🌐 SPM & TSM level visibility

🎯 Top 4 & Bottom 4 TSM performance

📍 State-wise & month-wise slicers

🟩🟥 Color-coded performance bars

📉 Gap analysis between Retail vs Lost Cases

🔄 Dynamic DAX calculations for market insights

📈 Real-time decision support for sales managers
