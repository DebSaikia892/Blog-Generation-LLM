How It Works
The user enters a blog topic.
The user selects the desired word count.
The user chooses the target audience:
Researchers
Data Scientists
Common People
A dynamic prompt is generated using LangChain.
The local LLaMA model generates blog content based on the prompt.
The generated blog is displayed in the Streamlit application.

Installation
Clone the Repository
git clone https://github.com/your-username/blog-generation-llm.git
cd blog-generation-llm
Create a Virtual Environment
python -m venv venv
Activate the Environment

Install Dependencies
pip install -r requirements.txt

Model Setup
Download a compatible GGUF LLaMA model and update the model path in the application.
Example:
model = r"path/to/llama-2-7b-chat.Q8_0.gguf"

Running the Application
streamlit run app.py
