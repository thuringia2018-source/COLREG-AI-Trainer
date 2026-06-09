# Web-ready Data Structure v1.8

COLREG Trainer v1.8 introduces a web-ready data structure for future browser and mobile app development.

## Goal

The goal is to separate the validated training content from the Python terminal interface so that the same data can later be used in a web application.

## Data Files

| File                       | Purpose                                 |
| -------------------------- | --------------------------------------- |
| `data/quiz_questions.json` | Multiple-choice quiz and exam questions |
| `data/scenarios.json`      | Scenario training items                 |
| `data/oral_questions.json` | Oral exam questions and model answers   |
| `data/visual_cards.json`   | Lights and shapes visual trainer cards  |
| `data/sound_cards.json`    | Sound signal trainer cards              |
| `data/study_notes.json`    | Study notes by rule/category            |
| `data/coverage.json`       | COLREG rules and annex coverage data    |
| `data/web_manifest.json`   | Web app dataset metadata                |

## Media Folders

```text
media/sounds/
media/svg/
media/images/
```

### `media/sounds/`

Contains synthetic sound training files for COLREG sound signal practice.

These are training sounds only and are not official ship whistle recordings.

### `media/svg/`

Reserved for future original SVG vessel illustrations.

The future web app should use original custom SVG graphics, not copyrighted images copied from books or websites.

### `media/images/`

Reserved for future image assets.

## Future Web App Use

The future web app can load these JSON files directly and build:

* Quiz Mode
* Exam Mode
* Scenario Mode
* Oral Exam Mode
* Lights & Shapes Trainer
* Sound Signal Trainer
* Weak Rules Dashboard
* Progress Tracking
* Study Reports

## Important Design Rule

The validated COLREG meanings, answers and explanations should not be changed during web conversion unless checked against official COLREG sources.

## Source Base

v1.8 is based on the verified v1.7 Python learning-engine version.

v1.7 was tested against the COLREG Consolidated 2018 rules and includes Rules 1–41 and Annex I–IV training coverage.
