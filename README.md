
# SNHU - CS465 Full Stack MEAN Travlr Application

### Architecture
* Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
During the development of the Travlr Full Stack application, front end technologies involved creating views using handlebars which includes html with css using embedded handlebars code.
Next we used Angular which involves the creation of views using components. Each component when generated includes a css file, html file, and a typescript file. The html file is for generating the basic content
on the page, the css is for styling the page (along with bootstrap using classes), and typescript files are used for generating the actions or interactions with data on the web page component.
* Why did the backend use a NoSQL MongoDB database?
The backend used a NoSQL MongoDB database since the data was variable and didn't require structured tables, allowing for the data to be variable and efficient when querying.
This allows for our data to be formatted as JSON and allows for our data to dynamic and also non-formatted or structured in tables such as an SQL database.
The data also scales horizontally which allows for a significant amount of data to be stored and changed on the fly, versus a table which would require migrating the database and each individual table.

### Functionality
* How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
Javascript Object Notation (JSON) is a data format which allows for the structure to be wrapped in dictionaries or objects, which allows for easy translation of associations between data.
Javascript is a programming language, which although utilizes object oriented principles is primarily used for defining functions or behavior and interactions.
JSON ties the frontend with the backend by translating the NoSQL data (MongoDB data) into a Javascript Object.
* Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
An instance of refactoring the code involved implementing and improving the authentication of the application for users and limiting the content using JWT (Json web tokens) which authorize and identify a user.
The benefits here are that a user must be signed in, in order to view content on the website. This allows for the ability to create various types of users including permissions.

### Testing
* Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
Methods of testing involved hitting the created API using (GET/POST/PATCH/DELETE) calls and verifying that the request was being recieved with a 200 status code.
This meant that our API endpoints were valid and that the data operations were successful. It was also incredibly useful for testing the authentication aspect of the application since
we could easily enter the JWT token and make the same HTTP requests, acknowledging and verifying that our authentication does in fact work.
It was also incredibly useful to use the Web Browser debugger and console, since this is where errors and logs are displayed.

### Reflection
How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
This course has helped me grow exponentially in terms of my skills with frontend and backend, it was especially helpful to get the full range of experiences with both the server side (having an administrative aspect)
as well as creating a separate UI with Angular for the client side (separation of concerns).
