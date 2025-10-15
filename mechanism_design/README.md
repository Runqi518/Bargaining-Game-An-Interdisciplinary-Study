# Mechanism Design — All-Pay Auction Experiment

This folder documents the design, implementation, and results of all-pay auction experiments used to test how payoff uncertainty influences bidding behavior and the occurrence of the winner’s curse among AI agents.

## Game Introduction

An **all-pay auction** is a competitive bidding mechanism in which all participants submit their bids simultaneously, and each bidder is required to pay the amount they bid, irrespective of whether they win the auction. The highest bidder is awarded the asset or prize, while in the event of a tie, the winner is selected randomly among the top bidders.  

The strategic complexity of all-pay auctions arises from the fact that every bid represents a sunk cost: all participants incur a cost, but only the highest bidder secures the reward. This structure generates rich strategic behavior, including considerations of risk, overbidding, and the potential for a winner’s curse, particularly when participants face payoff uncertainty or incomplete information.  

![All-Pay Auction Game](./All-Pay%20Auction%20Game.png)

## Experiment Summary

- **Control Group**: Fixed asset value = $1,000.  
- **Treatment Group**: Asset value uniformly distributed in [$800,$1200].  

- **Hypothesis**: Payoff uncertainty increases the likelihood of the Winner’s Curse.  

- **Findings**:  
  - AI agents increased their bids under uncertainty.  
  - Winner’s Curse rate rose significantly in the treatment group.  
  - Different AI agents showed heterogeneous bidding tendencies.

  ## Contents

- [prompts_rules_interface.txt](./prompts_rules_interface.txt)  
  Documentation of prompts, rules, and interface setup used in the experiments.

- [transcripts_decision_logs.txt](./transcripts_decision_logs.txt)  
  Raw transcripts of AI agent interactions (ChatGPT, Doubao, DeepSeek, Qwen) and decision logs for each experimental round.

# Voting & Institutions
Building upon the theoretical foundations and auction-based mechanisms, this section shifts focus to a collective decision-making context, applying Nobel insights to develop a transparent and efficient voting framework.

## Real-world Collective Choice Case

The case concerns the ongoing efforts of the United Nations to coordinate global action on reducing carbon emissions to mitigate climate change. Different countries face varying levels of risk and economic cost:

- Developed economies can invest in green technology but worry about economic disruption.  
- Developing economies prioritize economic growth and have fewer resources for aggressive reductions.  
- Small island nations are highly vulnerable to climate impacts and strongly favor rapid action.  
- Fossil-fuel exporting countries have economic interests tied to oil and gas and prefer minimal intervention.

**Policy Options:**
1. Aggressive Reduction: Cut global carbon emissions by 50% by 2030.  
2. Moderate Reduction: Cut global carbon emissions by 30% by 2030.  
3. Minimal Reduction: Cut global carbon emissions by 10% by 2030.  
4. No Mandate: Leave emission reductions voluntary.

## Nobel Insights → Innovation
## Forward-Looking Design Challenge






## References

### Theoretical Background
- Baye, M.R., Kovenock, D., & de Vries, C.G. (1996). *The All-Pay Auction with Complete Information*. Economic Theory, 8, 291–305.  
- Kagel, J.H., & Levin, D. (2002). *Common Value Auctions and the Winner’s Curse*. Princeton University Press.  

### Software and LLM Interfaces
- OpenAI. *ChatGPT (GPT-4) API*. https://platform.openai.com/  
- ByteDance. *Doubao Interface*. https://www.doubao.com/  
- DeepSeek AI. *DeepSeek LLM Interface*. https://www.deepseek.com/  
- Alibaba Cloud. *Qwen (通义千问) Interface*. https://tongyi.aliyun.com/qwen  


