# Evaluation Workflow

A standardized workflow for conducting consistent, reproducible, and evidence-based evaluations of large language models.

This repository documents the end-to-end evaluation process used throughout **LLM Evaluation Lab**. Rather than relying on subjective impressions, every evaluation follows a structured methodology designed to produce transparent, repeatable, and well-documented results.

---

## Mission

Establish a consistent evaluation workflow that allows different reviewers to reach similar conclusions when evaluating the same AI response.

The workflow emphasizes:

- Repeatability
- Transparency
- Evidence-based analysis
- Consistent scoring
- Clear documentation

---

## Evaluation Process

### 1. Define the Evaluation

- Record the prompt.
- Define the evaluation objective.
- Identify the evaluation category.

Examples:

- Hallucination Detection
- Reasoning
- Translation
- Search Quality
- Safety
- Prompt Engineering

---

### 2. Record the Model

Document:

- Model name
- Version (if available)
- Date
- Platform

---

### 3. Preserve the Original Response

Never modify or rewrite the model's response before evaluation.

The original output should remain available for review.

---

### 4. Verify the Response

Check:

- Facts
- Sources
- Calculations
- Citations
- Logical consistency

Whenever possible, support corrections using authoritative evidence.

---

### 5. Apply the Universal Rubric

Every evaluation uses the standard scoring criteria defined in the **AI-Evaluation-Rubrics** repository.

Core categories include:

- Accuracy
- Reasoning
- Instruction Following
- Completeness
- Evidence Quality
- Clarity
- Safety

---

### 6. Apply Specialized Rubrics

Depending on the task, additional rubrics may be used.

Examples:

- Hallucination Rubric
- Reasoning Rubric
- Translation Rubric
- Pairwise Comparison Rubric
- Search Quality Rubric
- Safety Rubric

---

### 7. Document Findings

Every evaluation should include:

- Observations
- Errors
- Strengths
- Weaknesses
- Supporting evidence

Avoid unsupported opinions.

---

### 8. Assign Scores

Apply the appropriate scoring criteria.

Explain every score.

Scores should be reproducible by another evaluator using the same methodology.

---

### 9. Write Evaluator Notes

Summarize:

- Major findings
- Important limitations
- Suggested improvements
- Overall assessment

---

### 10. Publish

Publish the completed evaluation together with:

- Prompt
- Response
- Evidence
- Rubric scores
- Reviewer notes

---

## Guiding Principles

The workflow is built around a few simple ideas:

- Evaluate the response, not the model.
- Verify before scoring.
- Explain every conclusion.
- Separate facts from opinions.
- Preserve reproducibility.
- Document uncertainty.
- Prioritize evidence over intuition.

---

## Related Repositories

- AI-Evaluation-Rubrics
- AI-Hallucination-Database
- LLM-Evaluation-Benchmarks
- Prompt-Arena
- AI-Safety-Evaluation
- Search-Quality-Ratings
- Bilingual-LLM-Evaluation
- Prompt-Engineering-Cookbook

---

## Status

**Version 0.1**

This workflow will continue to evolve as additional evaluation methods, rubrics, and benchmarking techniques are incorporated into the LLM Evaluation Lab.
