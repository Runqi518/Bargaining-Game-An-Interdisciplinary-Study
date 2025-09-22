# Bargaining-Game-An-Interdisciplinary-Study
 

## Abstract
This project investigates the simultaneous-demand bargaining game under incomplete information, combining theoretical, computational, and experimental approaches. We implement Bayesian Nash equilibria computations in Google Colab, illustrate extensive-form sequential adaptations in Game Theory Explorer (GTE), conduct human experiments and LLM simulations via oTree, and analyze strategic behavior across multiple conditions. The goal is to compare theoretical predictions, human behavior, and AI agent responses, providing insights into fairness, risk, and strategic reasoning. This repository supports Problem Set 1 & 2 for COMSCI/ECON 206: Computational Microeconomics. <br>


## Task Summary
The project is organized into five main components:
1. **Problem Set Materials**
   - You can view or download the full Problem Set PDF here:  
<a href="./ProblemSet.pdf" download>Download Problem Set PDF</a>

Includes Problem Set 1 updates, acknowledgments, responses, and Problem Set 2 work.
   
2. **Economist**
   - [economist/](economist/) — Analytical treatment of auction formats and economic modeling.

3. **Computational Scientist**
   - [computational_scientist/](computational_scientist/) — Coding and simulation:
     - [Colab Notebook](computational_scientist/Colab/) — Implements the normal-form simultaneous-demand bargaining game and computes Bayesian Nash equilibria.
     - [GTE Folder](computational_scientist/GTE/) — Extensive-form sequential adaptation for illustrative SPNE analysis.

4. **Behavioral Scientist**
   - [behavioral_scientist/](behavioral_scientist/) — Human experiments and LLM agent comparison:
     - [oTree Project](behavioral_scientist/otree_app/) — Interactive bargaining game for human participants.
     - [LLM Session Data](behavioral_scientist/llm/) — Prompts, transcripts, and model settings for GPT-4 simulation.
     - [Screenshots](behavioral_scientist/screenshots/) — Illustrations of session outcomes and game setup.

5. **Mechanism Design**
   - [mechanism_design/](mechanism_design/) — Auction mechanism implementation, testing, and analysis.

## Additional Materials

- [**Acknowledgements**](Acknowledgements.md)  
  This document lists the individuals, references, and resources that supported the development of this project.  

- [**Responses**](Responses.md)  
  This file contains detailed responses to feedback, clarifications, and follow-up notes related to the assignments and project work.



## Reproduction Steps

1. Review [ProblemSet.pdf](ProblemSet.pdf) for acknowledgments, responses, and updates.
2. Explore each component in the following order: economist → computational_scientist → behavioral_scientist → mechanism_design.
3. For computational experiments:
   - Open the [Colab Notebook](computational_scientist/Colab/ProblemSet1_2a.ipynb) and run all cells.
   - Optionally explore different parameters to observe variations in Bayesian Nash equilibria.
4. For behavioral experiments:
   - Navigate to the [oTree Project](behavioral_scientist/otree_app/) and follow instructions to run sessions locally.
   - Review [LLM Session Data](behavioral_scientist/llm/) for AI agent responses.
5. For mechanism design:
   - Explore auction formats and simulation outputs in [mechanism_design/](mechanism_design/).

## References

Osborne, M. J., & Rubinstein, A. (1994). A Course in Game Theory. MIT Press.  <br>
Shoham, Y., & Leyton-Brown, K. (2008). Multiagent Systems. Cambridge University Press.  <br>
Knight, V. (2021). NashPy: A Python library for the computation of equilibria of 2-player strategic games, Version 0.0.28.  <br>
Savani, R., & von Stengel, B. (2015). Game Theory Explorer – Software for the Applied Game Theorist. Computational Management Science, 12, 5–33.  <br>
Sargent, T. J., & Stachurski, J. (2021). Quantitative Economics (Python), Version 0.5.1.  <br>


## License
This repository is for educational purposes within COMSCI/ECON 206: Computational Microeconomics (Autumn 2025). <br>
Please cite all tools, textbooks, and research papers appropriately.


## Repository Structure

```text
Bargaining-Game-An-Interdisciplinary-Study/
├── README.md
├── ProblemSet.pdf
├── Acknowledgements.md
├── Responses.md
├── economist/
│   ├── README.md              # Definitions, citations, equilibrium proofs
│   └── refs/                  # PDFs and BibTeX
├── computational_scientist/
│   ├── README.md              # How-to-run + GTE screenshots (with captions)
│   ├── Colab                  # Google Colab notebook
│   └── GTE                    # Game Theory Explorer outputs screenshots
├── behavioral_scientist/
│   ├── bargaining_game.otreezip   # oTree deployment package
│   ├── README.md              # Deployment steps, session config, ethics note
│   ├── screenshots/           # Human session screenshots
│   └── llm/                   # prompts.txt, transcript.md, settings.json
├── mechanism_design/
│   ├── Game.png
│   ├── README.md              # Deployment steps, session config, ethics note
│   ├── prompts_rules_interface.txt
│   └── transcripts_decision_logs.txt
              



