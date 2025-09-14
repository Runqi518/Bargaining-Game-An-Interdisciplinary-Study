# COMSCI-ECON-206 ProblemSet1

## Abstract
This project explores the interdisciplinary study of economic theory, computational analysis, and behavioral science applied to the assigned problem set. The goal is to combine theoretical modeling, simulation, and experimental insights to better understand decision-making processes. This repository supports Problem Set 1 for COMSCI/ECON 206: Computational Microeconomics
It deploys a 2-player resource allocation game with the following rules:
Two players simultaneously choose a nonnegative integer.
If the sum of their choices ≤ 10, 100 or 1000, each receives exactly what they chose.
If the sum > 10, 100 or 1000, both receive 0.
This setup generates a tension between individual maximization and joint feasibility, illustrating themes of fairness, coordination, and equilibrium prediction.

## Task Summary
The repository integrates three disciplinary perspectives:
Part1 Economist: Theoretical analysis of Nash and Bayes–Nash equilibria, welfare benchmarks, and refinements.
Part2 Computational Scientist: Reproduction of equilibria using Google Colab (NashPy, QuantEcon) and Game Theory Explorer (GTE).
Part3 Behavioral Scientist: oTree experiment with human participants and an LLM “ChatBot” agent, with comparison to theory.


## Reproduction Steps
To reproduce the results in this repository:
1. Clone the repository
git clone https://github.com/Runqi518/Bargaining-Game-An-Interdisciplinary-Study.git
cd Bargaining-Game-An-Interdisciplinary-Study
2. Economist (theory & welfare)
Read economist/README.md for definitions, textbook citations, and references.
Contains theoretical writeups and references to Nash (1950), Harsanyi (1967), and Fehr–Schmidt (1999).
3. Computational Scientist (coding & tools)
Open computational_scientist/notebook.ipynb in Google Colab or Jupyter.
Explore GTE screenshots under computational_scientist/screenshots/.
4. Behavioral Scientist (experiment & AI)
Run the oTree app in behavioral_scientist/bargaining_game.otreezip.
Screenshots of human session results are in behavioral_scientist/screenshots/.
LLM transcripts, prompts, and JSON settings are stored in behavioral_scientist/llm/.
behavioral_scientist/README.md provides deployment instructions, ethics notes, and session configs.

## Repository Structure
Bargaining-Game-An-Interdisciplinary-Study/
│── README.md                     # Main project overview
│── economist/                    # Theory & references
│   └── README.md                 # Citations, definitions, equilibrium proofs
│── computational_scientist/      # Simulations & coding tools
│   ├── notebook.ipynb            # Colab-exported notebook
│   ├── README.md                 # How-to-run and GTE notes
│   └── screenshots/              # GTE outputs (PNG with captions)
│── behavioral_scientist/         # Experiments & LLM analysis
│   ├── bargaining_game.otreezip  # oTree app
│   ├── screenshots/              # Human session screenshots
│   ├── llm/                      # prompts.txt, transcript.md, settings.json
│   └── README.md                 # Deployment, ethics, configs
│── refs/                         # PDFs/BibTeX as permitted


## License
This repository is for educational purposes within COMSCI/ECON 206: Computational Microeconomics (Autumn 2025).
Please cite all tools, textbooks, and research papers appropriately.