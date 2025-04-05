Calculator web app which was dockerized

The current project Dockerises a Node.js calculator microservice which we developed in the last task. 
The service has 4 mathamatical operations: addition, subtraction, multiplication, and division.

The software used here involves-Docker desktop,node.js,visual studio and git

In order to access the driectory we clone the repo with the commands
git clone https://github.com/Zappymanwho/sit323-2025-prac5p.git
cd sit323-2025-prac5p

You may use the current dockerfile app
In the terminal for the project folder
docker build -t calculator-app .
To run the image we use the command:
docker-compose up

To run calculator functions on the application
Addition
http://localhost:3060/add?num1=10&num2=5
Subtraction
http://localhost:3060/subtract?num1=15&num2=5
Multiplication
http://localhost:3060/multiply?num1=4&num2=5
Division
http://localhost:3060/divide?num1=20&num2=4

