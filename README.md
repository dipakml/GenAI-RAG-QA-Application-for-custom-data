## GenAI RAG Based Q/A Application for custom data 

![](https://res.cloudinary.com/cognitives-s3/image/upload/c_limit,dpr_auto,f_auto,fl_lossy,h_1900,q_auto,w_1900/v1/cog-live/n/1271/2023/Jan/30/XJjQaSivFeb8luqCBLAO.jpg)


### Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Demo](#demo)
  * [Steps in project development](#steps-in-project-development)
  * [Technical Stack](#technical-stack)
  * [Installation](#installation)



### Overview 
This project demonstrates the development of a state of the art Question and Answer (Q/A) application powered by Large Language Models(LLM's) with Retrieval Augmented Generation(RAG). Unlike traditional Q/A systems, the application is tailored for handling custom data, providing a dynamic and highly adaptable solution.


### Motivation
Customized Information Retrieval: Addressing the need for tailored solutions, the project aims to provide organizations with a Q/A application specifically designed to extract meaningful insights from their unique and custom datasets.

Enhanced User Interaction: Motivated by a desire to elevate user experience, we leverage state-of-the-art Generative AI to create an application that responds contextually, providing a more natural and engaging interaction.



### Demo
[Visit this link for live demo of the web application](https://concretstrength7.herokuapp.com/)

Web application Snapshot:

<img target="_blank" src="https://github.com/dipakml/Prediction-of-Concrete-Compressive-Strength/blob/master/webapp_snapshot.png" width=600>


### Steps in project development

- Prepare/Gather the data & process it in specified format
- Langchain for loading the data 
- Create chunks with langchain text splitter
- Create embeddings using OpenAI embeddings 
- FAISS for efficient similarity search 
- Langchain Chat model- ChatopenAI
- Langchain QA chain - RetrievalQA
- Session state history enabled for accessing the chat history 

### Technical Stack 

- Langchain
- OpenAI LLM & Embeddings
- FAISS
- Streamlit


### Installation 
- Clone this repository and unzip it.
- After downloading, cd into the working directory.
- Begin a new virtual environment with Python 3 and activate it.
- Install the required packages using pip install -r requirements.txt
- Execute the command: streamlit run app.py


