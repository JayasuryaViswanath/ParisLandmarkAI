# ParisLandmarkAI
This project implements a concise Parisian travel information retrieval system using the OpenAI Chat Completions API (gpt-3.5-turbo). It demonstrates sequential querying and context management within a conversational framework.


# ParisianPathfinder: Your Concise AI Travel Guide to Paris

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)

**Embark on a virtual tour of the City of Lights with ParisianPathfinder!** This repository showcases a Python script that leverages the power of the OpenAI API (specifically the `gpt-3.5-turbo` model) to provide concise and informative answers to common tourist questions about iconic landmarks in Paris.

## Overview

This project demonstrates how to build a simple yet effective conversational travel guide. It takes a predefined set of questions about Parisian landmarks and uses the OpenAI API to generate helpful and to-the-point responses, simulating a knowledgeable travel assistant.

**Key Features:**

* **AI-Powered Information:** Utilizes the `gpt-3.5-turbo` model for intelligent and relevant answers.
* **Concise Responses:** The AI is instructed to provide information in a brief and easy-to-understand manner.
* **Conversational Context:** Maintains a history of the conversation to provide context for subsequent questions.
* **Iterative Querying:** Demonstrates how to ask multiple questions and receive sequential responses.
* **Clear and Simple Code:** The Python script is well-commented and easy to follow.

## Getting Started

To run this project, you'll need to have the following:

1.  **Python 3.x installed** on your system. You can download it from [python.org](https://www.python.org/).
2.  **An OpenAI API key.** You can obtain one by signing up at the [OpenAI Platform](https://platform.openai.com/).
3.  **The `openai` Python library installed.** You can install it using pip:

    ```bash
    pip install openai
    ```

## Setup

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/](https://github.com/)[Your Username]/[Your Repository Name].git
    cd [Your Repository Name]
    ```

    *(Replace `[Your Username]` and `[Your Repository Name]` with your actual GitHub details.)*

2.  **Set up your OpenAI API key:**

    You need to set your OpenAI API key as an environment variable. You can do this in your terminal before running the script:

    ```bash
    export OPENAI_API_KEY="YOUR_OPENAI_API_KEY"
    ```

    *(Replace `"YOUR_OPENAI_API_KEY"` with your actual API key.)*

    Alternatively, you can set it directly within the Python script, but **this is not recommended for security reasons**:

    ```python
    import os
    from openai import OpenAI

    client = OpenAI(api_key="YOUR_OPENAI_API_KEY") # Replace with your actual key
    ```

## Running the Script

Once you have the dependencies installed and your API key configured, you can run the script:

```bash
python your_script_name.py
