# LLM-Surprisal-Project
Explores GPT-2's sensitivity to negation by calculating the surprisal of the LLM to psycholinguistic minimal-pair stimuli through the transformers Python library.

Research question: Are LLMs sensitive to negation?

To explore an LLM's sensitivity to negation thoroughly, these questions were addressed when creating the stimuli:

- Do LLMs display consistently higher **surprisal** when presented with `semantically similar` words or with `logical opposites` in negation tasks?
- Do LLMs display different **surprisal** values to a target word depending on whether it follows an `affirmative` or `negated` sentence?


Results: 
The results indicate that GPT-2 exhibits some limited sensitivity to semantic relationships under negation; however, it does not consistently demonstrate sensitivity to the logical meaning of negation itself. Specifically, surprisal was slightly higher for semantically similar completions compared to logical opposite completions, aligning with our prediction if the model was sensitive to negation. However, contrary to predictions, the surprisal for completions with the same word as the subject is lower than both of these conditions. This suggests that the differences may be due to token familiarity and frequency rather than logical reasoning for negation.

This code was completed in Python within a Google Colab Notebook. This project was created as a final project for the UCSD course COGS 150: Large Language Models

Author: Amanda Chang (June 2025)
