# JSON-RPC Gateway

Built ground up for cloud-ready (micro)services atop [Krakend](https://github.com/devopsfaith/krakend) for performance and reliability, [JSON-RPC](https://www.jsonrpc.org/specification) Gateway is a gateway service for orchestrating an infinite number of services that communicate over [JSON-RPC](https://www.jsonrpc.org/specification) - a very simple cross-language, multi-transport, RPC protocol.

## Features 

- Can proxy JSON-RPC messages between multiple transports (Websocket, message broker, etc)
- Granular JSON-RPC routing (Method, Request, Response, etc)
- Service Discovery
- [Open Tracing](https://opentracing.io/) Support
- Versioning of all configuration for quick-n-easy rollback
- Automatic SSL certificate procurement
- Plugin API for extension (Rate Limiting, Cors, Auth, etc)
- Highly-available
- Open-source management dashboard
