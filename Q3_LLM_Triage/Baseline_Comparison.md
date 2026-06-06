# Baseline Comparison

## Baseline Method

Hugging Face `facebook/bart-large-mnli` Zero-Shot Classifier

## Comparison Results

| Dimension | LLM-Based Approach | Baseline Approach |
|-----------|-------------------|------------------|
| Message 1 Category | Facilities | Facilities |
| Message 2 Category | Procurement | Governance |
| Message 3 Category | Accessibility | Social |
| Urgency Detection | HIGH, MEDIUM, HIGH | Not supported |
| Structured Output | Full JSON with 10 fields | Category only |
| Confidence Score | Included | Limited |
| Escalation Reason | Included | Not available |
| Follow-up Recommendation | Included | Not available |

## Findings

The LLM-based approach produced richer operational outputs than the zero-shot classifier. While the baseline classifier correctly identified broad categories, it did not provide urgency levels, escalation recommendations, confidence scores, or follow-up actions.

The LLM approach demonstrated better suitability for ESG operational triage because it generated structured JSON outputs that can be integrated into workflow automation and reporting systems.
