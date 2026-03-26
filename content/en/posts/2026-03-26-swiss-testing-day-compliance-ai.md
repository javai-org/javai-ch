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

## Defining quality in a dangerous decade

The afternoon panel brought together Bertrand Meyer, Elmar Jürgens, and Marcel Gygli, moderated by Anne-Lea Marte, to tackle a deceptively simple question: in a world where systems learn, how do we define quality?

The answers diverged immediately. Gygli framed quality in terms of whether users get what they need. Jürgens pushed back: for casual software, perhaps — but business-critical systems demand more. Meyer took the broadest view, insisting that quality is multi-dimensional, lives in the eyes of all stakeholders, and must be sustained over time.

On speed, the panellists struck a cautious note. Jürgens warned of a trade-off if code generation outpaces test generation. Gygli posed a sharper question: if 90% of generated code is correct but the remaining 10% is extremely hard to test or debug, the apparent speed gain may be illusory.

The discussion grew more pointed on responsibility. When AI systems cause harm, who is accountable? Jürgens was unequivocal: those who created the software. Meyer warned that both AI hype and AI denial are dangerous, and that decision-makers are too easily swept along by enthusiasm. All three agreed that education and regulation are essential to keep human safeguards in place.

Asked what is nonsense in the industry, the panel did not hold back. Meyer singled out putting agents in charge with humans as backup. Gygli took aim at vibe coding. Jürgens called most productivity measurement approaches meaningless.

On what they would like to see happen, the panellists converged on regulation. Gygli called for usable regulation that reflects what society actually needs. Meyer — joking that "America innovates, China copies, Europe regulates" — expressed hope for more mathematical proofs in testing. Jürgens hoped Meyer was right, but noted that formal methods remain limited in practice.

## When generated code cannot be tested

Jonas Hermansson shared a candid account of building software entirely with AI agents. His team now uses multiple agent teams with distinct roles — frontend, backend, database — and deploys twice as many testing agents as development agents.

The lessons were hard-won. Early experiments with vibe-coded solutions produced code that was effectively untestable. A generated login feature contained a bug traceable to an ambiguous requirement. A QA wrapper that tested intent from requirements to end product still missed concurrency bugs. In the end, the team reintroduced manual testing as a final sanity check — expensive, but necessary.

Perhaps the most striking revelation: Hermansson's team no longer maintains code at all. When something needs to change, they regenerate from scratch. It is a radical workflow that raises as many questions as it answers.

## The closing keynote: a call for statistical thinking

Robert Sabourin — academic and veteran testing practitioner — delivered a closing keynote that reframed the conference's undercurrent of anxiety as opportunity. He addressed the danger-alert tone that the organisers had deliberately set, countering it with a positive message about the business opportunities that arise from testing AI-driven systems.

{{< figure src="images/test-oracle.jpeg" alt="Slide on probabilistic test oracles from Robert Sabourin's closing keynote" caption="Robert Sabourin on the need for experiments and probabilistic testing" >}}

Most significantly for the themes of this conference, Sabourin made an explicit case for probabilistic testing. He urged testers to develop a statistical mindset, arguing that stochastic services must be tested probabilistically — not with the binary pass/fail verdicts inherited from deterministic software. It was a fitting conclusion to a day that had circled this idea repeatedly without always naming it directly.

## The thread that connects it all

Across the day's programme, a common thread was unmistakable: the testing profession is grappling with systems that do not behave the same way twice. Traditional pass/fail testing was built for deterministic software. The systems now being deployed — from LLM-powered agents to synthetic media detection — demand new approaches: statistical measurement, probabilistic guarantees, and governance frameworks that can accommodate uncertainty.

Swiss Testing Day 2026 showed that the profession knows this. The question now is how quickly the tooling and practices will catch up.
