# ⚖️ Autonomous Legal Intelligence & Social Automation Engine
### *End-to-End Agentic Workflow: From Judicial Trends to Brand-Compliant Content*


## 📌 Project Overview
Monitoring daily judicial updates is a manual bottleneck for legal-tech firms. This project provides an autonomous agentic solution that tracks legal trends, filters them for strategic value using LLMs, generates branded infographics, and handles social media distribution.

**Key Impact:**
- ⏱️ **Efficiency:** Reduced manual research and design time from **4 hours to 30 seconds**.
- 🛡️ **Safety:** 100% Brand Safety via an integrated **Human-in-the-Loop (HITL)** approval gate.
- 🎨 **Visual Automation:** Integrated **Nano Banana** for automated infographic generation.

---

## 🏗️ Architecture & Workflow

The system is orchestrated using **n8n** and follows a multi-stage agentic logic:



1. **Data Ingestion (Extraction):** Monitors Judicial RSS feeds for the latest updates.
2. **Data Sanitization:** Custom **JavaScript Nodes** sanitize raw XML data into structured JSON, ensuring high accuracy for the LLM.
3. **Strategic Filtering (Reasoning):** Uses **Gemini 2.5 Flash** to act as a "Growth Head," identifying trends that match specific product solutions (e.g., Court Automation).
4. **Creative Synthesis:** Insights are sent to the **Nanobanana API** to generate infographics using corporate hex codes.
5. **Human-in-the-Loop (Safety):** The workflow pauses and sends an approval request via **Gmail**.
6. **Automated Distribution:** Upon approval, assets are hosted via **Imgbb** and published to the **LinkedIn API**.

---

## 🛠️ Tech Stack

- **Orchestration:** n8n
- **LLM:** Gemini 2.5 Flash
- **Visual AI:** Nanobanana
- **Languages:** JavaScript (Node.js), Python
- **APIs:** LinkedIn, Gmail, Imgbb, RSS/XML
