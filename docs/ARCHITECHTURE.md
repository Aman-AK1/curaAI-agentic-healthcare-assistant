# CuraAI — High-Level Architecture

```text
User (Web Browser)
        ↓
Next.js UI  (src/pages, src/components)
        ↓
API Routes  (src/pages/api/*.js)
        ↓
MongoDB Models (src/models/*.js)
        ↓
Agentic Responsibilities
    - Symptom Analysis Agent
    - Medical Knowledge Agent
    - Report Understanding Agent
    - Hospital Recommendation Agent
    - Action & Planning Agent
