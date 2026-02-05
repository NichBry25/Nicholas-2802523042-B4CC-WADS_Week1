# Nicholas-2802523042-B4CC-WADS_Week1

Hello. My name is Nicholas Bryan (2802523042) from B4CC.

# The Trade-Off: Microservices Are Not “Free”

There are some things most people don't pay attention to.
Microservices introduce:
- Network latency
- Distributed system complexity
- Data consistency challenges
- Service discovery and routing needs
- Monitoring and observability requirements

You are trading internal complexity (inside one codebase) for distributed complexity (across many systems). If you don’t have proper infrastructure — containerization (Docker), orchestration (Kubernetes), API gateways, logging systems — microservices can become chaotic. In fact, many startups adopt microservices too early and regret it.

# When Should You Use Microservices?

Microservices make sense when:
- Your system is large and growing
- Multiple teams are working independently
- You require high scalability and resilience
- Different domains evolve at different speeds

They are usually unnecessary when:
- Your app is small
- Your team is small
- Your scaling needs are minimal

A well-designed monolith is often the best starting point. Many successful companies began with monoliths and gradually evolved into microservices as needed.