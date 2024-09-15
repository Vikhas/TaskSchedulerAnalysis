---
# Cloud Task Scheduling Algorithms Performance Analysis

Cloud computing has become a critical technology in recent times, allowing individuals and organizations to access computing resources (software, hardware, and platforms) as services over the Internet. As the cloud serves millions of users simultaneously, ensuring high performance and maintaining quality of service (QoS) is essential.

In this project, we explore and compare the performance of three task scheduling algorithms in cloud computing
1. **First Come First Serve (FCFS)**
2. **Shortest Job First (SJF)**
3. **Particle Swarm Optimization (PSO)**

## Problem Statement

Task scheduling is one of the most crucial factors in determining the performance of a cloud computing environment. It plays a vital role in efficiently managing cloud resources and ensuring that users' requests are handled optimally. Poor scheduling can lead to longer waiting times, inefficient resource allocation, and lower system performance.

This project aims to analyze how different task scheduling algorithms impact cloud performance in terms of:
- **Algorithm complexity**
- **Resource availability**
- **Total Execution Time (TET)**
- **Total Waiting Time (TWT)**
- **Total Finish Time (TFT)**

## Key Features
- **CloudSim Simulation**: We use the CloudSim simulator to evaluate the performance of FCFS, SJF, and PSO task scheduling algorithms.
- **Static Task Scheduling**: The algorithms are static, meaning tasks and resources are predetermined before the simulation begins.
- **Performance Metrics**: The simulation focuses on key performance metrics, such as total execution time, waiting time, and resource utilization.

## Technologies Used
- **CloudSim**: A framework used for modeling and simulating cloud computing environments and scheduling algorithms.
- **Java**: The programming language used to implement the task scheduling algorithms.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cloud-task-scheduling.git
   cd cloud-task-scheduling
   ```
2. Install the necessary dependencies (CloudSim).
3. Compile and run the Java program to simulate the performance of the scheduling algorithms.
4. Analyze the results for FCFS, SJF, and PSO based on the performance metrics (TET, TWT, TFT).

## Results & Analysis
The performance of the algorithms is evaluated based on their:
- **Efficiency in resource allocation**.
- **Impact on total execution and waiting times**.
- **Scalability and performance under different cloud load conditions**.

The metaheuristic approach, **Particle Swarm Optimization (PSO)**, is particularly interesting due to its adaptive nature in optimizing task allocation compared to traditional static algorithms like FCFS and SJF.

## Conclusion
This project highlights the importance of efficient task scheduling in cloud computing. By simulating the performance of these algorithms, we demonstrate the trade-offs between simplicity and optimization, and how advanced algorithms like PSO can lead to better cloud performance in high-demand environments.

---
