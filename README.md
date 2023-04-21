# CS465
Full Stack Development I

*Architecture*

    Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page  application (SPA).
    Why did the backend use a NoSQL MongoDB database?
    
    The majority of the visual development on this project was utilizing HTML. That gave a good foundation to the customer side of the application, with each new page containing a new HTML reference file. From there, the view was morphed into Handlebars via Express, and given functionality via JavaScript through an Angular framework. Finally, the SPA was created to handle the administrative functions for the site (adding, editing, removing trips, etc.) A NoSQL MongoDB database was used for a backend database because of its speed and its ability to scale to larger projects easier. Using MongoDB Compass was an intuitive way to view the database, its collections, and its elements in a neat way. 
    
    Because of the use of MongoDB, Express, Angular and Node, the stack for this application is referred to as a MEAN stack.
    
 *Functionality*

    How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
    Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
    
    JSON is majorly different from JavaScript in that it handles data as a key name/value pair. This was a fantastic way to handle the data from the trips and the logins via the SPA. This format made it easier to edit values that were placed in a "pretty" format by changing the value associated to the name of the key. This was done for one of my trips where I changed the price of the trip via the JSON data format. Because you're not changing code like you would with JavaScript, it makes it incredibly easy to change the value of something without affecting any UI components.
    
 *Testing*

    Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
    
    This was an area that I ended up struggling with the most on this project, specifically with the API endpoints. I understand the basic concept of the routes and endpoints, as well as the methods to perform actions, but using a new program to test these (I used Postman), made it a little difficult to master these concepts. The program is very intuitive and easy to use, but it's still something I'm not used to using. It was nice being able to obtain tokens via Postman to use in my browser when testing login/logout functions.
    
 *Reflection*

    How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
    
    While I certainly haven't mastered any of the skills I've learned in this MEAN stack, I feel like I have a much better grasp on the big scope of a project and how it all comes together. I think this provides a great perspective on how each part of the project needs to handle everything and come together. Because I struggled at times getting the application to function correctly on all ends, I definitely learned to push through the struggle and put together something that works mostly well, giving me additional confidence for my next project!


