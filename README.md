# Risk Analysis & Fraud Detection Dashboard

A modern, interactive Web Application designed to analyze transactions, detect potential fraud, trigger custom risk rules, and display action plans and connections using React, Vite, and Tailwind CSS.

## 🚀 Features

* **Interactive Dashboard:** Real-time summary and detailed reporting of analyzed transaction data.
* **Risk & Fraud Detection:** Automated evaluation using custom risk analysis algorithms (`riskAnalysis.js`).
* **Triggered Rules & Action Plans:** Highlighting flagged transactions, action plan recommendations, and connection graphs.
* **CSV Import & Parser:** Upload external datasets via CSV files using custom utilities (`csvParser.js`).
* **Sample Datasets:** Built-in sample datasets (`sampleDatasets.js`) for quick testing and demonstration.
* **Modern UI:** Responsive, clean interface styled with Tailwind CSS and custom UI components.

## 🛠️ Tech Stack

* **Frontend:** React.js, Vite
* **Styling:** Tailwind CSS, PostCSS
* **Icons / Assets:** Custom SVG icons (`shield.svg`)

## 📂 Project Structure

```text
project/
├── public/
│   └── shield.svg
├── src/
│   ├── components/
│   │   ├── ActionPlanCard.jsx
│   │   ├── ConnectionCard.jsx
│   │   ├── FlaggedTransactionsTable.jsx
│   │   ├── InputPanel.jsx
│   │   ├── ReportDashboard.jsx
│   │   ├── StatusBadge.jsx
│   │   ├── SummaryCard.jsx
│   │   └── TriggeredRulesCard.jsx
│   ├── data/
│   │   └── sampleDatasets.js
│   ├── utils/
│   │   ├── csvParser.js
│   │   └── riskAnalysis.js
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
└── vite.config.js
