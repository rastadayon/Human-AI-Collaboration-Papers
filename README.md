# Human-AI-Collaboration-Papers
## Papers on Human-AI Collaboration in Individual and Team Settings
---
| Title  | Year | Venue | Link | Summary |
| --- | --- | --- | --- | --- |
| On the Utility of Learning about Humans for Human-AI Coordination  | 2019  | NeurIPS | [link](https://arxiv.org/abs/1910.05789) | summary |
| Human-AI Collaboration in a Cooperative Game Setting: Measuring Social Perception and Outcomes  | 2020  | ACM on Human-Computer Interaction | [link](https://dl.acm.org/doi/abs/10.1145/3415167) | summary |
| Exploring Trust in Human–AI Collaboration in the Context of Multiplayer Online Games  | 2023  | Systems | [link](https://www.mdpi.com/2079-8954/11/5/217) | summary |
| Understanding Human-AI Cooperation Through Game-Theory and Reinforcement Learning Models  | 2021  | Hawaii International Conference on System Sciences | [link](https://par.nsf.gov/servlets/purl/10284453) | summary |
| Trust in an AI versus a Human teammate: The effects of teammate identity and performance on Human-AI cooperation  | 2023  | Computers in Human Behavior | [link](https://www.sciencedirect.com/science/article/pii/S0747563222003569) | [summary](#trust-in-an-ai-versus-a-human-teammate:-the-effects-of-teammate-identity-and-performance-on-human-ai-cooperation) |
| Uncalibrated Models Can Improve Human-AI Collaboration  | 2022  | NeurIPS | [link](https://papers.nips.cc/paper_files/paper/2022/hash/1968ea7d985aa377e3a610b05fc79be0-Abstract-Conference.html) | [summary](#uncalibrated-models-can-improve-human-ai-collaboration) |
| Human-AI Collaborative Bayesian Optimisation  | 2022  | NeurIPS | [link](https://papers.nips.cc/paper_files/paper/2022/file/6751611b394a3464cea53eed91cf163c-Paper-Conference.pdf) | [summary](#human-ai-collaborative-bayesian-optimisation) |
| The Utility of Explainable AI in Ad Hoc Human-Machine Teaming  | 2021  | NeurIPS | [link](https://papers.nips.cc/paper_files/paper/2021/hash/05d74c48b5b30514d8e9bd60320fc8f6-Abstract.html) | summary |
| Evaluation of Human-AI Teams for Learned and Rule-Based Agents in Hanabi | 2021  | NeurIPS | [link](https://papers.nips.cc/paper_files/paper/2021/hash/86e8f7ab32cfd12577bc2619bc635690-Abstract.html) | summary |
| Evaluating and Rewarding Teamwork Using Cooperative Game Abstractions  | 2020  | NeurIPS | [link](https://papers.nips.cc/paper_files/paper/2020/hash/4d95d05a4fc4eadbc3b9dde67afdca39-Abstract.html) | [summary](#evaluating-and-rewarding-teamwork-using-cooperative-game-abstractions) |
| Are Two Heads Better Than One in AI-Assisted Decision Making? Comparing the Behavior and Performance of Groups and Individuals in Human-AI Collaborative Recidivism Risk Assessment  | 2023  | CHI Conference on Human Factors in Computing Systems | [link](https://dl.acm.org/doi/abs/10.1145/3544548.3581015) | [summary](#are-two-heads-better-than-one-in-ai-assisted-decision-making?-comparing-the-behavior-and-performance-of-groups-and-individuals-in-human-ai-collaborative-recidivism-risk-assessment) |
| Who Should I Trust: AI or Myself? Leveraging Human and AI Correctness Likelihood to Promote Appropriate Trust in AI-Assisted Decision-Making  | 2023  | CHI Conference on Human Factors in Computing Systems | [link](https://dl.acm.org/doi/abs/10.1145/3544548.3581058) | summary |
| Modeling Human Trust and Reliance in AI-Assisted Decision Making: A Markovian Approach  | 2023  | AAAI | [link](https://ojs.aaai.org/index.php/AAAI/article/view/25748) | [summary](#modeling-human-trust-and-reliance-in-ai-assisted-decision-making-a-markovian-approach) |

<!-- | Title  | Year  | venue | [link]() | summary | -->
### Trust in an AI versus a Human teammate: The effects of teammate identity and performance on Human-AI cooperation
#### Abstract
Recent advancements in artificial intelligence (AI) have led to the development of more powerful AI agents capable of serving as competent teammates for humans. This paper dicusses the problems of trust in a human-AI collaboration setting and questions if more humanlike features will lead to an improved human-AI joint performance. This research investigates the impact of teammate identity (human vs. AI) and teammate performance (low-performing vs. high-performing AI) on human-AI cooperation through a human subjects study. Results indicate that humans exhibit greater behavioral trust in AI, accepting their decisions more frequently compared to human teammates. Notably, teammate performance significantly influences human-AI joint performance, while teammate identity does not. The findings advise caution against deceiving humans about the identity of AI in future applications involving human-AI cooperation.

#### What is reported
1. General study framework
2. Human-AI joint performance in a chess task for each of the different cases (human vs. AI identity / low-performing vs. high-performing AI).
3. Participants' self-reported trust in their teammate in each of the previously mentioned cases.
4. Participants' self-reported helpfulness and competency of their teammates in each of the previously mentioned cases.
5. Means and standard deviations for human-AI joint performance.
6. Means and standard deviations for human behavioral trust in their teammates.


### Uncalibrated Models Can Improve Human-AI Collaboration
#### Abstract
This paper explores the practical applications of AI where AI models assist human users in decision-making. The AI provides advice with a measure of confidence, allowing humans to gauge its reliability. **The study shows that presenting AI models as more confident than they actually are, even if they are well-calibrated, can enhance human-AI performance**. To achieve this, the researchers trained a model to predict how humans incorporate AI advice based on a large dataset of human-AI interactions. By transforming the AI's prediction confidence to make it uncalibrated, they improved the final human prediction. The results were validated across four tasks involving images, text, and tabular data, with hundreds of human participants. Simulation analysis further supports their findings, emphasizing the importance of jointly optimizing the human-AI system rather than solely focusing on optimizing the AI model.

#### What is reported
1. Information about the dataset
2. Accuracy of the individual on each task before and after AI advice
3. The human model's accuracy for the task with multiple different reported AI confidences.
4. Mathematical reasoning on when over/underconfident AI advice helps + Heatmap demonstraiting that
5. Accuracy of the Human-AI system in a real world experiment after modifying the reported AI confidence.


### Human-AI Collaborative Bayesian Optimisation
Could be potentially useful for the defense part of the attack!

### Evaluating and Rewarding Teamwork Using Cooperative Game Abstractions
No AI involved but they predict how well a team of individuals can perform together using cooperative game theory. Could be useful! 

### <h3 style="color:brown;">Are Two Heads Better Than One in AI-Assisted Decision Making? Comparing the Behavior and Performance of Groups and Individuals in Human-AI Collaborative Recidivism Risk Assessment</h3>

#### Abstract
In this paper, the focus is on comparing the behavior and performance of groups and individuals in AI-assisted decision making, particularly in the context of recidivism risk assessment. Six aspects are examined, including decision accuracy and confidence, appropriateness of reliance on AI, understanding of AI, decision-making fairness, and willingness to take accountability. The results show that groups tend to rely more on AI models, regardless of correctness, but they are more confident in overturning incorrect AI recommendations. Additionally, groups tend to make fairer decisions than individuals based on the accuracy equality criterion, and they are more willing to credit AI when correct decisions are made. The paper concludes by discussing the implications of these findings.
#### Measurements
- Decision accuracy (Individual and group)
- Reliance on AI (Over-liance and under-liance for both individual and group)
- Decision confidence (Self-reported confidence on likert scale - Confidence for correct final decision and incorrect final decisions)
- Understanding of AI (Importance of different features for the AI model)
- Fainess in decision making (Fairness of decision based on race)
- Accountability (Self-reported)

#### What is reported
1. **Comparison on decision accuracy** for individual+AI and group+AI
2. **Comparison on reliance on AI** for overall reliance, under-reliance and, over-reliance in both individual and group setting 
3. **Comparison on decision confidence** for correct and incorrect final decision of the individuals and the groups, as well as the correct and incorrect final decisions for when the final prediction agreed or disagreed with the AI
4. **Comparison on understanding of AI** reporting the Pearson correlation coefficient between the true and the subject's percieved feature importance
5. **Comparison on decision making fairness** 
6. **Comparison on accountability** assigned by the subjects to themselves and the AI model, for when the individual or group's final decision was correct vs incorrect, when the AI's recommendation was correct vs incorrect
7. Some exploratory analyses
8. Reasoning behind choosing the recidivism risk prediction as the task for their experiment

### Modeling Human Trust and Reliance in AI-Assisted Decision Making A Markovian Approach
They perform analysis based on Prospect Theory for one of their baselines. 

#### Abstract

Understanding how humans interact with and rely on AI is crucial for better decision-making support. Unlike previous studies that often approached human reliance on AI analytically, considering cost-benefit analysis, this study takes psychological factors like trust in AI  into account. **This paper introduces a hidden Markov model to study the affective process of human-AI interaction in AI-assisted decision making.** It explores how humans adjust their trust in AI over time and make reliance decisions based on that trust. The model outperforms various baselines in predicting human reliance behavior using real human behavior data. The study also provides insights into how contextual factors like decision stakes and interaction experiences influence trust and reliance dynamics in AI-assisted decision making. The proposed model also sheds light on how contextual factors like decision stakes and interaction experiences influence humans' trust and reliance dynamics in AI-assisted decision making.

#### What is reported
1. How their Hidden MArkov Model is structured and trained
2. What baselined were used to predict the AI-reliance for the experiment
3. The performance of their method vs the baseline methods for predicting the AI-reliance in High Penalty (HP) and Low Penalty (LP) settings for the population
4. The reliance probability distribution predicted by their method vs the baslines for the 4 actions (appropriate rejection, inappropriate rejection, appropriate acceptance, inappropriate acceptance)
5. The performance of their method vs the baseline methods for predicting the AI-reliance in High Penalty (HP) and Low Penalty (LP) settings for individuals
6. The trust state transition probability difference (%) for HP vs. LP, previous experience et−1 being appropriate vs. inappropriate acceptance, or inappropriate vs. appropriate rejection