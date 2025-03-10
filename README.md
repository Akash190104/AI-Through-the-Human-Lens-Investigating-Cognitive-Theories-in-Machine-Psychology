# AI-Through-the-Human-Lens-Investigating-Cognitive-Theories-in-Machine-Psychology

# AI Through the Human Lens: Investigating Cognitive Theories in Machines

## Overview
This project investigates whether Large Language Models (LLMs) exhibit human-like cognitive patterns based on psychological frameworks. The study evaluates models using:

- **Thematic Apperception Test (TAT)** – Analyzing personality and motivation through story generation.
- **Framing Bias** – Testing how linguistic framing affects decision-making.
- **Moral Foundations Theory (MFT)** – Evaluating moral reasoning across ethical dimensions.
- **Cognitive Dissonance** – Measuring inconsistencies in model responses.

## Models Evaluated
The study evaluates the following LLMs:
- **GPT-4o**
- **QvQ 72B**
- **LLaMA 70B**
- **Mixtral 8x22B**
- **DeepSeek V3**

## Methodology
Each cognitive framework is tested using structured prompts and automated scoring.

### 1. Thematic Apperception Test (TAT)
- **Objective:** Assess whether models generate coherent and psychologically rich narratives.
- **Process:** Models are provided with images and prompted to tell a story.
- **Analysis:** Themes like anxiety, motivation, and relational depth are identified using automated scoring.

### 2. Framing Bias
- **Objective:** Evaluate susceptibility to linguistic framing effects.
- **Process:** Models respond to positively and negatively framed questions.
- **Analysis:** Contradictions and entailments are measured to detect bias.

### 3. Moral Foundations Theory (MFT)
- **Objective:** Determine how models respond to moral dilemmas.
- **Process:** Models answer moral questions aligned with six ethical dimensions (e.g., Care/Harm, Fairness/Cheating).
- **Analysis:** Responses are scored and compared to human baselines.

### 4. Cognitive Dissonance
- **Objective:** Measure inconsistencies in model-generated responses.
- **Process:** Models are presented with conflicting scenarios.
- **Analysis:** Contradictions, rationalization complexity, and response stability are evaluated.

## Key Findings
- **LLMs exhibit human-like biases and reasoning patterns.**
- **Models show strong susceptibility to positive framing.**
- **Liberty/Oppression concerns dominate moral reasoning.**
- **Contradictions are often rationalized extensively.**

## Implications
- Understanding AI cognitive biases is crucial for responsible deployment.
- Aligning LLMs with human psychological principles can improve interpretability.
- Future research should expand cognitive testing for more robust AI evaluation.

## Codebase
The repository includes:
1. **Dataset & Prompts** – Structured question sets for each cognitive test.
2. **Evaluation Scripts** – Automated scoring and analysis tools.
3. **Results & Analysis** – Processed outputs and statistical breakdowns.

## References
This work builds on psychological and AI cognitive research. Key references include:
- Tversky & Kahneman (1981) – Framing effects in decision-making.
- Haidt (2008) – Moral Foundations Theory.
- Festinger & Carlsmith (1959) – Cognitive dissonance.
- Recent AI safety and machine psychology research.

## Citation
If you use this work, please cite:
```
@misc {
   title={AI Through the Human Lens Investigating Cognitive Theories in Machine Psychology},
   author={Kundu, Akash and Goswami, Rishika},
   year={2025},
   organization={Apart Research},
   note={Research submission to the Women in AI Safety Hackathon research sprint hosted by Apart.},
   month={March},
   howpublished={https://apartresearch.com}
}
