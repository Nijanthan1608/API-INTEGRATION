# API-INTEGRATION

"COMPANY":CODTECH IT SOLUTION

"NAME":NIJANTHAN R

"INTERN ID":CTIS4548

"DOMAIN NAME":FULL STACK WEB DEVELOPMENT

"DURATION":4 WEEKS

"MENTOR":NEELA SANTHOSH

Project Description: Responsive Weather Webpage Using Public API
This project involves the development of a responsive web page that dynamically fetches and displays real-time weather information using a public Application Programming Interface (API). The primary objective of the project is to demonstrate the use of modern web technologies—HTML, CSS, and JavaScript—to retrieve external data asynchronously and present it in an interactive and user-friendly interface.
The web page allows users to search for current weather conditions by entering the name of a city. Upon submitting the city name, the application communicates with the Open-Meteo public API, which provides accurate and up-to-date meteorological data without requiring authentication or an API key. This makes the solution lightweight, accessible, and suitable for educational and demonstration purposes.
The application is implemented as a single-page web solution with all code merged into one HTML file. The structure of the page is defined using HTML, which organizes the content into logical sections such as the input area, search button, and weather display card. Cascading Style Sheets (CSS) are used to style the interface, ensuring visual clarity and responsiveness across different screen sizes, including mobile phones, tablets, and desktops. A modern layout, soft color gradients, and intuitive spacing enhance the overall user experience.
JavaScript is used to handle all dynamic functionality. When a user enters a city name and clicks the search button, the application first sends a request to the Open-Meteo geocoding service to convert the city name into geographical coordinates (latitude and longitude). These coordinates are required to accurately retrieve weather information. Once the coordinates are obtained, a second API request is made to fetch the current weather data, including temperature and wind speed.
The Fetch API is used to perform asynchronous network requests, ensuring that the page does not reload during data retrieval. Error handling mechanisms are implemented to manage invalid input, network issues, or cases where the entered city cannot be found. Informative messages are displayed to guide the user in such scenarios, improving usability and reliability.
The retrieved weather data is dynamically inserted into the webpage using Document Object Model (DOM) manipulation. This allows the weather information to update instantly based on user input. The weather display section remains hidden until valid data is successfully loaded, which helps maintain a clean and organized interface.
In conclusion, this project successfully demonstrates how a responsive web page can integrate a public API to display live data dynamically. It highlights key concepts such as API consumption, asynchronous JavaScript, responsive design, and user-centric interface development. The solution is scalable and can be easily extended to include additional features such as forecasts, icons, or location-based detection, making it a strong foundation for more advanced web applications.

**OUTPUT**
<img width="1151" height="653" alt="Image" src="https://github.com/user-attachments/assets/8fe95a2c-2631-43ce-bc2c-e4d5212cb36d" />
