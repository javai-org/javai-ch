---
title: "Quantifying Risk Is Easy. Quantifying Likelihood Is the Hard Part."
date: 2026-04-02
description: "Most software engineers have never quantified uncertainty. With LLMs, that's no longer viable. Here's how probabilistic testing can help."
image: /images/risk-matrix.webp
---

# Quantifying Risk Is Easy. Quantifying Likelihood Is the Hard Part.

Most software engineers have never quantified uncertainty. With LLMs, that's no longer viable. Here's how probabilistic testing can help.

![NASA-style risk matrix](/images/risk-matrix.webp)

2 April 2026

The NASA risk matrix is one of the most widely used frameworks in risk management. Plot consequence on one axis, likelihood on the other, and you have a visual tool for prioritising threats. It appears in everything from spacecraft engineering to financial regulation, from healthcare to software development.

But the two axes are not equally difficult to assess.

## Consequence is tractable

The vertical axis — consequence, impact, severity — is often surprisingly amenable to quantification. In most domains, consequences can be expressed in terms that humans already understand and measure routinely.

Monetary cost is the most obvious. A system failure that corrupts a transaction has a definable cost: the value of the transaction, the cost of remediation, potential regulatory penalties, reputational damage that can be estimated in terms of customer churn. Insurance and actuarial science have been quantifying consequences for centuries.

Where monetary cost is inadequate, human welfare provides a fallback. Health systems measure outcomes in quality-adjusted life years (QALYs). Safety-critical industries measure harm in terms of injuries, hospitalisations, fatalities. These are grim metrics, but they are measurable, and they allow consequences to be compared across different risk scenarios.

The point is not that measuring consequence is easy — it requires effort, data, and careful modelling. The point is that we have established methods for doing it.

## Likelihood is harder

The horizontal axis — likelihood, probability, frequency — is another matter entirely.

For some risks, likelihood can be estimated from historical data. If a mechanical component has failed three times in the past thousand deployments, you have an empirical basis for estimating failure probability. Reliability engineering has developed sophisticated tools for this.

But many risks do not come with historical baselines. Novel systems, unprecedented conditions, emergent behaviours — these produce scenarios where there is no track record to draw upon. What is the likelihood that a cyberattack will exploit a newly discovered vulnerability? What is the probability that a regulatory change will render a business model non-compliant? What is the chance that an AI model will produce a confidently wrong answer in a high-stakes context?

These are not merely difficult questions. They are questions that often go unasked — or, worse, are answered with intuition dressed up as analysis.

## Software's history of ignoring the question

Most software engineers have never quantified uncertainty. When a network call occasionally timed out, it was handled — mostly — but how often it happened, and whether that frequency was acceptable, went unmeasured. Without a framework for thinking about the problem, the field normalised ignoring it.

Testing, in this context, was a matter of verifying that outputs matched expectations. Pass or fail. Green or red. When a test failed intermittently, it was labelled "flaky" and either fixed or — more often — muted. When failures occurred in production, they were investigated as one-off anomalies. There was no systematic effort to measure the *rate* at which failures occurred, or to ask whether that rate was acceptable.

This worked well enough when non-determinism could be dismissed as an occasional annoyance. It does not work when non-determinism is the design.

## LLMs make the problem unavoidable

Large language models are stochastic by construction. Ask the same question twice and you may get different answers. This is not a bug to be fixed — it is a fundamental characteristic of how these systems operate.

The implications for testing are profound. A single test run tells you almost nothing about system behaviour. A test that passes today may fail tomorrow, and both outcomes may be entirely consistent with the model's design. The question "does this work?" must be replaced with "how often does this work?" — and that question demands statistical methods.

This is not a niche concern. LLMs are being deployed in customer service, medical triage, legal research, financial analysis — domains where confidence in system behaviour matters enormously. Yet the testing tools available to most development teams were designed for a deterministic world. They produce binary verdicts when what is needed is a probability distribution.

The uncomfortable truth is that many organisations deploying LLM-powered systems have no rigorous answer to the question: how often does this system fail?

## Regulators are starting to notice

FINMA — Switzerland's financial market supervisor — issued [Guidance 08/2024](https://www.finma.ch/en/news/2024/12/20241218-mm-finma-am-08-24/) in December 2024, setting expectations for AI governance in supervised institutions. The guidance requires financial institutions to perform regular testing, monitor performance over time, and maintain documentation of how AI systems behave.

Notably, FINMA expects institutions to use *performance indicators* — quantitative measures of how well a system achieves its objectives. This is a significant departure from pass/fail testing. It requires measurement, not merely verification.

FINMA is not alone. The EU AI Act, which comes into full effect in August 2026, mandates performance measurement and monitoring for high-risk AI systems. ISO 42001, the international standard for AI management systems, requires organisations to define and track performance metrics.

The regulatory direction is clear: organisations must be able to demonstrate, with evidence, that their AI systems perform within acceptable bounds. Subjective assessments — "we think it works" — will not satisfy auditors.

## The answer: probabilistic testing

If the question is "how often does this work?", the method must be statistical.

Probabilistic testing runs a test many times, measures the success rate, and applies statistical inference to determine whether the observed rate meets a defined threshold at a given confidence level. Instead of asserting that a function returns a specific value, you assert that the function succeeds at least 99.5% of the time with 95% confidence.

This produces structured, quantitative evidence: success rates, confidence intervals, trend data. It transforms compliance from a subjective judgement into a measurable, auditable claim.

The [punit](https://github.com/javai-org/punit) framework, developed by Javai, implements this approach for Java applications. Built as a JUnit 5 extension, it runs tests multiple times and applies hypothesis testing to determine whether system behaviour is acceptable. Developers can define statistical expectations in familiar test syntax, without needing to become statisticians.

The framework supports three modes:

- **Explore**: Discover optimal configurations for non-deterministic operations — which model, which prompt, which parameters minimise failures?
- **Measure**: Establish empirical baselines for success rates and latency distributions, producing data that can inform SLAs and regulatory documentation.
- **Regression**: Detect when system behaviour drifts beyond acceptable bounds, catching degradation before it reaches production.

This is not a replacement for traditional testing. Deterministic code should still be tested deterministically. But where non-determinism is inherent — and with LLMs, it always is — probabilistic methods are the only honest approach.

## Not all risks are software risks

It would be a mistake to suggest that probabilistic testing solves the entire likelihood problem. Many risks — geopolitical, macroeconomic, regulatory, reputational — cannot be reduced to software test results.

But software-related risks *can* be quantified, and quantified with rigour. For organisations deploying AI systems, this is no longer optional. FINMA expects it. The EU AI Act mandates it. Auditors will ask for the evidence.

Most software engineers have never quantified uncertainty. With LLMs, that era of comfortable ignorance is over. The non-determinism is too visible, the stakes too high, the regulatory scrutiny too intense.

It is time to take uncertainty seriously — and that means measuring it.

---

*For technical documentation and getting-started guides, visit [javai.org](https://javai.org). For regulatory context, see [Why Probabilistic Testing Matters for Swiss Regulation](/en/posts/2026-03-21-why-probabilistic-testing/).*

Copyright © 2026 by [javai.ch](https://javai.ch/).
