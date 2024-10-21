# WorldWise 🌍

WorldWise is a React-based application designed for tracking places (cities and countries) visited around the world. It allows users to interact with a real-world map, place markers, and save notes about their experiences. With additional features like city management, Wikipedia integration, and a placeholder authentication system, this app serves as an excellent learning project for React Router and Context API.

## Features

- **Interactive World Map:** Powered by Leaflet, users can search for and explore cities and countries.
- **Place Markers:** Users can add markers to the places they've visited and save personal notes or opinions about each location.
- **City Management:** Create, update, and delete city entries. When adding a new city, users can also choose a date and year of their visit via a detailed form.
- **Wikipedia Integration:** Fetch additional information about cities from Wikipedia.
- **Authentication:** A basic placeholder for login and logout, with future plans for full authentication.
- **Responsive Design:** Optimized for different screen sizes.

![WorldWise 1](https://github.com/user-attachments/assets/7537d90c-12da-4f34-bb01-98117eeda5a1)
![WorldWise 2](https://github.com/user-attachments/assets/de694102-e219-4a57-aca1-d8505e044ec9)
![WorldWise 3](https://github.com/user-attachments/assets/c50f87a5-74f9-4627-9279-4123d23f6936)
![WorldWise 4](https://github.com/user-attachments/assets/b962aaa2-d3eb-4ab6-a37c-e5fd62c4566c)
![WorldWise 5](https://github.com/user-attachments/assets/e26ad95c-646a-4389-a8a1-419a9b47233b)
![WorldWise 6](https://github.com/user-attachments/assets/1a7663b1-f89d-436a-b05c-46721c14f09c)


## Technologies Used

- **React:** Frontend framework for building the UI and managing state.
- **React Router:** For managing navigation and routing within the application.
- **Vite:** Build tool for a fast and optimized development environment.
- **JSON-server:** Mock server for handling API requests and data persistence.
- **Leaflet:** Library for rendering and interacting with the map.
- **Context API:** For managing global application state.

## Installation

To run this project locally, follow these steps:
1. Clone the repository
   git clone https://github.com/yordan-gergov01/WorldWise.git
    cd WorldWise
2. Install dependencies
   npm install
3. Start the development server
   npx json-server --watch data/db.json --port 8000
4. Start JSON-server for backend data:
   npx json-server --watch data/db.json --port 8000
5. Open the application: Navigate to http://localhost:5173 in your browser.

## Usage

- **Login/Logout:** Use the authentication button in the top-right corner of the application to simulate a login/logout experience.
- **Mark a Location:** Click on any location on the map to mark it and add it to your list of visited places. You can also add a note about your experience and select the date of your visit.
- **City Details:** Fetch more information about each city directly from Wikipedia by clicking on the city name.
- **Manage Cities:** Add, update, or delete cities using the provided forms.



