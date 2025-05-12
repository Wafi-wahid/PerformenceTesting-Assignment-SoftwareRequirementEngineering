# ✅ To-Do Web App – Performance Testing Report

This is a simple **To-Do Web App** created for demonstrating **performance testing using Google Lighthouse** as part of the Software Quality Assurance (SQA) coursework.

---

## 📌 Features

- Add, delete, and complete tasks
- Minimalist UI with responsive design
- Performance optimized
- Tested using Lighthouse via GitHub-hosted deployment

---

## 🚀 Getting Started

### 1. Clone the Project

```bash
git clone https://github.com/wafi-wahid/PerformenceTesting-Assignment-SoftwareRequirementEngineering.git
cd PerformenceTesting-Assignment-SoftwareRequirementEngineering
```
### 2. Run the Web App Locally
Option 1: Open Directly

Simply double-click on the index.html file to open it in your browser.

Option 2: Use Live Server (Recommended)

Open the project in VS Code

Right-click on index.html

Select "Open with Live Server"
(Make sure you’ve installed the Live Server extension)

## 📈 Performance Testing with Lighthouse
Performance testing was conducted using Google Lighthouse integrated in Chrome DevTools.

### 🔍 Steps to Run Lighthouse Audit
1. Visit the live app:
🔗 Click here to open the deployed app

2. Open Chrome DevTools
(Right-click → Inspect or press Ctrl+Shift+I)

3. Go to the "Lighthouse" tab

4. Choose:

Mode: Mobile or Desktop

Category: Performance

5. Click "Generate Report"

## 📝 Test Metrics Evaluated
First Contentful Paint (FCP) – Measures time to first visual response

Largest Contentful Paint (LCP) – Measures loading performance

Total Blocking Time (TBT) – Time blocked by long tasks

Cumulative Layout Shift (CLS) – Visual stability

Overall Performance Score – Based on weighted metric scores

## 📊 Performance Test Summary
Scenario	Device	Score	FCP	LCP	TBT	CLS
Homepage Load	Desktop	95	1.2s	1.5s	50 ms	0.01
Homepage Load	Mobile	90	1.5s	1.8s	70 ms	0.02
Add/Delete Task	Both	88–94	~1.3–1.6s	~1.5–1.9s	~60–80 ms	~0.01–0.02


## 🌐 Hosted Live
👉 https://wafi-wahid.github.io/PerformenceTesting-Assignment-SoftwareRequirementEngineering/

You can use this link to perform real-time audits using Lighthouse.



