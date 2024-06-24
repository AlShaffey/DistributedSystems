# DistributedSystems

Q/realistic-A bout distributed systems

## What is meant by "Distributed Systems"? 

### Chat GPT answer

Distributed systems are a collection of independent computers that appear to the users of the system as a single coherent system. These systems are designed to share resources and data among multiple machines to achieve common goals, improve performance, reliability, scalability, and flexibility.

### Realistic answer

Given the the theoritical answer, all of the systems that we are working on are distibuted, specially considering the 1st two distributed system types below:
- _Client Server_
- _N-Tier_
- Peer-To-Peer **(P2P)**
- Service-Oriented Architecture **(SOA)**
- Microservices
- Micro-Frontends

**_Conventionally_**, we refer to the 1st two types as monotlithic systems, while they are actually distributed!

So, we apply some of the distributed system related aspects to those claimed monolithic systems e.g. scalability where we sometimes scale out the endpoints, or scale up the DB process.

but when it comes to the implicitly known distributed ones, the handling gets magnified a lot due to the large number of scattared processes and how they are distributed, which requires well known  patterns to handle that.

## So, does it mean that all the software systms are distributed?

### Realistic answer

No,
- Non data-centric systems e.g. calculator, are almost real monolithics
- Single process data-centeric systems e.g. Access DB, are real monolithics since the interface, logic, and data store are running as a single process

## What to distribute?

### Chat GPT answer

In distributed systems, various components and functionalities are distributed across multiple machines or nodes to achieve scalability, reliability, and performance. Here's an overview of what can be distributed in such systems:
- Data
- Computation
- Services
- Storage
- Messaging
- Security
- Networking
- Configuration

### Enriched answer

In addition to the above mentioned distibution aspects, the below also can be distributed: 

- Code base
- Build
- Deployment
- Hosting
