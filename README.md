# LB-B Personnel Attendance Dashboard

Static dashboard built from the `LB-B Attendance Report` sheet. Data are aggregated by date, shift, and day/night, without publishing individual employee names or IDs.

## Deploy
1. Create a GitHub repository named `lbb-personnel-dashboard` under `Huan289100`.
2. Upload `index.html` and `data.js` to the repository root.
3. Open Settings → Pages → Deploy from a branch → main / (root) → Save.
4. Visit `https://huan289100.github.io/lbb-personnel-dashboard/` after GitHub Pages publishes it.

**Interpretation:** Code `On Duty` and `OT` are counted separately. Other codes are not automatically interpreted as absence. This is an attendance-record dashboard, not a headcount-based staffing fulfillment report. The workbook must be reprocessed to refresh `data.js`.
