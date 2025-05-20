## Software Architecture - Detailed Tutorial

### 1. Fundamentals of Architecture

* Software Architecture defines system structure, components, and their interactions.
* Goals: Manage complexity, support scalability, maintainability, and performance.

### 2. Why Architecture is Required

* Early design decisions shape the system's scalability, security, and reliability.
* Modularization enables team collaboration, reuse, and reduces tech debt.

### 3. Vertical and Horizontal Scaling

* **Vertical Scaling**: Increase machine resources (CPU, RAM).
* **Horizontal Scaling**: Add more servers to distribute load.
* Horizontal scaling supports fault tolerance and high availability.

### 4. Need for Distributed Systems

* Handles high traffic and large-scale data.
* Enables component independence, fault tolerance, and geo-redundancy.

### 5. CAP Theorem

* **Consistency**: Latest data on every read.
* **Availability**: Response for every request.
* **Partition Tolerance**: System withstands network failures.
* Choose 2 of 3 in any distributed system.

### 6. ACID Properties

* **Atomicity**: All or nothing.
* **Consistency**: Data integrity.
* **Isolation**: Transactions don’t interfere.
* **Durability**: Changes persist after commit.

### 7. Latency, Throughput, Availability

* **Latency**: Time per request.
* **Throughput**: Requests processed per second.
* **Availability**: System uptime percentage.

### 8. High Availability & Replication

* Achieved via redundancy, failover, load balancing, and geo-replication.
* **Replication Types**:

  * Master-Slave
  * Multi-Master
  * Synchronous vs Asynchronous

### 9. Consistency Models

* **Strong**: Always latest data
* **Weak**: No guarantee of latest
* **Eventual**: Becomes consistent over time

### 10. Advanced Data Structures

* **LRU Cache**: Discards least recently used item.
* **Graph**: Nodes & edges, used in networks, maps.
* **Dijkstra Algorithm**: Shortest path in graph.

### 11. Load Balancers

* **Round Robin**: Evenly distributes traffic.
* **Layer-4 LB**: Based on TCP/UDP.
* **Layer-7 LB**: Based on HTTP headers/content.
* **Consistent Hashing**: For distributed systems.
* **DNS LB**: Uses DNS to resolve multiple IPs.

### 12. Networking and Data Centres

* **OSI Model**: 7-layer model for network communication.
* Components: DNS Server, NAT, Routers, Switches.
* **Spine-Leaf Architecture**: Data center topology.
* **Layer 2/3 Traffic**: Ethernet vs IP routing.
* **Tunnels & VPNs**: Secure network communication.

### 13. Cluster Management

* Manages resources, workloads, and health in a cluster.
* Global architecture spans multiple regions.

### 14. Microservices Architecture

* **API Gateway**: Entry point for services.
* **REST API**: Communication between services.
* **Scaling**: Deploy multiple instances.
* **Security**: Auth, rate-limiting, logging.

### 15. Security in Microservices

* **API Rate Limiting**: User, concurrency, location-based, etc.
* **OAuth**: Authorization standard with Auth Server and Resource Server.

### 16. Deployment Types

* **Master-Slave**
* **Master-Master**
* **Single Master**
* **Tape Backup** (for long-term storage)

### 17. Virtualization & Containerization

* **Virtual Machines**: Full OS per instance.
* **Docker**: Lightweight containerized apps.
* **Kubernetes**: Container orchestration.

### 18. Disaster Recovery & Business Continuity

* Redundant deployments, backups, automated failover.
* Active-active, active-passive strategies.

### 19. Cluster Architecture

* **GFS**: Google File System.
* **Hadoop + MapReduce**: Batch processing.
* **Spark**: In-memory big data processing.
* **Kubernetes**: Scalable deployment.

### 20. Architectural Patterns

* Client-Server, Proxy (Forward, Reverse), Layered, MVC
* SaaS, PaaS, IaaS
* Broker, Leader Election, Hybrid, Edge, CDN

### 21. Consistent Hashing in Depth

* Used in cache, load balancing, and traffic routing.
* Helps reduce rebalancing when nodes change.

### 22. Cloud Technologies

* **AWS EC2**: Virtual machines.
* **AWS CloudWatch**: Monitoring, logs.
* **AWS Firewall**: Security configurations.

### 23. Event-Driven Architecture

* **Kafka**: Pub-Sub model.
* **Observer Pattern**: Reactive design.
* Kafka scaling with partitions, consumer groups.

### 24. Performance Tuning (25 Techniques)

* Multithreading, async IO, caching, batching, pooling, DB indexing, etc.

### 25. Database Types & Design

* SQL (Relational)
* NoSQL (Cassandra, MongoDB)
* Graph DB, Elastic DB
* Redis vs Memcache
* Read Speed: Memory > SSD > HDD

### 26. Security Architecture

* Firewall, OAuth, WAF, TLS
* ZTNA, API Security, DoS Prevention
* Network vs App-Level Security, SASE

### 27. Comparative Trade-offs

* Strong vs Eventual Consistency
* CAP vs ACID
* LB Types
* Rate Limiters
* Deployment: Master-Master vs Master-Slave
* Hot vs Warm Standby
* VM vs Docker
* Hadoop vs Spark
* SaaS vs PaaS vs IaaS

### 28. Framework-based Design Thinking

* Use structured frameworks for problem-solving and decision making.

### 29. Soft Skills for Architects

* Effective Communication
* Emotional Intelligence
* Conflict Resolution
* Persuasion Techniques

### 30. Capacity Planning

* Decide RAM, CPU, Disk based on load, throughput, and latency goals.

### 31. System Design Case Studies

* **WhatsApp**: Real-time messaging, encryption, delivery acknowledgements.
* **Netflix**: CDN, microservices, failover, personalization.
* **Google Search**: Crawling, indexing, ranking, caching.
* **Google Maps**: Graph, tile serving, route calculation, geo data.

### 32. Mock Interviews & Practice

* Simulate interviews, whiteboard challenges, tradeoff discussions.

### 33. Miscellaneous Topics

* Pick from: Cyber Security, Data Center Design, Proprietary Frameworks, etc.



