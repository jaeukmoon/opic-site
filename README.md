# OPIc Question Bank

A simple, static bilingual (English / Korean) question bank for practicing the OPIc speaking test, organized by topic and by monthly lesson.

**Live site:** https://jaeukmoon.github.io/opic-site/

## What this is

- A single-page static site (no build step, no dependencies) driven by `data/questions.json`.
- **Questions only.** It contains OPIc exam question prompts and their Korean translations — no model answers, scripts, or strategies. It is a prompt bank for self-practice.
- Features: topic sidebar with counts, English/Korean search, question-type badges (description / past experience / comparison / routine / role play / current issue), per-question topic tags on the monthly sections, dark mode, and a toggle to hide the Korean translation for speaking practice.

## Structure

```
index.html            # the whole app (HTML + CSS + JS inline)
data/questions.json    # the question data (topics[] -> questions[]{en, ko, type, topicHint?})
```

## Local preview

```
python -m http.server 8799
# open http://localhost:8799
```

## Note

Question prompts are the standardized functional prompts of the OPIc format. Personal study use.
