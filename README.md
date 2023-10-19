# CleverNewsTask
## Services
### Api-Gateway
```
API Gateway is a fully managed service for developers,
designed to create, publish, maintain, monitor and
ensure API security at any scale. Via Application API
access data, business logic, or functionality
your backend services. API Gateway allows you to create RESTful APIs and
WebSocket, which are the main component of applications for two-way
communications in real time. API Gateway Supports Workloads
in containers and serverless workloads, as well as web applications.

API Gateway takes care of all the tasks associated with receiving and processing hundreds of
thousands of concurrent API calls, including traffic management, CORS support,
authorization and access control, regulation of the number of requests, monitoring
and API versioning. Working with API Gateway does not require minimum payments
or start-up investment. You pay for API calls received and volume transferred
data and can use API Gateway's tiered pricing model
lower your costs as your API usage scales.

URL: http://localhost:8765
```

### Config Server
```
Spring Cloud Config is Spring's client/server approach for storing and serving 
distributed configurations across multiple applications and environments.

This configuration store is ideally versioned under Git version control and 
can be modified at application runtime. While it fits very well in Spring 
applications using all the supported configuration file formats together with 
constructs like Environment, PropertySource, or @Value, it can be used in any 
environment running any programming language.
Configs are stored in resources 'config' folder
```

### Exception-Service
```
This is a service that catches exceptions thrown in our application and 
view them in REST. It is not a microservice.
```

### Log-Service
```
This is a service that listens to all layers of the application and logs them 
using logback. It is not a microservice.
```

### News-Service
```
This is a microservice that performs CRUD operations with news and their comments.
Secured: CRD operations
URL: http://{api-gateway}/news
```

### Server
```
Eureka is the Netflix Service Discovery Server and Client. The server can be 
configured and deployed to be highly available, with each server replicating state about the registered services to the others.
```

### User-Service
```
This is a microservice that allows you to login, register, or validate a JWT Token.
URL: http://{api-gateway}/users
```

## Endpoints
About endpoints and api, you can introduce by running the application and following to link
```
http://{api-gateway}/{service}/swagger-ui.html
```
