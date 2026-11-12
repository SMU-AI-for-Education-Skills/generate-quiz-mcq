---
name: generate-quiz-mcq
description: Generate summative multiple-choice quiz questions with one correct answer each from user-provided course materials. Excludes formative SCORM and H5P questions.
---

# Generate Summative Quiz Questions

## Draft a batch

Generate eight conceptual questions per batch. Use both difficulty levels, **Somewhat Hard** and **Difficult**, across the batch.

- Before drafting each question, identify a specific statement in the supplied material that directly supports the correct answer. Build the question around that anchor. Replace any question whose answer cannot be traced to the source.
- Test understanding beyond recall. Write a neutral stem that leaves students to identify the relevant concept or reasoning without cues.
- Give each question five bulleted options of 7 to 15 words each. Make exactly one option correct, randomise its position, and label it **(Correct)**. Show the correct option in green where supported.
- Use "None of the other answers are correct" as the correct option in at least two questions per batch. In those questions, verify that all four substantive options are false. For each, cite the source that establishes the correct conclusion and check privately why each listed alternative fails.
- Avoid absolutes such as "all", "every", "must", "only", and "guarantees" in distractors.

Use British English and ASCII throughout. Avoid contractions and ampersands. Normalise punctuation and accented characters in source quotations while preserving the wording.

## Present and review

Number each question and label its difficulty. After the stem and options, quote the supporting statement and give its slide number or another precise location if the material is not a slide deck. List each anchor if the answer relies on several statements. Keep the supporting quotation and location as the source note. Omit separate explanation lines, including **Rationale:** and *Why:*. Separate question blocks with a horizontal rule.

Before presenting a question, verify that the stem gives no cues, exactly one option is correct, and the source quotation directly supports the answer. Apply the same checks after revisions.

Ask which question numbers to add to the current quiz and what edits the selected questions need. Show any revised questions and confirm the revised text before proceeding.

## Continue or export

Ask whether the user wants to supply more material or finalise the quiz. For more material, draft another batch and append newly accepted questions to the current quiz list. When the user finalises, provide one downloadable Markdown file titled **Current Quiz Questions**. Put each question stem on the same line as its sequential Markdown list number (for example, `1. Question stem?`). Indent the five bulleted options beneath the numbered item and retain the correct-answer marker. Incorporate approved edits. Do not use per-question headings. Omit source notes, difficulty and type labels, and review instructions.
