# First_Agent
# 🏗️ Step 1: Main Agent Setup (OpenAI Agents SDK)

This notebook demonstrates how to create a foundational **main agent** using the OpenAI Agents SDK.  
This agent is designed for use in larger multi-agent products, like AI Ad Generators.

---

## 🔧 Tech Stack

- OpenAI Agents SDK
- Google Gemini (via LiteLLM)
- Google Colab-compatible
- Tracing disabled for clean output

---

## 🎯 Agent Role

> **Name:** `PlatinumAdAgent`  
> **Purpose:** Acts as the main decision-maker agent for real estate ad workflows.  
> **Instructions:** It receives user input and waits for tools to process it in future steps (tools not added yet).

---

## 🧪 Current Status

- Agent responds to real-estate related inputs.
- No tools attached yet.
- No ad is generated here — this is just the foundational main agent setup.

---

## 📥 Input Example

```text
"I want to create an ad for a 5 marla house in Bahria Town"
