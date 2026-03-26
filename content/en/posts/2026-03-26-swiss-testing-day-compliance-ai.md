---
title: "Compliance and AI Feature Strongly at Swiss Testing Day 2026"
date: 2026-03-26
description: "Swiss Testing Day 2026 put AI compliance and non-deterministic testing at centre stage, with speakers from banking, governance, and software engineering converging on a shared challenge."
summary: "Swiss Testing Day 2026 made one thing clear: compliance and AI are no longer parallel conversations. From Bertrand Meyer's keynote on software verification to a standout talk on why AI is useless for compliance — and indispensable — the conference showed that testing non-deterministic systems is the defining challenge for quality professionals today."
featured_image: "images/bertrand-meyer.jpg"
featured_image_alt: "Bertrand Meyer speaking at Swiss Testing Day 2026"
featured_image_caption: "Software Correctness Authority Bertrand Meyer"
---

Swiss Testing Day 2026, held in Zurich on 26 March, brought together testers, quality engineers, and compliance professionals for a day of talks and panels focused overwhelmingly on one theme: what happens when AI enters systems that must be reliable, auditable, and correct?

## Software correctness meets non-determinism

The opening keynote by Bertrand Meyer — pioneer of design-by-contract and the Eiffel programming language — set the tone. Meyer covered a wide range of issues but kept returning to a central idea: proving that software does what it promises. Large language models, with their inherent non-determinism, have made this challenge harder, not easier.

Meyer stressed that the performance of stochastic features — especially LLMs — must be *measured*, because a simple pass/fail verdict is not sufficient. Yet he did not go into detail on *how* to measure such systems, instead reiterating his long-standing conviction that correctness must be built into software from the ground up.

He ended on an optimistic note, arguing that the need for skilled software engineers will not disappear, even as their tools change. Generated code must still be verified, and human understanding of the code remains essential.

## Testing strategy is not a list of goals

Iosif Itkin challenged the audience to think carefully about what testing strategy actually means — and what it is not. It is not a list of goals. It is not the same as quality assurance, which requires a different mindset entirely.

Drawing extensively on the book *Good Strategy/Bad Strategy*, Itkin delivered a valuable reminder: organisations that are serious about AI need to design their testing strategy deliberately, not let it emerge by accident.

## Agentic testing already delivers in banking

A team from the Swiss banking sector presented "Avalon", an agent-based system that generates synthetic test data. While the talk moved quickly into product specifics, the key takeaway was clear: this is a sophisticated agentic application already delivering measurable productivity gains. The system operates transparently, revealing LLM interactions and tool calls in real time through its interface.

## The compliance talk of the day

The standout session was Nick Gushchin's *Why AI Is Useless for Compliance …and Why You Still Need It*. Gushchin, an AI Transformation Manager, laid out a structured approach to AI risk management using a likelihood-and-impact matrix — a proven framework, he emphasised, whose importance is no less relevant in the age of AI.

His central question — how to quantify the "likelihood" dimension when dealing with non-deterministic systems — is precisely the challenge that probabilistic testing frameworks aim to address. This was the first talk at the conference to explicitly confront the problem of testing systems whose outputs are inherently variable.

No hype, no hand-waving — just practical, grounded guidance for anyone responsible for testing and reliability in AI-driven environments.

## The thread that connects it all

Across the day's programme, a common thread was unmistakable: the testing profession is grappling with systems that do not behave the same way twice. Traditional pass/fail testing was built for deterministic software. The systems now being deployed — from LLM-powered agents to synthetic media detection — demand new approaches: statistical measurement, probabilistic guarantees, and governance frameworks that can accommodate uncertainty.

Swiss Testing Day 2026 showed that the profession knows this. The question now is how quickly the tooling and practices will catch up.
