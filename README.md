# Live-Climates

## URL: https://jeevithaj8.github.io/Live-Climates/

Weather Dashboard

Project Overview:


You will develop a web-based Weather Dashboard app that provides real-time weather information to travelers. The app will interact with the OpenWeather API and include temperature, humidity, weather conditions, and corresponding weather icons.


Features to Implement:

1. Search Functionality:

Input box where users can type and search for a city name.



2. Weather Details Display:

Temperature (°C/°F).

Humidity (%).

Weather condition (e.g., "Sunny", "Rainy").

Weather icons to represent conditions (sun for clear weather, clouds for cloudy weather, etc.).



3. Error Handling:

Gracefully handle invalid city names (e.g., show "City not found" message).

Handle API errors like failed fetch requests.



4. UI/UX:

Clean, responsive design using HTML, CSS, and JavaScript.

Visually appealing layout with appropriate icons.



5. Deployment:

Deploy on a free hosting platform like Render.com, Netlify, or Railway.app.

Make the app lightweight and fast for quick access.



6. GitHub Repository:

Upload the source code with a well-documented README.

Include instructions for installation, running the app locally, and deployment.




Technologies and Tools:

Frontend: HTML, CSS (Flexbox/Grid, media queries), JavaScript (for API calls and DOM manipulation).

API: OpenWeather API (free-tier version).

Hosting: Render, Railway, or Netlify.

Version Control: Git and GitHub for storing code.


Step-by-Step Development Plan:

1. Initial Setup:

Set up a basic HTML structure with a simple layout.

Link CSS for styling and JavaScript for functionality.

Obtain an API key by signing up for the OpenWeather API.


2. Build Core Functionality:

Search Input: Create an input field where users can enter a city name and a search button.

API Integration: Use JavaScript's fetch() to make GET requests to the OpenWeather API.
Example endpoint:

https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}&units=metric

Extract Weather Data: Parse the JSON response to get temperature, humidity, and weather description.


3. Display Weather Data:

Use DOM manipulation to display the fetched data dynamically (temperature, humidity, and description).

Display weather icons using OpenWeather's icon data or custom images.


4. Handle Errors:

Check if the city is valid (e.g., show a user-friendly message for invalid input).

Handle network errors or issues when fetching data.


5. Design a Responsive UI:

Style the app using CSS to make it clean and attractive.

Use Flexbox/Grid for layout and add media queries to ensure mobile responsiveness.


6. Deploy the App:

Choose a free hosting service (Netlify, Render, or Railway) and deploy the web app.


7. Upload Code to GitHub:

Create a GitHub repository and upload the code.

Write a clear README.md file with the following sections:





Bonus Enhancements (Optional):

Add a Toggle Button to switch between °C and °F.

Include a 5-Day Forecast if time permits.

Add a background image that changes based on weather conditions (e.g., sunny, rainy).


Expected Deliverables:

A working, deployed Weather Dashboard accessible via a web link.

Features: City search, real-time weather data (temperature, humidity, condition), error handling, and responsive design.

GitHub repository with source code and project documentation.


