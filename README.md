Multi-Hop Reasoning in health Knowlede Graphs using Reinforcement Learning
============================
Master Thesis, Daniel Patzer, June 2020. Defended on June 14, 2020.

This work was done in cooperation with Rose-Hulman Institute of Technology at Technical University Berlin under the supervision of Prof. Dr.-Ing. Sebastian Möller.

_License: BSD 3 clause_

_Contact: Daniel Patzer (dan.p at online.de)_

---
### ABSTRACT

The demand for clinical decision support systems in medicine and self-diagnostic symptom checkers has substantially increased in recent years. They depend on large biomedical databases, such as knowledge graphs (KG), to derive inferences. KGs express medical concepts as connections between multiple nodes in a graph. Most biomedical KGs are incomplete and miss relationships between nodes. \
This work employed a deep medical reasoning system to infer missing relationships from a biomedical KG by synthesizing existing information. A question answering (QA) framework is conducted to explicitly infer relationships that are not directly linked in the KG. An embedding-based model was trained to answer questions based on semantic similarities. We were able to achieve high accuracy scores using the statistic metrics Hits@k and MRR. Further investigations revealed limitations when facing more complex chains of reasoning and the lack of transparency in cases of misclassifications. Following the latest research, we were able to overcome these limitations by using a path-based, multi-hop reinforcement learning (RL) approach. We trained the RL agent and presented its ability to use the symbolic compositionality of relations in a qualitative analysis. Given a question, the agent 'walks' on the graph by choosing relations at each step. Thus, providing an explainable reasoning path. Such computational methods can help in a variety of downstream tasks, such as generate hypotheses of potential protein associations or predict explainable interactions in drug-symptom networks.

[CONTINUE..](https://github.com/patzaa/KG-Reasoning/blob/master/Master_Thesis.pdf)
