# Palo Alto Planning Commission Insights

This Streamlit application provides an interactive dashboard for exploring data related to the Palo Alto Planning & Transportation Commission (PTC). It's designed as a learning tool for those new to Python, data visualization, and the Streamlit framework, showcasing how to build a simple but powerful data application.

![App Screenshot](LWA-demo-lab-bar.png)

## Overview

The goal of this project is to make the activities of the Palo Alto Planning & Transportation Commission more transparent and understandable to the public. The app visualizes meeting data, project proposals, and commissioner stances, offering insights for homeowners, renters, and investors.

## Key Features

*   **Interactive Meeting Chart:** An Altair-powered bar chart showing meeting dates and durations. Hover over the bars to see details about each meeting.
*   **Project Map:** A Folium-based interactive map that displays the locations of proposed development projects. Click on the pins for project details.
*   **Commissioner Stances:** A color-coded table that provides a quick overview of each commissioner's stance on key issues.
*   **Detailed Data Tables:** Sortable and searchable tables for in-depth information on meetings, projects, and commissioner positions.
*   **Video Explainers:** Embedded videos offering analysis and interpretation of the commission's activities for different audiences.

## Tech Stack

This application is built with Python and leverages the following libraries:

*   **[Streamlit](https://streamlit.io/):** For creating the web application and user interface.
*   **[Pandas](https://pandas.pydata.org/):** For data manipulation and analysis.
*   **[Folium](https://python-visualization.github.io/folium/):** For generating the interactive map.
*   **[Altair](https://altair-viz.github.io/):** For creating the interactive bar chart.
*   **[streamlit-player](https://pypi.org/project/streamlit-player/):** A Streamlit component for embedding video players.

## Data Sources

The application uses the following CSV files, which are included in this repository:

*   `PAPTC-meeting-metrics_1H2025.csv`: Contains data about the Planning Commission meetings, including dates, durations, and topics discussed.
*   `PAPTC_projects_1H2025_map_table_v2.csv`: Includes information about development projects, such as their name, address, description, and geographical coordinates.
*   `PAPTC-commissioner-stances_2025-08-19_v3.csv`: Provides details on the commissioners' stances on various policy issues.

## Getting Started

To run this application on your local machine, please follow these steps:

### Prerequisites

*   Python 3.7+
*   pip (Python package installer)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

### Running the App

1.  **Start the Streamlit application:**
    ```bash
    streamlit run streamlit_app.py
    ```
2.  Open your web browser and navigate to the local URL provided by Streamlit (usually `http://localhost:8501`).

## Code Structure

*   `streamlit_app.py`: The main Python script that contains the entire Streamlit application.
*   `requirements.txt`: A list of the Python libraries required to run the app.
*   `*.csv`: The data files used by the application.
*   `LWA-demo-lab-bar.png`: The screenshot image displayed in this README.

## License

This project is licensed under the Apache License, Version 2.0. See the [LICENSE](LICENSE) file for more details.
