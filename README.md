# AgentLegal - The Indian Law Chatbot

AgentLegal is a legal chatbot designed to assist with queries related to Indian law. Built by **Lawgorithms**, this agent leverages the power of **Python**, **Streamlit**, **RAG (Retrieval-Augmented Generation)**, and **HuggingFace** to provide accurate legal information, making it an ideal tool for corporate settings. 

## Features

- **Legal Expertise**: Provides information on Indian law, focusing on corporate legal queries.
- **Streamlit UI**: A simple, user-friendly web interface for users to interact with the chatbot.
- **RAG & HuggingFace Models**: Combines Retrieval-Augmented Generation techniques with HuggingFace's transformer models to generate accurate, reliable responses.
- **Large Language Models**: Leverages the advanced technology of LLM's to make sure that the perfect response is generated by the agent.
- **Corporate Focus**: Tailored for use in corporate environments, addressing common legal questions related to business law, contracts, labor laws, and compliance in India.

## Technology Stack

- **Python**: Core programming language used for backend logic and AI model integration.
- **Langchain**
- **Pinecone**: Vector Database.
- **AWS**: Cloud Infrastructure.
- **HuggingFace Transformers**: Transformer models from HuggingFace's library for natural language processing (NLP).
- **Generative AI**: Mistral AI, all-MiniLM-L12-v2
- **MySQL**: Feedback mechanism to store user feedback.
- **Streamlit**: Framework used to build the web-based user interface.

## Installation

The installation requires the following modules to be installed on your system: 
1. streamlit
2. langchain
3. langchain-community
4. pinecone-client
5. openai sentence-transformers
6. huggingface-hub
7. nltk 
8. sqlalchemy
9. mysqlclient
10. rouge-score
11. bert-score
12. plotly

You can install all modules through this one command: 
pip install streamlit langchain langchain-community pinecone-client openai sentence-transformers huggingface-hub nltk sqlalchemy mysqlclient rouge-score bert-score plotly

Note: 
You would also be required to run the python code to download vader_lexicon for sentiment analysis:

import nltk
nltk_download('vader_lexicon')


## Usage

Once you have cloned the repository, run the app.py file on your terminal with the command: 
streamlit run /add_your_path/app.py

Once the app is running, users can interact with AgentLegal through the web interface to ask questions about Indian law. The chatbot is particularly well-suited for handling legal queries in a corporate environment, providing detailed responses related to:

- Contract law
- Corporate governance
- Labor laws
- Compliance regulations

## Structure

- `app.py`: The main file for running the Streamlit app.
- `RAG.ipynb`: Contains the logic for the Retrieval-Augmented Generation model.
- `Vector_Database.ipynb`: Contains the logic for embedding documents
- `data`: Multiple folders containing legal cases, and contracts.


## Future Enhancements

- Expand legal coverage to include more sectors beyond corporate law.
- Add support for additional languages (e.g., Hindi, Tamil) to reach a wider audience.
- Improve chatbot personalization based on user profiles.


## Contact

If you have any questions or need further assistance, feel free to contact the **Lawgorithms** team

---

*Built with passion by the Lawgorithms team.*
