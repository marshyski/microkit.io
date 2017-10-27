# What Is Microservices

> Microservices is a variant of the service-oriented architecture \(SOA\) architectural style that structures an application as a collection of loosely coupled services. In a microservices architecture, services should be fine-grained and the protocols should be lightweight. The benefit of decomposing an application into different smaller services is that it improves modularity and makes the application easier to understand, develop and test. It also parallelizes development by enabling small autonomous teams to develop, deploy and scale their respective services independently. It also allows the architecture of an individual service to emerge through continuous refactoring.  Microservices-based architectures enable continuous delivery and deployment.
>
> [https://en.wikipedia.org/wiki/Microservices](https://en.wikipedia.org/wiki/Microservices)



Microservices have different design patterns based on the workloads and needs of business capabilities.  Those patterns are as followed:

**Ambassador** - a smart proxy to offload common client connectivity tasks such as routing, generating tracing-ID and authentication in a language agnostic way.

**Anti-corruption layer** - implements a modern interface between new and legacy applications, to ensure that the design of a new application is not limited by goo and dependencies of an legacy systems.

**Backends for Frontends** - Separate backend services for different types of clients or customer segments. That way, a single backend service doesn’t need to handle all data formats from a data source, or conflicting requirements of various client types. This pattern can help keep each services simple, by minimizing maintenance on the frontends.

**Bulkhead** - isolates critical resources, such as connection pool, memory, and CPU, for each workload or service. By using bulkheads, a single workload \(or service\) can’t consume all of the resources, starving others. This pattern increases the resiliency of the system by preventing cascading failures caused by one service.

**Gateway Aggregation** - aggregates requests to multiple individual microservices into a single request, reducing chattiness between consumers and services.

**Gateway Offloading** - enables each microservice to offload shared service functionality, such as the use of SSL certificates, to an API gateway.

**Gateway Routing** - routes requests to multiple microservices using a single endpoint, so that consumers don't need to manage many separate endpoints.

**Sidecar** - deploys helper components of an application as a separate container or process to provide isolation and encapsulation.

**Strangler **- supports incremental migration by gradually replacing specific pieces of functionality with new services.





