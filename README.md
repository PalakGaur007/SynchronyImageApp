# SynchronyImageApp
This application is a Spring Boot REST API that allows users to register, and manage images using the Imgur API. 
## Features  
- User registration with basic information  
- Image upload, view, and delete functionality  
- OAuth2 security for API endpoints  
- In-memory H2 database for storing user information  
  
## Setup  
1. Clone the repository.  
2. Build the project using Maven: `mvn clean install`.  
3. Run the application: `mvn spring-boot:run`.  
  
## Testing  
Run the tests using: `mvn test`.  
  
## Imgur API Integration  
The application integrates with the Imgur API for image operations. Ensure you have the necessary API keys and configurations.  
  
## Security  
The API is secured using OAuth2. Configure your OAuth2 provider details in `application.properties`.  
 
