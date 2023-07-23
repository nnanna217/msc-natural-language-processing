# msc-cop509-natural-language-processing

 This coursework implements an information retrieval, topic modelling and summarisation tool. 
 
 ## Datasets

## Task Descriptions: Information Retrieval, Topic Modelling, and Summarisation

1. **Pre-process the dataset.** Include explanations where needed.
2. **Latent Semantic Indexing (LSI)**. Use the pre-processed dataset for the remaining tasks.
   - **_Develop a Latent Semantic Indexing (LSI) model:_** Develop functionality such that for each query, the LSI model retrieves the top 10 most similar reviews from the dataset.
   - **_Empirically tune your LSI model (weighting scheme and SVD dimensions)_:** Present the results using tables and graphs. Provide brief remarks on your observations. 
3.  **Neural information retrieval.**
    - **Develop a neural information retrieval model**: Compare its performance to that of your best-tuned LSI model (from Task 2). Present all results in tables and graphs and explain the findings.
    - Develop an interactive interface that will allow the user to type in their own query and to interact with
the results.
5. **Topic modelling and visualisation of search results**.
(a) Extend your answer to Task 3 to include topic modelling functionality. For this, implement and tune a topic model of your choice (e.g. Latent Dirichlet Allocation (LDA), Gensim, BERTopic) that takes the top n search results and clusters them into topics (n can be user-defined or set to 50) (10 marks). Evaluate the performance of the model using suitable evaluation metrics, and explain the findings (max 100 words) (5 marks).
(b) Add functionality that will enable the user to interactively visualise the topics and keywords (15 marks).
6. [20 marks] Summarisation of search results.
(a) Extend your answer to Task 3 to include an approach (either neural or non-neural) that takes the top 10 search results and summarises them (5 marks). Evaluate the performance of the model using suitable evaluation metrics. Explain the findings (max 100 words) (5 marks).
(b) Add extra functionality of your choice that is related to summarisation (e.g. enable the user to choose which results to summarise) (10 marks).

 
