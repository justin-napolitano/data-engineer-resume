---
slug: github-data-engineer-resume-note-technical-overview
id: github-data-engineer-resume-note-technical-overview
title: Data Engineer Resume
repo: justin-napolitano/data-engineer-resume
githubUrl: https://github.com/justin-napolitano/data-engineer-resume
generatedAt: '2025-11-24T18:34:45.244Z'
source: github-auto
summary: >-
  This repo offers a customizable LaTeX resume template tailored for clarity and
  professionalism. Inspired by AltaCV and AwesomeCV, it runs on XeLaTeX and
  includes various page styles.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: note
entryLayout: note
showInProjects: false
showInNotes: true
showInWriting: false
showInLogs: false
---

This repo offers a customizable LaTeX resume template tailored for clarity and professionalism. Inspired by AltaCV and AwesomeCV, it runs on XeLaTeX and includes various page styles.

## Key Features

- Clean, professional design using LaTeX
- Multiple layouts: single/double-sided, headers, highlight bars
- Customizable colors and sections
- Overleaf template available for online editing

## Tech Stack

- LaTeX (TeX)
- Makefile for build automation
- Python for dependency management

## Quick Start

### Prerequisites

- XeLaTeX
- Python 3.x
- Make utility

### Installation

```bash
git clone https://github.com/justin-napolitano/data-engineer-resume.git
cd data-engineer-resume
python3 python-build.py
make clean
make html
```

You'll find the output in `resume.pdf`. 

**Gotcha:** Check `requirements.txt` for any dependencies. Enjoy crafting your resume!
