# system-design-revision

# [CS75 (Summer 2012) Lecture 9 Scalability Harvard Web Development](https://youtu.be/-W9F__D3oY4?si=oE2LquIcABKw5T8L)

Lecture explores scalability in web applications,challenges developers face and the strategies they employ to build scalable systems.

## Understanding the Challenges of Scalability

### Scaling Databases
Databases are fundamental to web applications, but traditional approaches may struggle to handle increasing loads. In lecture discusses techniques such as:
- *Sharding:* Distributing data across multiple servers based on a predefined key.
- *Replication:* Creating multiple copies of data to enhance availability and reliability.
- *NoSQL Databases:* Exploring alternatives like MongoDB and Cassandra for their scalability benefits over traditional relational databases.

### Caching Strategies
Caching plays a crucial role in improving application performance. Key points covered include:
- *In-Memory Caching:* Leveraging tools like Redis and Memcached to store frequently accessed data in memory, reducing database load and improving response times.
- *Cache Invalidation:* Strategies for managing cache invalidation to ensure data consistency and freshness.
- *Expiration Policies:* Implementing policies to expire cached data based on usage patterns or time limits.

### Load Balancing
Efficiently distributing incoming requests across multiple servers is essential for scalability. Topics discussed include:
- *Load Balancer Configuration:* Utilizing technologies such as Nginx and HAProxy to evenly distribute traffic and prevent overload on any single server.
- *Session Affinity:* Ensuring that requests from the same user are routed to the same server to maintain session state.
- *Health Checking:* Monitoring server health and automatically rerouting traffic in case of failures to maintain system reliability.

### Optimizing Code for Performance
Efficient code is critical for scalability. Topics discussed include:
- *Profiling:* Using tools to identify performance bottlenecks in code and database queries.
- *Benchmarking:* Testing application performance under various load conditions to identify potential issues.
- *Reducing Latency:* Optimizing network communication and database access to minimize response times and improve overall system performance.

## Key Strategies for Scalability

### Start Early
Scalability should be considered from the initial stages of application design and development. Architectural decisions made early on can have a significant impact on scalability later.

### Continuous Monitoring
Regular performance testing and monitoring are essential to identify issues and fine-tune systems as traffic and data volumes grow. Automated monitoring tools can help detect anomalies and optimize system performance.

### Architectural Decisions
The architecture of a system plays a crucial role in its scalability. emphasizes the benefits of distributed systems, microservices, and cloud-native architectures for scalability over monolithic approaches.
