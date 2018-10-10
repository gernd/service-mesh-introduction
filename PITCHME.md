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
- network logic (inter-service communication via http, resilience patterns, service discovery …)
- mesh provides support for network functions like resiliency, service discovery, client-side load balancing, monitoring... etc
- service mesh proxies communication via protocols like HTTP or gRPC -> language agnostic
@ulend
---
## Sources 
- https://medium.com/microservices-in-practice/service-mesh-for-microservices-2953109a3c9a
--- 
## Thanks for discussing!
- https://www.github.com/gernd/service-mesh-introduction
