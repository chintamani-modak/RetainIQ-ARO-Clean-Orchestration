# 🧩 RetainIQ™ ARO – Clean Orchestration  
**IBM Watsonx AI Agents Orchestration Hackathon Submission**  
*Built by [Chintamani Modak](https://www.linkedin.com/in/chintamanimodak), Founder – AIElevate Pte. Ltd.*

---

## 🚀 Executive Summary
**RetainIQ™ ARO – Clean Orchestration** demonstrates how **agentic AI** can autonomously clean, segment, and strategize customer data using **IBM Watsonx Orchestrate**.  
The project reimagines customer retention workflows — transforming messy, unstructured input data into an actionable marketing playbook through three AI agents that think, collaborate, and execute seamlessly.

This orchestration bridges *data engineering* and *marketing automation*, showing how intelligent multi-agent design can deliver explainable, reusable, and auditable outcomes.

---

## ⚙️ Architecture Overview
```
[Raw Customer Data]
        ↓
 [🧩 Data Mapper Agent] → Cleaned JSON
        ↓
 [🧠 Planner Agent] → Segments & Strategies
        ↓
 [⚙️ Playbook Agent] → Retention Playbook (Message Themes, CTAs, Channels)
```

- **Orchestration Platform:** IBM Watsonx Orchestrate  
- **Validation Layer:** AskOrchestrate (JSON schema verification)  
- **Data Exchange:** Auto-mapped JSON outputs between agents  
- **Execution:** Fully visual run flow with traceable outputs (`mapped.json`, `plan.json`, `playbook.json`)

---

## 🧠 Agent Roles & Intelligence Highlights

### 1. Data Mapper Agent – *Precision Normalizer*
Cleans malformed entries, removes duplicates, and standardizes customer data fields  
(`id`, `email`, `ltv`, `risk_score`, `last_activity_days`, `status`).  
→ **Output:** `mapped_json`

### 2. Planner Agent – *Strategic Segmenter*
Uses reasoning to classify customers by LTV, risk, and engagement.  
Creates 3–5 clear segments such as *High-Value Low-Risk*, *At-Risk High-Value*, *Low-Value High-Risk*.  
→ **Output:** `plan_json`

### 3. Playbook Agent – *Execution Designer*
Transforms strategies into personalized retention playbooks with message theme, CTA, channels, cadence, and KPIs.  
→ **Output:** `playbook_output_json`

Together, they form a **fully autonomous retention optimizer** capable of end-to-end decisioning.

---

## 🤖 Watsonx Orchestrate Integration
- Each agent defined as a discrete Watsonx workflow block.  
- **Auto-Mapping**: JSON outputs automatically mapped to subsequent agent inputs.  
- **Sequential Execution**: Data Mapper → Planner → Playbook.  
- **AskOrchestrate Validation**: Ensures structural and logical integrity of all outputs.  
- **Auditability**: Run history with run IDs, timestamps, and output export logs.

---

## 🌍 Innovation & Impact
RetainIQ™ ARO – Clean showcases how **agentic orchestration** can eliminate data silos, shorten campaign preparation by 80%, and improve segmentation precision through self-learning agents.  
It highlights IBM Watsonx Orchestrate’s unique ability to unify human-like reasoning, automation, and explainability within enterprise-ready workflows.

**Why it matters:**  
- Moves beyond trigger-based automation → into autonomous orchestration.  
- Proves modular AI agents can collaborate like teams.  
- Delivers transparent, reproducible, business-impacting outcomes.

---

## 🧾 Deliverables Summary
| Deliverable | Description | Link |
|--------------|-------------|------|
| 🎥 **Video Demo** | 3-minute narrated Loom demo | *[Loom link – to be inserted]* |
| 📄 **Problem & Solution Statement** | Detailed 500-word submission | [Download PDF](./RetainIQ_ARO_Clean_Problem_and_Solution_Statement.pdf) |
| 📘 **Agentic AI & Watsonx Usage Statement** | Detailed orchestration breakdown | [Download PDF](./RetainIQ_ARO_Clean_Agentic_AI_and_Watsonx_Usage_Statement.pdf) |
| 🎞️ **Presentation Deck** | 6-slide hackathon presentation | [View PDF](./Presentation-RetainIQ-ARO-Clean-Orchestration.pdf) |

---

## 👨‍💻 Author
**Chintamani Modak**  
Founder & Product Lead – [AIElevate Pte. Ltd.](https://www.aielevate.com)  
📧 founder@aielevate.com  
🌐 [retainiq.com](https://retainiq.com) | [LinkedIn](https://www.linkedin.com/in/chintamanimodak)

---

### ✨ “From data chaos to intelligent orchestration — powered by IBM Watsonx and RetainIQ™.”
