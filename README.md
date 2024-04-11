# Project Setup Guide

## How to Execute the Source Code?

### Step-by-Step Instructions:

1. Begin by cloning the project repository from the following URL:

    ```bash
    Project Repository: https://github.com/
    ```

2. **Step 01:** Set up a Conda environment upon accessing the repository:

    ```bash
    conda create -n project_env python=3.8 -y
    ```

    Activate the Conda environment:

    ```bash
    conda activate project_env
    ```

3. **Step 02:** Install all the necessary dependencies listed in `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

4. Create a `.env` file within the project root directory. Populate this file with your API credentials for OpenAI. Format it as shown below:

    ```ini
    OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
    ```

5. **Step 03:** Execute the main application script:

    ```bash
    python app.py
    ```

6. Access the application by opening your web browser and navigating to `localhost`.

## Technology Stack Overview:

- Python
- LangChain
- Flask
- OpenAI
- GPT 3
- ChoromaDB

With these steps, you can effortlessly set up and run the project locally. Explore the functionalities seamlessly within your development environment.
