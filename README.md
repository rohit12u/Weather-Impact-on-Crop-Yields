# Weather-Impact-on-Crop-Yields

🌾 Weather Impact on Crop Yield Analysis

This project explores the relationship between weather conditions (temperature, rainfall, and humidity) and crop yield across various Indian states. It leverages data science techniques, visualizations, and machine learning to analyze and predict crop yield performance. The system also includes database integration to store and manage agricultural data efficiently.

-> Features

📊 Data Visualization: Analyze the impact of weather conditions on crop yield using interactive plots.

🌦️ Weather Analysis: Evaluate the effects of temperature, rainfall, and humidity across regions.

🤖 Machine Learning: Predict future crop yields based on historical weather data.

📁 Database Integration: Organize and manage data with a robust SQL database design.

🗺️ Regional Analysis: Compare crop performance across different states and regions of India.

-> Technologies Used

Frontend: Streamlit for creating an interactive user interface.

Backend: Python for data processing, visualization, and machine learning.

Database: MySQL for storing crop, weather, and state-related data.

-> Libraries:

Pandas and NumPy for data manipulation.

Seaborn and Matplotlib for visualizations.

Scikit-learn for machine learning algorithms.

-> Project Workflow

1. Upload Dataset: Users can upload custom CSV files containing crop and weather data.


2. Filter Data: Filter datasets by state, crop, year, and other attributes for detailed analysis.


3. Visualize: Generate bar plots for yield analysis against weather factors.


4. Predict Yield: Use machine learning to predict crop yield based on weather inputs.


5. Database Management: Store and query data using a structured MySQL database design.

-> Database Design

The project features a normalized SQL database design with the following key tables:

CropData: Stores details of states, crops, weather, and yield.

States: Contains information about states, regions, population, and area.

CropTypes: Classifies crops into categories like cereals, pulses, oilseeds, etc.

WeatherData: Tracks weather parameters (temperature, rainfall, humidity) by state and year.

-> How to Use

1. Clone the repository and set up the environment:

git clone https://github.com/your-username/your-repo.git
cd your-repo


2. Install dependencies:

pip install -r requirements.txt


3. Set up the MySQL database using the provided SQL script.


4. Run the Streamlit app:

streamlit run app.py


5. Upload your dataset, filter data, analyze, and predict!

-> Future Enhancements

🌐 Integration with APIs: Fetch live weather data for real-time predictions.

📈 Advanced Models: Incorporate deep learning for more accurate yield predictions.

🌍 Geospatial Visualizations: Map-based analysis of crop yield and weather conditions.

Feel free to contribute, report issues, or suggest improvements!

Developed by: [Rohit Sen]
🌾 Weather Impact on Crop Yield Analysis Tool | 2024


