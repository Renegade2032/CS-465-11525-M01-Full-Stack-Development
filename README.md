CS 465 Full Stack Project
Architecture
Compare and contrast the frontend development you used, including Express HTML, JavaScript, and the SPA.
During this project I worked with Express HTML, JavaScript, and a single-page application (SPA). Express HTML was mainly used to create pages that were rendered by the server. JavaScript made the application interactive and handled things like user input and requests to the backend. The SPA allowed the application to update information without reloading the entire page, which made it faster and provided a better user experience.
Why did the backend use a NoSQL MongoDB database?
MongoDB was a good choice because it stores data as JSON-like documents. Since the application sends and receives JSON, it makes it easy for the frontend and backend to work together. MongoDB is also flexible because the data structure can change without needing to redesign the entire database.

Functionality
How is JSON different from JavaScript, and how does JSON tie together the frontend and backend?
JSON is a format for storing and transferring data, while JavaScript is a programming language. The frontend sends requests using JSON, and the backend responds with JSON data. This allows both sides of the application to communicate and exchange information.
Provide examples of refactoring and explain the benefits of reusable UI components.
As I worked through the project, I cleaned up code by reusing functions instead of writing the same code multiple times. I also reused UI components where possible instead of creating new ones for every page. This made the project easier to maintain, reduced duplicate code, and made future updates much easier.

Testing
Explain your understanding of methods, endpoints, and security in a full stack application.
API methods such as GET, POST, PUT, and DELETE are used to retrieve, create, update, and remove data. Endpoints are the URLs where those requests are sent. During this project I learned that testing these endpoints is important to make sure they return the correct information and handle errors properly. After adding authentication, testing became more important because protected endpoints should only be accessible after a user successfully logs in.

Reflection
How has this course helped you reach your professional goals?
This course helped me better understand how a full stack web application works from beginning to end. Before this class I had only limited experience with secure coding. Now I have worked with Angular, Express, MongoDB, REST APIs, authentication, and secure login practices. These are all skills that will help me as I continue working toward a career in software development and systems analysis. I also learned how the frontend, backend, and database all work together, which gives me a much better understanding of how modern web applications are built.

