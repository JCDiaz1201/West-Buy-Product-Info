# West Buy: Product-Info Micro-Service

![alt text](https://scotch-res.cloudinary.com/image/upload/w_1050,q_auto:good,f_auto/v1540545426/tzs50mjrlopv85r3qjpq.jpg "MERN Stack Technologies Used")

### Concept
West Buy is a full stack e-commerce application built following a micro-service oriented architecture. Each service that makes the West Buy application is a stand alone full stack application complete with its own front end, back end, and database.

The Product-Info component was originally built with an React-Express-Node-MySQL stack and later made to work with both a Postgres, and MongoDb database. 

### Back End Optimization
When the component was made to work with both Postgres and MongoDb the back end was also optimized to handle hundreds more requests per second than its original production build as well as a significant reduction of max request latency. The application was deployed via AWS featuring auto-scaling groups that scale horizontally both at the application instance level and at the database level based on a pre-determined network traffic threshold. 

## How to use
- Run webpack live server with
    - npm start
- Build production bundle.js with
    - npm run build
