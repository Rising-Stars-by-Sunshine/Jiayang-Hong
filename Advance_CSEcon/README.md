# Questions for milestone 2

**Question 1 on Beyond Computer Science and Economics Methodology 1 Behavioral Game Theory and Mechanism Design: Innovating Behavioral Game Theory Tools**

Analyze your experience with oTree, identifying pain points in behavioral game theory research. Review related literature and class discussions to understand experimental economics' goals. Propose a software solution that outperforms oTree in at least three aspects, enhancing strategic interaction studies. Highlight why these advancements are crucial. Submit a concise essay question answer (500 words max) with your analysis and proposals, backed by literature and class insights. Your innovative ideas can significantly contribute to experimental economics, addressing current limitations and paving the way for advanced research methodologies. 

In the analysis, you must provide at least one example of your personal experience in deploying the trust game using oTree, together with a screenshot.

**Question 2 Beyond Computer Science and Economics Methodology 2 Multi-agent Reinforcement Learning:  Advancing Multi-Agent Reinforcement Learning**

Delve into the limitations of current multi-agent reinforcement learning (MARL) frameworks, focusing on environment constraints and agent algorithm customizations. Choose a classic game (e.g., Prisoner's Dilemma, Battle of the Sexes, or the Trust Game) to illustrate these limitations. Describe the development process of a MARL agent for your selected game, detailing the definition of states, actions, and rewards grounded in fundamental behavioral assumptions. Your analysis should provide insights into overcoming MARL's current limitations, fostering advancements in the field. Submit a comprehensive report (500 words max) with your findings and proposals.

In the analysis, you must provide at least one example of your personal experience in endeavoring to deploy the gameplay using one of the MARL frameworks, together with a screenshot. 

**Question 3 Brainstorm your research idea by criticizing existing research: Critiquing and Expanding upon Existing Research**

Objective: The goal of this assignment is to engage critically with existing research in the field of federated learning, using the specific paper presented by the guest speaker as a primary example. Students will assess the paper's research questions, methodologies, and application scenarios and propose new research ideas addressing the identified limitations or gaps.

Instructions:

1. Summary of the Paper

Core Research Questions: Briefly summarize the paper's primary research questions. What is the main problem or challenge the paper seeks to solve or understand?
Methodologies: Describe the methods employed in the paper to address the research questions. Consider the approaches, models, or experimental designs used.
Application Scenarios: Outline the application scenarios discussed in the paper. How does the paper propose to apply its findings or solutions in real-world contexts?

2. Critique of the Research Question

Reflect on the research questions posed in the paper. Are there other more significant objectives or questions that could be more relevant or impactful in this context? Explain why these alternative questions or objectives might offer more value or insight.

3. Critique of the Methodology

Analyze the assumptions made in the paper regarding the strategic environment and behavioral foundations. Discuss whether these assumptions are justified or if they require more reasonable treatment. Suggest how the methodology could be improved or altered to address these concerns.

4. Critique of the Application Scenario

Evaluate the relevance and currency of the federated learning scenarios presented in the paper. With the rapid advancement in technology, consider whether there are more modern or advanced application scenarios that could be more effective in solving similar issues, such as blockchain, generative AI, other privacy-preserving technologies, or quantum computing.

5. Beyond Computer Science and Economics

Consider the role of bounded rationality in both human and AI agents within the context of the paper's findings. Propose how the results might change if the study incorporated participants with specific psychological heuristics or different versions of AI, such as ChatGPT.
You must provide a concrete example: Conduct a mini-experiment by interviewing a human subject not in our class about their perspective on the paper's scenarios or crafting prompts to ask ChatGPT and analyze its responses. Discuss how these insights could dramatically alter the paper's conclusions.
# Answers
## Question 1: Personal Experience with oTree
Reflecting on my personal experience with deploying the trust game using oTree, alongside reviewing related literature, has provided a comprehensive understanding of the objectives of experimental economics and the operational challenges faced by researchers. Experimental economics aims to empirically test economic theories by observing decision-making processes in controlled environments, as noted by Smith (1982). However, the effectiveness of these experiments heavily relies on the tools used, such as oTree, which facilitates the simulation of economic interactions.	
During my hands-on experience with oTree, I encountered issues related to user interface complexity and data analytics limitations. The user interface was not always intuitive, causing difficulties for participants in understanding the game mechanics, which could potentially influence their decisions and affect the experiment's outcome. This issue directly contrasts with the experimental economics goal of creating clear and controlled conditions for testing economic behaviors and theories. A more intuitive and user-friendly interface would ensure that participants' actions are genuine reflections of their decision-making processes rather than reactions to navigational confusion.Additionally, the process of analyzing data gathered from the trust game in oTree was cumbersome and disjointed, requiring external tools for in-depth analysis. This limitation hinders the immediate and detailed examination of experimental data, essential for validating economic theories and understanding complex behavioral patterns, as emphasized in the literature (Friedman and Sunder, 1994).Moreover, the real-time interaction capabilities in oTree were inadequate for capturing the dynamic nature of economic decision-making, particularly in games that simulate immediate trust-building scenarios. This shortfall impacts the ability to study strategic interactions authentically, as dynamic and timely decision-making processes are crucial for experiments aiming to mimic real-world economic interactions (Camerer, 2003).

![Picture 1: Personal Experience with oTree](image-url-1)
To overcome these limitations and better align with the goals of experimental economics, I propose the development of a new software solution that addresses these critical areas. Enhancing the UI/UX design would make the experimental platform more accessible and engaging, ensuring that participant behavior accurately reflects theoretical predictions. Integrating sophisticated data analytics within the platform would facilitate real-time, comprehensive analysis of behavioral patterns, supporting the immediate application and testing of economic theories. Improving real-time interaction capabilities would also enable a more authentic simulation of economic scenarios, essential for studying strategic decision-making processes.

![Picture 2: oTree Improvement](image-url-2)
In summary, my experience with oTree and the insights gained from related literature underscore the need for advanced experimental software that can more effectively support the goals of experimental economics. By addressing the identified limitations, the proposed software would not only improve the methodology of experimental economics but also enhance the overall quality and relevance of research findings in this field.


## Question 2: Multi-Agent Reinforcement Learning (MARL) Frameworks
Analyzing the limitations of current multi-agent reinforcement learning (MARL) frameworks through the lens of the classic game Tic-Tac-Toe reveals key areas for enhancement, particularly in environment constraints and agent algorithm customizations. In Tic-Tac-Toe, two players take turns marking spaces in a 3×3 grid, aiming to place three of their marks in a horizontal, vertical, or diagonal row. This game serves as an ideal model to illustrate MARL's limitations due to its simple yet strategic nature. The current MARL frameworks, such as the one adapted for the PettingZoo API, often struggle with predefined environment constraints that limit the flexibility needed for dynamic strategy formulation. Additionally, agent algorithm customizations in these frameworks are typically rigid, not allowing for nuanced behavior modeling that evolves with the game's context (Terry et al. 2021).
Developing a MARL agent for Tic-Tac-Toe requires defining states, actions, and rewards that mirror the fundamental behavioral assumptions of game theory. The states in this game are represented by the configurations of the grid, accounting for each player's moves. The actions are the choices of grid positions to mark, and the rewards are based on winning, losing, or drawing the game, which encourage strategic play. In my personal endeavor to deploy Tic-Tac-Toe using a MARL framework, I encountered the challenge of creating an agent that could not only learn the basic rules but also develop strategies that adapt to the opponent's actions. The MARL environment often imposed rigid constraints that hampered the agent's ability to learn from the nuanced dynamics of the game, such as anticipating the opponent's moves and strategizing accordingly.

![Picture 3: Code for Strategic Play](image-url-3)
![Picture 4: Challenge of Adapting to Opponent’s Actions](image-url-4)
To overcome these limitations, a more flexible MARL framework is necessary. Such a framework would allow for a dynamic definition of states that evolve with the game's context, enabling agents to learn and adapt their strategies effectively. Enhanced algorithm customizations are also essential, allowing agents to model complex behaviors like deception or strategic foresight, which are crucial in games like Tic-Tac-Toe.An advanced MARL system for Tic-Tac-Toe would incorporate these features, facilitating the development of agents capable of complex strategic thinking and adaptive learning. This would not only improve performance in specific games like Tic-Tac-Toe but also contribute to the broader field of MARL by providing a template for creating more sophisticated and adaptable learning agents.
In conclusion, addressing the limitations of current MARL frameworks, as demonstrated through the deployment of Tic-Tac-Toe, requires innovations in environment flexibility and agent customization. By enhancing these aspects, MARL can be advanced to produce agents that are capable of complex and strategic interaction, reflecting the intricate nature of behavioral game theory.

## Question 3: Federated Learning Incentive Mechanism
### Summary of the Paper
- **Core Research Questions**: Core Research Questions:
The paper addresses the design of an incentive mechanism in federated learning (FL) to handle partial client participation, aiming to achieve an unbiased and high-performance global model. It tackles the challenge of designing a practical incentive mechanism that ensures the convergence of FL with randomized client participation, addressing the bias issue due to partial client participation (Luo et al. 2023).

- **Methodologies**:The paper employs a game-theoretic approach to develop an incentive mechanism, modeling the interaction between the server and clients as a sequential two-stage Stackelberg game. It proposes an adaptive model aggregation scheme and derives a new FL convergence bound to evaluate clients' contributions based on their participation levels and data heterogeneity (Luo et al. 2023).

- **Application Scenarios**: The paper employs a game-theoretic approach to develop an incentive mechanism, modeling the interaction between the server and clients as a sequential two-stage Stackelberg game. It proposes an adaptive model aggregation scheme and derives a new FL convergence bound to evaluate clients' contributions based on their participation levels and data heterogeneity (Luo et al. 2023).


### Critiques
- **Research Question**: While the research question is relevant, there could be exploration into how the incentive mechanism affects long-term client engagement and model sustainability. Investigating how varying incentive strategies impact client retention and model accuracy over time could provide more comprehensive insights into the efficacy of FL systems.

- **Methodology**: The methodology assumes clients are rational and respond predictably to incentives, which might not always hold true in real-world scenarios. A more nuanced approach could consider behavioral economic factors affecting client decisions. Furthermore, the methodology could be expanded to include dynamic pricing strategies that adapt to changing network conditions and client contributions.

- **Application Scenario**: The methodology assumes clients are rational and respond predictably to incentives, which might not always hold true in real-world scenarios. A more nuanced approach could consider behavioral economic factors affecting client decisions. Furthermore, the methodology could be expanded to include dynamic pricing strategies that adapt to changing network conditions and client contributions

### Beyond Computer Science and Economics
Incorporating bounded rationality into the model could provide a more realistic simulation of human-AI interactions in federated learning systems. Examining the impact of psychological heuristics on client participation could lead to more robust incentive mechanisms

![Picture 5: GPT’s Answer for Question 5](image-url-5)
After chating with gpt, I find that Integrating bounded rationality into federated learning (FL) research reveals the complexity of decision-making processes in human and AI agents, challenging the notion of purely rational behavior in economic models. Recognizing the influence of cognitive biases and heuristics necessitates more adaptable and nuanced incentive mechanisms that cater to the varied motivations of participants. This approach could lead to more effective and sustainable federated learning systems, where incentives are aligned with the diverse and dynamic behaviors of all agents involved. Embracing this complexity is crucial for advancing FL research and practice, promoting a more holistic and effective design of learning ecosystems.


## Bibliography
- Camerer, Colin F. (2003). *Behavioral Game Theory: Experiments in Strategic Interaction*. Princeton University Press.
- Friedman, Daniel, and Sunder, Shyam. (1994). *Experimental Methods: A Primer for Economists*. Cambridge University Press.
- Luo, Bing, et al. (2023). *Incentive Mechanism Design for Unbiased Federated Learning with Randomized Client Participation*. ArXiv (Cornell University).
- Smith, Vernon L. (1982). *Microeconomic Systems as an Experimental Science*. The American Economic Review.
- Terry, J. K., et al. (2021). *PettingZoo: Gym for Multi-Agent Reinforcement Learning*. ArXiv.org.
- *The Impact of Quantum Computing on the Future of Blockchain Security*. (n.d.). LinkedIn.
