# Parsons Problems Survey Study

An interactive study to investigate student performance and perception of Parsons Problems in programming education.

## Overview

This PreTeXt-based survey consists of:

- Pre-study questionnaire (demographics, programming experience, self-efficacy)
- Practice Parsons Problems with explanations
- Test problems with difficulty ratings
- Post-study feedback

## Structure

```
source/
├── main.ptx           # Main document
├── sec-questionnaire.ptx    # Pre-study survey
├── sec-parsons-intro.ptx    # Practice problems
├── sec-parsons-test.ptx     # Test problems
└── sec-feedback.ptx         # Post-study feedback
```

## Building the Survey

1. Install PreTeXt and dependencies:

```bash
python -m venv .venv
.\.venv\Scripts\activate
pip install pretext
```

2. Build the web version:

```bash
pretext build web
```

3. Preview locally:

```bash
pretext view web
```

## Deployment

Deploy to GitHub Pages:

```bash
pretext deploy
```

## Survey Components

### Section A: Basic Information

- Student ID
- School/Class information
- Demographics

### Section B: Programming Self-Efficacy

- 6-item questionnaire
- 5-point Likert scale responses

### Section C: Programming Background

- Prior experience
- Concept familiarity
- Language exposure

### Section D: Practice & Test Problems

- 3 practice Parsons Problems
- 4 test problems with difficulty ratings
- Post-problem reflection
