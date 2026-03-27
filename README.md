# Smart Travel Planner Tool – Capstone Project Proposal

## 1. Tech Stack

**- Frontend:**  
- React: For building an interactive, responsive web application.
- TailwindCSS or Material UI: For styling the interface and making everything look consistent.
- Axios: For handling API requests between the frontend and backend.

**- Backend:**  
- Node.js with Express: For managing server side logic, routing, and integration with external APIs.

**- Database:**  
- MongoDB: A cloud based NoSQL database used to store user profiles, saved trips, preferences, and itineraries.

**- External APIs:**  
- OpenWeather API: Provides current and forecast weather data.
- Google Places API: Supplies information on attractions, restaurants, and points of interest.  
- Skyscanner API: Enables flight search and pricing data.

**- Hosting:**  
- Vercel: For deploying the frontend.  
- Render or Heroku: For hosting and scaling the backend services.  
- MongoDB Atlas: For cloud database hosting and management.

---

## 2. Focus of the Project

This will be an evenly focused full stack application. The frontend will deliver a smooth, intuitive travel planning experience, while the backend will handle API integrations, data processing, and itinerary generation. Both sides will work together to provide users with accurate, real‑time travel information and personalized trip recommendations.

---

## 3. Project Type

Website: A responsive web application accessible through modern browsers.

---

## 4. Project Goal

The Smart Travel Planner Tool aims to simplify the overwhelming process of planning a trip. The goal is to make travel planning quick, personalized, and stress free. The app will help users:  
- Discover destinations  
- Check seasonal and current weather  
- Explore local attractions  
- Compare flight options  
- Build optimized itineraries  

---

## 5. User Demographic

The app generally targets people ages 18-55 who enjoy traveling, are comfortable with technology, and prefer a simple, streamlined planning experience:  
- Busy professionals looking for quick, easy trip ideas  
- Young adults and couples planning short getaways  
- Families wanting weather appropriate destinations  
- Solo travelers exploring new places  
- Budget minded travelers comparing options  

---

## 6. Data and API

**- Data:**  
The app will use travel related data such as weather forecasts, destination details, local attractions, flight prices, and basic user preferences.

**- Data Collection:**  
Travel data will be retrieved through third party APIs (OpenWeather, Google Places, and Skyscanner) and processed on the backend before being sent to the frontend. User generated data, such as saved trips, will be stored in MongoDB.

**- API:**  
The backend will integrate with the OpenWeather API, Google Places API, and Skyscanner API to provide current weather, attraction information, and flight options.

---

## 7. Project Approach

**- Database Schema**  
- Users: Stores basic user information, preferences, and saved trips.
- Trips: Stores user‑generated itineraries with fields such as destination, dates, budget, and selected activities.

**- Potential API Issues**  
- Data Consistency: Ensuring weather, attractions, and flight data remain accurate across different API sources.  
- Rate Limits: Managing API request limits from providers like OpenWeather, Google Places, and Skyscanner.  
- Error Handling: Handling failed API calls gracefully to maintain a smooth user experience.

**- Sensitive Information**  
- No sensitive personal data will be collected beyond basic user preferences and saved trip details. The app focuses on travel information and itinerary planning.

**- Functionality**  
- Destination Exploration: Users can view weather, attractions, and flight options for various destinations.  
- Itinerary Builder: Users can create, edit, and save personalized trip plans.  
- Search & Filter: Users can search destinations and filter results by weather, budget, or travel dates.

**- User Flow**  
- Homepage: Displays search options, featured destinations, and quick‑start planning tools.  
- Destination Pages: Shows weather, attractions, and flight information for selected locations.  
- Itinerary Page: Allows users to build and save customized trip plans.

---

## 8. Stretch Goals

- User Feedback: Allowing users to rate destinations or provide trip notes  
- Social Sharing: Enabling users to share itineraries with friends or family 
- Mobile App Version: Converting the web app into a React Native mobile application
