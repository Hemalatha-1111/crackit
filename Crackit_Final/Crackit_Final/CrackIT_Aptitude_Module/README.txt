CrackIT Aptitude Module

Included:
- crackit.html: updated CrackIT dashboard with the existing UI preserved and a fully functional Aptitude test module.
- aptitude_dataset.json: 124 aptitude questions (40 Quantitative Aptitude, 44 Logical Reasoning, 40 Verbal Ability).

Test behavior:
- Randomly selects 20 questions from the dataset.
- 20-minute timer.
- Previous/Next navigation and question-number jump navigation.
- Questions may remain unanswered.
- Submit Test appears ONLY on the last question.
- Submit works before the timer ends.
- If timer reaches zero, the test is automatically submitted.
- Results show correct, wrong, unanswered, score, category performance and recommendations.
- Retake generates a new randomized test.

This is a browser-based implementation and does not require Flask or an external database for the dataset.
