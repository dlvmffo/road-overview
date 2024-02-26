## About The Project

The application gives an overview of road conditions using GeoJSON data.

Features in the application:

- Road is colored based on eemi grades (1-1.49 = blue, 1.5-2.49 = light-green, 2.5-3.49 = dark-green, 3.5-4.49 = yellow, 4.5-5.00 = red)
- Options can be chosen in a dropdown to choose different evaluations and changes are reflected in the map
- Legend information is provided to have a quick overview of different grades on the road
- Hovering on the road gives an overview of the road conditions
- Road sections can be clicked to add details such as title, description, status and author
- Attributes comparison can be seen as a bar graph on the landing page
- Navbar provides access to different sections such as overview, statistics and todos
- Overview section gives a tabular overview of the road information and can be navigated via pagination for clean access to the large data source
- Statistic section extends the graphical overview on the landing page with a tabular representation of different metrics of the data such as min, max and total of different attributes
- Todos section gives an overview of the saved road information which can be deleted or edited as needed

### Built With

- [![React][React.js]][React-url]
- [![Leaflet][Leaflet.js]][Leaflet-url]
- Tailwind

## Getting Started

- Clone or Unzip the repository

- Run `docker-compose build --no-cache`in the root directory

- Run `docker-compose up` in the root directory to start the server and application

- Navigate to the directed port http://localhost:5174/ (server can be reached under http://localhost:3000/)

### Prerequisites

- docker

### (In case docker does not run the frontend)

- If there are problems running the frontend, please go to the individual folders
- Start with api folder and follow the instructions to get the server running. It can be reached under http://localhost:3000
- Then go to the edgital_road_overview folder and follow the instructions down below the section, Getting Started, to get the frontend running. It can be reached under http://localhost:5174

[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Leaflet.js]: https://img.shields.io/badge/Leaflet-fbfbfb?style=for-the-badge&logo=leaflet&logoColor=b8e365
[Leaflet-url]: https://leafletjs.com/
