# Gender Bias in Machine Translation

## Overview
This project investigates gender bias in machine translation systems, focusing on their ability to produce gendered forms (masculine and feminine) when translating sentences from English into target languages with grammatical gender. The research evaluates the performance of several state-of-the-art models, including GPT (OpenAI), Claude (Anthropic), and Gemini (Google DeepMind).

## Objective
The primary objective is to determine whether machine translation models accurately reflect gendered forms when translating a demonym (nationality) into languages with grammatical gender. The study seeks to highlight patterns of gender bias, assess linguistic accuracy, and explore potential improvements.

## Dataset
- **Source Sentence Format**: "I am <demonym>"
- **Source Language**: English
- **Target Languages**: Spanish (spa), Italian (it), German (deu), and French (fra).
- **Demonyms**: The dataset includes demonyms from 193 UN-recognized countries.

## Methodology
1. **Data Preparation**:
   - Compile a list of demonyms from all 193 UN-recognized countries.
   - Create test sentences in the format: "I am <demonym>".
   
2. **Translation**:
   - Translate the sentences from English to the target languages using each model (GPT, Claude, Gemini).
   - Ensure consistent input prompts and translation settings for comparability.

## Status
- **GPT**: Completed.
  - Experiment completed, but metrics and detailed analysis are still pending.
- **Claude**: Testing not yet started.
- **Gemini**: Testing not yet started.
- **Other Languages**: Updates will follow after additional testing.

## Results and Metrics
- (pending)
