# Conversational-Information-Seeking
A Conversational Information Seeking (CIS) Paper Reading List Maintained by Chuan Meng.

The format of a piece of literature is as follows:
- [Titile and the link for pdf](). 
  - Authors.
  - ***Publisher and publish time***. 
  - Comments.

Here is the catelogue:
- [Survey](#Survey)
- [Conceptualization](#Conceptualization)
- [Preference elicitation](#Preference-elicitation)
- [Asking Clarifying Question](#Asking-Clarifying-Question)
- [User study](#User-Study)
- [Mixed Intiative](#Mixed-Intiative)
- [Evaluation](#Evaluation)
- [Very ealy papers for CIS](#Very-Ealy-Papers-for-CIS)
- [Indri Python Interface](#Indri-Python-Interface)
- [Undetermined](#Undetermined)


***

## Survey
- [Conversational Information Seeking](https://arxiv.org/abs/2201.08808). 
  - Hamed Zamani, Johanne R. Trippas, Jeff Dalton, and Filip Radlinski.
  - ***arXiv:2201.08808, 2022***. 
  - N/A.
- [Neural Approaches to Conversational Information Retrieval](https://arxiv.org/abs/2201.05176). 
  - Jianfeng Gao, Chenyan Xiong, Paul Bennett, and Nick Craswell.
  - ***arXiv:2201.05176, 2022***. 
  - N/A.

## Conceptualization
- [Conceptualizing Agent-Human Interactions During the Conversational Search Process](https://core.ac.uk/download/pdf/159074386.pdf). 
  - Leif Azzopardi, Mateusz Dubiel, Martin Halvey, and Jeﬀery Dalton.
  - ***The Second International Workshop on Conversational Approaches to Information Retrieval (CAIR), 2018***. 
  - Outline the actions and intents of users and systems explaining how these actions enable users to explore the search space and resolve their information need. This work provides a conceptualization of the CIS process and a framework for the development of practical CIS systems. Introduce a typology of conversational search systems. This typology relates conversational search systems to other types of interactive system, such as chatbots, information retrieval and dialogue systems.
- [A Theoretical Framework for Conversational Search](https://dl.acm.org/doi/abs/10.1145/3020165.3020183). 
  - Filip Radlinski and Nick Craswell.
  - ***Proceedings of the 2017 Conference on Conference Human Information Interaction and Retrieval (CHIIR), 2017***. 
  - N/A.


## Mixed Intiative
- [Mixed Initiative in Dialogue: An Investigation into Discourse Segmentation](https://aclanthology.org/P90-1010/). 
  - Marilyn A. Walker and Steve Whittaker.
  - ***28th Annual Meeting of the Association for Computational Linguistics (ACL), 1990***. 
  - The first systematic study of mixed initiative in dialogues is by Walker and Whittaker.


## Undetermined
- [Neural matching models for question retrieval and next question prediction in conversation](). 
  - Liu Yang, Hamed Zamani, Yongfeng Zhang, Jiafeng Guo, and W. Bruce Croft.
  - ***Proceedings of the 2017 ACM SIGIR Workshop on Neural Information Retrieval, 2017***. 
  - Next question prediction, propose a model for retrieving the next question in conversation.

- [Analyzing and Characterizing User Intent in Information-seeking Conversations](https://dl.acm.org/doi/abs/10.1145/3209978.3210124). 
  - Chen Qu, Liu Yang, W. Bruce Croft, Johanne R. Trippas, Yongfeng Zhang, and Minghui Qiu.
  - ***The 41st International ACM SIGIR Conference on Research & Development in Information Retrieval (SIGIR), 2018***. 
  - The studies on human generated dialogues on question answering websites have provided analysis on the intent of each utterance. Motivated by the lack of data for training machine learning models, this paper collects forum threads of on-line technical support platforms as samples of information-seeking dialogues. This approach allows the authors to create the large-scale MSDialog corpus with 35.5K dialogues. The authors reuse an existing taxonomy for classifying forum messages with user intents and extend it with four new labels. This taxonomy has been used to annotate a subset of the MSDialog dataset (2K dialogues) using crowdsourcing. Then, the authors extract sequences of utterance labels as dialogue ﬂow patterns and compare them with patterns extracted from the Ubuntu Dialog Corpus. The authors report that while the extracted patterns are the same for both dialogue datasets, their relative frequencies are diﬀerent. MSDialog has been collected on a technical support forum provided by Microsoft. forum threads are usually much shorter than text- and speech-based dialogues and their utterances are much longer.

- [User Intent Prediction in Information-seeking Conversations](https://dl.acm.org/doi/abs/10.1145/3295750.3298924). 
  - Chen Qu, Liu Yang, W. Bruce Croft, Yongfeng Zhang, Johanne R. Trippas, Minghui Qiu
  - ***Proceedings of the 2019 Conference on Human Information Interaction and Retrieval (CHIIR), 2019***. 
  - Predicting user intent.

## Preference Elicitation
- [Coached Conversational Preference Elicitation: A Case Study in Understanding Movie Preferences](https://aclanthology.org/W19-5941.pdf). 
  - Filip Radlinski, Krisztian Balog, Bill Byrne, and Karthik Krishnamoorthi.
  - ***Proceedings of the 20th Annual SIGdial Meeting on Discourse and Dialogue, 2019***. 
  - The paper focuses on the movie recommendation scenario, and is focused specifcally on the preference elicitation phase, in which the assistant is instructed to learn more about the user tastes rather than make a recommendation.
- [Towards Conversational Search and Recommendation: System Ask, User Respond](https://dl.acm.org/doi/abs/10.1145/3269206.3271776). 
  - Yongfeng Zhang, Xu Chen, Qingyao Ai, Liu Yang, and W. Bruce Croft.
  - ***Proceedings of the 27th ACM International Conference on Information and Knowledge Management (CIKM), 2018***. 
  - Conversational preference elicitation.
 
## Very Ealy Papers for CIS
- [Mixed-initiative interaction](https://ieeexplore.ieee.org/document/796083). 
  - James F. Allen, Curry I. Guinn, and Eric Horvtz.
  - ***IEEE Intelligent Systems and their Applications, 1999***
  - N/A.
- [Cases, scripts, and information-seeking strategies: On the design of interactive information retrieval systems](https://www.sciencedirect.com/science/article/pii/095741749500011W). 
  - Nicholas J Belkin, Colleen Cool, Adelheit Stein, and Ulrich Thiel.
  - ***Expert systems with applications, 1995***. 
  - Propose an interactive IR system using script-based information-seeking dialogues. Considered conversational information retrieval by characterizing information-seeking strategies. They proposed scripts that can be followed by a system for different types of retrieval tasks, using case-based reasoning to select next steps and offer users choices. 
- [I3R: A new approach to the design of document retrieval systems](https://asistdl.onlinelibrary.wiley.com/doi/abs/10.1002/(SICI)1097-4571(198711)38:6%3C389::AID-ASI1%3E3.0.CO;2-4). 
  - W Bruce Croft and Roger H Thompson.
  - ***Journal of the american society for information science, 1987***
  - Introduce an intelligent intermediary for IR.
- [Information retrieval through man‐machine dialogue](https://www.emerald.com/insight/content/doi/10.1108/eb026631/full/html). 
  - Robert N Oddy.
  - ***Journal of documentation, 1977***
  - Propose the concept of IR through man-machine dialog.



## User Study
- [Exploring conversational search with humans, assistants, and wizards](https://dl.acm.org/doi/abs/10.1145/3027063.3053175). 
  - Alexandra Vtyurina, Denis Savenkov, Eugene Agichtein, and Charles LA Clarke.
  - ***Expert systems with applications, 1995***. 
  - Study how users behave when interacting with a human expert, a commercial intelligent assistant, and a human disguised as an automatic system. Concretely, authors ask 21 participants to solve 3 information seeking tasks by conversing with three agents: an existing commercial system, a human expert, and a perceived experimental automatic system, backed by a human “wizard behind the curtain.” They conclude that people do not have biases against CIS systems, as long as their performance is acceptable.



## Asking Clarifying Question
- [Exploiting Document-based Features for Clarification in Conversational Search](). 
  - Ivan Sekulić, Mohammad Aliannejadi, and Fabio Crestani.
  - ***European Conference on Information Retrieval (ECIR), 2022***. 
  - Document features for clarifying questions.
- [Towards Facet-Driven Generation of Clarifying Questions for Conversational Search](https://dl.acm.org/doi/abs/10.1145/3471158.3472257). 
  - Ivan Sekulić, Mohammad Aliannejadi, and Fabio Crestani.
  - ***Proceedings of the 2021 ACM SIGIR International Conference on Theory of Information Retrieval (ICTIR), 2021***. 
  - N/A.
- [Template-guided Clarifying Question Generation for Web Search Clarification](https://dl.acm.org/doi/abs/10.1145/3459637.3482199). 
  - Jian Wang and Wenjie Li.
  - ***Proceedings of the 30th ACM International Conference on Information & Knowledge Management (CIKM), 2021***. 
  - Investigate a template-guided clarifying question generation method for Web search clarification, with the objective of jointly learning to select appropriate question templates and fill with slot values.
- [ConvAI3: Generating Clarifying Questions for OpenDomain Dialogue Systems (ClariQ)](http://convai.io/ConvAI3_ClariQ2020.pdf). 
  - Mohammad Aliannejadi, Julia Kiseleva, Aleksandr Chuklin, Jeff Dalton, and Mikhail Burtsev.
  - ***Conversational AI challenge series (ConvAI3), 2020***. 
  - Organize a shared task which pose questions on when to ask clarifying questions and how to generate them, concluding all the aforementioned works.
- [Analyzing and Learning from User Interactions with Search Clarifcation](https://dl.acm.org/doi/abs/10.1145/3397271.3401160). 
  - Hamed Zamani, Bhaskar Mitra, Everest Chen, Gord Lueck, Fernando Diaz, Paul N. Bennett, Nick Craswell, and Susan T. Dumais.
  - ***Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR), 2020***. 
  - Generate and select clarifying questions. Further analyzed user interactions in Bing’s search panes, and provided insights into user click bias and the impact of clarification on search experience. 
- [Analyzing and Learning from User Interactions with Search Clarifcation](https://dl.acm.org/doi/abs/10.1145/3397271.3401160). 
  - Hamed Zamani, Bhaskar Mitra, Everest Chen, Gord Lueck, Fernando Diaz, Paul N. Bennett, Nick Craswell, and Susan T. Dumais.
  - ***Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR), 2020***. 
  - Generating and selecting clarifying questions.
- [Guided Transformer: Leveraging Multiple External Sources for Representation Learning in Conversational Search](https://dl.acm.org/doi/abs/10.1145/3397271.3401061). 
  - Helia Hashemi, Hamed Zamani, and W Bruce Croft.
  - ***Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR), 2020***. 
  - Extende the idea of pseudo relevance feedback and leveraged top-retrieved clarifying questions and documents for document retrieval and next clarifying question selection on Qulac.
- [ Leading Conversational Search by Suggesting Useful Questions](https://dl.acm.org/doi/10.1145/3366423.3380193). 
  - Corbin Rosset, Chenyan Xiong, Xia Song, Daniel Campos, Nick Craswell, Saurabh Tiwary, and Paul Bennett
  - ***Proceedings of The Web Conference (WWW), 2020***. 
  - Additionally considered to incorporate user past search behaviors. Query suggestion，propose to suggest query by its usefulness. Real user needs mined from information seeking sessions in Bing sessions. Tackle the task of question suggestion in a “People Also Ask” search engine setting. They argue that a useful question is not simply related to the topic of a user’s query, but should also be “conversation leading” and provide meaningful information for the user’s next step. They propose a BERT-based and a generative GPT-2-based model for question suggestion. They find that questions generated by GPT-2 are syntactically correct, but less useful than the ones selected by BERT from a pre-defined pool of questions.
- [Ranking Clarification Questions via Natural Language Inference](https://dl.acm.org/doi/10.1145/3340531.3412137). 
  - Vaibhav Kumar, Vikas Raunak, and Jamie Callan.
  - ***Proceedings of the 29th ACM International Conference on Information & Knowledge Management (CIKM), 2020***. 
  - N/A.
- [Mimics: A Large-scale Data Collection for Search Clarification](https://dl.acm.org/doi/10.1145/3340531.3412772). 
  - Hamed Zamani, Gord Lueck, Everest Chen, Rodolfo Quispe, Flint Luu, and Nick Craswell.
  - ***Proceedings of the 29th ACM International Conference on Information & Knowledge Management (CIKM), 2020***. 
  - Publish an annotated dataset consisting of real-world user interactions. Introduced MIMICS, a collection of search clarification datasets containing real Web search queries sampled from Bing’s search logs. 
- [Asking Clarifying Questions in Open-Domain Information-Seeking Conversations](https://dl.acm.org/doi/abs/10.1145/3331184.3331265). 
  - Mohammad Aliannejadi, Hamed Zamani, Fabio Crestani, and W. Bruce Croft.
  - ***Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieva (SIGIR), 2019***. 
  - Relese dataset Qulac.
- [Identifying unclear questions in community question answering websites](https://link.springer.com/chapter/10.1007/978-3-030-15712-8_18). 
  - Jan Trienes and Krisztian Balog.
  - ***European Conference on Information Retrieval (ECIR), 2019***. 
  - Focuse on identifying unclear CQA posts that require further clarification.
- [Asking Clarification Questions in Knowledge Based Question Answering](https://aclanthology.org/N19-1013/). 
  - Jingjing Xu, Yuechen Wang, Duyu Tang, Nan Duan, Pengcheng Yang, Qi Zeng, Ming Zhou, and Xu Sun.
  - ***Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP), 2019***. 
  - Create a clarification identification and generation dataset where they solve clarification identification as a binary classification problem. They employs a binary classifier to predict whether to answer the query or ask clarifying question given current context. Then, according to the classification result, use answer or question reranker to rank and select the top response.
- [Answer-based Adversarial Training for Generating Clarification Questions](https://aclanthology.org/N19-1013/). 
  - Sudha Rao and Hal Daumé III.
  - ***Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (NAACL, short paper), 2019***. 
  - Propose a model for generating a clarifying question for identifying missing information in a closed-domain setting. They propose a reinforcement learning model that maximizes a utility function based on the added value obtained by the potential response to the clarifying question.
- [Generating a Common Question from Multiple Documents using Multi-source Encoder-Decoder Models](https://aclanthology.org/P18-1255/). 
  - Woon Sang Cho, Yizhe Zhang, Sudha Rao, Chris Brockett, and Sungjin Lee.
  - ***Proceedings of the 3rd Workshop on Neural Generation and Translation, 2019***. 
  - Propose a task of generating common questions from multiple documents for ambiguous user queries.
- [Learning a Deep Listwise Context Model for Ranking](https://dl.acm.org/doi/abs/10.1145/3209978.3209985). 
  - Qingyao Ai, Keping Bi, Jiafeng Guo, and W. Bruce Croft.
  - ***The 41st International ACM SIGIR Conference on Research & Development in Information Retrieval (SIGIR), 2018***. 
  - The paper uses the average BERT representations of questions and answers in each historical conversation turn as well as features from query performance prediction (QPP) for next clarifying question selection.
- [Toward Voice Query Clarification](https://dl.acm.org/doi/abs/10.1145/3209978.3210160). 
  - Johannes Kiesel, Arefeh Bahrami, Benno Stein, Avishek Anand, and Matthias Hagen.
  - ***The 41st International ACM SIGIR Conference on Research & Development in Information Retrieval (SIGIR), 2018***. 
  - This paper reveals that asking natural language questions is the most convenient interaction form in conversational systems and users enjoy such interactions. Study the impact of voice query clarification on user satisfaction and conclude that users like to be prompted for clarification.
- [Learning to ask good questions: Ranking clarification questions using neural expected value of perfect information](https://aclanthology.org/P18-1255/). 
  - Sudha Rao and Hal Daumé III.
  - ***Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics (ACL, Long Papers), 2018***. 
  - Collected a clarifying question dataset from the posts in StackOverﬂow and proposed to select clarification questions based on the expected value of perfect information considering the usefulness of potential answers to a candidate question.
- [Situational Context for Ranking in Personal Search](https://dl.acm.org/doi/abs/10.1145/3038912.3052648). 
  - Hamed Zamani, Michael Bendersky, Xuanhui Wang, and Mingyang Zhang.
  - ***Proceedings of the 26th International Conference on World Wide Web (WWW), 2017***. 
  - ask for clarification.
- [What do you mean exactly? Analyzing clarification questions in CQA](https://ieeexplore.ieee.org/abstract/document/6812556). 
  - Pavel Braslavski, Denis Savenkov, Eugene Agichtein, and Alina Dubatovka
  - ***Proceedings of the 2017 Conference on Conference Human Information Interaction and Retrieval, 2017***. 
  - N/A
- [Exploratory Search: Beyond the Query-Response Paradigm](https://ieeexplore.ieee.org/abstract/document/6812556). 
  - Ryen W. White and Resa A. Roth.
  - ***Synthesis Lectures on Information Concepts, Retrieval, and Services, 2009***. 
  - Their goal is not always to find the relevant passages for the user questions but also non-relevant passages that contain related topics in order to do clarification or recommendation sometimes 


## Evaluation
- [Meta-evaluation of Conversational Search Evaluation Metrics](https://dl.acm.org/doi/10.1145/3445029). 
  - Zeyang Liu, Ke Zhou, Max L. Wilson.
  - ***Transactions on Information Systems (TOIS), 2021***. 
  - N/A.
- [How Am I Doing?- Evaluating Conversational Search Systems Offline](https://dl.acm.org/doi/10.1145/3451160). 
  - Zeyang Liu, Ke Zhou, Max L. Wilson.
  - ***Transactions on Information Systems (TOIS), 2021***. 
  - Propose a metric for offline evaluation of conversational search systems based on user interaction model, which models user queries and system responses with subtopics, and the bahavours of the user model is conditioned on the answers returned by the system.

## Indri Python Interface
- [Pyndri: A Python Interface to the Indri Search Engine](https://link.springer.com/chapter/10.1007/978-3-319-56608-5_74). 
  - Christophe Van Gysel, Evangelos Kanoulas, and Maarten de Rijke.
  - ***European Conference on Information Retrieval (ECIR), 2017***. 
  - N/A.
- [Indri: A language model-based search engine for complex queries](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.65.3502&rep=rep1&type=pdf). 
  - Trevor Strohman, Donald Metzler, Howard Turtle, and W. Bruce Croft.
  - ***Proceedings of the international conference on intelligent analysis. 2005***. 
  - N/A.
