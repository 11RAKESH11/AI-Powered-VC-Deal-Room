# 🏗️ VC Deal Room AI — System Architecture

> **An AI-driven, multi-agent due diligence and investment intelligence platform powered by IBM Watsonx Orchestrate.**

---

## 🌐 Overall System Architecture

```text
┌─────────────────────────────────────────────────────────────────┐
│                        VC DEAL ROOM AI PLATFORM                 │
├─────────────────────────────────────────────────────────────────┤
│     INPUT LAYER     │     ORCHESTRATION LAYER     │  OUTPUT LAYER │
│─────────────────────│─────────────────────────────│───────────────│
│ • Startup Data      │ • IBM Watsonx Orchestrate   │ • Investment  │
│ • Financials        │ • Workflow Engine           │   Memos       │
│ • Pitch Decks       │ • Agent Coordinator         │ • Risk Reports│
│ • Market Data       │ • Conflict Resolver         │ • Valuation   │
│ • Team Info         │                             │   Models      │
└─────────────────────────────────────────────────────────────────┘
↓
┌─────────────────────────────────────────────────────────────────┐
│                    MULTI-AGENT ANALYSIS LAYER                   │
├─────────────────┬─────────────────┬─────────────────┬───────────┤
│  FINANCIAL      │   MARKET        │    RISK         │ VALUATION │
│  Deep Diver     │ Quantum Analyst │ Red Team        │ Sniper    │
├─────────────────┼─────────────────┼─────────────────┼───────────┤
│  FOUNDER        │    TECH         │     EXIT        │ PORTFOLIO │
│  Profiler       │ Due Diligence   │ Lens            │ Optimizer │
├─────────────────┴─────────────────┴─────────────────┴───────────┤
│                DEAL CONDUCTOR (Orchestrator)                    │
└─────────────────────────────────────────────────────────────────┘
