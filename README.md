# AI Coding Assistant with DeepSeek, LangChain, and Ollama
This project builds a local interactive coding assistant using DeepSeek LLM (R1 series), LangChain, and Ollama. It offers a streamlined chat interface to assist developers in generating, debugging, and documenting Python code effectively. The interface is built using Streamlit, and runs fully locally without relying on external APIs. This assistant is tailored for real-time conversations with an LLM specialized in programming and debugging. It uses Python 3.12.4 and integrates DeepSeek-R1 via Ollama.

## Installation Steps
1. Clone the repository:
```shell
git clone https://github.com/fahriialfiansyah/gen-ai-deepseek-r1-langchain-ollama.git
```
2. Navigate to the project directory:
```shell
cd gen-ai-deepseek-r1-langchain-ollama
```
3. Create and activate a Python virtual environment:
```shell
# Create environment
python -m venv .venv

# Activate it
.venv/Scripts/activate  # On Windows
# source .venv/bin/activate  # On macOS/Linux
```
4. Install dependencies via pip:
```shell
pip install -r requirements.txt
```
5. Download and install Ollama
Visit https://ollama.com and follow installation instructions.
6. Pull the DeepSeek-R1 model via Ollama:
```shell
ollama pull deepseek-r1:3b
# or
ollama pull deepseek-r1:1.5b
```
7. Run the app locally:
```shell
streamlit run app.py
```
