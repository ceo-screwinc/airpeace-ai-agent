# 🤖 AI Agent for AIRPEACE

## 🚀 Overview & Business Problem

This project features a specialized Autonomous AI Agent built to solve the critical problem of information overload and customer service scalability for high-volume businesses like Air Peace Limited.

### The Challenge:
Air Peace, like all big airlines, gets tons of questions online about their flights, baggage, and policies. it's hard for their human team to answer everyone super fast.

### The Solution:
The AIRPEACE AI AGENT provides 24/7, instant, and accurate support. This solution is designed to augment the human team, handling the repetitive 85% of queries so the experts can focus on complex, high-value issues.

---

## ⚙️ Tech Stack & Workflow Architecture

This entire solution is built on modern, scalable, and cost-effective tools.

### 🧱 Core Components:

* Platform: n8n (Self-Hosted)
    * *Purpose:* Provides the robust automation framework, workflow visualization, and secure hosting environment.
* Brain / Intelligence: OpenAI (GPT-4.1-mini)
    * *Purpose:* The Large Language Model (LLM) connected via the OpenAI Chat Model node for state-of-the-art conversational ability.
* Memory: Simple Memory
    * *Purpose:* Enables the agent to remember the context of previous messages for natural, flowing conversations.
* Source of Truth: Google Docs
    * *Purpose:* The external Knowledge Base (KB) for all official service facts, accessed by the KnowledgeBaseTool to ensure answers are always on-brand and verifiable.

### 🛡️ Guardrail Configuration (The Key to Trust)

The System Prompt for the AI Agent strictly instructs it to ONLY use the provided Google Docs Knowledge Base. If a question is asked that is outside the KB, the agent is programmed to professionally decline the request. This ensures security and trust.

---

## 🎬 Video Presentation & Live Demo

Watch the fulL LOOM video presentation to see the agent in action, including a breakdown of the guardrails and the full business case.

([YOUR_LOOM_SHAREABLE_LINK_HERE](https://www.loom.com/share/644d5f664b264cc281664f11641923de))

---

## 💾 Workflow File

This JSON file contains the complete, portable n8n workflow.

* File: AIRPEACE AI AGENT.json

### How to Use:
1.  Download the .json file.
2.  Import it directly into your n8n instance.
3.  Connect your own OpenAI API Key and Google Sheets/Docs credentials to run the agent.

---

## 🙋‍♂️ About the Builder

[ceo david] | AI Automation Enthusiast

* Focus: Building scalable, secure, and cost-effective AI solutions using no-code/low-code platforms.
* Contact: [[Your LinkedIn Profile Link](https://www.linkedin.com/in/ebuka-okpala-a90283255/)]
