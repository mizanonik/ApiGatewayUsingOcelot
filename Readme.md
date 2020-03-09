## Api Gateway using Ocelot

### What is api gateway

Api Gateway is the entrypoint of the complete system. It sits in front of the application, receives request from client application and redirects to corresponding api endpoint.

### Why api gateway

Microservice architecture is getting widely accepted day by day. With the use of this architecture api gateway is getting more important. In microservice architecture single service is used for single operation and finally we end up with huge number of services. For example in an e-comerce project we have diffrent services like Customer service, Order Service, Cart service, Payment service and so on. And we have to make call to these different services for out client applications, Which is not ideal. If we use api gateway our client api will make call only to the api gateway and api gateway redirect the call to the corresponding apis.

Another benifit of api gatway is we can secure our application using the gateway. whenever client application makes a call to api gateway it will check id the user is 