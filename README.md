# BlackbirdLM

**BlackbirdLM** is building the observability and traceability layer for agent-native systems—from solo LLM agents to fully orchestrated multi-agent workflows.

We’re solving one of the hardest problems in the emerging agent ecosystem: **trust**.

---

## 🔍 The Problem

As AI agents become more autonomous and operates at scale, they:
- Call tools and other agents (black-box behavior)
- Pass context (or fail to)
- Make decisions with opaque reasoning
- Fail silently or misleadingly

This breaks trust for developers, users, and regulators.

---

## 🚀 Our Solution: `agent-trace` (v1)

BlackbirdLM’s first release is **`agent-trace`**, a framework for **robust, explainable, and complete agent tracing**.

### ✳️ Core Capabilities

- **🔁 Workflow Tracing**  
  Supports flow, cyclical, and graph-based agent executions.

- **📞 Agent + Tool Calling Logs**  
  Full visibility into agent and sub-agent/tool calls.

- **🧠 Context-Transfer Trace**  
  Can agents reliably pass learnings or reasoning if requested?

- **🤔 Feeling-Unsure Trace**  
  Can the agent flag uncertainty or state missing inputs?

- **🧾 Complete Logs**  
  Full logs in both system and human-readable formats for observability,
