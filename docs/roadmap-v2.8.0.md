# Roadmap v2.8.0 — Candidate Exam Mode + Wrong Answer Tracer

## Goal

The goal of v2.8.0 is to turn COLREG AI Trainer from a visual quiz tool into a structured candidate-exam system.

Instead of only showing questions and answers, the application should evaluate how well the candidate recognizes COLREG situations, applies the correct rule, and understands the correct avoiding action.

## Main Priorities

### 1. Candidate Exam Mode

Create a dedicated exam-style mode where the candidate receives randomized visual scenarios and must answer without seeing the rule, title, or scenario label in advance.

Planned question types:

- Which COLREG Rule applies?
- What situation is shown?
- Which vessel is the give-way vessel?
- Which vessel is the stand-on vessel?
- Is the shown action correct or wrong?
- What should the vessel do next?

### 2. Wrong Answer Tracer

Track the exact type of mistake when a candidate answers incorrectly.

Example mistake categories:

- Confused crossing with head-on
- Confused overtaking with crossing
- Failed to identify give-way vessel
- Failed to identify stand-on vessel
- Misunderstood Rule 18 hierarchy
- Misunderstood restricted visibility situation
- Misread day shape or vessel status

### 3. Score by Rule

Create a results summary by COLREG rule.

Example:

- Rule 7: 80%
- Rule 13: 60%
- Rule 14: 90%
- Rule 15: 70%
- Rule 18: 50%
- Rule 19: 75%

This helps the candidate understand exactly where to focus.

### 4. Review Mistakes Mode

Add a dedicated mode for repeating only the questions the candidate answered incorrectly.

The purpose is repeated learning, not only scoring.

### 5. Full-Screen Image Viewer

Add a full-screen image viewer for visual questions.

This is important for:

- Day shapes
- Wake direction
- Relative vessel position
- Restricted visibility
- Narrow channel layout
- Traffic Separation Scheme layout

### 6. Short Explanation After Answer

After each answer, show a short and clear explanation.

The explanation should include:

- Correct rule
- Correct answer
- Why it is correct
- Why the wrong answer is unsafe or incorrect

### 7. Preparation for AI Examiner

The v2.8.0 data structure should prepare the application for a future AI examiner.

Future AI examiner requirements:

- Rule metadata
- Correct answer logic
- Explanation text
- Mistake classification
- Candidate performance history
- Oral answer evaluation

## Recommended Development Order

1. Improve metadata for every visual card
2. Add randomized exam logic
3. Add score by rule
4. Add wrong answer tracer
5. Add review mistakes mode
6. Add full-screen image viewer
7. Prepare stable base for AI examiner

## Long-Term Direction

The long-term goal is to make COLREG AI Trainer a professional maritime exam-preparation product with:

- Visual recognition training
- Rule-based explanation
- Weak-area tracking
- Repeated mistake correction
- AI oral examination
- Training manager / instructor-ready reports
