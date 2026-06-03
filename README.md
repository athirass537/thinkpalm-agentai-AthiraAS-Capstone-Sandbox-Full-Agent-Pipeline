 Maritime QA Agentic Pipeline — a fully working end-to-end system that hits all the rubric requirements:
Architecture (3 Agents)

🧠 Orchestrator Agent — Receives task input, decomposes it into sub-tasks, identifies applicable regulations (SOLAS, MARPOL, ISM), and dispatches to sub-agents
⚖️ Compliance Agent — Analyzes each regulation framework, runs pass/warn/fail checks against maritime rules, assigns severity
📄 Report Agent — Synthesizes findings into a structured report with risk score, corrective actions, and re-inspection timeline

Memory (Short + Long-term)

Short-term session memory tracks vessel name, frameworks, violations across pipeline steps
Long-term memory persists run history, total violations, vessel list, and timestamps across runs

Tool Calling

Simulated tool invocations: imo_lookup(), solas_check(), marpol_check(), ism_audit(), incident_db_query() — shown in the pipeline flow

Working UI

Pre-built prompt chips for SOLAS fire safety, ISM audit, MARPOL emissions, PSC inspection
Live agent flow diagram showing active/done states
History panel with run log and memory summary
Agents, Memory, and Logs tabs for inspection

Click ▶ RUN PIPELINE to execute the full agentic chain 
