# API-studentManagementSystem

This is a RESTful API for managing student information. It allows you to add new students to the system and retrieve information about existing students.

# Technologies Used
This API is built using the following technologies:

1. Java
2. Spring Boot
3. Maven

# API Endpoints
<strong>POST /addStudent</strong>
This endpoint allows you to add a new student to the system.

<strong>Request Body</strong>
The request body should be a JSON object with the following properties:
<ul>
<li>rollNo (integer): The roll number of the student</li>
<li>name (string): The name of the student</li>
<li>mobileNumer (string): The mobile number of the student</li>
<li>age(integer): The age of the student</li>
</ul>

<strong>GET /getStudentInfo</strong>
This endpoint allows you to retrieve information about a student.

Query Parameters
The following query parameter is required:

<strong>rollNo (integer)</strong>: The roll number of the student you want to retrieve information for

# Running the API Locally
To run this API locally, you will need to have Java and Maven installed on your system. Follow these steps:

1. Clone this repository to your local machine
2. Navigate to the project directory
3. Run the command mvn spring-boot:run
4. The API will be accessible at http://localhost:8080

# Contributing
If you find any issues or have suggestions for improving this API, feel free to open an issue or submit a pull request.
