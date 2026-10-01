# 1now-lockout-response
Interactive Client Support Workflow for handling rental lockout incidents at 1Now
# 🚗 Lockout Response Console — 1Now Client Support

🌐 **Live Working Demo:** [https://moeez-ahmad-1.github.io/1now-lockout-response/](https://moeez-ahmad-1.github.io/1now-lockout-response/)

---

## 📌 Problem Overview
A vehicle rental operator receives an urgent signal: a renter is locked out of their vehicle in the middle of an active rental period. 

* **Business Impact:** Every minute the driver is stranded threatens customer trust, creates potential safety hazards, and drains operator support bandwidth.
* **Operational Goal:** Provide an automated decision-engine prototype that ingests lockout reports, evaluates vehicle telematics/fob status, verifies renter identity, and routes the ticket to the fastest resolution path (remote unlock, host spare key, or local emergency dispatch).

---

## ⚡ Key Features
- **Smart Decision Engine:** Evaluates lock type (Smart App vs. Traditional Key), identity status, and coverage location in real time.
- **Interactive Trace Log:** Live console UI rendering step-by-step decision steps with realistic latency delays.
- **Automated Communication:** Generates ready-to-send SMS templates for renters with one-click clipboard copy functionality.
- **Edge Case Coverage:** Built-in validation for unverified IDs, custom issues, off-grid/remote locations, and after-hours emergency locksmith billing rates.

---

## 🛠️ Built With & Workflow
- **Claude (Anthropic)** — Prompt engineering, problem formulation, edge-case logic mapping, and full code generation (HTML/CSS/JS).
- **GitHub & GitHub Pages** — Version control, hosting, and continuous deployment.

---

## 🚀 How to Access
1. Visit the live interactive console: [1Now Lockout Response Console](https://moeez-ahmad-1.github.io/1now-lockout-response/)
2. Select a sample booking or enter a custom ID.
3. Choose the issue type (e.g., *Keys locked inside*, *App unlock failed*).
4. Click **Run routing** to view the live decision trace and resolution card.
