# Maritime Phonetic RAG

General-purpose Speech-to-Text like OpenAI's **Whisper** are highly capable but suffer from a significant "Domain Gap" when applied to maritime VHF radio. High background noise, static, and specialised terminologies like vessel names, call signs, and waypoints lead to high Word Error Rates (WERs). 

## Problem Statement
Currently, watch officers must manually transcribe VHF exchanges into logs. While ASR can automate this,standard models fail because:

1. **Acoustic Similarity:** "Sierra Mike" sounds like "Sarah Mike" to a model trained on conversational English.
2. **Technical Jargon:** Maritime-specific abbreviations and location names are often treated as out-of-vocabulary (OOV) errors.
3. **Signal Quality:** VHF audio is and prone to atmospheric interference.

## Proposed Solution: Phonetic Retrieval-Augmented Generation

## Tech Stack
