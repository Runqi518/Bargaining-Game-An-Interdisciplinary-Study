# Bargaining Game: An Interdisciplinary Study
 Author: Runqi Li

## Abstract
This project investigates the simultaneous-demand bargaining game under incomplete information, combining theoretical, computational, and experimental approaches. We implement Bayesian Nash equilibria computations in Google Colab, illustrate extensive-form sequential adaptations in Game Theory Explorer (GTE), conduct human experiments and LLM simulations via oTree, and analyze strategic behavior across multiple conditions. The goal is to compare theoretical predictions, human behavior, and AI agent responses, providing insights into fairness, risk, and strategic reasoning.

## Disclaimer
This repository supports the final research proposal submitted to COMSCI/ECON 206: Computational Microeconomics, instructed by Prof. Luyao Zhang at Duke Kunshan University in Autumn 2025.

## Acknowledgments
I would like to sincerely thank Professor Luyao Zhang for her detailed and constructive feedback, which helped clarify inconsistencies between game representations, refine payoff rules, and improve the clarity of figures and theoretical alignment. <br>
I am also grateful to Shiqi Chen and Boyan Zhang for their insightful peer reviews, which strengthened the project’s interdisciplinary coherence and analytical rigor. Special thanks to Peilin Wu, Chenlei Tao, and other group members for their valuable discussions and game collaboration. Their collective feedback significantly enhanced both the clarity and depth of this study. <br>
I also acknowledge the valuable support of AIGC tools and open-source communities that enabled this project, including Python, Jupyter/Google Colab, NashPy, QuantEcon, Game Theory Explorer (GTE), oTree, Matplotlib, Git & GitHub, and LLM agents (e.g., GPT-4, Doubao, DeepSeek, Qwen).

## Statement of Growth
Through this interdisciplinary project, I advanced my ability to design and analyze strategic interaction by integrating game theory, mechanism design, and computational experimentation. <br>
1) Developing a Bayesian bargaining model and extending it with machine learning algorithms deepened my understanding of how data-driven methods can simulate and explain social behaviors such as fairness, cooperation, and bounded rationality. 
2) By applying reinforcement learning and supervised modeling to compare human and AI negotiation patterns, I strengthened my technical mastery in model training, evaluation, and interpretation within a social-scientific framework.  <br>
3) Collaborating with peers and engaging in discussions on ethical implications, including algorithmic bias and welfare trade-offs, enhanced my communication and reflective judgment. Overall, this project enriched my intellectual development by merging quantitative rigor with social insight, and it fostered professional growth through collaborative research, responsible innovation, and clear interdisciplinary communication. <br>

How the project enhanced my skills in applying machine learning to social science：
   - Modeling Human Behavior: Learned to apply reinforcement learning and supervised models to simulate human bargaining behavior, capturing adaptation, cooperation, and fairness dynamics. <br>
   - Experiment–Simulation Integration: Used ML models to complement oTree-based human experiments, comparing algorithmic learning trajectories with real-world decision data. <br>
   - Algorithmic Fairness: Reflected on how model bias and outcome disparities can influence welfare assessments, enhancing awareness of ethical considerations in computational social science.


## Table of Contents
The project is organized into six main components:

1. **Economist**
   - [economist/](economist/) — Analytical treatment of auction formats and economic modeling.

2. **Computational Scientist**
   - [computational_scientist/](computational_scientist/) — Coding and simulation:
     - [Colab Notebook](computational_scientist/Colab/) — Implements the normal-form simultaneous-demand bargaining game and computes Bayesian Nash equilibria.
     - [GTE Folder](computational_scientist/GTE/) — Extensive-form sequential adaptation for illustrative SPNE analysis.

3. **Behavioral Scientist**
   - [behavioral_scientist/](behavioral_scientist/) — Human experiments and LLM agent comparison:
     - [oTree Project](behavioral_scientist/otree_app/) — Interactive bargaining game for human participants.
     - [LLM Session Data](behavioral_scientist/llm/) — Prompts, transcripts, and model settings for GPT-4 simulation.
     - [Screenshots](behavioral_scientist/screenshots/) — Illustrations of session outcomes and game setup.

4. **Mechanism Design**
   - [mechanism_design/](mechanism_design/) — Auction mechanism implementation, testing, voting and analysis


5. **Visualizations**
o All visualizations are available in the [Visualizations folder](visualizations/)

6. **Documentations**
o Documentation (final report, poster, field trip reflection). [docs folder](docs/)

## Embedded Media
### Poster
You can view our project poster here:  
[Project Poster (PDF)](docs/poster.pdf)  
### Demo Video
Watch the demo video on YouTube:  
[Demo Video](https://www.youtube.com/watch?v=7f7p0wknPi)  

## Reproduction Steps

1. Explore each component in the following order: economist → computational_scientist → behavioral_scientist → mechanism_design.
2. For computational experiments:
   - Open the [Colab Notebook](computational_scientist/Colab/ProblemSet1_2a.ipynb) and run all cells.
   - Optionally explore different parameters to observe variations in Bayesian Nash equilibria.
3. For behavioral experiments:
   - Navigate to the [oTree Project](behavioral_scientist/otree_app/) and follow instructions to run sessions locally.
   - Review [LLM Session Data](behavioral_scientist/llm/) for AI agent responses.
4. For mechanism design:
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
├── Final Research Proposal.pdf
├── visualizations
├── docs
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
              



