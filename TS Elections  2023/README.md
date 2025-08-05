# 🗳 Telangana State Election Results 2023 - Power BI Dashboard

This Power BI project presents a comprehensive and interactive dashboard of the *Telangana State Election Results 2023*, visualizing key insights such as party-wise seat wins, vote share, and candidate-level details using dynamic visuals and data modeling.

## 📊 Features

- ✅ *Interactive Summary Dashboard*
  - Total seats won by each party
  - Votes distribution using a pie chart
  - Geographic mapping of constituencies
  - Candidate and constituency-level drill-down

- 📌 *Key Visuals*
  - *Donut Chart*: Seats won by each party
  - *Pie Chart*: Vote count distribution by party
  - *Map Visual*: Location-based representation of constituencies
  - *Table Views*: Candidate name, party, and constituency

## 🧩 Data Model

- *Tables Used*:
  - Constanacy — Candidate, Party, Constituency details
  - SeatWon — Party-wise seat count
  - VOTE RATIO — Vote count by party
  - FLAG — Party flag/image mapping

- *Relationships*:
  - One-to-many relationships created between:
    - SeatWon[PARTY] → Constanacy[PARTY]
    - VOTE RATIO[PARTY] → Constanacy[PARTY]
    - FLAG[PARTY] → Constanacy[PARTY]

## 🧠 Insights

- The *Indian National Congress (INC)* won the majority with *64 seats*
- *Bharat Rashtra Samithi (BRS)* followed with *39 seats*
- The dashboard highlights strong regional patterns in party performance

## 🚀 Getting Started

1. Open the .pbix file in *Power BI Desktop*
2. Explore the interactive visuals and slicers
3. Modify filters or visuals to gain different insights

> *Note:* This dashboard is static and built using publicly available election data. You can modify or update it with new data sources as needed.

## 📌 Requirements

- Power BI Desktop (latest version recommended)
- Windows OS (for Power BI compatibility)


---

Created with ❤ using Power BI

