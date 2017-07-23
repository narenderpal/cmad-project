# CMAD Advanced Project

## A Question & Answers application (similar to StackOverflow) 

The minimally viable feature set include:

1. Ability to register and login
2. View a list of questions
3. Ask a question
4. View a specific question along with answer
5. Submit answers to questions
6. Ability to search for questions

### Application UI (SPA) built on React, Redux - 
http://35.184.123.212/#/

### Technology Stack
![Tech stack](/docs/screenshots/tech_stack.png)

### Architecture Diagram
![Arch diag](/docs/screenshots/arch_diag.png)

### Google Cloud VM Instances View
![gc_vm_instances diag](/docs/screenshots/gc_vm_instances.png)

### Google Cloud Build Triggers
![gc_build_triggers diag](/docs/screenshots/gc_build_triggers.png)

### REST API Details
https://app.swaggerhub.com/apis/narenderpal/cmad-app/1.2.0

### UI Service -
https://github.com/narenderpal/cmad-ui-app
UI-Service is the single page user interface application and the frontend door. Built on ReactJS , Redux, CSS, HTML, jQuery and using tools like Babel, Webpack.

### User Microservice - 
https://github.com/narenderpal/user-service
User-Service provides the user registration, authentication and authorisation. Implemented using Vert.x Java. Uses MongoDB as persistence store. JWT Auth for generating access token for user authentication. 

### Question Microservice - 
https://github.com/narenderpal/question-service
Question-service provides the functionality to view/post  questions/answers/comments. Implemented using Vert.x java. Used MongoDB as persistence store. 

### API Gateway Microservice - 
https://github.com/narenderpal/api-gateway
UI-Service is the single page user interface application (SPA) built on ReactJS , Redux, CSS, HTML, jQuery.



 
