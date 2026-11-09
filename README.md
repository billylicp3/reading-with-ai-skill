# Reading with AI

A reusable agent skill for turning a supplied academic paper into a standalone, interactive HTML reading companion. The framework supports orientation, source navigation and reflection; it does not replace reading the paper.

## Get the skill

Download this repository with **Code → Download ZIP**, extract it, and use the `reading-with-ai` folder. That folder contains `SKILL.md`, supporting instructions and an HTML starter. A repository ZIP and a skill-folder ZIP may have different layouts; follow your tool's documented importer requirements.

In a tool that supports local agent skills, ask it to install the `reading-with-ai` folder using its supported installation flow. This repository does not install itself, request credentials or run an installer. Merely pasting a GitHub link does not guarantee installation. ChatGPT, WorkBuddy and other tools differ in whether they support skills, files and HTML output; verify the actual feature in your account. This package has not been installation-tested across those products.

If native skills are unavailable, provide `SKILL.md` and its referenced files as task attachments and ask the assistant to follow them for the current task. This is a task-level fallback, not persistent installation.

## Use

Supply a lawfully accessible PDF, then ask:

> Use Reading with AI to create one English interactive HTML reading companion for the attached paper. I am new to this topic and want to understand the argument. Follow the skill's framework and visual style. Use only text you actually access; preserve source locations and distinguish author claims from your explanations. Deliver a downloadable, self-contained HTML file. If file creation is unavailable, say so.

For Chinese support, request a Chinese-support edition: Chinese UI and explanations with necessary English terminology, not sentence-by-sentence bilingual duplication. Request an English edition separately when needed.

## What it produces

- Before reading: paper identity, reading focus, essential abbreviations and an accessible SVG argument map.
- During reading: source-location / author-paraphrase / guiding-question table, optional explanations and keyword lookup.
- After reading: clearly labelled invented cases, optional fixed questions with explanations and source locations, and visible copyable follow-up prompts.
- A quiet cream-and-green design, responsive layout, text-size controls, keyboard-friendly interactions and a print view.

The generated page runs locally without a server, live AI calls, account, analytics or stored reader notes. Quiz explanations are prepared content, not live AI assessment. Correct answers do not establish deep reading.

## Adapt the framework

Tell your agent what to change, try the resulting guide on a real paper, then ask it to update a copy of this skill and its template to preserve your preferences. Keep source accuracy and disclosure while changing the reading route, layout, language or exercise design. Saving a skill does not train the model or guarantee identical results.

## Academic use

The skill retains concise references to public HKU guidance on learning goals, instructor rules and acknowledging AI assistance. It is an independent template, not an HKU-approved product or a universal institutional reading requirement. Source PDFs and private course materials are not distributed here. Source-paper rights remain with their respective holders.

Version: 1.0.0. Instruction/schema and starter-interaction checks are recorded locally by the maintainer. A fresh end-to-end paper generation and cross-tool installation still require testing.
