# Scraping-Temperature-Data

## Overview
This project is a web application that visualizes temperature data over time. It utilizes Streamlit for building the web interface and Plotly Express for creating interactive line plots. The data is sourced from a CSV file (`data.txt`) containing date and temperature information.

## Dependencies
The project relies on the following Python libraries:
- [Streamlit](https://streamlit.io/) - for building interactive web applications
- [Plotly Express](https://plotly.com/python/plotly-express/) - for creating interactive plots
- [Pandas](https://pandas.pydata.org/) - for data manipulation and analysis

## Setup
To run the project, follow these steps:
1. Clone the repository: `git clone https://github.com/tur14cus/scraping-temperature-data.git`
2. Install dependencies: `pip install streamlit plotly pandas`
3. Ensure you have a CSV file named `data.txt` containing date and temperature data.
4. Run the Streamlit application: `streamlit run webapp.py`

## Usage
The web application provides a line chart visualization of temperature data over time. Users can interact with the chart to explore the temperature trends.

## Structure
The project consists of the following files:
- `webapp.py`: Contains the Streamlit application code for visualizing temperature data.
- `data.txt`: CSV file containing date and temperature data.
- `README.md`: This readme file providing an overview of the project.

## Contributions
Contributions are welcome. Feel free to fork the repository, make improvements, and submit pull requests.

## License
This project is licensed under the [MIT License](LICENSE).
