# AnthropicAPI

Using Google Gemini APIs to build LLM based applications.

## About

This repository was created to complete the "Anthropic Building with API" course. It contains Jupyter Notebooks that demonstrate and implement the exercises and example projects from the course.

Note: I used a Gemini API key and Gemini-specific methods inside the notebooks to interact with LLM services. API keys are not included in this repository — please keep your keys private.

## Language composition

- Jupyter Notebook (.ipynb): primary content (course notebooks and examples)
- HTML: supporting/visualization files

## Getting started

1. Prerequisites
   - Python 3.10+
   - pip
   - Jupyter Notebook or JupyterLab

2. Install dependencies

If a requirements file exists, install with:

```bash
pip install -r requirements.txt
Configure your Gemini API key
Create a .env file or export the environment variable before running the notebooks. Example .env content:

Code
GEMINI_API_KEY=your_gemini_api_key_here
Or export in your shell:

bash
export GEMINI_API_KEY="your_gemini_api_key_here"
Do NOT commit your API keys to the repository.

Run the notebooks
Start Jupyter Lab or Notebook and open the .ipynb files:

bash
jupyter lab
# or
jupyter notebook
Structure
.ipynb files: course notebooks and examples
.html files: supporting visualizations and exported pages