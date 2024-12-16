-------------FLATDANGO-------------
Flatdangi is an interactive and dynamic movie website. It is a movie-ticket booking application built using HTML, CSS and Javascript.
It allows users to browse a list of movies , view detailed information for each movie- such as runtime, showtime, description and the available tickets.
It allows allows users to buy tickets.
Also, users can delete movies from the list if desired, making the app simple yet powerful.
Flatdango is designed to communicate with the backend server that is powered by JSON SERVER.
JSON SERVER serves the movie data and processes updates, such as reducing ticket availability or removing movies from the server.

The application fetches all movie data from the backend API on page load and dynamically renders the list of films.
 Clicking on a movie highlights it, displaying its poster and relevant details, while a "Buy Ticket" button allows users to purchase tickets. 
 Upon purchase, the available tickets count decreases both in the UI and on the server. I
 If a movie is no longer needed, a "Delete" button enables its removal from the list, with changes immediately reflected on the backend.


The project is lightweight, responsive, and showcases core web development skills, including DOM manipulation, 
event handling, and server-side communication using fetch API methods like GET, PATCH, and DELETE. 
To run the project locally, users need to set up a JSON Server and include sample movie data in a db.json file. 
The server runs on http://localhost:3000/films and seamlessly integrates with the front end for a smooth user experience. 
Flatdango highlights the balance between design and functionality, 
offering a clean interface that enhances usability while maintaining scalability for future features like search filters or user authentication.


This project demonstrates the use of modern front-end development techniques and is an excellent resource for learning about interactive web applications. 
