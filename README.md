# Book-Management-App

Library-managment-app
Library managment application with spring boot.

Getting Started
Tomcat server is configured in port 8082.
CorsFilter is used to get rid of CORS error we get while connecting to different server in localhost, here it is from Express server (4200 port) to Tomcat server (8082 port).
Right clik LibraryMgmntApplication.java and start as Java application.

Built With
Maven - Dependency Management
Spring Boot - Stand-alone spring applications
Spring Data JPA - Spring implementation for Data access layer

---------------------------------------------------------------------------------------------------------

LibraryManagementApp - Angular
This project was generated with Angular CLI version 7.3.5.

Development server
Run ng serve for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files. I've used proxy.conf.js to connect to Tomcat server running at 8082 port from express server.

Build
Run ng build to build the project. The build artifacts will be stored in the dist/ directory. Use the --prod flag for a production build.

Further help
To get more help on the Angular CLI use ng help or go check out the Angular CLI README.
