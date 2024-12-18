# Hate Speech Detection in Tweets

This repository include a solution for [HaSpeeDe3](https://github.com/mirkolai/EVALITA2023-HaSpeeDe3) challenge, focuesed on **Hate Speech Detection** in Twitter data using binary classification models. The tasks include both **in-domain** detection (within the same dataset) and **cross-domain** detection (across different datasets). Participants can use textual data alone or combine it with contextual metadata for improved accuracy.

---

## Tasks Overview

### Task A: Political Hate Speech Detection
**Goal**: Classify whether tweets contain political hate speech.  
- **Sub-tasks**:
  - **Textual**: Use only the tweet content from the **PolicyCorpusXL** dataset.
  - **Contextual**: Use tweet content + additional metadata (e.g., author details, friends, replies, retweets).

### Task B: Cross-Domain Hate Speech Detection
**Goal**: Detect hate speech across different domains.  
- **Sub-tasks**:
  - **XPoliticalHate**: Test on political hate speech (PolicyCorpusXL).
  - **XReligiousHate**: Test on religious hate speech using the **ReligiousHate** dataset.

Participants can optionally incorporate external data sources for Task B.

---

## Dataset Details
- **PolicyCorpusXL**: Dataset for political hate speech tasks.
- **ReligiousHate**: Dataset for religious hate speech detection.

---
## Performance Results

| Team        | Task A (textual/contextual) | Task B (XPoliticalHate) | Task B (XReligiousHate) |
|-------------|----------------------------|-------------------------|-------------------------|
| **our team** | **0.9192**                 | **0.9192**              | 0.6476                  |
| BERTicelli  | 0.8976                     | 0.8976                  | 0.5401                  |
| CHILab      | 0.8516                     | 0.8516                  | -                       |
| extremITA   | 0.9079                     | 0.9079                  | **0.6525**              |
| INGEOTEC    | 0.8845                     | 0.8845                  | 0.5522                  |
| LMU         | -                          | 0.9014                  | 0.6461                  |
| odang4      | 0.9128                     | 0.9128                  | 0.5213                  |
