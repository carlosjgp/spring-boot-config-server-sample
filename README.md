# spring-boot-config-server-sample

## Git repository as backend

### Server embedded

#### Run auto-configured service

#### Update configuration





### Server / Client



#### Rest only

##### Run Server

##### Run Client

##### Update configuration



#### RabbitMq Beam

```
cd server-client-rabbitmq-beam
```

##### Run RabbitMq

```
docker run -d --hostname my-rabbit --name rabbitmq-config-server -e RABBITMQ_DEFAULT_USER=user -e RABBITMQ_DEFAULT_PASS=password -e RABBITMQ_ERLANG_COOKIE='carlosjgp.com' -p 5672:5672 -p 15672:15672 rabbitmq:3.6.9-management
```
##### Run Server

##### Run Client

##### Update configuration
