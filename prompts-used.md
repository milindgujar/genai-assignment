# Prompts Used During GenAI Assignment

1. Project Setup
- "Using VS Code, I need to use GitHub Copilot extension to create a product application. The task is to use only GitHub Copilot and not any manual code. Can we do it? IF yes, I want you to generate the workspace and also provide me the file structure with pom file containing required dependencie"
- "The product application should use Java for backend services as for now, we are focusing on the backed part only. How to do it step-by-step, explain from folder creation to execution."
- "Give commands to create the folder and backend project structure using Java Spring Boot."

2. Backend Development (Spring Boot)
- "Create a backend-only product application using Spring Boot with JWT-based login, register, and role-based access."
- "I also want to Implement JWT Authentication in my Spring Boot app with login, register, and role-based access (user)."
- "Write the code for AuthController with /login and /register endpoints."
- "Create JwtService class to generate and validate JWT tokens."
- "Create MyUserDetailsService to load user by username from database."
- "Provide User and Role model classes using Spring JPA."
- "Add security configuration for Spring Boot with stateless JWT-based access."

3. Testing with Postman
- "Now as we are done with coding, tell me how to test login and register JWT APIs using Postman?"
- "Why am I getting 403 Forbidden even after sending correct token in Postman?"
- "This is my token — why is it not accepted in the Authorization header?"

4. Bug Fixes
- "Why am I getting a StackOverflowError on login API in Spring Boot?"
- "Update my security config to fix infinite recursion and correct JWT filter registration."
- "Fix the login endpoint to correctly authenticate user credentials with password encoding."

5. SonarQube Integration
- "How to integrate SonarQube with my Spring Boot application using Maven?"
- "Give me step-by-step instructions to run SonarQube locally and analyze my project."