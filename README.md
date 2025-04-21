# CS-465
Full Stack Web Application
**Architecture**: 

I implemented both traditional and multi-page approaches using Express with HTML templated and JavaScript, as well as modern single-page application (SPA) techniques in the development of this full stack application. The Express-based frontend served dynamic HTML content for the administrative interface, allowing for server-side rendering and secure data handling. In other hand, customer facing fronted utilized SPA principles, enabling smother user interactions and faster page loads through asynchronous data fetching and client-side rendering.
Talking about the backend, it was built using a NOSQLDB database, which offered flexibility in handling unstructured data and allowed for rapid iteration without the need to define a rigid schema upfront. It is useful for managing diverse user input and content, making it deal for a dynamic web application that needs to scale with evolving features.

**Functionality:**

JSON differs from JavaScript in that case it is a lightweighted data format designed for data interchange, not programming. JavaScript can manipulate data and control program flow, while JSON acts as the bridge between the frontend and backend. Where the frontend sent and received JSON data via HTTP requests and on the same hand the backend used Express and Node.js, parsed and responded with JSON to update the user interface dynamically.
In the process of development, I refactored several sections of code, particularly in the fronted components, to improve readability and efficiency. One major improvement involved abstracting from inputs and modals into resuable UI component. This is not only for reducing redundancy but also made the application easier to maintain and update. Reusable components also streamlined the debugging and testing process by isolating functionality and ensuring consistency across views.

**Testing:**

API testing plays a vital role in ensuring that the data request and retrieval endpoints function as expected. I used tools like Postman to test GET, POST, PUT, and DELETE methods, verifying correct responses and handling edge cases. Implementing secure admin login added another layer of complexity, requiring tests for authentication and session management. I ensured that protected routes were inaccessible without valid credentials and handled token-based authentication securely. Understanding RESTful endpoints and HTTP methods helped ensure reliable interaction between the frontend and backend, even with the added complexity of secure login protocols.

**Reflection:**

This course has significantly contributed to my professional development by providing a solid foundation in full stack web development. I have gained hands-on experience in building and securing a web application from start to finish. Skills such as setting up a Node.js backend, working with MongoDB, building a dynamic frontend, and implementing authentication have made me more confident and marketable as a developer. Additionally, learning how to communicate between components and layers of the application using APIs and JSON has given me practical knowledge applicable in real-world projects. This comprehensive experience will be a strong addition to my portfolio and resume, supporting my career aspirations in web development and software engineering.
