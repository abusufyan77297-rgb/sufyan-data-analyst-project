# 💳 UPI Transactions Interactive Dashboard (Excel)

An end-to-end, interactive **UPI Transactions Dashboard** built purely in **Microsoft Excel**. This dashboard analyzes over **500,000+ UPI transactions** (PhonePe dataset), offering actionable insights into payment app market share, transaction status, peak activity hours, state-wise volume, and bank-wise transaction values.

---

## 📊 Dashboard Preview

<img width="1947" height="1315" alt="Screenshot 2026-08-01 020548" src="https://github.com/user-attachments/assets/05378cab-f084-4112-8451-f8de83506861" />


---

## 🚀 Key Features & Highlights

- **Dynamic KPI Cards:**
  - **Total Transactions:** 502,887
  - **Total Amount:** ₹44 Cr
  - **Total Cashback:** ₹35 L
  - **Success Rate:** 91.00%
  - **Suspected Fraud Cases:** 17,089
- **Interactive Slicers / Filter Panel:** Filter data dynamically by Gender, Merchant Name, Merchant Category, and City.
- **Geographic Analysis:** Filled Map chart displaying transaction distribution across Indian States (Maharashtra, Karnataka, Delhi, etc.).
- **Time Series & Hourly Heatmap:** 
  - Daily trend line showing fluctuation in transaction volume over 30 days.
  - Custom 24-hour bar chart highlighting peak transaction hours (18:00 - 21:00).
  - **Day vs. Hour Matrix (Heatmap):** Pivot table heat-map mapping hourly transaction intensity across days of the week.
- **Market Share & Status Breakdowns:**
  - Donut charts showing App Share (PhonePe ~48.26%, Google Pay ~21.88%, Paytm ~14.89%) and Transaction Status (Success, Failed, Pending, Refunded).
  - Horizontal Bar Charts analyzing volume by Top Banks (HDFC, SBI, Kotak, etc.) and Transaction Types (P2M, P2P, Bill Payment, etc.).

---

## 🛠️ Data Engineering & Excel Techniques Used

1. **Data Cleaning & Transformation:** Handled missing values, standardized datetime strings, and structured raw transaction datasets.
2. **Feature Engineering:** Extracted `Hour` and `Day` parameters using formulas (`HOUR()`, `TEXT()`) and mixed referencing (`$A185`, `C$184`) to create custom matrix calculations.
3. **Data Modeling & Pivot Tables:** Built multiple optimized Pivot Tables to summarize high-volume raw data without crashing Excel.
4. **Custom Formatting:** 
   - Applied Custom Number Formatting (`"₹ "0.00,," Cr"`) to display large currency values clearly in Crores (Cr) and Lakhs (L).
   - Applied Conditional Formatting (Color Scales) for the Day-vs-Hour Heatmap.
5. **Dashboard UI/UX:** Formatted cohesive color themes, card shadows, aligned chart structures, and integrated multi-slicer connections for a seamless user experience.
6. ---

## 💡 Key Business Insights

1. **Peak Activity:** Transaction volume peaks heavily during evening hours (6 PM – 9 PM / 18:00 – 21:00) across all weekdays.
2. **Dominant Payment Type:** **P2M (Person-to-Merchant)** accounts for the highest transaction value (~₹18.88 Cr).
3. **App Market Leader:** **PhonePe** leads the app market share with **48.26%**, followed by Google Pay at **21.88%**.
4. **Top States:** **Maharashtra** and **Karnataka** drive the highest transaction volumes in India.

---

## 👤 Author

- **Name:** Sufyan Ahmad
- **Role:** Data Analyst / IT Student
- **Tools:** Microsoft Excel | Power BI | SQL | Python
- **Portfolio:** [Live Pakistan Intern](https://www.livepakistan.site/intern)

---

⭐ **If you find this project useful, feel free to give it a star!**

---

## 📁 Repository Structure

```text
├── Data/
│   └── UPI_Raw_Data.xlsx          # Raw transaction data
├── Dashboard/
│   └── UPI_Transactions_Dashboard.xlsx  # Complete interactive Excel dashboard
├── Assets/
│   └── Dashboard_Screenshot.png   # Preview image for documentation
└── README.md                      # Project documentation
