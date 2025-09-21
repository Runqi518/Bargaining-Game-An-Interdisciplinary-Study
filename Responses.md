# Point-by-Point Response

## Reviewer #1 (Remarks to the Authors)

### 1. Comment
There is a key inconsistency between the normal-form game (Parts 1 and 2a), which treats the game as simultaneous, and the extensive-form SPNE solution (Part 2b), which treats it as sequential. However, these two formats are conceptually and mathematically distinct. The SPNE solution from Game Theory Explorer (GTE) is valid only for sequential-move games, yet you apply the same game tree and logic to interpret a simultaneous-move context. This creates a mismatch and undermines the validity of the comparative equilibrium analysis.

**Response:**  
I appreciate the professor’s observation regarding the inconsistency between the normal-form game (Parts 1 and 2a), treated as simultaneous, and the extensive-form SPNE solution (Part 2b), analyzed as sequential.  
In the revised submission, I addressed this by:

- Explicitly labeling the Colab analysis (Part 2a) as a Bayesian normal-form game, where players simultaneously choose type-contingent strategies and equilibria are Bayesian Nash.
- Restricting the GTE analysis (Part 2b) to a hypothetical sequential version, with clear notes that SPNE outcomes are pedagogical illustrations rather than predictions of the simultaneous-move game.
- Emphasizing that the information structure is not fully represented in the sequential tree, further limiting the comparability.

### 2. Comment
The interpretation of equilibrium payoffs is not consistent. In some sections, both players choose the maximum demand, and you assume a proportional adjustment to produce equal payoffs. However, this mechanism is not clearly defined or justified based on your payoff matrix or equilibrium logic.

**Response:**  
Thank you for highlighting the ambiguity in how equilibrium payoffs were interpreted when players both demanded the maximum amount.  
In the revised version, I have standardized the rule as follows:

- **Strict feasibility rule:** if the sum of demands exceeds the cap \(S\), both players receive zero payoff.  
- This rule is now stated explicitly at the beginning of Part 2a (Google Colab normal-form computation) and applied consistently throughout the analysis.  
- The earlier mention of proportional adjustment has been removed, as it was not formally supported by the payoff matrix or equilibrium logic. Instead, the payoff interpretation is now fully aligned with the feasibility rule, ensuring consistency across theoretical, computational, and experimental sections.

---

## Reviewer #2 (Remarks to the Authors)

### 3. Comment
To deepen this, a brief reflection could be added on potential bias in the small-scale human experiment—for example, noting that the participants might share implicit social norms, which could differ from the more diverse preferences in real-world bargaining scenarios, and how this might influence results.

**Response:**  
I appreciate Shiqi’s thoughtful suggestion to reflect on potential bias in the small-scale human experiment.  
In the revised submission, I added a short reflection in the Behavioral Scientist section, noting that the observed fairness-oriented strategies might partly reflect shared norms among participants, and that results could differ in a broader sample with more heterogeneous preferences. This addition clarifies the boundaries within which the experimental findings should be interpreted.

### 4. Comment
Figures and screenshots are not labeled, captioned, or referenced in the text. This makes the paper harder to follow and reduces the quality of the reader’s experience. Several insightful theoretical ideas are buried in large paragraphs without clear signposting.

**Response:**  
I appreciate this valuable feedback on the presentation of figures and text organization.  
In the revised version:

- All figures and screenshots now have clear labels and captions (Figure 1–12 and Table 1) and are explicitly referenced in the main text.  
- Long paragraphs were broken up, and explicit signposting sentences were added to improve readability and highlight the progression of theoretical ideas.
