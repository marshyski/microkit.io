# Golang Kits

Most of the resources on this page are a list of top golang kits.  In the curated lists you'll find common packages used to form a  minimum skeleton of a microservice project in golang.  You'll find common packages for configurations, logging, serialization, http and other related service oriented architectures.

### Golang Microservices Kits

**\*\*** - Most popular

**$$** - Enterprise friendly

[**ardanlabs/kit**](https://github.com/ardanlabs/kit) - Set of common packages used by all or most projects at ArdanLabs

* **cfg** - Package cfg provides configuration options that are loaded from the environment. Configuration is then stored in memory and can be retrieved by its proper type.
* **log** - Package log provides a simple layer above the standard library logging package. The base API provides two logging levels, DEV and USER.
* **mapstructure** - Package mapstructure is a Go library for decoding generic map values to structures and vice versa, while providing helpful error handling.
* **pool** - Package pool manages a pool of routines to perform work. It does so my providing a Do function that will block when the pool is busy.
* **runner** - Package runner provide support for writing tasks that must complete within a certain duration or they must be killed. It also provides support for notifying the task the shutdown using a C.
* **tcp** - Package tcp provides the boilerplate code for working with TCP based data. The package allows you to establish a TCP listener that can accept client connections on a specified IP address and port.
* **timezone** - Package timezone provides two ways to retrieve the timezone for any latitude, longitude position.
* **udp** - Package udp provides the boilerplate code for working with UDP based data. The package allows you to establish a UDP listener that can accept data on a specified IP address and port.
* **web** - Package web provides a thin layer of support for writing web services. It integrates with the ardanlabs kit repo to provide support for routing and application context.

\*\* [**go-kit/kit**](https://github.com/go-kit/kit) - A standard library for microservices. [https://godoc.org/github.com/go-kit/kit](https://godoc.org/github.com/go-kit/kit)

* **auth/jwt** - Package provides a set of interfaces for service authorization through JSON Web Tokens.
* **circuitbreaker** - Package circuit-breaker implements the circuit breaker pattern.
* **endpoint** - Package endpoint defines an abstraction for RPCs.
* **log** - Package log provides a structured logger.
* **metrics** - Package metrics provides a framework for application instrumentation.
* **ratelimit** - Package provides a rate limiter middleware based on a token-bucket algorithm.
* **sd** - Package sd provides utilities related to service discovery.
* **tracing **- Package tracing provides helpers and bindings for distributed tracing.
* **transport** - Package transport contains bindings to concrete transports.
* **util/conn** - Package conn provides utilities related to connections.

$$ [**go-ozzo**](https://github.com/go-ozzo) - Ozzo is a framework consisting of fully decoupled packages supporting rapid Web application development

* **ozzo-config** - Package supporting layered application configuration in popular formats, such as JSON, YAML, TOML.
* **ozzo-dbx** - Package that enhances the standard database/sql package by providing powerful data retrieval methods as well as DB-agnostic query building capabilities.
* **ozzo-di** - Package implementing a dependency injection container.
* **ozzo-log** - Package providing high-performance asynchronous logging, message filtering by severity and category, and multiple message targets.
* **ozzo-routing** - An extremely fast HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.
* **ozzo-validation** - Package that supports data validation with configurable and extensible validation rules in usual code constructs instead of mysterious and error-prone struct tags.

[**goadesign/goa**](https://github.com/goadesign/goa) - Design-based APIs and microservices in Go [http://godoc.org/github.com/goadesign/goa](http://godoc.org/github.com/goadesign/goa)

* **client** - Package to build API clients
* **cors** - Package cors provides the means for implementing the server side of CORS
* **design** - Package design defines types which describe the data types used by action controllers.
* **encoding** - Package encoding provide goa adapters to many different encoders.
* **goagen** - Package codegen contains common code used by all code generators.
* **logging**    - Package logging contains logger adapters that make it possible for goa to log messages to various logger backends.
* **middleware** - Middlewares for gzip, basic auth, JWT and X-Ray.

[**gorilla**](http://www.gorillatoolkit.org/) - Gorilla is a web toolkit [https://github.com/gorilla/](https://github.com/gorilla/)

* **context** - Package context stores values shared during a request lifetime.
* **csrf** - Package csrf \(gorilla/csrf\) provides Cross Site Request Forgery \(CSRF\) prevention middleware for Go web applications & services.
* **css/scanner** - Package gorilla/css/scanner generates tokens for a CSS3 input.
* **feeds** - Syndication \(feed\) generator library for golang.
* **handlers** - Package handlers is a collection of handlers \(aka "HTTP middleware"\) for use with Go's net/http package \(or any framework supporting http.Handler\).
* **http** - Package gorilla/http is a high level HTTP client.
* **mux** - Package mux implements a request router and dispatcher.
* **pat** - Package gorilla/pat is a request router and dispatcher with a pat-like interface.
* **reverse**    - Package gorilla/reverse is a set of utilities to create request routers.
* **rpc** - Package gorilla/rpc is a foundation for RPC over HTTP services, providing access to the exported methods of an object through HTTP requests.
* **schema** - Package gorilla/schema fills a struct with form values.
* **securecookie** - Package securecookie encodes and decodes authenticated and optionally encrypted cookie values.
* **sessions** - Package sessions provides cookie and filesystem sessions and infrastructure for custom session backends.
* **websocket** - Package websocket implements the WebSocket protocol defined in RFC 6455.

[**koding/kite**](https://github.com/koding/kite) - Micro-service framework in Go [https://godoc.org/github.com/koding/kite](https://godoc.org/github.com/koding/kite)

* **config** - Package config contains a Config struct for kites.
* **dnode** - Package dnode implements a dnode scrubber.
* **kitectl**    - Command line tool for using kite services.
* **kitekey**    - Package kitekey provides method for reading and writing kite.key file.
* **kontrol**    - Package kontrol provides an implementation for the name service kite.
* **protocol** - Package protocol defines the communication between the components of the Kite infrastructure.
* **reverseproxy** - Package provides a reverse proxy for third party kites to register themself to proxy-kite.
* **systeminfo** - Package systeminfo provides a way of getting memory usage, disk usage and various information about the host.
* **tunnelproxy** - Package tunnelproxy implements a reverse-proxy for kites behind firewall or NAT.

[**micro/micro**](https://github.com/micro/micro) - A microservice toolkit for distributed systems development [https://micro.mu/docs/](https://micro.mu/docs/)

* **api** - Package api is an API Gateway.
* **bot** - Package bot is a Hubot style bot that sits a microservice environment.
* **car** - Package car is a language agnostic rpc proxy.
* **cli** - Package cli is a command line interface.
* **new** - Package new generates micro service templates.
* **run** - Package run is a micro service runtime.
* **web** - Package web is a web dashboard and reverse proxy for micro web apps.

[**nytimes/gizmo**](https://github.com/nytimes/gizmo) - A Microservice Toolkit from The New York Times [https://godoc.org/github.com/NYTimes/gizmo](https://godoc.org/github.com/NYTimes/gizmo)

* **config** - Package config contains a handful of useful functions to load to configuration structs from JSON files, JSON blobs in Consul k/v or environment variables.
* **pubsub** - Package pubsub contains two generic interfaces for publishing data to queues and subscribing and consuming data from those queues.
* **server** - Package server is the bulk of the toolkit and relies on \`server.Config\` for any managing \`Server\` implementations.
* **web** - Package web contains a handful of very useful functions for parsing types from request queries and payloads.

### Additional Libraries

[Shopify/sarama](https://github.com/Shopify/sarama) - Sarama is a Go library for Apache Kafka

[capitalone/fpe](https://github.com/capitalone/fpe) - A format-preserving encryption implementation in Go

[chrislusf/gleam](https://github.com/chrislusf/gleam) - Fast, efficient, and scalable distributed map/reduce system, DAG execution, in memory or on disk, written in pure Go, runs standalone or distributedly

[crosbymichael/skydock](https://github.com/crosbymichael/skydock) - Service discovery via DNS for docker

[dropbox/godropbox ](https://github.com/dropbox/godropbox)- Common libraries for writing Go services/applications

[edsrzf/mmap-go](https://github.com/edsrzf/mmap-go) - A portable mmap package for Go

[emirpasic/gods](https://github.com/emirpasic/gods) - GoDS \(Go Data Structures\). Containers \(Sets, Lists, Stacks, Maps, Trees\), Sets \(HashSet, TreeSet\), Lists \(ArrayList, SinglyLinkedList, DoublyLinkedList\), Stacks \(LinkedListStack, ArrayStack\), Maps \(HashMap, TreeMap, HashBidiMap, TreeBidiMap\), Trees \(RedBlackTree, AVLTree, BTree, BinaryHeap\), Comparators, Iterators, Enumerables, Sort, JSON

[facebookgo/grace](https://github.com/facebookgo/grace) - Graceful restart & zero downtime deploy for Go servers

[facebookgo/inmem](https://github.com/facebookgo/inmem) - Package inmem provides an in memory LRU cache with TTL support

[jonbodner/proteus](https://github.com/jonbodner/proteus) - A simple tool for generating an application's data access layer

[kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - Golang library for managing configuration data from environment variables

[miekg/dns](https://github.com/miekg/dns) - DNS library in Go

[travisjeffery/jocko](https://github.com/travisjeffery/jocko) - Kafka implemented in Golang with built-in coordination \(No ZK dep, single binary install\)

[uber/jaeger](https://github.com/uber/jaeger) - Jaeger, a Distributed Tracing System



