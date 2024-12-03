# CHatbot-using-groq
conda create -p env python=3.10 -y
conda activate env/
pip install -r requirements.txt
streamlit run app.py
pip install langchain_groq