# CS-465

*Architecture*

In this full-stack project, I used many frontend development methods. One approach involved using Express with HTML templates and JavaScript. This approach facilitated server-rendered pages, where the server sends fully rendered HTML to the client on each request. This was suitable for smaller, less interactive pages due to it being straight forward.

In contrast, I also used a single-page application (SPA) powered by Angular. The Angular SPA rendered views on the client side, delivering a dynamic user experience. It updated content without needing full page reloads to enhance responsiveness. While Express handled page routing on the server, Angular managed routing on the client. This resulted in smoother transitions and a more interactive user experience.

The backend used a NoSQL MongoDB database. MongoDB offers flexibility in managing unstructured data, which is useful in full-stack development where requirements change. MongoDB’s document-based structure aligns well with JSON, creating seamless data transfer between the frontend and backend.

Functionality

JSON (JavaScript Object Notation) is a lightweight data format that is like JavaScript objects. While JavaScript is a programming language for adding dynamic behavior on web pages, JSON is utilized to structure and transmit data between the frontend and backend. In my project, JSON responses from the Express API were received by the Angular SPA, enabling seamless data exchange and updates.Throughout the full-stack development process, I revised code to optimize efficiency. 

Testing

In a full-stack application, methods correspond to HTTP verbs such as GET, POST, PUT, and DELETE, which are used for CRUD operations. These verbs are managed by endpoints, which are the API routes that execute these operations. Security layers, such as JWT authentication, introduce complexity during testing because valid tokens are necessary for testing protected routes.

To test API endpoints, I used tools like Postman for manual testing of requests and ensuring correct responses. Additionally, I used automated tests in Angular to verify the UI components’ proper interaction with the backend. Testing with authentication involved generating and incorporating tokens into requests to simulate authenticated user flows. This facilitated an understanding of how authorization influences data retrieval and validation in practical applications.

Reflection

This course has greatly advanced my professional objectives by strengthening my understanding of full-stack development workflows. I have acquired knowledge in designing backend APIs, constructing responsive frontend applications, and connecting NoSQL databases with Express. Furthermore, I have developed skills in effectively building RESTful APIs, constructing SPAs with Angular, structuring projects for maintainability, utilizing JSON for frontend-backend integration, and performing API testing with security considerations.

These skills enhance my marketability in the software development field. I can now confidently contribute to projects that need a comprehensive understanding of how frontend and backend systems communicate, testing and securing applications, and constructing scalable, reusable user interface components.
