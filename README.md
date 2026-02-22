# ai-contract-risk-analyzer-with-automated-reporting

## 🚀 Project Overview

An end-to-end AI automation workflow that analyzes uploaded contracts, detects risky clauses, assigns a numeric risk score (0–100), generates a structured legal assessment, converts the results into a professional PDF report, and automatically emails the report to the user — built entirely in n8n using OpenAI and automated document generation.

An enterprise-grade AI automation workflow built in **n8n** that performs intelligent contract risk analysis and automatically generates a structured PDF report delivered via email.

This system simulates a digital contract review assistant capable of identifying risky clauses, legal concerns, compliance issues, and mitigation recommendations.

---

## ⚙️ What This Project Does

This workflow:

1. Accepts contract uploads (PDF / DOC / DOCX)
2. Extracts contract text
3. Uses OpenAI to:
   - Analyze contract clauses
   - Identify risky provisions
   - Assign a risk level (Low / Medium / High / Critical)
   - Generate a numeric risk score (0–100)
   - Provide legal concerns & compliance issues
   - Deliver actionable recommendations
4. Formats results into a structured HTML report
5. Converts HTML into a professional PDF
6. Automatically emails the report to the recipient

---

## 🏗 Workflow Architecture
                ┌─────────────────────────┐
                │   Contract Upload Form  │
                │ (PDF / DOC / DOCX)      │
                └────────────┬────────────┘
                             ↓
                ┌─────────────────────────┐
                │   Text Extraction Node  │
                └────────────┬────────────┘
                             ↓
                ┌─────────────────────────┐
                │ Workflow Configuration  │
                └────────────┬────────────┘
                             ↓
    ┌─────────────────────────────────────────────┐
    │        OpenAI Clause Analysis Engine        │
    │  - Risk Classification                      │
    │  - Clause Detection                         │
    │  - Compliance Flagging                      │
    │  - Legal Concern Identification             │
    │  - Numeric Risk Score (0-100)               │
    └────────────┬────────────────────────────────┘
                 ↓
    ┌─────────────────────────┐
    │ Structured Output Parser│
    └────────────┬────────────┘
                 ↓
    ┌─────────────────────────┐
    │   Risk Scoring Engine   │
    └────────────┬────────────┘
                 ↓
    ┌─────────────────────────┐
    │ HTML Report Generator   │
    └────────────┬────────────┘
                 ↓
    ┌─────────────────────────┐
    │  HTML → PDF Conversion  │
    └────────────┬────────────┘
                 ↓
    ┌─────────────────────────┐
    │  Automated Gmail Sender │
    └─────────────────────────┘

---

## 🧩 Core Technologies Used

- **n8n** – Workflow orchestration  
- **OpenAI GPT-4o-mini** – Contract clause risk analysis  
- **Structured JSON Output Parsing**  
- **HTML to PDF Conversion API**  
- **Gmail API Integration**  
- **Dynamic HTML Report Generation**  
- **Automated Email Delivery**

---

## 📊 AI Output Structure

The system returns structured legal intelligence including:

- Contract filename
- Analysis timestamp
- Risk level classification
- Risk score (0–100)
- Risky clauses with:
  - Clause text
  - Risk type
  - Severity
  - Detailed explanation
- Legal concerns
- Compliance issues
- Actionable recommendations
- Executive summary

---

## 📄 Sample Output Includes

✔ Executive Risk Summary  
✔ Risk Score Visualization  
✔ Clause-by-Clause Breakdown  
✔ Legal & Compliance Flags  
✔ Mitigation Recommendations  
✔ Professional Branded PDF Report  

---

## 🎯 Real-World Use Cases

- Legal tech automation
- Contract pre-screening
- Procurement risk evaluation
- Vendor agreement review
- Startup legal due diligence
- Compliance monitoring
- Enterprise risk assessment automation

---

## 🛠 How to Use

1. Import the JSON workflow into n8n  
2. Configure:
   - OpenAI credentials  
   - Gmail OAuth credentials  
   - PDF Generator API  
3. Activate workflow  
4. Upload a contract via the generated form  
5. Receive automated risk report via email  

---

## 🔐 Important Note

This tool provides AI-assisted contract risk analysis and is not a substitute for professional legal advice.

---

## 📌 Why This Project Matters

This project demonstrates:

- AI-powered document intelligence
- Enterprise workflow automation
- Structured LLM output parsing
- Automated report generation
- End-to-end system orchestration
- Legal tech automation capability

---

## 🧠 Built For

- Legal Tech Startups
- Enterprise Automation Teams
- AI Engineers
- Automation Engineers
- Compliance Teams
- Procurement Departments

---

## 📈 Portfolio Value

This project showcases advanced:

- Prompt engineering
- Structured LLM output design
- Automation architecture
- Production-ready workflow design
- API integration
- Document intelligence systems

---

