# WHO COVID-19 Global Data Explorer

This project is a simple Streamlit dashboard for exploring global COVID-19 case and death statistics by country and region, using WHO data.

## Features
- Interactive charts for top 10 countries by cumulative cases and deaths
- Region filter in the sidebar
- Sample data table


## How to Run Locally
1. Place `metadata.csv` (WHO COVID-19 global summary) in the project folder.
2. Install required packages:
   ```powershell
   pip install pandas matplotlib streamlit
   ```
3. Start the app:
   ```powershell
   streamlit run app.py
   ```
4. After running the command, Streamlit will display a local URL in the terminal (e.g., `http://localhost:8501`).
5. Open this URL in your web browser to access the dashboard.

## How to Access on Streamlit Cloud
If you have deployed this project on [Streamlit Cloud](https://streamlit.io/cloud):
1. Share the public Streamlit Cloud URL (e.g., `https://your-username-your-app.streamlit.app`).
2. Anyone with the link can access the dashboard online without installing anything locally.

## File Structure
- `app.py` — Streamlit dashboard code
- `metadata.csv` — WHO COVID-19 global summary data

## Notes
- This app is designed for the WHO global COVID-19 summary, not the CORD-19 research dataset.
- For other datasets, update the code and README accordingly.

## Author
Charlesomondi-dot
