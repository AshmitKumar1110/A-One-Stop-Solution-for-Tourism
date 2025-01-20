
# A One-Stop Solution for Tourism
# Overview
The One-Stop Solution for Tourism Dashboard is an interactive web application designed to provide users with a comprehensive tourism platform for exploring India's rich cultural, natural, and adventurous destinations. Users can view popular destinations, book hotels, access weather forecasts, interact with personalized travel assistants, and more.

# Features
Interactive Destination Explorer: Browse through curated destinations across India, complete with categories, average costs, and availability.

Dynamic Maps: Explore destinations using an interactive map powered by Folium.

Hotel Booking: View hotel options, calculate costs, and complete bookings with integrated PayPal payment options.

Travel Planner: Customize travel plans by selecting destinations, dates, and budgets.

Weather Forecast: Get real-time weather updates for your chosen destination.

Personalized Chatbot: Interact with an AI-powered assistant to answer your travel queries.

Pricing Calculator: Calculate your travel expenses using a sidebar tool.

User Reviews: Submit and view reviews for destinations and hotels.

# Installation
# Prerequisites
Python 3.8 or later
Required packages (listed in requirements.txt)

# Steps
## Steps to Publish the Project

1. **Clone the Repository**:
    ```bash
    git clone <repository-url>
    cd <repository-folder>
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Application**:
    ```bash
    streamlit run boom.py
    ```

4. **Open in Your Browser**:
    Visit the following URL:
    ```
    http://localhost:8501
    ```

5. **Push the Project to GitHub**:
    ```bash
    git add .
    git commit -m "Initial commit"
    git push origin main
    ```


# Dependencies
## Requirements

The application uses the following Python libraries. You can install them using the `requirements.txt` file.

### Install Dependencies:
```bash
pip install -r requirements.txt

folium==0.19.2
pandas==2.2.3
paypalrestsdk==1.13.3
Requests==2.32.3
streamlit==1.39.0
streamlit_folium==0.23.2
```


# Usage
Navigate through the sidebar to explore various features such as destinations, hotel booking, travel planning, and weather forecasting.
Use the chatbot to get personalized travel recommendations.
Plan your trip and manage expenses using the travel planner and pricing calculator.
Book hotels securely with integrated PayPal payments.

# Contributions
Contributions to enhance the project are welcome. Please submit a pull request or open an issue for any feature suggestions or bug reports.

# License
This project is licensed under the MIT License. See the LICENSE file for details.

# Acknowledgments
Special thanks to the open-source community for the amazing libraries and tools that power this project.

