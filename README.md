# Chatbot
Project Overview
This project focuses on developing an Educational Chatbot using advanced language models. The chatbot is designed to provide relevant responses based on user queries, integrating technologies like Sentence Transformers and Pinecone for efficient data retrieval and query refinement. The chatbot is built with a Streamlit interface, offering a user-friendly platform for interaction.

Key Features
Advanced Query Processing: Utilizes OpenAI's GPT-3.5 for understanding and refining user queries.
Efficient Data Retrieval: Integrates Pinecone, a vector database for similarity search, ensuring relevant and quick responses.
Conversation Context Management: Maintains conversation history for contextual understanding using Streamlit's session state.
Intelligent Response Generation: Leverages the power of Sentence Transformers and Pinecone Index for matching user queries with accurate responses.
Installation
To set up the chatbot, follow these steps:

Clone the Repository:


git clone [https://github.com/HrishikeshRajulu/Chatbot.git]
Install Dependencies:
Navigate to the project directory and install the required packages.


pip install -r requirements.txt
API Keys:
Ensure you have the necessary API keys for OpenAI and Pinecone.

Run the Application:
Start the Streamlit app.


streamlit run app.py
Usage
Launch the chatbot interface in your web browser.
Type your query in the provided text box.
The chatbot will refine your query, search for relevant context, and provide a response.
