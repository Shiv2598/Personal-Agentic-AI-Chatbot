🚀 Project Setup Guide
This guide provides step-by-step instructions to set up your project environment, including setting up a Python virtual environment using Pipenv, pip + venv, or Conda, and running your AI chatbot application.

📁 Table of Contents
Setting Up a Python Virtual Environment

Using Pipenv

Using pip and venv

Using Conda

Running the Application

Phase 1: Create AI Agent

Phase 2: Setup Backend with FastAPI

Phase 3: Setup Frontend with Streamlit

⚠️ Important Notes

Setting Up a Python Virtual Environment
Using Pipenv
Install Pipenv (if not already installed):

bash
Copy
Edit
pip install pipenv
Install dependencies:

bash
Copy
Edit
pipenv install
Activate the virtual environment:

bash
Copy
Edit
pipenv shell
Using pip and venv
Create a virtual environment:

bash
Copy
Edit
python -m venv venv
Activate the virtual environment:

macOS/Linux:

bash
Copy
Edit
source venv/bin/activate
Windows:

cmd
Copy
Edit
venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Using Conda
Create a Conda environment:

bash
Copy
Edit
conda create --name myenv python=3.11
Activate the environment:

bash
Copy
Edit
conda activate myenv
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Running the Application
Phase 1: Create AI Agent
bash
Copy
Edit
python ai_agent.py
Phase 2: Setup Backend with FastAPI
(Run in a separate terminal)

bash
Copy
Edit
python backend.py
Phase 3: Setup Frontend with Streamlit
bash
Copy
Edit
python frontend.py
⚠️ Important Notes
Always keep the backend script (backend.py) running in a separate terminal while using the frontend or interacting with the AI agent.

Ensure all dependencies are correctly installed in the active environment.

Use compatible Python version (preferably Python 3.11).
