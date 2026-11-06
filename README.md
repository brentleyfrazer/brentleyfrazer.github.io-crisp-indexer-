# brentleyfrazer.github.io-crisp-indexer-
---
MS Crisp: Dynamic E-Prime Indexer
DYNAMICTEXT.DEV SEMANTIC TECHNOLOGIES
---
License: Free Trial then individual or Proprietary/Commercial License Required
---
Effective communication quantifies in the ratio of signal to noise. My research reveals the vast majority of static in communication (ambiguity, passive voice, hedging, moral obfuscation, hidden observers, tense wobbles, etc.) arise from the misuse of the English language copula.

The case for E-Prime rests on the simple proposition that "isness" conditions the brain to operate within a medieval Aristotelian framework, which hinders our ability to understand modern problems and opportunities.
If we consider the human brain as a computer, the fundamental law of computing applies: garbage in, garbage out. Using the wrong software inevitably guarantees wrong answers.

DynamicText.dev presents MS Crisp, a deterministic semantic parser designed to implement English Prime (E-Prime) constraints, eliminate passive copular nominalization, and compute agency metrics for natural language.
Developed from doctoral research conducted at Griffith University by Dr. Brentley Frazer, MS Crisp served as the algorithmic verification engine for Scoundrel Days (UQP, 2017)—the first creative longform work in literary history composed entirely in 100% E-Prime. 

Ms Crisp functions as an advanced editorial tool for technical writers, legal drafters, and narrative stylists who need to systematically purge passive voice and eliminate ambiguous assertions. 

Devs will find MS Crisp provides remedy to the tendency of Large Language Models to assign unwarranted truth-values to hallucinated premises. Algorithmic machine hallucinations occuer because standard English treats equivalence (X is Y) as reality rather than subjective observation.

Ms Crisp provides users with a native 'E-Prime / High-Agency Writing' filter utilising Deterministic Copula Suppression and Dynamic Agency Metrics to Mitigate Ontological Hallucinations in Generated Text
---
Theoretical Framework
Standard English relies heavily on the copula (to be), which introduces two structural flaws: 
1. The "Is of Identity" ($X \text{ is } Y$): Falsely equates a subject with a label, bypassing context and perception.
2. The "Is of Predication" ($X \text{ is } \text{cold}$): Projects internal subjective perception onto objective external reality.

In human writing, reliance on the copula leads to passive, frozen prose. In generative language models (LLMs), copular predication contributes significantly to ontological hallucinations—assigning unjustified truth-values to probabilistic associations.
Ms Crisp enforces active agency by stripping away the copula and evaluating the text along two mathematical vectors:
Bourland Crispiness Index ($I_C$): The ratio of copula-free sentences to total sentences ($I_C = \frac{S_{\text{crispy}}}{S_{\text{total}}}$).
Copula Density ($D_C$): The absolute frequency percentage of copular tokens relative to the total lexicon.
---
Quickstart
```python
from crisp_indexer import CrispIndexer

indexer = CrispIndexer()
text = "The system runs smoothly. It processes every record without delay."

results = indexer.analyze(text)

print(f"Crispiness Index: {results['crispiness_index']}") # 1.0
print(f"100% E-Prime: {results['is_100_percent_eprime']}") # True
