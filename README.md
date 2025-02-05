Chat with LLM Models - Streamlit App
This Streamlit app allows users to interact with various Large Language Models (LLMs), such as llama2 and deepseek-r1. Users can submit prompts, view responses in real time, and monitor the response duration. The app utilizes the llama_index library to interact with models and stream responses.

Features:
Real-time chat with LLM models
Model selection via the sidebar (llama2, deepseek-r1)
Streaming of responses with updates on the fly
Logging of user inputs, model responses, and any errors
Displays response time for each interaction
Requirements:
To run this app, ensure you have the following dependencies installed:

Python 3.8+
Streamlit
llama_index (for model interaction)
ollama (LLM API)
Install dependencies:
bash
Copy
Edit
pip install streamlit llama_index ollama
How to Run:
Clone or download the repository.
Install the required dependencies listed above.
Run the Streamlit app:
bash
Copy
Edit
streamlit run app.py
Open the app in your web browser (usually available at http://localhost:8501).
Interact with the models by entering prompts in the text box.
Select a model (llama2 or deepseek-r1) from the sidebar.
How It Works:
Sidebar Model Selection: Select your preferred model (llama2 or deepseek-r1).
User Input: Enter a prompt in the chat input field. This will be logged and passed to the selected model.
Response Streaming: The model generates a response in real time. As the response is being streamed, it's displayed on the app.
Duration: The duration of the response generation is displayed alongside the model's answer.
Logs:
Logs are generated for each user input, model response, and any errors that occur during the response generation process.
Logs are displayed in the Streamlit app for transparency and troubleshooting.
Error Handling:
The app includes basic error handling to display messages in case of issues, such as a failed model response or missing files.
Example Interaction:
User: "What is the capital of France?"
Assistant: "The capital of France is Paris."
Duration: The time taken for the assistant to generate the response is displayed.
