# 🛡️ Smart LLM Security Gateway & AI Firewall

An enterprise-grade middleware defense system and SOC dashboard built to secure Large Language Model applications in real-time. It intercepts user inputs, inspects incoming prompts, blocks injection attacks, redacts sensitive PII, and provides real-time threat telemetry.

---

## 🚀 Key Features

* **Real-time Prompt Injection Shield:** Detects and mitigates jailbreak techniques, DAN prompts, and adversarial system prompt extraction.
* **PII & Secret Redaction:** Intercepts credit card numbers, SSNs, and sensitive user credentials before hitting the model backend.
* **Automated Red-Team Audit Suite:** Built-in security testing framework that executes adversarial attack suites and generates live compliance scorecards.
* **SOC Threat Analytics Dashboard:** Interactive telemetry dashboard featuring live attack timeline graphs (via Recharts), active guardrail toggles, and forensic audit logs.

---

## 🏗️ Architecture & Pipeline

[ User Input ]
│
▼
┌──────────────────────────────────────────────┐
│       Smart LLM Security Gateway            │
│  ├── 1. Prompt Injection Filter              │
│  ├── 2. PII / Secret Masking                 │
│  └── 3. Toxicity & Jailbreak Detector        │
└──────────────────────────────────────────────┘
│                           │
[ BLOCKED ]                 [ ALLOWED ]
│                           │
▼                           ▼
(Audit Log / SOC)           (LLM Backend Provider)

---

## 🛠️ Tech Stack

* **Frontend:** React, Recharts, Lucide Icons, CSS3 Grid/Flexbox
* **Backend:** Python, FastAPI, Pydantic, LLM Guard
* **Database/Logging:** SQLite / Dynamic Audit State Management
* **Security Layer:** Real-Time Token Guardrails, PII Sanitizers
