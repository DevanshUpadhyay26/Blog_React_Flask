## Objective
Create a basic blog application with a list view and a detail view for blog posts, and deploy it to a cloud platform. This task will assess your skills in frontend development, backend development, database management, and deployment.
#### Add-ons 
Implement user authentication
Add a comment system for blog posts
Implement a search functionality
## Backend: Flask
Login: 
User: 1. Admin(Can do anything to a normal user’s post, also can delete a user from db, and delete a post, comment also.) 
2. Normal – Create(POST method), Read(GET method), Comment(PUT method), UPDATE blog Posts(PUT Method)
Search Functionality: Parse The Post Title and display that post. (Optional)
Post Form: Title, Short Description, Long Description, Comment Set up a RESTful API with the following endpoints:
#### API Endpoints
GET/posts [list all posts]
GET /posts/:id [get a specific post]
POST /posts [create a new post]
PUT /posts/:id [update a post]
DELETE /posts/:id [delete a post]
#### Database Implementation
Implement a simple database model for blog posts using any SQL or NoSQL database
SQLAlchemy OR SQLite
Implement basic error handling and input validation
## Frontend: React
Create a responsive layout with
Header,
Content Area,
Footer
Implement a list view of blog posts,
Title,
excerpt
detailed view for individual blog posts
Form for new blogs
Client side form validation (Login, Blog Post)
## Full Stack Integration
Connect the frontend to the backend API
Implement proper error handling and loading states
Use appropriate state management techniques
## Deployment
Deploy the full stack application to a cloud platform (e.g., Render, Fly.io, Heroku)
Ensure the deployed application is fully functional
Provide clear documentation on how to access and use the deployed application