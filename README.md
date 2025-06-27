# 🤖 ChatMux – The LLM-Agnostic Chatbot (MCP-Compatible)

**ChatMux** is a multi-model chatbot designed to operate independently of any single large language model (LLM).  
Instead of relying on a fixed backend like GPT-4, **ChatMux** dynamically connects to various LLM providers — such as OpenAI, Claude, Gemini, Mistral, and more — adapting in real time to your preferences, context, or cost constraints.

> 🧠 A single chatbot, powered by many brains.

---

## 🎯 What is ChatMux?

ChatMux is not a framework.  
It’s a **fully functional, intelligent chatbot** that uses multiple LLMs as interchangeable engines. It can switch between providers seamlessly — manually or automatically — and is fully compatible with the **Model Composition Protocol (MCP)** for advanced model orchestration.

Whether you need high-accuracy reasoning, fast responses, low-cost inference, or region-specific availability, **ChatMux picks the right engine for the job.**

---

## 🔥 Key Features

- ⚙️ **Multi-model support**
  - OpenAI (GPT-4, GPT-3.5)
  - Anthropic (Claude)
  - Google (Gemini)
  - Mistral
  - Cohere
  - Local or open-source models (LLaMA, MPT, Falcon, etc.)

- 🔀 **Intelligent routing**
  - Choose the best model based on cost, speed, or context
  - Fallback and chaining support via MCP
  - Custom strategies (e.g., use Gemini for search, GPT-4 for reasoning)

- 🧠 **One interface, many engines**
  - No need to manage different APIs — ChatMux handles the switching
  - Unified experience, regardless of underlying model

- 🌐 **Vendor neutrality**
  - Avoid lock-in
  - Optimize for performance, pricing, and availability

---

## 🗺 Roadmap (High-Level)

| Feature                         | Status     |
|----------------------------------|------------|
| Multi-LLM engine switching       | 🕓 Planned |
| MCP protocol integration         | 🕓 Planned |
| CLI & web-based interaction      | 🕓 Planned |
| Persistent user memory           | 🕓 Planned |
| RAG integration (vector search)  | 🕓 Planned |
| v0.1 public release              | ⏳ Coming Soon |

---

## 📖 License

Apache License 2.0  
© 2025 **Matías Salinas**

---

## ⭐ GitHub Repository

🔗 https://github.com/msalinas92/ChatMux

If you're interested in vendor-agnostic conversational AI, protocol-level interoperability, or building on top of multiple LLMs without friction — consider starring the repo or contributing!
