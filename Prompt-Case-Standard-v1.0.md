# Prompt-Case-Standard-v1.0

**LLM Evaluation Lab**

Standard Operating Procedure (SOP) for creating individual prompt evaluation case files.

---

# Purpose

This document defines the standardized workflow used to evaluate a single prompt across one or more Large Language Models (LLMs).

The objective is to produce evaluations that are:

- Reproducible
- Transparent
- Evidence-backed
- Consistent
- Easy to review
- Easy to compare over time

Every prompt archive within the LLM Evaluation Lab should follow this standard.

---

# 1. Standard Folder Structure

```
prompt-XXX-short-title/

├── README.md
├── prompt.md
├── assessment.md
├── responses/
│   ├── chatgpt.md
│   ├── claude.md
│   ├── gemini.md
│   └── ...
│
└── evidence/
    ├── sources.md
    └── screenshots/
        ├── README.md
        ├── chatgpt-response-01.jpg
        ├── chatgpt-response-02.jpg
        ├── chatgpt-response-stitched.jpg
        ├── claude-response-01.jpg
        ├── ...
```

---

# 2. Naming Conventions

## Prompt folders

```
prompt-001-nonexistent-treaty
prompt-002-...
```

Always use:

- three-digit numbering
- lowercase
- hyphen-separated words

---

## Response files

```
chatgpt.md
claude.md
gemini.md
```

Raw responses only.

No scoring.

No commentary.

---

## Screenshot files

Original captures:

```
chatgpt-response-01.jpg
chatgpt-response-02.jpg
```

Composite image:

```
chatgpt-response-stitched.jpg
```

Never overwrite originals.

---

# 3. Screenshot Policy

Screenshots are primary evidence.

Capture:

- displayed model
- response formatting
- citations
- visible disclaimers
- UI elements relevant to interpretation

If a response exceeds one screen:

- capture overlapping screenshots
- preserve every original image

---

# 4. Stitching Policy

When stitching is required:

1. Keep every original screenshot.
2. Create one stitched composite.
3. Verify every seam manually.
4. Never discard originals.

If stitching artifacts remain:

- disclose them.
- never edit response content.

---

# 5. Evidence Requirements

Every factual assessment must be supported by evidence.

Evidence may include:

- official government sources
- official databases
- standards organizations
- peer-reviewed literature
- primary historical sources

Secondary sources may be used only when primary sources are unavailable.

All evidence should be documented in:

```
evidence/sources.md
```

---

# 6. Assessment Workflow

Evaluation sequence:

1. Record prompt.
2. Capture raw model response.
3. Preserve screenshots.
4. Research ground truth.
5. Document evidence.
6. Score using approved rubric.
7. Write assessment.
8. Update repository index.

Never score before establishing ground truth.

---

# 7. GitHub Commit Checklist

Before committing:

✓ Folder structure validated

✓ All required files present

✓ Raw responses unchanged

✓ Evidence documented

✓ Assessment completed

✓ Screenshot filenames standardized

✓ Screenshot README updated

✓ Links verified

✓ Markdown rendered correctly

✓ Index updated

---

# 8. Common Pitfalls Identified During Prompt 001

Prompt 001 revealed several workflow issues.

### Architecture changes during evaluation

Avoid redesigning repository structure after evaluation begins.

Freeze architecture early.

---

### Screenshot management

Always retain original screenshots.

Composite images supplement, but never replace, originals.

---

### Incomplete captures

If full-page capture is impossible:

- disclose limitation
- preserve available evidence
- never conceal missing information

---

### Naming consistency

Standardize filenames before publishing.

Avoid renaming files after links have already been created.

---

### Assessment independence

Separate:

- raw responses
- evidence
- evaluator analysis

Never mix them.

---

# 9. Lessons Learned

Prompt 001 demonstrated:

- methodology matters more than appearance
- reproducibility is more valuable than subjective opinion
- documented limitations increase credibility
- evidence should be traceable from claim to source
- architecture should remain stable throughout evaluation
- preserving original artifacts improves auditability

---

# 10. Standard Operating Procedure (SOP)

For every new prompt:

1. Define the prompt.
2. Collect responses.
3. Preserve screenshots.
4. Research authoritative ground truth.
5. Document evidence.
6. Evaluate using approved rubric.
7. Record assessment.
8. Update repository index.
9. Verify repository integrity.
10. Publish.

Every evaluation should be independently reproducible by another reviewer using the archived materials.

---

Version: 1.0

Status: Adopted

Applies to:
All prompt case archives within the LLM Evaluation Lab.
