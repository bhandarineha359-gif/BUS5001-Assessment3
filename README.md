# BUS5001-Assessment3
# BUS5001 Assessment 3 — Robotic Process Automation, AI and Cloud-Enabled ESG Analytics

## Student Information

| Field | Detail |
|-------|--------|
| Subject | BUS5001 |
| Assessment | Assessment 3 |
| Due Date | 11:59 pm AEST, Sunday 7th June 2026 |
| Weighting | 40% |

---

## Repository Purpose

This repository contains evidence, experiment logs, screenshots, and supporting files for the four questions in BUS5001 Assessment 3. It is submitted alongside the written report.

---

## Repository Structure

```
BUS5001-Assessment3/
│
├── README.md                        ← This file
│
├── Q1_Chatbot/
│   ├── README.md                    ← Q1 evidence summary
│   ├── Flow_Diagram.png             ← Dialogflow CX conversation flow diagram
│   ├── Intent_Report_Water_Leak.png ← Intent with training phrases
│   ├── Entity_Building.png          ← @building custom entity
│   ├── Entity_Severity.png          ← @severity custom entity
│   ├── Location_Page.png            ← Location page configuration
│   ├── Severity_Page.png            ← Severity page with routing logic
│   ├── Description_Page.png         ← Description page configuration
│   ├── Escalation_Page.png          ← Critical escalation page
│   ├── Confirmation_Page.png        ← Confirmation page configuration
│   ├── Test_Case_1.png              ← Standard flow test (High severity)
│   └── Test_Case_2.png              ← Critical escalation test
│
├── Q3_LLM_Triage/
│   ├── README.md                    ← Q3 experiment log summary
│   ├── Prompt_Template.md           ← Improved ESG triage prompt (v2.0)
│   ├── Message1_Output.json         ← LLM output: water leak
│   ├── Message2_Output.json         ← LLM output: supplier policy
│   ├── Message3_Output.json         ← LLM output: accessibility blocked
│   └── Baseline_Comparison.md       ← Comparison vs Hugging Face zero-shot
│
├── Q4_NotebookLM/
│   ├── README.md                    ← Q4 evaluation notes
│   ├── Scenario1.png                ← Student exam prep screenshot
│   ├── Scenario2.png                ← Researcher policy synthesis
│   ├── Scenario3.png                ← Lecturer governance workshop
│   ├── Scenario4.png                ← MBA Scope 3 briefing
│   └── Evaluation_Notes.md          ← Critical analysis summary
│
└── References/
    └── Sources.md                   ← APA 7 reference list
```

---

## What Each Section Contains

### Q1 — ESG Sustainability Incident Chatbot (Dialogflow CX)
Screenshots of the built chatbot including intents, entities, pages, routes, and two test case transcripts. The chatbot handles water leak incident reporting with critical severity escalation.

### Q3 — LLM ESG Message Triage
The improved prompt template (v2.0), three JSON outputs from running ESG messages through the LLM, and a comparison table against a Hugging Face zero-shot baseline classifier.

### Q4 — NotebookLM Evaluation
Screenshots from four academic scenarios tested in NotebookLM, plus evaluation notes covering accuracy, usefulness, and limitations.

---

## How to Navigate

- For chatbot evidence → go to `Q1_Chatbot/`
- For LLM prompt and outputs → go to `Q3_LLM_Triage/`
- For NotebookLM screenshots → go to `Q4_NotebookLM/`
- For references → go to `References/`

Each folder has its own `README.md` explaining the contents.
