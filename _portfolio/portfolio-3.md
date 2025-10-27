---
title: "AI Alignment Red Teaming"
excerpt: "Creates a more robust form of testing the security of harmless large language models. <br/><img src='/images/d20d4e15caa35ee126705d33ee5bdd1ccbe7ff4f-2880x1620.png'  width='50%' style='margin-top: 20px;'/>"
collection: portfolio
---

![Constitutional AI](/images/d20d4e15caa35ee126705d33ee5bdd1ccbe7ff4f.png)
[Photo: Anthropic](https://www.anthropic.com/research/collective-constitutional-ai-aligning-a-language-model-with-public-input)

This project leverages Open AI's API and the few-shot prompting technique to develope a dual-agent framework designed to evalutate and strengthen AI safety. The system consists of two agents: a main agent, trained to answer standard questions, and an adversarial agent, which attempts to prompt the main agent into violating safety protocols. By simulating adversarial prompts, the framework exposes vulnerabilities in model behavior.

 We combined this strategy with the principles of Constitutional AI: defining a set of 'constitutions', guiding rules and ethical regulations, that an agent must follow. This approach allows the system to iteratively reduce harmful or unsafe outputs while maintaining the model's helpfulness.

[GitHub Repo](https://github.com/vanyadimri/AIRedTeaming)