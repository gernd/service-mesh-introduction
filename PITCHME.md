### Service Mesh Introduction
![Logo](jambit_logo.png)
---
## Basic idea
Separation of 
@ul
- business logic of a service (e.g. computation of results, integration logic)
- network logic (inter-service communication via http, resilience patterns, service discovery …)
@ulend
---
### Service Mesh Definition
@ul
- inter-service communication infrastructure
- all service-to-service communication will take place on top of a „service mesh“ aka sidecar service
- mesh provides support for network functions like resiliency, service discovery, client-side load balancing, monitoring... etc
- service mesh proxies communication via protocols like HTTP or gRPC -> language agnostic
@ulend
---
### Pros
@ul
- reusable commodity features
- solves most of the problems in the microservice world
- more freedom for choosing a technology as functionality is already and no library has to exist for the chosen technology
@ulend
---
### Cons
@ul
- added complexitiy: service mesh dramatically increases the number of used instances
- every service call has to go through the sidecar proxy
- only a subset of intraservice communication problems are solved (e.g. not transformation/type mapping, integration with other services and systems …)
- service meshes are quite immature
@ulend
---
## Sources 
- https://medium.com/microservices-in-practice/service-mesh-for-microservices-2953109a3c9a
--- 
## Thanks for discussing!
- https://www.github.com/gernd/service-mesh-introduction
