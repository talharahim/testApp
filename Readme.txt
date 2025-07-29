---Prerequisites---
System Requirements:
Node.js v14+
npm v6+
Java JDK 11+
Maven 3.x
Chrome browser
ChromeDriver (in system PATH or managed with WebDriverManager)

exctract to to relevant location and follow these commands from powershell or command prompt in installation directory

1. Setup Instructions

Backend (Node.js)

cd backend
npm install
node index.js

Runs on http://localhost:5000


2. Frontend (React)
cd frontend
npm install
npm start



3. Copy Test Code in and Install Maven Dependencies
mvn clean compile

Make sure backend is running at http://localhost:5000 before executing.
Make sure frontend is running at http://localhost:3000 before executing.

4. UI Tests (Selenium)
mvn test -Dtest=TodoUITest

5. API Tests (REST-assured)

mvn test -Dtest=TodoApiTest






