# Module 08 Reflection — High Level Networking

## 1. What is an API and why is it important?
An API (Application Programming Interface) is a set of rules and protocols that allows different software applications to communicate with each other. It is important because it enables integration between systems without exposing internal implementation details, making software more modular, scalable, and reusable.

---

## 2. What is REST API?
REST (Representational State Transfer) API is an architectural style for designing web services that use HTTP methods and treat data as resources identified by URIs. It emphasizes simplicity, scalability, and stateless communication between client and server.

---

## 3. Why is REST so popular?
REST is popular because it is simple to implement, easy to understand, lightweight, and works well with HTTP. It is also easy to test and integrate with different systems, making it widely adopted in modern web development.

---

## 4. Explain the REST architectural constraints.
REST has several constraints:
- Uniform Interface: Consistent way to interact with resources.
- Client-Server: Separation between client and server.
- Stateless: Each request contains all necessary information.
- Cacheable: Responses can be stored for reuse.
- Layered System: Architecture can have multiple layers.
- Code on Demand (optional): Server can send executable code.

---

## 5. What does stateless mean in REST?
Stateless means the server does not store any information about previous requests. Each request must contain all the data needed to process it, which improves scalability and reliability.

---

## 6. Explain HTTP methods used in REST.
- GET: Retrieve data
- POST: Create new data
- PUT: Update/replace existing data
- PATCH: Partially update data
- DELETE: Remove data

Each method defines a specific type of operation on resources.

---

## 7. What is JSON and why is it commonly used?
JSON (JavaScript Object Notation) is a lightweight data format used for data exchange. It is commonly used because it is easy to read, write, and parse, and is compatible with many programming languages.

---

## 8. What is gRPC?
gRPC is a high-performance communication framework developed by Google that allows client and server to communicate as if calling local functions. It uses Protocol Buffers and HTTP/2 for efficient data transfer.

---

## 9. Difference between REST and gRPC
- REST uses HTTP/1.1 and JSON, while gRPC uses HTTP/2 and Protocol Buffers.
- REST is human-readable and widely supported, while gRPC is faster and more efficient.
- gRPC supports streaming and better performance for microservices.
- REST is better for public APIs, while gRPC is often used for internal systems.

---

## 10. When should we use gRPC instead of REST?
gRPC should be used when:
- High performance and low latency are required
- Communication is between microservices
- Real-time streaming is needed
- Bandwidth efficiency is important

REST is still preferred when compatibility with browsers and simplicity are more important.