# Harvest Hope Community Food Bank — AI-Assisted Management System
**Tools:** Excel, Power BI, Python, Claude AI (Anthropic)  
**Organization:** Harvest Hope Community Food Bank — Mapleburg, OH *(fictional demo)*  
**Period:** July 2025 – June 2026 (12 months)  
**Year:** 2026

## Project Overview
A volunteer-friendly food bank management system built to demonstrate how AI can support charitable operations. Claude AI generated 12 months of realistic fictional data and built a dynamic Excel workbook for daily inventory tracking, paired with a 3-page Power BI dashboard for leadership reporting. The system tracks donations, distributions, expiry dates, and stock levels across 50 food items and 4 partner pantries — with live-updating formulas and urgency alerts that require no technical knowledge to operate.

## Excel Workbook
`HarvestHope_FoodBank_Systemv1.xlsx` — 6-sheet workbook for volunteer data entry and inventory management

| Sheet | Description |
|-------|-------------|
| Current Inventory | Live inventory with SUMIFS formulas, expiry alerts, and conditional formatting |
| AI Recommendations | Priority scoring based on expiry urgency, demand, and shortage risk |
| Donations Log | Volunteer entry log for incoming donations (1,009 records) |
| Distribution History | Log of outgoing distributions to partner pantries (1,677 records) |
| Food Catalog | Master list of 50 food items with categories and demand weights |
| Partner Pantries | 4 partner pantry locations and contact information |

**Key formulas:**
- Qty on Hand dynamically subtracts distributions from non-expired donations using SUMIFS
- Expiry Status auto-classifies each item as OK / NOTICE / WARNING / CRITICAL / OUT OF STOCK
- AI Priority Score = 40% Expiry Urgency + 35% Demand Weight + 25% Shortage Risk

## Dashboard Pages

**Page 1 — Inventory at a Glance**
- Total Units on Hand: 26,651
- Items Out of Stock: 12 | Items Expiring within 3 Days: 3 | Items Expiring within 7 Days: 6
- Bar chart: Units on Hand by Category — Canned Vegetables and Canned Protein lead inventory
- Donut chart: Expiry Status breakdown — 50% OK, 24% Out of Stock, 14% Notice, 6% Critical, 6% Warning

**Page 2 — Expiry & Stock Alerts**
- Items Expiring Soon table with color-coded expiry status (CRITICAL / WARNING) and exact dates
- Treemap: 1,507 units at risk across 4 categories — Breakfast (701), Dry Goods (275), Pantry Staples (268), Baby & Infant (263)
- Items Out of Stock: 12 items out, concentrated in Fresh Produce, Dairy & Refrigerated, and Bread & Bakery

**Page 3 — Donation & Distribution Trends**
- Total Donations: 47,864 units | Total Distributions: 12,957 units | Net Units: 34,907
- Line chart: Monthly donation and distribution trends July 2025 – June 2026, with a notable November 2025 spike (holiday giving season)
- Top 10 Donated Items: All canned goods — Canned Green Beans leads at 2,300 units

## Key Findings
- Donations consistently outpace distributions, suggesting an opportunity to expand distribution capacity or partner pantry relationships
- Fresh Produce, Dairy & Refrigerated, and Bread & Bakery are entirely out of stock, reflecting the real-world challenge of managing perishables
- The November 2025 donation spike illustrates seasonal giving patterns and the importance of capacity planning ahead of the holiday season
- Canned goods dominate both donations and on-hand inventory, reflecting typical donor behavior and operational preference for non-perishables

## Skills Demonstrated
- AI-assisted fictional dataset generation (1,009 donations, 1,677 distributions, 50 items, 4 pantries)
- Dynamic Excel inventory system with SUMIFS formulas that auto-update on volunteer data entry
- Expiry tracking and urgency classification with conditional formatting
- AI priority scoring combining expiry, demand, and shortage signals
- Power BI data modeling with Date Table, DAX measures, and cross-table relationships
- Leadership-ready dashboard design for charitable institution boards

## Files in This Repository
- `HarvestHope_FoodBank_Systemv1.xlsx` — Full Excel workbook with 12 months of data and dynamic inventory formulas
- `HarvestHope_FoodBank_Dashboard.pdf` — Full dashboard export (3 pages)
  
