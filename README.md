# RABBITMQ + JAVASCRIPT

Simple use example used msg broker in this case RabbitMQ

## Prerequisites
- docker
- node
- npm


Install docker rabbitmq
```
docker run -d -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management
```

## Execute
**Send message**
```
npm run start:send
```

**Receive message**
```
npm run start:receive
```