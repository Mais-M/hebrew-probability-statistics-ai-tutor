# Hebrew AI Tutor for Probability & Statistics

A Hebrew AI learning-agent prototype for Probability and Statistics, designed to support beginners through clear, step-by-step explanations based only on uploaded PDF sources.

## Project Overview

This project explores how an AI tutor can support learning in a responsible, transparent, and source-grounded way.

The agent is designed as a patient private tutor in Hebrew. It helps users understand probability and statistics concepts, solve exercises step by step, and learn at their own pace.

The key idea behind the project is simple:

> The tutor should not only know how to answer — it should also know when not to answer.

If the answer is not found in the uploaded PDF sources, the tutor is instructed to say:

> "אני לא מוצא/ת את זה במקורות שהועלו."

## Why I Built This

Probability and statistics are foundational for understanding data, machine learning, artificial intelligence, uncertainty, and evidence-based decision-making.

Many people use AI tools for learning, but AI-generated answers are not always clearly grounded in reliable sources. This project focuses on building a learning agent that is more transparent, careful, and source-aware.

## What the Tutor Does

* Explains probability and statistics concepts in Hebrew
* Supports beginners with no prior background
* Solves exercises step by step
* Explains formulas in simple language
* Adapts explanations to the user's level
* Uses uploaded PDF files as its source of truth
* Avoids inventing information that is not in the sources
* Responds respectfully and professionally

## Responsible AI Principles

This project was designed with several responsible AI principles in mind:

* **Transparency** — the user should understand that answers are based on uploaded sources
* **Explainability** — the tutor explains concepts clearly, not just final answers
* **Accountability** — the tutor is instructed not to present unsupported information as fact
* **Source grounding** — answers should rely only on the uploaded PDF materials
* **Privacy awareness** — the tutor uses only the files provided by the user
* **Responsible use** — the tutor avoids harmful, offensive, or irrelevant content
* **Copyright awareness** — original PDF course materials are not included in this repository
* **Limit awareness** — the tutor should clearly state when information is missing from the sources

## Repository Contents

```text
README.md
system_prompt.md
example_outputs.md
screenshots/
```

## Screenshots

The infographic below summarizes the learning-agent concept:

![LinkedIn Infographic](screenshots/linkedin_infographic.png)

## Important Note About PDF Sources

The original PDF course materials are not included in this repository due to copyright considerations.

This project documents the agent design, system instructions, example behavior, and learning workflow — not the original course content.

## Current Status

Prototype stage.

The agent was designed and tested as a Claude Project using uploaded PDF materials as the knowledge base.
