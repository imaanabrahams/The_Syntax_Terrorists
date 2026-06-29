# 📊 HR Pulse | Minimalist Employee Management Dashboard

An elegant, lightweight, vanilla web application designed to streamline internal HR operations. Manage employee directories, track attendance, handle time-off requests, and review payroll records effortlessly—all from a sleek, localized frontend dashboard.

---

## 🚀 Features

*   **👥 Employee Directory:** Browse, filter, and view detailed profiles of your entire workforce.
*   **📅 Attendance Tracker:** Monitor daily clock-ins, clock-outs, and overall hours logged.
*   **⏳ Leave Management:** Review and process employee time-off requests seamlessly.
*   **💳 Payroll Records:** Keep a transparent log of financial disbursements and salary structures.
*   **🔒 Local Data Architecture:** Powered by structured JSON data structures for quick rendering without complex database overhead.

---

## 🛠️ Tech Stack

This project is built using pure, unadulterated web technologies for maximum speed and zero dependencies:

*   **HTML5** - Semantic structure and layout.
*   **CSS3** - Custom styling, responsive flexbox/grid components, and modern UI variables.
*   **Vanilla JavaScript (ES6+)** - Reactive dashboard logic, data filtering, and dynamic DOM manipulation.
*   **JSON Data Layer** - Mocked production-ready schemas for rapid testing.

---

## 📂 Project Architecture

```text
plain_html_project/
├── 📂 assets/
│   ├── 📂 css/
│   │   └── 📄 styles.css           # Custom UI themes and responsive design
│   └── 📂 js/
│       ├── 📄 embeddedData.js      # Bootstrapped local application storage
│       └── 📄 app.js               # Core application and routing logic
├── 📂 data/
│   ├── 📄 attendance-records.json  # Clock-in/out data streams
│   ├── 📄 employees.json           # Comprehensive employee data
│   ├── 📄 payroll-records.json     # Salary and transaction histories
│   ├── 📄 time-off-requests.json   # Pending and approved leave logs
│   └── 📄 user.json                # Currently logged-in admin details
├── 📄 index.html                   # Dashboard core landing page
└── 📄 README.md                    # Documentation
