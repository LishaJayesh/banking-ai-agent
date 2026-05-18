# Banking Customer Support AI Agent
A fully autonomous multi-agent system that classifies, routes, and responds to customer support messages — without human intervention for routine interactions.

- 4 specialist agents orchestrated via LangGraph StateGraph — Classifier, Positive Feedback, Negative Feedback, Query Handler
- 100% automated message classification; LLM-driven flow control with no boolean flags
- Live SQLite ticket DB: creation, lookup, escalation detection & LLMOps quality logging
- Multi-turn memory via LangGraph MemorySaver; responses scored on Empathy, Accuracy & Clarity
