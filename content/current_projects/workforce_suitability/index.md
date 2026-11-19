---
title: "AI Workforce Suitability: Evaluating LLM Capabilities for Workforce Tasks"
short_title: AI Workforce Suitability
authors:
  - admin
  - Patrick Quinn
  - Jonathan Prunty
  - José Hernández-Orallo
  - Lucy Cheke
date: 2025-10-20
lastmod: 2026-11-04
show_date: false
summary: >-
  We use performance on annotated AI benchmarks to build capability profiles,
  then compare them with the demands of the tasks people do at work. The resulting
  suitability scores give a capability-based indicator of current AI exposure
  and help organisations decide which tasks to pilot.
resource_kind: Research project
links:
  - name: Read the paper
    url: /publication/2026_workplace_suitability/
  - name: View the slides
    url: "https://www.dropbox.com/scl/fi/yqswou2cq65arwc4b2vik/UK-AI-Forum.pptx?rlkey=b718c0tbn2iqx6i2hz6ea4nls&e=1&st=cg33s3mv&dl=0"
  - name: Original project code
    url: https://github.com/markotesic/ai-workforce-suitability
image:
  preview_only: true
featured: true
---

## Which workplace tasks are current AI systems suited to?

A single benchmark score tells us little about which parts of a job an AI system can handle. This project compares what an AI system can do with the capabilities a particular workplace task requires.

## How we assessed suitability

We annotated benchmark questions with the cognitive capabilities needed to answer them, then used performance on those questions to build profiles for six AI systems. We asked 410 employees across six occupational domains which of the same capabilities mattered for their work. Comparing the model profiles with those task requirements gives a suitability score for each model and task.

These scores can also be read as a capability-based indicator of current AI exposure. They estimate how much of a task’s capability requirements current systems can meet, giving organisations a starting point for deciding what to test in their own workflows.

{{< figure src="featured.png" alt="Diagram showing task requirements and AI capability profiles feeding into a suitability assessment" caption="The framework compares what a task requires (top) with what an AI system can do (bottom). The match helps identify candidates for an AI pilot." >}}
