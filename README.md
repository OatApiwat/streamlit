# streanlit
## Create ENV
cd path/to/your/project
python -m venv streamlit_env
streamlit_env\Scripts\activate
deactivate

## Installation
pip install streamlit pandas numpy
pip freeze > requirements.txt
pip install -r requirements.txt


## TEST
streamlit hello
## RUN
streamlit run app.py
python -m streamlit run app.py