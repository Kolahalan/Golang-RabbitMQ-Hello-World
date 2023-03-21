# RabbitMQ-Hello-World
A basic program with Go to understand and test RabbitMq pulled from docker hub

#### Use the following command to pull docker image from docker hub 
`docker run -d --hostname my-rabbit --name some-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management`

##### After the image is pulled, go the browser, visit http://localhost:15672 and login with username: `guest` , password: `guest` 

#### Within the terminal
`go run send.go`

`cd .\event\`

`go run receive.go`

