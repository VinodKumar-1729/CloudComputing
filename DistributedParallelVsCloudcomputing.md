### **1. Distributed Computing**
- **Definition**: A computing paradigm where multiple computers work together to achieve a common goal, sharing resources and workloads over a network.
- **Characteristics**:
  - Geographically dispersed systems.
  - Emphasis on fault tolerance and resource sharing.
  - Systems communicate via message passing.
  - Examples: Hadoop, Apache Spark.
  
- **Key Phases**:
  - **Task Distribution**: Breaking down large computational tasks into smaller subtasks and assigning them to multiple nodes.
  - **Communication & Synchronization**: Nodes exchange data/messages and synchronize tasks to ensure accuracy.
  - **Fault Tolerance**: Mechanisms to handle failures of individual nodes without interrupting the system.
  - **Result Aggregation**: Combining results from distributed nodes to generate the final output.

---

### **2. Parallel Computing**
- **Definition**: A type of computation where many calculations or processes are carried out simultaneously within a single system.
- **Characteristics**:
  - Involves tightly coupled systems.
  - Requires shared memory or a multi-core processor.
  - High-speed communication between processes.
  - Examples: GPU processing, parallel algorithms like matrix multiplication.
  
- **Key Phases**:
  - **Task Decomposition**: Dividing tasks into independent or interdependent threads.
  - **Parallel Execution**: Running threads simultaneously across processors or cores.
  - **Synchronization**: Ensuring consistency between parallel threads using locks or semaphores.
  - **Performance Optimization**: Managing load balancing and minimizing communication overhead.

---

### **3. Cloud Computing**
- **Definition**: A paradigm that provides on-demand access to computing resources like servers, storage, and applications over the internet.
- **Characteristics**:
  - Elastic and scalable.
  - Supports multitenancy.
  - Service models: IaaS, PaaS, SaaS.
  - Examples: AWS, Microsoft Azure, Google Cloud.

- **Key Phases**:
  - **Resource Provisioning**: Allocating resources dynamically based on user requirements.
  - **Virtualization**: Abstracting physical resources to provide scalability and isolation.
  - **Service Delivery**: Delivering computing as a service (e.g., storage, computation).
  - **Monitoring and Maintenance**: Ensuring system health and performance.

---

### **Comparison of Distributed Parallel vs Cloud Computing**

| **Aspect**             | **Distributed Computing**           | **Parallel Computing**              | **Cloud Computing**                  |
|-------------------------|-------------------------------------|-------------------------------------|-------------------------------------|
| **Architecture**        | Multiple independent systems       | Multi-core systems                  | Virtualized shared infrastructure   |
| **Communication**       | Network-based message passing      | Shared memory or interconnect buses | API-based over the internet         |
| **Scalability**         | Moderate                          | Limited by physical resources       | Highly scalable                     |
| **Fault Tolerance**     | High                              | Limited                             | High                                |
| **Use Cases**           | Big Data, global simulations      | Real-time processing, HPC tasks     | Web hosting, on-demand services     |

---

### **Additional Points for Competitive Edge**

1. **Hybrid Models**:
   - Understand cases where distributed and parallel systems overlap within cloud infrastructures.
   - Example: HPC workloads on cloud platforms (e.g., AWS ParallelCluster).

2. **Performance Metrics**:
   - Distributed: Latency, throughput, fault recovery time.
   - Parallel: Speedup, efficiency, scalability.
   - Cloud: Cost efficiency, uptime, resource utilization.

3. **Key Algorithms**:
   - Distributed: MapReduce, Gossip protocols.
   - Parallel: Divide and Conquer, Parallel Prefix Sum.
   - Cloud: Load Balancing (Round-robin, Weighted algorithms).

4. **MCQ Hints**:
   - Focus on service-level agreements (SLAs) in Cloud Computing.
   - Questions may test the distinction between tightly coupled (Parallel) and loosely coupled (Distributed) systems.
   - Expect numericals comparing execution time in parallel vs distributed systems.

5. **Emerging Trends**:
   - Edge Computing: Bridging distributed systems with cloud environments.
   - Serverless Computing: Abstracting infrastructure in cloud models.
   - Quantum Computing: Parallelism on quantum hardware.

---

### **Sample Question**
1. **Which system typically uses shared memory for communication?**  
   A) Distributed Computing  
   B) Parallel Computing  
   C) Cloud Computing  
   D) All of the above  
   **Answer**: B) Parallel Computing  

2. **What is the main advantage of cloud computing over distributed computing?**  
   A) Fault tolerance  
   B) Cost-effectiveness  
   C) Task decomposition  
   D) Low latency  
   **Answer**: B) Cost-effectiveness  
