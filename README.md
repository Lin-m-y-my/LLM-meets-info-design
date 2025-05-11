# LLM-meets-info-design
This project evaluates LLMs’ capabilities in Bayesian persuasion tasks, focusing on their performance as both senders and receivers in discrete and continuous state space models. The discrete model features a two-state, two-action setup where the sender designs signals to maximize the receiver’s likelihood of choosing a favorable action. The continuous model extends this to a state space over $[0, 1]$, testing LLMs’ ability to handle complex signaling strategies, such as partitioning the state space. We employ two experimental approaches: direct strategy reporting, where LLMs articulate their signaling or action strategies in natural language, and simulation-based interaction, where LLMs adapt strategies over repeated trials without guaranteed sender commitment. Additionally, we introduce a novel case study, the Michelin Inspector Recommendation problem, to explore LLMs’ ability to craft persuasive text-based signals in a realistic persuasion scenario.
## llm_info.ipynb
Run this file to see the simulation results of LLMs which is the the experiment in 3.2 in project and results in 4.2. 
## Michelin_LLM.ipynb
The codes for LLM interactions in the Michelin Inspecotor Recommendation problem. Please see the specific problem setting in the paper
## Michelin_LLM_learning.ipynb
The codes for LLM interactions with ambiguous information in the Michelin Inspecotor Recommendation problem. Please see the specific problem setting in the paper.
