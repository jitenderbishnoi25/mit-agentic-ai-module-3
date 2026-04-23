# MIT Applied Agentic AI for Organizational Transformation — Module 3

This repository contains coursework and materials for **Module 3** of the *MIT Applied Agentic AI for Organizational Transformation* course.

---

## dbot — Discord Pirate Bot

> **Credit:** This bot was originally created by [avathuy](https://github.com/avathuy) and is sourced from [github.com/avathuy/dbot](https://github.com/avathuy/dbot). Licensed under the [MIT License](LICENSE).

A Discord bot that answers like a pirate.

### Setup

Update the `.env` file with your credentials:
- Discord bot token: https://discord.com/developers/applications
- OpenAI key: https://platform.openai.com/account/api-keys

### Run — Hello Bot

```bash
python discord_only.py
```

### Run — Pirate Bot

```bash
pip install -r requirements.txt
python mybot.py
```

---

## Project Reflection

**Discord Server:** [Join here](https://discord.com/channels/1496637348740333609/1496637349252173826)

This project provided a practical introduction to building AI-powered bots and integrating them into a real communication platform. Rather than using GitHub Codespaces, I set up the environment locally in VS Code, connected it to a GitHub repository, and credited the original author of the base code. I used Claude Code as an agentic assistant throughout — it helped me navigate the codebase, resolve dependency issues, and debug errors without needing to context-switch into documentation.

From an organizational standpoint, a bot like this has meaningful potential in the insurance industry. Customer service teams frequently handle repetitive, high-volume queries about policy details, coverage limits, and claims status — exactly the kind of interactions a well-prompted AI bot could handle at scale, reducing wait times and freeing up human agents for more complex cases. Beyond customer-facing use, our organization already uses Microsoft Copilot internally to increase productivity, so there is an established cultural openness to AI tooling. A domain-specific Discord or Teams bot, trained on internal policy documentation, could extend that productivity benefit further — acting as an always-available first point of contact for both employees and customers alike.
