# Changelog v1.8

## COLREG Trainer v1.8 — Web-ready Data Structure

This version prepares COLREG AI Trainer for future web application development.

The Python trainer remains fully functional, while the training content is now also exported into clean JSON files that can later be reused by a browser/mobile version.

## Main Improvements

- Added web-ready JSON data structure
- Added separate JSON files for quiz questions, scenarios, oral questions, visual cards, sound cards, study notes and coverage
- Added `web_manifest.json`
- Added `media/svg/` folder for future original vessel illustrations
- Added new menu option: Web-ready Data Report
- Preserved verified v1.7 learning engine logic

## Web-ready Data Files

```text
data/quiz_questions.json
data/scenarios.json
data/oral_questions.json
data/visual_cards.json
data/sound_cards.json
data/study_notes.json
data/coverage.json
data/web_manifest.json