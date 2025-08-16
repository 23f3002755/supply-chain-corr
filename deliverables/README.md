# Supply Chain Correlation Matrix (Excel)

Email: 23f3002755@ds.study.iitm.ac.in

This repository contains the correlation analysis and heatmap of supply chain metrics:
- Supplier_Lead_Time
- Inventory_Levels
- Order_Frequency
- Delivery_Performance
- Cost_Per_Unit

Files:
- `correlation.csv` — Correlation matrix (Excel ToolPak → Data Analysis → Correlation), with labels in first row/column.
- `heatmap.png` — Excel conditional formatting (3‑color scale) with Red (low, −1) → White (0) → Green (high, +1), sized 512×512 px.

Steps followed:
1. Enabled Analysis ToolPak (File → Options → Add‑ins → Excel Add‑ins → Analysis ToolPak).
2. Data → Data Analysis → Correlation; selected 5 columns with headers; output to new worksheet.
3. Saved matrix as CSV with labels.
4. Applied Conditional Formatting → Color Scale:
   - Min: Number −1 (Red)
   - Mid: Number 0 (White)
   - Max: Number +1 (Green)
5. Captured square screenshot and resized to 512×512 px as `heatmap.png`.

Validation checklist:
- README includes email ✅
- `correlation.csv` present and contains a 5×5 labeled matrix ✅
- `heatmap.png` present, Red‑White‑Green, 400–512 px square ✅
