# Beyond-GPS-Navigation-Bot
To get started with NaviBot-Voice-Assistant, follow these steps: This is the step by step guide for installation.

Navigate to the project directory:

cd NaviBot-Voice-Assistant
Activating venv (optional)

conda create -n venv python=3.10+
conda activate venv
Install dependencies:

pip install -r requirements.txt
Configure environment variables

Rename `.env-sample` to `.env` file
Replace the API your Google API Key, 
Kindly follow refer to this site for getting your own key

Run the chatbot:

streamlit run app.py
