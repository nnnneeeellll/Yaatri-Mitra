
**Yaatri Mitra** is an intelligent, AI-powered web application designed to assist travelers in finding the perfect hotel based on personalized preferences. This app integrates multiple technologies to provide a seamless and user-friendly experience for hotel recommendations, ensuring travelers can make informed decisions when planning their trips.

### Key Features:
- **Hotel Recommendations**: The app leverages a custom-built recommendation algorithm to suggest hotels based on customer star ratings, reviews, and other preferences. By analyzing sentiment from hotel reviews, it ensures that only the best hotels are recommended.
  
- **Sentiment Analysis**: The application employs a sentiment analysis system to evaluate customer reviews, providing users with a clearer picture of hotel quality based on positive or negative sentiments.

- **Real-time Weather Updates**: Using the **Open-Weather API**, the app provides real-time weather updates for hotel locations, helping users plan their travels according to the weather conditions.

- **Location Integration**: The app integrates **Google Maps API** to display hotel locations and nearby areas, offering users a map view of the destination and ease of navigation.

- **User-Friendly Interface**: Built with **Streamlit**, the web app features a simple and intuitive interface, ensuring a smooth user experience. The frontend is designed to allow easy hotel filtering based on city, price, rating, and amenities, while the backend uses **Flask** to manage requests and provide seamless data integration.

### Technologies Used:
- **Python**: Used for backend development, logic implementation, and handling data processing tasks such as sentiment analysis and recommendation generation.
- **Flask**: A lightweight web framework used to build the backend and route API requests between the frontend and recommendation system.
- **Streamlit**: A powerful framework to rapidly create interactive web apps, which is used here to build the frontend, displaying hotel recommendations, maps, and weather updates.
- **Open-Weather API**: Provides real-time weather data for the destination city, helping users plan their trips accordingly.
- **Google Maps API**: Displays hotel locations on an interactive map and enables users to explore nearby areas.

### How It Works:
1. **Hotel Selection**: Users input their travel preferences, such as city, budget, and amenities, into the app.
2. **Review Sentiment Analysis**: The sentiment analysis system processes hotel reviews to provide a comprehensive evaluation of the hotel's quality.
3. **Weather Forecast**: The app fetches current weather data for the hotel’s location, helping users plan their visit.
4. **Recommendations & Maps**: Based on the user preferences, the app provides hotel recommendations, displaying hotel locations on an interactive map for easy navigation.

**Yaatri Mitra** simplifies the hotel selection process by offering data-driven insights, allowing travelers to make well-informed choices with ease. Whether you're traveling for business or leisure, this app is designed to make your trip planning as hassle-free as possible.
