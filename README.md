# 🎈 Streamlit + LLM Examples App

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/streamlit/llm-examples?quickstart=1)

Starter examples for building LLM apps with Streamlit.

## Overview of the App

This app showcases a growing collection of LLM minimum working examples.

Current examples include:

- Chatbot
- File Q&A
- LangChain Quickstart
- LangChain PromptTemplate
- LangChain Search

## Demo App

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://llm-examples.streamlit.app/)

### Get an OpenAI API key

You can get your own OpenAI API key by following the following instructions:

1. Go to https://platform.openai.com/account/api-keys.
2. Click on the `+ Create new secret key` button.
3. Next, enter an identifier name (optional) and click on the `Create secret key` button.

### Enter the OpenAI API key in Streamlit Community Cloud

To set the OpenAI API key as an environment variable in Streamlit apps, do the following:

1. At the lower right corner, click on `< Manage app` then click on the vertical "..." followed by clicking on `Settings`.
2. This brings the **App settings**, next click on the `Secrets` tab and paste the API key into the text box as follows:

```sh
OPENAI_API_KEY='xxxxxxxxxx'
```

## Run it locally

Before activating a virtual environment (venv), you need to create the virtual environment. Here are the steps you typically follow:

1. Create a new virtual environment:
   ```bash
   python3 -m venv {{path/to/venv}}
   ```
   
   This command creates a new virtual environment at the specified path. Replace `{{path/to/venv}}` with the desired location for your virtual environment.

2. Activate the virtual environment:

- For macOS/Linux (bash/zsh):
    ```bash
    source {{path/to/venv}}/bin/activate
    ```
- For Windows (Command Prompt):
    ```bash
    {{path/to/venv}}\Scripts\activate.bat
    ```
- For Windows (PowerShell):
    ```bash
    {{path/to/venv}}\Scripts\Activate.ps1
    ```
Activating the virtual environment modifies the shell's environment variables to use the Python interpreter and packages installed within the virtual environment.

After activating the virtual environment, you can install and use Python packages specific to that environment without interfering with the system-wide Python installation.

Remember to replace `{{path/to/venv}}` with the actual path where you created your virtual environment.

Note: The `python3` command assumes you have Python 3 installed. If you have a different version of Python installed, adjust the command accordingly (e.g., `python2`, `python3.9`, etc.).

3. Install requirements

    ```sh
    pip install -r requirements.txt
    ```

4. Run the application

    ```sh
    streamlit run Chatbot.py
    ```