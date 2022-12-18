# CS-465
## CS-465 Full Stack Development with MEAN

### Architecture
- Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
  - We used Express HTML to create dynamic webpages, used especially in our single page appliaction. Through our Express code, we could update HTML content to reflect changes in data.
- Why did the backend use a NoSQL MongoDB database?
  - MongoDB uses JavaScript, specifically JSON key/value pairs. This allows our application to run JavaScript nearly exclusively, cutting down on different systems involved in our application, and therefore cutting the workload of learning/developing/securing yet another technology.
### Functionality
- How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
  - JSON stands for JavaScript Object Notation, and is used to represent key/value pairs in a format usable by JavaScript. We use JSON objects to communicate between the front and back end, whether through the authentication process or trip retrieval.
- Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
  - At one point in the development process, we switch between a multi-page application to a single-page application. In doing this switch, we coded a loop in JavaScript to render each trip we had stored in the database as opposed to hard coding each trip in HTML. This not only saved time, but resulted in much less code thereby increasing readibility.
### Testing
- Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
  - API endpoints are how our front end communicate with the back end. These endpoints process methods (whether putting new trips into the database, getting trip information, posting updates to existing trips, etc) that do an action on our database. In these endpoints, and the methods they use, we use authentication to ensure that each call to the endpoints is done by the proper user. In regards to testing the functionality of these aspects of the system, I used the Postman API testing system to make sure each API endpoint was functional and secure.
### Reflection
- How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
  - I have learned an incredible amount about web development, especially as it relates to the communication between front and back end systems. While I may not use the MEAN stack exclusively in my career, learning about this stack has undoubtedly helped my general understanding of web applications and I'll be able to carry this knowledge further.
