# Mechanism Design — All-Pay Auction Experiment

This folder contains documentation and experimental results for **Section 7: From Game Theory to Mechanism Design — Testing Winner’s Curse on AI Agents**.

## Contents

- [prompts_rules_interface.txt](./prompts_rules_interface.txt)  
  Documentation of prompts, rules, and interface setup used in the experiments.

- [transcripts_decision_logs.txt](./transcripts_decision_logs.txt)  
  Raw transcripts of AI agent interactions (ChatGPT, Doubao, DeepSeek, Qwen) and decision logs for each experimental round.

## Game Introduction

An **all-pay auction** is a competitive bidding mechanism in which all participants submit their bids simultaneously, and each bidder is required to pay the amount they bid, irrespective of whether they win the auction. The highest bidder is awarded the asset or prize, while in the event of a tie, the winner is selected randomly among the top bidders.  

The strategic complexity of all-pay auctions arises from the fact that every bid represents a sunk cost: all participants incur a cost, but only the highest bidder secures the reward. This structure generates rich strategic behavior, including considerations of risk, overbidding, and the potential for a winner’s curse, particularly when participants face payoff uncertainty or incomplete information.  

![All-Pay Auction Game](./All-Pay%20Auction%20Game.png)

## Experiment Summary

- **Control Group**: Fixed asset value = $1,000.  
- **Treatment Group**: Asset value uniformly distributed in $[800,1200]$.  

- **Hypothesis**: Payoff uncertainty increases the likelihood of the Winner’s Curse.  

- **Findings**:  
  - AI agents increased their bids under uncertainty.  
  - Winner’s Curse rate rose significantly in the treatment group.  
  - Different AI agents showed heterogeneous bidding tendencies (ChatGPT conservative, Doubao aggressive, etc.).

## References

### Theoretical Background
- Baye, M.R., Kovenock, D., & de Vries, C.G. (1996). *The All-Pay Auction with Complete Information*. Economic Theory, 8, 291–305.  
- Kagel, J.H., & Levin, D. (2002). *Common Value Auctions and the Winner’s Curse*. Princeton University Press.  

### Software and LLM Interfaces
- OpenAI. *ChatGPT (GPT-4) API*. https://platform.openai.com/  
- Baidu. *Doubao (Ernie Bot) Interface*. https://yiyan.baidu.com/  
- DeepSeek AI. *DeepSeek LLM Interface*. https://www.deepseek.com/  
- Alibaba Cloud. *Qwen (通义千问) Interface*. https://tongyi.aliyun.com/qwen  


