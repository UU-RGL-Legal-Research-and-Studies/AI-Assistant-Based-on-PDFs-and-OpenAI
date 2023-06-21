# AI-Assistant-Based-on-PDFs-and-OpenAI

This project is a chatbot that can answer questions based on PDFs provided by the user. It uses OpenAI's GPT-3.5-turbo model for generating responses. The chatbot interface is built using Gradio. A so-called Pinecone database is in place, which contains embeddings of the PDFs provided by the users (semantic meaning converted to numbers in the database). 

The current code has as its starting position that the chatbot functions as an AI Legal Assistant. This can be edited by the user in order to personalize the chatbot for own needs. 

The code for the project has been written with ChatGPT. The code used is in Python.

## Setup

1. Clone this repository to your local machine.
   git clone https://github.com/yourusername/AI-Legal-Assistant.git
2. Navigate to the cloned repository.
   cd AI-Legal-Assistant
3. Install the required dependencies using pip:
   pip install -r requirements.txt
4. Set the following environment variables:
   - `Open_AI_Key`: Your OpenAI API key.
   - `Pinecone_API_Key`: Your Pinecone API key.
   - `Pinecone_API_Env`: Your Pinecone API environment.

## Usage

1. Run the script `main.py`:
   python main.py
2. The Gradio interface will launch in your default web browser.
3. Enter the path to the folder containing your PDF legal documents in the "Folder Path" field.
4. Enter your query in the "Query" field.
5. Click "Submit" to get the answer to your legal question.

## Note

This chatbot is intended to provide general guidance and information. It is not a substitute for professional (legal) advice. Always consult with a qualified (legal) professional for advice.





