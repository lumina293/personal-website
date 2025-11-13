---

# **Week 1 — Core JavaScript & Data Handling**

---

### **Day 1 – JavaScript Basics**

**Goal:** Learn JavaScript fundamentals to handle simple variables, functions, and console testing.

**Learning Checklist (3h total)**

* [ ] JS syntax, `let`, `const` (30 min) – [MDN JS Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
* [ ] Data types: string, number, boolean, array, object (30 min)
* [ ] Functions and arrow functions (30 min)
* [ ] Conditionals and loops (45 min)
* [ ] Console testing, `console.log`, debugging basics (45 min)

**Project Tasks Checklist (3h total)**

* [ ] Create sample transaction array including merchant info
* [ ] Write functions to calculate total income, total expense, and saving
* [ ] Test calculations in console with sample data

**Recap**

* Understand JS syntax and how it runs in the browser
* Able to define variables, functions, and arrays
* Can compute totals and display them via console

---

### **Day 2 – Functions, Arrays & Loops**

**Goal:** Process transaction arrays dynamically using loops and array methods.

**Learning Checklist (3h total)**

* [ ] Arrays: `.map()`, `.filter()`, `.reduce()` (90 min) – [JavaScript.info Arrays](https://javascript.info/array)
* [ ] Loops (`for`, `for...of`, `forEach`) (45 min)
* [ ] Conditional logic in loops (45 min)

**Project Tasks Checklist (3h total)**

* [ ] Filter transactions into income vs expenses
* [ ] Group transactions by category
* [ ] Group transactions by merchant and sum totals

**Recap**

* Able to filter, map, and reduce transaction data
* Can summarize totals by category and merchant
* Loops and array methods used to transform data

---

### **Day 3 – Objects & JSON**

**Goal:** Work with nested objects and structure data for analysis.

**Learning Checklist (3h total)**

* [ ] Objects, key-value access, nested objects (60 min)
* [ ] JSON: stringify and parse (45 min)
* [ ] Using `.reduce()` for aggregations (45 min)
* [ ] Testing and debugging object outputs (30 min)

**Project Tasks Checklist (3h total)**

* [ ] Build `analyzeTransactions()` to output totals, category sums, merchant sums
* [ ] Test function with multiple sample transactions
* [ ] Print structured summary in console

**Recap**

* Can structure analyzed data in objects
* Understand JSON and aggregation with reduce
* Prepared dataset ready for later visualization

---

### **Day 4 – File Parsing (CSV/Excel)**

**Goal:** Read real CSV and Excel files from browser.

**Learning Checklist (3h total)**

* [ ] File input elements (`<input type="file" multiple />`) (45 min)
* [ ] FileReader API basics (30 min)
* [ ] PapaParse for CSV parsing (60 min) – [PapaParse Docs](https://www.papaparse.com/docs)
* [ ] SheetJS for Excel parsing (45 min) – [SheetJS Docs](https://docs.sheetjs.com/)

**Project Tasks Checklist (3h total)**

* [ ] Implement drag & drop or file picker
* [ ] Parse CSV files and convert to transaction objects
* [ ] Parse Excel files and convert to transaction objects with merchant info

**Recap**

* Can read files from browser
* Converted CSV/Excel into usable JS objects
* Merchant info included for analysis

---

### **Day 5 – Data Cleaning & Standardization**

**Goal:** Prepare clean, standardized transaction data.

**Learning Checklist (3h total)**

* [ ] String manipulation (`split`, `trim`, `toLowerCase`) (45 min)
* [ ] Date parsing and formatting (`Date()` and `toLocaleDateString`) (60 min)
* [ ] Type conversion (`Number()`) (45 min)
* [ ] Error handling with `try…catch` (30 min)

**Project Tasks Checklist (3h total)**

* [ ] Normalize merchant names and categories
* [ ] Standardize dates and amounts
* [ ] Remove empty or invalid rows

**Recap**

* Learned how to clean and normalize raw data
* Can handle errors in parsing or conversion
* Data ready for aggregation

---

### **Day 6 – Derived Data & Aggregation**

**Goal:** Transform transactions into visualizable data objects.

**Learning Checklist (2h total)**

* [ ] Derived data concept: summaries, aggregation (45 min)
* [ ] Modular functions and reusable code (45 min)
* [ ] Testing transformations (30 min)

**Project Tasks Checklist (4h total)**

* [ ] Calculate totals: income, expense, saving
* [ ] Group by category, day, merchant
* [ ] Create `prepareData()` function with all derived data

**Recap**

* Can compute aggregates for charts
* Built a single function to prepare all derived data for visualization
* Data structure ready for Chart.js

---

### **Day 7 – Integration Practice**

**Goal:** Combine all logic into one workflow.

**Learning Checklist (2h total)**

* [ ] Import/export JS modules (30 min)
* [ ] Debugging and console tips (60 min)
* [ ] Review all previous concepts (30 min)

**Project Tasks Checklist (4h total)**

* [ ] Import all modules (parse, clean, analyze)
* [ ] Run full flow with sample files
* [ ] Console log final summary object

**Recap**

* Full pipeline: file → parse → clean → analyze
* Ready to connect to charts
* Core JS logic complete

---

# **Week 2 — Visualization & App Integration**

---

### **Day 8 – Chart.js Basics**

**Goal:** Learn Chart.js and create initial static charts.

**Learning Checklist (3h total)**

* [ ] Chart.js setup in Next.js (30 min)
* [ ] Chart types: bar, doughnut, line (60 min)
* [ ] Chart configuration: datasets, labels, colors (60 min)
* [ ] Static chart testing (30 min)

**Project Tasks Checklist (3h total)**

* [ ] Render one static donut chart
* [ ] Render one static column chart
* [ ] Experiment with colors, labels, and tooltips

**Recap**

* Can create charts in the browser
* Understand datasets and chart options
* Ready to feed dynamic data

---

### **Day 9 – Connect Data to Charts**

**Goal:** Visualize processed transaction data dynamically.

**Learning Checklist (2h total)**

* [ ] DOM manipulation (`getElementById`) (45 min)
* [ ] Event listeners for file uploads (45 min)
* [ ] Chart updates with new data (30 min)

**Project Tasks Checklist (4h total)**

* [ ] Donut chart: expense by category
* [ ] Column chart: expense by day
* [ ] Bar chart or table: expense by merchant

**Recap**

* Charts reflect actual transaction data
* Dynamic updates on file upload work

---

### **Day 10 – Display Single Value Summaries**

**Goal:** Show total income, total expense, and saving.

**Learning Checklist (2h total)**

* [ ] DOM updates: `innerText`, `innerHTML` (60 min)
* [ ] Number formatting (`toLocaleString`) (60 min)

**Project Tasks Checklist (4h total)**

* [ ] Total income card
* [ ] Total expense card
* [ ] Total saving card

**Recap**

* Summary cards working
* Dynamic values update correctly with charts

---

### **Day 11 – Dynamic Updates & Event Handling**

**Goal:** Refresh dashboard on new file uploads.

**Learning Checklist (2h total)**

* [ ] Event listeners (`change`, `drop`) (45 min)
* [ ] JS functions to trigger data pipeline (45 min)
* [ ] Updating charts/cards efficiently (30 min)

**Project Tasks Checklist (4h total)**

* [ ] Connect file upload to `prepareData()`
* [ ] Update charts dynamically
* [ ] Update summary cards dynamically

**Recap**

* Dashboard fully reactive
* Can upload multiple files, charts update automatically

---

### **Day 12 – Data Persistence**

**Goal:** Save and reload processed data with localStorage.

**Learning Checklist (2h total)**

* [ ] `localStorage` basics (30 min)
* [ ] JSON stringify and parse (30 min)
* [ ] Reloading charts from stored data (60 min)

**Project Tasks Checklist (4h total)**

* [ ] Save prepared data on every upload
* [ ] Load stored data on page reload
* [ ] Verify charts and cards restore correctly

**Recap**

* Users’ data persists between sessions
* Full app state can reload without re-uploading

---

### **Day 13 – Error Handling & Testing**

**Goal:** Make app robust to invalid inputs.

**Learning Checklist (2h total)**

* [ ] Defensive programming (30 min)
* [ ] Error handling for missing columns or invalid data (60 min)
* [ ] Testing multiple edge cases (30 min)

**Project Tasks Checklist (4h total)**

* [ ] Handle invalid/missing files
* [ ] Alert user for errors
* [ ] Ensure console/logs are informative

**Recap**

* App handles invalid data gracefully
* Dashboard is stable and reliable

---

### **Day 14 – Deployment & Showcase**

**Goal:** Launch and document the project.

**Learning Checklist (2h total)**

* [ ] Git basics: commit, push, branches (30 min)
* [ ] Deploy Next.js app on Vercel (60 min)
* [ ] Writing README & project description (30 min)

**Project Tasks Checklist (4h total)**

* [ ] Push code to GitHub
* [ ] Deploy live app on Vercel
* [ ] Prepare demo summary for portfolio/WeCamp

**Recap**

* Fully deployed, shareable dashboard
* Project documented and ready for showcase
