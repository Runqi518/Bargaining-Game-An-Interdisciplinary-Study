# Behavioral Scientist
This section presents the behavioral scientist component, combining human experimental sessions and LLM simulations in a resource allocation game to compare decision-making patterns. It documents human choices, reasoning, and fairness considerations, alongside AI agent behavior under different prompts and settings. 

## Otree Deployment Steps
1. Unzip the otree_app.zip file (if not already extracted).
2. Navigate to the extracted folder in terminal.
3. Install oTree (if not already installed):
   ```bash
   pip install otree
   ```
4. Run the app locally:
   ```bash
   otree devserver
   ```
5. Open your browser and go to http://localhost:8000 to interact with the game.
6. Follow instructions in the app to start a session and play the game.

## Game Process
Each player is assigned a private minimum demand and selects a demand from a discrete set of possible values.
The total demands of all players are compared to a common resource cap. If the sum does not exceed the cap, each player receives their chosen demand as the payoff. Otherwise, all receive zero.
For further exploration, the upper limit of the resource cap was varied (10, 100, 1000) to observe strategic effects.
All session screenshots are available in the [screenshots folder](./screenshots/). 

## LLM Experiments
The LLM experiments simulate human decision-making using AI agents.
Prompts, transcripts, and settings for AI agent sessions are in the [llm folder](./llm/).

## Ethics Note
All participants (including simulated LLM agents) follow rules of fairness and informed decision-making.
Data collected is only for academic purposes and does not involve real sensitive personal information.
Any use of AI agents is clearly documented and reproducible, ensuring transparency in the research process.
