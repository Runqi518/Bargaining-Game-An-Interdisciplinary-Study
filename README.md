# COMSCI-ECON-206 ProblemSet1

## Abstract
This project explores the interdisciplinary study of economic theory, computational analysis, and behavioral science applied to the assigned problem set. The goal is to combine theoretical modeling, simulation, and experimental insights to better understand decision-making processes. This repository supports Problem Set 1 for COMSCI/ECON 206: Computational Microeconomics. <br>

It deploys a 2-player resource allocation game with the following rules: <br>
• Two players simultaneously choose a nonnegative integer. <br>
• If the sum of their choices ≤ 10, 100 or 1000, each receives exactly what they chose. <br>
• If the sum > 10, 100 or 1000, both receive 0. <br>

This setup generates a tension between individual maximization and joint feasibility, illustrating themes of fairness, coordination, and equilibrium prediction. <br>

## Task Summary
The repository integrates three disciplinary perspectives:

Part1 Economist: Theoretical analysis of Nash and Bayes–Nash equilibria, welfare benchmarks, and refinements. <br>

Part2 Computational Scientist: Reproduction of equilibria using Google Colab (NashPy, QuantEcon) and Game Theory Explorer (GTE). <br>

Part3 Behavioral Scientist: oTree experiment with human participants and an LLM “ChatBot” agent, with comparison to theory. <br>


## Reproduction Steps

To reproduce the results in this repository:

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Runqi518/Bargaining-Game-An-Interdisciplinary-Study.git
   cd Bargaining-Game-An-Interdisciplinary-Study

2. Economist (theory & welfare)

• Read economist/README.md for definitions, textbook citations, and references. <br>
• Contains theoretical writeups and references to Nash (1950), Harsanyi (1967), and Fehr–Schmidt (1999).  

3. Computational Scientist (coding & tools)

• Open computational_scientist/notebook.ipynb in Google Colab or Jupyter. <br>
• Explore GTE screenshots under computational_scientist/screenshots/.  

4. Behavioral Scientist (experiment & AI)

• Run the oTree app in behavioral_scientist/bargaining_game.otreezip. <br>
• Screenshots of human session results are in behavioral_scientist/screenshots/. <br>
• LLM transcripts, prompts, and JSON settings are stored in behavioral_scientist/llm/. <br>
• See behavioral_scientist/README.md for deployment instructions, ethics notes, and session configs. <br>


## Repository Structure

```text
Bargaining-Game-An-Interdisciplinary-Study/
├── README.md
├── economist/
│   ├── README.md              # Definitions, citations, equilibrium proofs
│   └── refs/                  # PDFs and BibTeX (optional)
├── computational_scientist/
│   ├── notebook.ipynb         # Colab-exported notebook
│   ├── README.md              # How-to-run + GTE screenshots (with captions)
│   └── screenshots/           # images (e.g., gte_1.png, sim_1.png, ...)
├── behavioral_scientist/
│   ├── bargaining_game.otreezip   # oTree deployment package
│   ├── README.md              # Deployment steps, session config, ethics note
│   ├── screenshots/           # Human session screenshots
│   └── llm/                   # prompts.txt, transcript.md, settings.json
└── refs/                      # Central bibliography (if consolidated)

```text


## License
This repository is for educational purposes within COMSCI/ECON 206: Computational Microeconomics (Autumn 2025). <br>
Please cite all tools, textbooks, and research papers appropriately.

## References
Chen, Daniel L., Martin Schonger, and Chris Wickens. 2016. “oTree—An
Open-Source Platform for Laboratory, Online, and Field Experiments.”
Journal of Behavioral and Experimental Finance 9: 88–97. https://doi.org/10.1016/j.jbef.2015.12.001

Fudenberg, Drew, and Jean Tirole. 1991. Game Theory. Cambridge, MA: MIT
Press.

Vincent Knight (2021). Nashpy: A Python library for the computation of
equilibria of 2-player strategic games, Version 0.0.28

Thomas J. Sargent and John Stachurski (2021). Quantitative Economics
(Python), Version 0.5.1

Rahul Savani and Bernhard von Stengel (2015). Game Theory Explorer – Software for the Applied Game Theorist. Computational Management Science
12, 5–33.

Shoham, Yoav, and Kevin Leyton-Brown. 2009. Multiagent Systems:
Algorithmic, Game-Theoretic, and Logical Foundations. Cambridge:
Cambridge University Press.