# Project Instructions: AI Music Generation and Benchmarking

This document is your complete step-by-step guide. Follow it from start to finish, filling in the [Final Report Template (.docx)](./final_report_template.docx) as you go.

## What You'll Do

You will generate **2 songs** using [suno.com](https://suno.com) and refine each one across **3 rounds** of prompt engineering. For each round, you'll evaluate the output using the [HARMONIC Scoring Rubric](./scoring_rubric_harmonic-songs.md) embedded in the report template. At the end, you'll write a combined summary report reflecting on both songs.

**Total output:** 2 songs x 3 rounds = 6 generated tracks, 6 completed rubrics, and 1 summary report — all captured in a single .docx file.

> **Before you begin:** Download the [Final Report Template (.docx)](./final_report_template.docx). This is the document you will fill in throughout the project and submit when finished. It includes a task checklist, all rubric tables, prompt fields, and the summary report outline.

---

## Phase 1: Preparation (Before You Generate)

### 1.1 Choose Your Genre(s)

Pick a musical genre, style, or tradition you know well. Your two songs can be:
- **Same genre** — to explore how different prompting strategies affect the same style
- **Different genres** — to compare how well the AI handles different musical traditions

The choice is yours. Pick whatever lets you bring the most expertise to the evaluation.

### 1.2 Document Your Expertise

For each genre you're working with, fill in **Section 1 (Genre Expertise)** of the report template:
- Your experience level (years of listening, study, practice, or performance)
- 3-5 essential characteristics that define the genre
- Key artists or works that exemplify it

### 1.3 Brainstorm Your Initial Prompts

Before touching Suno, draft your first prompt for each song. Suno's limit is **200 characters**, so every word counts. Consult the [Prompt Engineering Guide](./instructions_prompt_engineering_text-to-music-LLMs.md) for strategies on constructing effective prompts.

Think about what unique insights you bring: music theory knowledge, instrumental experience, familiarity with a niche genre, cultural or regional traditions. Use that expertise to craft prompts that are specific and informed.

---

## Phase 2: Generate, Evaluate, Refine (3 Rounds per Song)

Work through 3 rounds for each song. You can work on both songs in parallel or finish one before starting the other.

### Round 1: Baseline

**For each song:**

1. Go to [suno.com](https://suno.com) and log into your free account
2. Select the **"Classical lyrics model"** (not the "ReMi" model)
3. Enter your initial prompt and click the **Create** button
4. Suno generates multiple versions — listen to all of them and **pick the best one**
5. Fill in the **Round 1** section of the report template for this song:
   - Paste your exact prompt (verbatim) in the prompt field
   - Complete the HARMONIC rubric table with scores and justifications
   - Note strengths and weaknesses
6. Save the audio file as `SongA_Round1.mp3` or `SongB_Round1.mp3`

**Don't overthink Round 1** — it serves as your baseline. The point is to see where the AI starts so you can steer it.

### Round 2: Targeted Refinement

**For each song:**

1. Review your Round 1 rubric scores and notes
2. Identify the **2-3 lowest-scoring categories** in the rubric
3. Revise your prompt to specifically address those weaknesses. Use the [Prompt Engineering Guide](./instructions_prompt_engineering_text-to-music-LLMs.md) for refinement strategies. Document:
   - What you changed in the prompt
   - Why you changed it (which rubric scores motivated the change)
   - Which refinement strategy you used (see categories below)
4. Generate a new track on Suno with the revised prompt
5. Pick the best version and fill in the **Round 2** section of the report template (rubric, prompt, refinement notes)
6. Save the audio file as `SongA_Round2.mp3` or `SongB_Round2.mp3`

### Round 3: Fine-Tuning

**For each song:**

1. Review your Round 2 rubric scores and compare to Round 1
2. Assess what improved and what didn't — was your refinement strategy effective?
3. Make a final prompt revision, using more advanced techniques:
   - Contrast pairs ("energetic but not chaotic")
   - Precise technical adjustments (specific instruments, tempo, structure)
   - Building on what worked while addressing remaining gaps
4. Generate, pick the best version, and fill in the **Round 3** section of the report template
5. Save the audio file as `SongA_Round3.mp3` or `SongB_Round3.mp3`
6. Fill in the **Score Trajectory** table for this song in the report template

---

## Phase 3: Summary Report

Complete **Section 4 (Summary Report)** of the report template. Write a one-page combined analysis covering both songs. Address these points:

### A. Overall Impressions
- How do your final versions of Song A and Song B compare?
- Which song turned out better, and why?

### B. Prompt Engineering Strategies
- What refinement strategies did you use? (Classify using the categories below.)
- Which strategies were most/least effective?
- What did you learn about working within the 200-character limit?

### C. Quality Trajectory
- How did HARMONIC scores change across your 3 rounds for each song?
- Did scores consistently improve, plateau, or fluctuate?
- Was there a point of diminishing returns?

### D. Big Questions
- Your personal observations on AI-generated music: creativity, originality, limitations
- Concerns about intellectual property, displacement of human musicians, or other implications
- Predictions for where this technology is heading

---

## Prompt Refinement Strategy Categories

When documenting your refinement strategy for each round, classify it using one or more of these categories:

1. **Technical specificity** — Adding musical theory elements or structure details
2. **Reference enhancement** — Adding artist, song, or era references
3. **Emotional elaboration** — Expanding on mood, feeling, or emotional arc
4. **Constraint adjustment** — Changing specific musical parameters (tempo, key, etc.)
5. **Cultural contextualization** — Adding cultural or historical context
6. **Feedback incorporation** — Directly addressing issues identified in the previous round's rubric
7. **Prompt restructuring** — Reorganizing the same information for clarity
8. **Length modification** — Substantially changing prompt length

---

## What to Submit

Upload everything to the [Google Drive submission folder](https://drive.google.com/drive/folders/1lGPb4_kcT_QaKL55pP-ZQE0Eg5bmnqR0?usp=sharing):

| Item | Details |
|------|---------|
| **Completed report** (.docx) | Your filled-in [Final Report Template](./final_report_template.docx) with all rubrics, prompts, and summary |
| **Song A audio files** | `SongA_Round1.mp3`, `SongA_Round2.mp3`, `SongA_Round3.mp3` |
| **Song B audio files** | `SongB_Round1.mp3`, `SongB_Round2.mp3`, `SongB_Round3.mp3` |

**Total uploads:** 1 completed .docx report + 6 audio files = 7 files

---

## Evaluation Tips

When scoring with the HARMONIC rubric:

- **Be objective** — Evaluate against genre standards, not personal taste
- **Be specific** — Cite concrete musical moments to justify your scores
- **Be consistent** — Apply the same criteria across all rounds and both songs
- **Consider context** — Judge relative to the state of AI music generation, not against professional human composers
