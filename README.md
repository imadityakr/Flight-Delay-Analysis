✈️ Flight Delay Analysis Using PySpark

This project analyzes US domestic flight delay data using Apache Spark (PySpark). It processes large datasets to uncover patterns in delays caused by airlines, weather, and other factors.

🔍 Objective

To perform distributed data processing and analysis using PySpark and generate insights into:

Causes of flight delays
Average delay per airline and airport
Monthly and hourly delay trends
Impact of weather on delays
🛠 Technologies Used

PySpark – for distributed data processing
Python (Pandas, Matplotlib, Seaborn) – for data wrangling and visualization
Google Colab / Jupyter Notebook – for execution
Datasets – US Flight Delay public datasets (Bureau of Transportation Statistics)


📁 Project Structure
flight-delay-analysis/
├── data/                    # Contains datasets (.csv)
├── notebooks/               # Jupyter/Colab notebooks with code
├── visuals/                 # Output graphs and plots
└── README.md                # Project overview


📊 Key Insights

Certain airlines have consistently higher delay percentages.
Flights scheduled in late evenings show more delays.
Weather-related delays are most common during winter months.

🚀 How to Run

Clone this repo:
Open the notebook in Google Colab or Jupyter Notebook.
Upload the datasets or use public links (modify in code accordingly).
Run cells step-by-step to process and visualize the data.


📌 Future Improvements

Automate with Apache Airflow
Add real-time delay predictions using ML
Deploy dashboard using Streamlit
