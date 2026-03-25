# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an academic project for **IPHS300 AI for Humanity (Spring 2025) at Kenyon College** — specifically Mini-Project #3: AI Music Generation and Benchmarking Creativity. It is a documentation and research repository, not a software application.

Students use text-to-music LLMs (suno.com) to generate **2 songs**, each refined across **3 rounds** of prompt engineering (200-char limit), and evaluate outputs using the HARMONIC scoring rubric. Total: 6 generated tracks, 6 rubrics, 1 combined summary report.

## Repository Structure

- `docs/` — All project documentation:
  - `instructions_research_study.md` — The single authoritative step-by-step project guide (2 songs, 3 rounds)
  - `instructions_prompt_engineering_text-to-music-LLMs.md` — Reference guide for prompt construction and refinement strategies
  - `scoring_rubric_harmonic-songs.md` — The HARMONIC scoring rubric (6 sections, 100-point scale with weighted components)
  - `rubric_prompt_engineering.md` — Meta-analysis framework for analyzing prompt strategy effectiveness across participants
  - `reference_ai-generated-music.md` — Reference links
  - `paper_frontiersinai_computational_creativity_and_music_gen_fcarnovalini.pdf` — Background paper on computational creativity
- `songs/samples/` — Sample AI-generated music files (mp3/mp4)

## Key Concepts

- **HARMONIC rubric**: 6-section weighted evaluation framework — Novelty & Originality (25pts), Musical Value & Quality (25pts), Genre-Specific Achievement (15pts), AI Generation Quality (15pts), Human-AI Interaction (10pts), Audience & Cultural Relevance (10pts). Each component scored 1-5 and multiplied by its weight.
- **Prompt refinement strategies** are classified into 8 categories: technical specificity, reference enhancement, emotional elaboration, constraint adjustment, cultural contextualization, feedback incorporation, prompt restructuring, and length modification.
- **Workflow**: 3-round cycle per song — Round 1 (baseline), Round 2 (targeted refinement), Round 3 (fine-tuning). Students choose whether their 2 songs use the same or different genres.

## Environment

- Python `.venv` exists (Python 3.12) but there is no application code — the `.gitignore` is a standard Python template.
