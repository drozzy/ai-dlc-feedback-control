# AI-DLC as an Event-Driven Feedback Controller for Software Delivery

Andriy Drozdyuk · November 2026

**[Read the paper (PDF)](ai-dlc-feedback-control.pdf)**

## Abstract

Software development with an LLM agent already contains feedback. The Kiro
host returns tool results to the model, while a person reviews delivery
evidence and writes the next prompt. AI-DLC keeps that execution loop and makes
three additional loops explicit: human governance, lifecycle progression, and
recorded evidence. Together, these four loops form an event-driven feedback
system. The model proposes actions, Kiro tools change delivery state, evidence
returns through tests, sensors, reviewers, and people, and rules and people
determine whether workflow state advances. The aligned diagrams show how work
held informally by the person becomes explicit lifecycle routing, guarded tool
use, evidence records, durable state, and gates.

## Related

- [AI-DLC Workflows documentation](https://awslabs.github.io/aidlc-workflows/)
- [AI-DLC Workflows source](https://github.com/awslabs/aidlc-workflows)
- [Kiro](https://kiro.dev/)
