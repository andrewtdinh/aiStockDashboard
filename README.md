# aiStockDashboard
Playing around with building an AI stock dashboard

1. Download and install ollama from ollama.com
2. Extract ollama and install it
3. In a terminal, run `ollama run llama3.2-vision`
4. Open another tab in the terminal.  Navigate into this repo directory and create a virtual environment named `venv` with `python3 -m venv venv` at the root level
5. Activate your virtual environment with `source venv/bin/activate`
6. Install modules with `pip install -r requirements.txt`
7. Run streamlit with `streamlit run stock_dash.py`

Currently it gives an error when we click on the button to `Run AI Analysis`.  A screenshot of the error is attached.  Other than that, the dashboard is generated fine.