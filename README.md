# Nicholas-2802523042-B4CC-WADS_Week1

Hello. My name is Nicholas Bryan (2802523042) from B4CC.

# Web Development and Microservices: From Monoliths to Modular Systems

Modern web development is no longer just about building pages and connecting them to a database. It’s about designing systems that scale, evolve, and survive change. As applications grow in complexity — whether they’re e-commerce platforms, financial dashboards, or real-time analytics tools — architecture becomes as important as code.
This is where microservices enter the picture.

# The Evolution of Web Architecture

In the early days, most applications were built as monoliths: one codebase, one deployment, one tightly coupled system. Everything — authentication, payments, product catalog, notifications — lived inside the same application.
That approach works beautifully at small scale. It’s simple. It’s fast to build. It’s easy to deploy.

- But as the system grows, problems start appearing:
- Small changes require redeploying the entire app
- A bug in one feature can crash everything
- Scaling one component means scaling the entire system
- Development teams block each other

To solve these growing pains, engineers began splitting applications into smaller, independent services — each responsible for a single domain.

That’s microservices.

# What Are Microservices?

Microservices are an architectural style where an application is composed of small, independent services that communicate over a network (usually via HTTP or messaging systems).

Each service:
- Has its own codebase
- Owns its own database
- Can be deployed independently
- Focuses on a specific business capability
- For example, an online store might be divided into:
- User Service – authentication, profiles
- Product Service – inventory and catalog
- Order Service – checkout logic
- Payment Service – transaction processing
- Notification Service – email/SMS updates

Instead of one large application, you now have a collection of smaller systems working together.

# Why Microservices Became Popular

Microservices align well with how modern teams operate and how modern systems scale.
1. Independent Scaling
If your payment system experiences heavy load, you scale only that service — not the entire application.
This is cost-efficient and performance-oriented.

2. Faster Development Cycles
Different teams can work on different services simultaneously without stepping on each other’s toes.
Frontend team updating UI?
Backend team optimizing orders?
DevOps team improving deployment pipelines?

All can move independently.

3. Technology Flexibility
Each service can use the most suitable technology stack.
One service in Node.js
Another in Python
A high-performance component in Go
A legacy integration in Java

This flexibility is powerful — but it also increases complexity.