# 07 Advanced Topics: System Design

Designing systems that can handle scale.

## Scalability
- **Vertical Scaling (Scaling Up):** Adding more power (CPU, RAM) to an existing server. Limited by hardware.
- **Horizontal Scaling (Scaling Out):** Adding more servers to a pool of resources. Often preferred for modern web applications.

## Key Concepts
- **Load Balancing:** Distributing incoming network traffic across multiple servers to ensure no single server bears too much demand.
- **Caching:** Storing copies of frequently accessed data in a fast temporary storage (like Redis or Memcached) to reduce database load.
- **Database Sharding:** Dividing a large database into smaller, faster, more easily managed parts called data shards.
- **Message Queues:** Asynchronous communication protocols (like RabbitMQ or Kafka) that decouple services.
- **CAP Theorem:** In a distributed system, you can only guarantee two of the following: Consistency, Availability, and Partition Tolerance.
