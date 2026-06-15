---
title: "Key Principles in Designing Agents for Production - Part II: Design Principles for Camunda Agents"
url: "https://camunda.com/blog/2026/06/key-principles-in-designing-agents-for-production-part-2/"
date: "2026-06-03"
author: "Niall Deehan"
feed_url: "https://camunda.com/blog/"
---
This article explores how to structure AI agents for production use by separating decision-making from execution responsibilities. The dynamic execution component of a Camunda Process Agent is an ad hoc subprocess requiring configuration of three key elements: the LLM selection, system prompt, and user prompt. Agent tools should remain decoupled from high-level configuration, allowing modifications without redesigning the entire agent architecture.
