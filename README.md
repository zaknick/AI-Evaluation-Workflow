# AI-Evaluation-Workflow

A standardized workflow for conducting consistent, reproducible, and evidence-based evaluations of large language models.

This repository documents the end-to-end evaluation process used throughout the **LLM Evaluation Lab**. Rather than relying on subjective impressions, every evaluation follows a structured methodology designed to produce transparent, repeatable, and well-documented results.

---

## Mission

Establish a standardized evaluation workflow that enables independent reviewers to reach consistent conclusions when evaluating the same AI response.

The workflow emphasizes:

- Repeatability
- Transparency
- Evidence-based evaluation
- Consistent scoring
- Clear documentation
- Reproducibility

---

## Evaluation Types

### Single-Case Evaluation

Used for evaluating an individual model response, such as a hallucination analysis, reasoning assessment, or case study.

### Benchmark Evaluation

Used for evaluating multiple prompts, repeated trials, or multiple models using a common methodology to enable statistical comparison.

---

## Evaluation Process

### 1. Define the Evaluation

- Record the prompt
- Define the evaluation objective
- Identify the evaluation category

Examples:

- Hallucination Detection
- Reasoning
- Translation
- Search Quality
- Safety
- Prompt Engineering

---

### 2. Record the Evaluation Environment

Document whenever available:

- Model name
- Model version
- Platform
- Evaluation date
- Temperature or generation settings
- Tool access
- Web browsing enabled or disabled
- System instructions (when known)
- Number of trials performed

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

For each supporting source, record whenever practical:

- Source authority
- Publication date
- Retrieval date

---

### 5. Apply the Universal Rubric

Every evaluation uses the standard scoring methodology defined in the **AI-Evaluation-Rubrics** repository.

---

### 6. Apply Specialized Rubrics

Depending on the evaluation, one or more specialized rubrics may also be applied.

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

### 9. Resolve Reviewer Disagreements

When multiple evaluators participate:

- Document disagreements.
- Re-examine supporting evidence.
- Revise scores when warranted.
- Record the rationale for any score changes.

Evaluation outcomes should be evidence-driven rather than consensus-driven.

---

### 10. Write Evaluator Notes

Summarize:

- Major findings
- Important limitations
- Suggested improvements
- Overall assessment

---

### 11. Publish

Publish the completed evaluation together with:

- Prompt
- Response
- Evaluation environment
- Supporting evidence
- Rubric scores
- Reviewer notes

---

## Evaluation Template

Every completed evaluation should document:

- Evaluation date
- Evaluator
- Model name
- Model version
- Platform
- Prompt
- Prompt parameters
- Temperature or generation settings
- Tool access
- Web browsing status
- System instructions (when known)
- Number of trials
- Model response
- Supporting evidence
- Rubric scores
- Findings
- Evaluator notes

---

## Workflow Outputs

Every completed evaluation should produce:

- A documented evaluation record
- Supporting evidence
- Universal rubric scores
- Specialized rubric scores (when applicable)
- Findings suitable for publication

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

- [AI-Evaluation-Rubrics](https://github.com/zaknick/AI-Evaluation-Rubrics)
- AI-Hallucination-Database *(coming soon)*
- LLM-Evaluation-Benchmarks *(coming soon)*
- Prompt-Arena *(coming soon)*
- AI-Safety-Evaluation *(coming soon)*
- Search-Quality-Ratings *(coming soon)*
- Bilingual-LLM-Evaluation *(coming soon)*
- Prompt-Engineering-Cookbook *(coming soon)*

---

## Status

**Current Version:** 0.1

This repository defines the operational methodology of the [**LLM Evaluation Lab**](https://github.com/zaknick/LLM-Evaluation-Lab). The workflow will continue to evolve as additional evaluation methods, rubrics, and benchmarking techniques are developed and validated.

---

## License

This project is licensed under the **MIT License**.

The MIT License permits reuse, modification, and distribution with attribution while preserving the original copyright notice. See the [LICENSE](LICENSE) file for details.
