Project title: 

Bad Bank 

Description and motivation:

this application was built as a coding assignment. it helps students to guage how their coding knowledge is growing  as the course progresses. i personally chose to build this app because i found it to be a fun project. 

it is a banking application that tracks users account inforamtion and also keeps track of the amount of "money" they have in their account, and allows them to withdraw and deposit. (This app is not for production purposes at this moment)

installation guidelines:

GIT CLONE onto your local machine , open your terminal and run the following commands 

$ npm init -y
$ npm install 
check the dependencies for express and cors if not showing run following commands
$ npm install express
$ npm install cors

then for the docker container open docker on your local machine
run commands 
$ docker run -p 27017:279017 --name badbank -d mongo
//to make sure docker is running run following command
$docker ps
then run 
$ node index.js     you should get the following response  in your terminal 

Running on port: 3000
Connected successfully to db server
 
Navigate to     http://localhost:3000      in your browser 







https://user-images.githubusercontent.com/103603599/212222040-0f5472ef-0656-4695-8fa6-605438d8218b.mov


languages and technology used: Node, JS, HTML, CSS, cors, Express, MongoDB, docker



License: MIT
