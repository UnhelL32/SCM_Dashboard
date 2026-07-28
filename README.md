# SCM-by-MInhaj
SCM app demo
# Supply Chain Management Dashboard Web Application

![Version](https://img.shields.io/badge/version-3.0.0-indigo)
![License](https://img.shields.io/badge/license-MIT-blue)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-3.x-06B6D4?logo=tailwindcss)
![Chart.js](https://img.shields.io/badge/Chart.js-4.x-FF6384?logo=chartdotjs)

A modern, sleek, and minimalistic web-based Supply Chain Management Dashboard designed as a Single Page Application (SPA). Built with **HTML5**, **Tailwind CSS**, and **Chart.js**, this application enables real-time supply chain operational tracking, multi-segment analytics, dynamic data slicers, interactive record management, and custom schema expansion (e.g., ESG Compliance and LCC Analysis).

---

## Author & Executive Credits

* **Developer / Curator**: MD. Minhajul Haque
* **Student ID**: 1000056022
* **Program**: Master in Procurement and Supply Management (MPSM)
* **Institution**: BRAC University

---

## Key Features

* **Multi-Segment Navigation**:
  * **Overview**: Semicircle KPI gauge, high-level returns, fulfillment, and warehouse metrics.
  * **Supplier Analysis**: Total orders, on-time deliveries, return rates, and correct deliveries broken down by supplier.
  * **Warehouse Location**: Volume, return rates, delivery share, and fulfillment rates across regional warehouses.
  * **Product Category**: Order distribution and performance across product lines.
  * **Monthly Trends**: Trend lines and historical performance charts.
  * **Raw Data Sheet**: Complete master dataset table with inline row deletion and schema controls.

* **Interactive Global Slicers & Filters**:
  * Real-time filtering by **Month**, **Supplier**, **Warehouse**, **Shipping Method**, and **Product Category**.
  * Slicer options automatically update based on the active dataset.

* **Dynamic Data Management**:
  * **Add Record Modal**: Insert new operational records via an integrated modal form.
  * **Delete Capabilities**: Delete individual rows directly from the table or clear the dataset entirely.
  * **Custom Schema Engine**: Dynamically add custom columns (e.g., *ESG Audit Compliance*, *LCC Analysis ($)*, *Sourcing Risk Score*) directly into the live table and record forms.

* **CSV Import & Export Engine**:
  * **Import CSV**: Upload external `.csv` files to merge new data into the master sheet.
  * **Export CSV**: Download the active, filtered dataset as a `.csv` report titled with author credentials.

---

## Tech Stack

* **Structure**: Semantic HTML5
* **Styling**: Tailwind CSS (via CDN)
* **Visualizations**: Chart.js (v4.x)
* **Icons**: Lucide Icons
* **Typography**: Plus Jakarta Sans (Google Fonts)

---

## Getting Started

### Prerequisites

No build tools, Node.js, or local servers are required! The app runs directly in any modern web browser.

### Installation & Execution

1. **Clone or Download**:
   Save the application code into a file named `index.html`.

2. **Run the Application**:
   Double-click `index.html` or open it with your preferred web browser (Chrome, Firefox, Edge, Safari).

---

## How to Use

### 1. Filtering Data (Slicers)
Use the dropdown menus in the top header bar to filter data dynamically across all chart pages and the raw data sheet simultaneously. Click the **Reset** button (`↻`) to revert all slicers back to "All".

### 2. Adding a New Record
1. Click **Add Record** in the header.
2. Fill in the operational values in the modal form.
3. Click **Save Record** to push the data into the master sheet and instantly update all KPIs.

### 3. Adding Custom Columns
1. Click **Add Column** or click **Custom Column** on the Raw Data Sheet segment.
2. Type a column name or choose a preset (*ESG Audit Compliance*, *LCC Analysis*).
3. The new column will immediately render in the raw data table and extend the record entry form.

### 4. Importing & Exporting Data
* **Import**: Click **Import CSV** and choose a `.csv` file with matching header columns.
* **Export**: Click **Export CSV** to download a styled CSV report of your current filtered view.

---

## License

Distributed under the MIT License. See `LICENSE` for more information.
