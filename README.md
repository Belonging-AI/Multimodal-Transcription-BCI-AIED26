# Multimodal-Transcription-BCI-AIED26

This repository contains the implementation and prompt design for the multimodal transcription and a multi-agent system that identifies classroom interactions aligned with Belonging-Centered Instruction (BCI).

## Overview
- Multimodal transcription powered by Gemini
- 4-agent pipeline:
  - Triggering Utterance Spotter
  - Event Generator
  - Event Coder
  - Event Scorer

## Prompt Design of BCI Multi-Agent System
All agents follow a structured prompt design:
1. Role and goal
2. Input
3. Core instructions and process
4. Important reminders

See full details:
→ docs/prompt_design_description.pdf

## Protocol
The BCI protocol defines:
- Action indicators
- Behavior sets
- Scoring rubrics
- Exemplars
  
For BCI-AI paper published in AIED 2026, we focused on Decentering Teacher Authority
<p align="center">
  <img src="docs/DTA-AI.png" width="600"/>
</p>
