# CS-465-Full-Stack-Development-I



Architecture

•	Compare and contrast the types of front-end development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
	 	 o While developing the front-end portion of our project we developed in several stages. We first started in Express HTML. With Express HTML there was a lot of reloading, and because of 	 
    that, it caused slow load times for users. Handlebars or (hbs) were implemented to eliminate loading all of the components repeatedly. JavaScript allows for the implementation of both front and backend communication, considering HTML never provided the backend interactions and only the frontend. The single-page application or (SPA) allowed the user to fully load in one page from the MongoDB database and respond to user interactions as necessary without refreshing the entire page. 

   
•	Why did the backend use a NoSQL MongoDB database?

  o  Using NoSQL MongoDB database allowed us to utilize the previous implementation of NodeJS, as well as reading in JSON files. Additionally, it allows for the ability for future development as it is easily scalable and adaptable, making it a great choice for our project.
   



Functionality

•	How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces? 

 o	JSON allowed us to store data effectively for it to be retrieved to formatted into a Javascript object to be used within Javascript when connecting the frontend with the backend 
    	development. Because of this Javascript conversion, the ability to pull information requested from the front-end to the backend is relatively easy and expandable.

    
•	Provide instances in the full stack process when you refactored code to improve functionality and efficiencies and name the benefits that come from reusable user interface (UI) components.

  o One of the instances that sticks out to me the most is the implementation of the hbs and SPA. When we first started working on this project, we worked with Express HTML, and the load time 
   	was longer and every time the user interacted with the page, the whole page reloaded. Creating the hbs aspect of the program allowed for faster reload times and the SPA allowed for only 
   	certain components to be reloaded based upon user input. This improved user experience by eliminating multiple lengthy reload times with every interaction.


   

Testing

•	Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full-stack application.

   o	Utilizing MongoDBCompass allowed us to manually input data into our database to test and retrieve it from the client side. Additionally, it allowed us to delete portions as well as visually 
   see new portions being created using different API endpoints. We also used Postman which I must admit made testing a lot easier and is a great tool to use. With Postman, we were able to 
   register logins using the POST method. We were then able to log in and see trips using a token that was created when successfully logging in. We passed in that unique token identifier when 
   calling the POST method for trips and adding a new trip for that specific user. We could also use the GET method to get all the trips for that user and confirm what we just added was 
   reflected. It was a way to test all the API endpoints as well as the implementation of our database and the security layers with the added token implementation. 

   



Reflection

•	How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

   o	This was my first experience working with full-stack development. It was a lot of information and moving parts, but I really enjoyed how we made a basic webpage much more efficient, and 
   into an SPA. I had no idea how many different components would go into creating a webpage. Having the knowledge this course has brought to me allows me to better understand how webpages are 
   developed and what it takes to have a fully working frontend, and backend as well as a database, and each of the exchanges that take place between each of them. 


