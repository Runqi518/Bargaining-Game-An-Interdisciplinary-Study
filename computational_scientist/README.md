# Computational Scientist
This section documents the computational analysis of the simultaneous-demand bargaining game under incomplete information. The Google Colab notebook computes Bayesian Nash equilibria using type-contingent strategies, generating payoff matrices and solver outputs, while the Game Theory Explorer (GTE) folder illustrates a sequential extensive-form adaptation.

## Contents

- [Google Colab](computational_scientist/Colab/) - Notebook implementing the normal-form simultaneous-demand bargaining game with incomplete information. Includes payoff matrices, expected utilities, and solver outputs.
- [GTE](computational_scientist/GTE/) - Extensive-form sequential adaptation illustrating SPNE for pedagogical purposes.

## Google Colab (Normal Form & Computation)
- Players: i ∈ {A, B}, with private types tA ∈ {30,50}, tB ∈ {40,60}, each realized with 0.5 probability.
- Actions: {0, 25, 50, 75, 100}, chosen simultaneously.
- Payoffs: If dA + dB ≤ 100, each player receives their chosen demand; otherwise 0.
## How to Run
Follow these steps to run the notebook:

1. Open the notebook in [ProblemSet1_2a](computational_scientist/Colab/ProblemSet1_2a.ipynb).
2. Make sure you are signed in with a Google account.
3. To execute all cells:
   - Click Runtime → Run all
   - Or run each cell manually by clicking the play button on the left of each cell.
4. Ensure the required Python packages are installed (most should already be included in Colab):
5. Optionally, you can modify input parameters in the notebook to explore different scenarios.

## 2. Game Theory Explorer (Extensive Form & SPNE)
- Sequential adaptation: Player A moves first, Player B moves second; actions {0, 50, 75, 100}.
- SPNE computed using backward induction under full-information assumptions (illustrative only).
- Payoffs follow the same feasibility rule as Colab.


## References
Vincent Knight (2021). Nashpy: A Python library for the computation of equilibria of 2-player strategic games, Version 0.0.28
Thomas J. Sargent and John Stachurski (2021). Quantitative Economics (Python), Version 0.5.1
Rahul Savani and Bernhard von Stengel (2015). Game Theory Explorer – Software for the Applied Game Theorist. Computational Management Science 12, 5–33.