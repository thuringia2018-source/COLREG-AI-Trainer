# Changelog v1.8

## COLREG Trainer v1.8 — Web-ready Data Structure

This version prepares COLREG AI Trainer for future web application development.

The Python trainer remains fully functional, while the training content is now also exported into clean JSON files that can later be reused by a browser/mobile version.

## Main Improvements

* Added web-ready JSON data structure
* Added separate JSON files for quiz questions, scenarios, oral questions, visual cards, sound cards, study notes and coverage
* Added `web_manifest.json`
* Added `media/svg/` folder for future original vessel illustrations
* Added new menu option: Web-ready Data Report
* Preserved verified v1.7 learning engine logic

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
```

## Current Data Counts

```text
Quiz questions: 274
Scenarios: 60
Oral questions: 59
Visual cards: 40
Sound cards: 24
```

## Purpose

The purpose of v1.8 is to create a bridge between the Python testing application and the future web app.

The same validated COLREG content can later be used in:

* Web quiz mode
* Web exam mode
* Scenario trainer
* Oral exam trainer
* Lights and shapes visual trainer
* Sound signal trainer
* Progress dashboard

## Status

Stable web-ready data version.

The application is still a Python trainer, but the content structure is now prepared for future web development.
