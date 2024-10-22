# HumanLLMHybridAnswerAggregation
Human-LLM Hybrid Answer Aggregation for Crowd Annotations


## For Categorical Answer(Label) Aggregation
Jiyi Li, "A Comparative Study on Annotation Quality of Crowdsourcing and LLM via Label Aggregation", Proceedings of the 2024 IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP 2024), pp. 6525-6529, Apr. 2024.
[Data](https://github.com/garfieldpigljy/CrowdLabelwithTextContent)

## For Text Answer Aggregation
Jiyi Li, "Human-LLM Hybrid Text Answer Aggregation for Crowd Annotations", Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing (EMNLP 2024), to appear, Nov. 2024.
[Data](https://github.com/garfieldpigljy/CrowdWSA2019)

The source code of the experiments and exploration study in the CodeTextAnswerAggregation folder. About the results in the source code. 

1. In the paper, the main results use five temperatures for LLM aggregators. There is also a study on the influences of different numbers (from one to nine) of LLM aggregators on the performance. In the file of "Human-LLM Text Answer Aggregation_Results_ChatGPT (Gemini).ipynb", e.g., in the cells for "Crowd + HumanAgg + ChatGPT", the outputs of the "Code" cells show the results of nine temperatures, while the main results using five temperatures are recorded in the "Markdown" cells. Temperature of 1 LLM aggregator: [0]; temperatures of 3 LLM aggregators: [0,0.5,1]; temperatures of 5 LLM aggregators: [0,0.25,0.5,0.75,1]; temperatures of 7 LLM aggregators: [0,0.1,0.25,0.5,0.75,0.9,1]; temperatures of 9 LLM aggregators: [0,0.1,0.25,0.5,0.75,0.9,1,1.1,1.25]. 

2. The Text-Inter-Annotator Agreement (TIAA) results for Crowd Creators (C.C.), Crowd Aggregators (C.A.) are in the file of Human-LLM Text Answer Aggregation_Exploration_Study_Gemini, not Human-LLM Text Answer Aggregation_Exploration_Study_ChatGPT. 



## Links

[Other Types of Crowdsourcing Data](https://github.com/garfieldpigljy/ljycrowd)