# Behavioral Scientist Component

## Deployment Steps
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

## LLM Session Config
- Folder: llm/
- Files:
  - prompts.txt: contains the prompts given to the LLM
  - transcript.md: records the LLM responses for each run
  - settings.json: model configuration (GPT-4, temperature=0.7, one-shot)
- Each run demonstrates the LLM’s choices and reasoning in the resource allocation game.

## Ethics Note
- All participants (including simulated LLM agents) follow rules of fairness and informed decision-making.
- Data collected is only for academic purposes and does not involve real sensitive personal information.
- Any use of AI agents is clearly documented and reproducible, ensuring transparency in the research process.
