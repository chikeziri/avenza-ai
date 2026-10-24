# Avenza

Avenza turns a research questionnaire into a live survey, collects the answers, and writes the report.

A team can upload a Word or PDF questionnaire, build one by hand, or ask Avenza to draft one. Avenza turns that document into a shareable survey. When responses come in, paid layers unlock descriptive charts, an AI-written Word report, and, if the study needs them, qualitative coding or inferential statistics.

**Live:** [avenzaai.com](https://avenzaai.com)

## Who it is for

Research teams, consultants, and students who already have the questions and need the survey, the responses, and a report they can hand over.

## What a study looks like

- Upload a questionnaire and see a structured preview before anyone pays. A guest can reach that preview. The survey does not go live until the rules for activation are met.
- Share one link. Responses collect in the project.
- Descriptive charts and a written report come after payment. The report says what was computed and what was written with AI.
- Qualitative work covers themes. Inferential work is checked against known statistical results, so a paid test is not a loose paragraph.
- A paid report is not released half-finished. If the analysis is not ready, Avenza does not hand over a “pending” document and call it done.

## Payments and access

Activation and the analysis layers are separate. A first activation can be free under the welcome rule. Unpaid accounts do not reach the paid layers. Paystack confirms a payment on the server. If a webhook is missed, the account can still be reconciled, including from the admin tools, so a person who paid is not left outside.

## How it is run

Avenza is a production service: a web app people can install on a phone, an API, background workers for the longer jobs, and an admin path for payments, entitlements, and email. Several model providers are allowed, with a cost cap, so a bad model name cannot silently spend the budget.

Inventa Labs keeps the product source private. This page is the public introduction.
