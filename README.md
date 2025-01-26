# Project Name
> HelpMateAI - Develop a generative search system for emails that helps organisation find and validate past decisions, strategies, and data in a huge corpus of email threads.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Goal is Develop a generative search system for emails that helps organisation find and validate past decisions, strategies, and data in a huge corpus of email threads.
- The project will have 3 layers.
- The Embedding Layer: The emails need to be effectively processed, cleaned, and chunked for the embeddings. Here, the choice of the chunking strategy will have a large impact on the final quality of the retrieved results.
- The Search Layer: Design at least 3 queries against which you will test your system. 
- The Generation Layer: The final prompt that will lead to the final response
- 
- I have implemented a similar RAG approach using LangChain. Please refer to file SemanticSpotter.ipynb	

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- OpenAI and ChromaDB were used to generate and store embeddings
- Once the embeddings are created, the top 10 results are collected from the vector store based on user query
- Results are re-ranked using cross encoder
- The top 3 results based on the new ranks are provided to LLM along with a useful prompt
- The response from the LLM is provided to the user. Please refer to Results_Snapshot file for the sample response to queries.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was part of our learning for ML C56
- The project was worked by Rishi


## Contact
Created by [@rishiash] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
