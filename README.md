# Superstore Sales & Logistics Performance Dashboard (Tableau)

An end-to-end business intelligence and data visualization project built using the Sample Superstore dataset in **Tableau Public**. This project explores multi-dimensional retail metrics including monthly sales/profit trends, category-level profitability, logistics shipping durations, and geospatial map distributions.

---

### 📊 Interactive Dashboard & Live Visualizations

👉 **[Access the Interactive Tableau Public Workbook](https://public.tableau.com/views/TableauFinalProject_1_17872530258020/Sheet1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

### 📌 Key Analysis Sections & Features

1. **Overall Sales & Profit Time Series (Dual-Axis):**
   - Monthly trend analysis (2020–2023) integrating Total Sales and Profit on a unified scale.
   - Customized `Ship Mode` and `Segment` parameter controls with explicit **Apply** buttons for optimized query execution.

2. **Sub-Category & Ship Mode Profitability Matrix:**
   - Multi-tiered hierarchical layout (`Category` → `Sub-Category` vs. `Ship Mode`).
   - Custom Calculated Field for **Profit Margin %** formatted with a diverging color scale centered at 0% neutrality.
   - Integrated Row and Column Grand Totals for holistic financial aggregation.

3. **Logistics & Delivery Duration Analysis (Geospatial Dashboard):**
   - Calculated delivery lead times (`Ship Date` - `Order Date`).
   - Order volume distribution grouped by delivery days.
   - **Geospatial Map (US States):** Gradient color map reflecting state-level average delivery durations.
   - Unified interactive dashboard driven by dynamic global filters (`Order Date`, `Segment`, `Ship Mode`).

4. **Funnel Interactivity & Parameter Actions (Advanced):**
   - Interactive parameters allowing users to dynamically evaluate average days from registration to conversion across funnel stages.

---

### 🛠️ Tech Stack & Tableau Techniques Used

- **Tool:** Tableau Public / Tableau Desktop
- **Visualizations:** Dual-Axis Line Charts, Heatmaps / Profitability Matrices, Symbol/Choropleth Maps, Interactive Dashboards.
- **Calculations & Features:** Calculated Fields (Profit %), Date Differences (`DATEDIFF`), Parameter Actions, Diverging Color Palette, Global Dashboard Actions.

---

### ✉️ Contact
Created by **Çağrı Yetkin** – [LinkedIn Profile](https://www.linkedin.com/in/cgrytkn)
