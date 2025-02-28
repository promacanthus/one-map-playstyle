# One Map Playstyle

## [Chap.0: ISO Network Model](docs/00-chapter_0.md)

- Introduce the architecture and basic concepts of the first three layers of the network.
- Explain the communication principles between the first three layers of the network.

## [Chap.1：Kubernetes Network](docs/01-chapter_1.md)

- 1.1 Kubernetes Network Model
  - Introduce the network architecture and basic concepts of Kubernetes.
  - Explain the relationship between Pods, Services, and network policies.
- 1.2 Network Communication Principles
  - Describe how containers communicate with each other.
  - Discuss network namespaces and virtual network interfaces.

## [Chap.2：Container Network Stack](docs/02-chapter_2.md)

- 2.1 Overview of Container Network Stack
  - Introduce how containers use the Linux network stack.
  - Describe the network interactions between containers and the host machine.
- 2.2 Network Namespaces
  - Deep dive into how Linux network namespaces work.
  - Demonstrate how to configure networks within namespaces.
- 2.3 Virtual Network Interfaces
  - Introduce the concept of virtual Ethernet pairs (veth pairs).
  - Demonstrate how to create and use veth interfaces.

## [Chap.3： Container Network Interface](docs/03-chapter_3.md)

- 3.1 Overview of CNI
  - Define the role and importance of CNI.
  - Discuss the types and functions of CNI plugins.
- 3.2 Common CNI Plugins
  - Compare different CNI plugins (e.g., Flannel, Calico, Weave).
  - Show how to install and configure a CNI plugin.
- 3.3 Mechanism of CNI
  - Explore the workflow of CNI, including the network configuration process when creating Pods.

## [Chap.4：Kubernetes Service](docs/04-chapter_4.md)

- 4.1 Types of Services
  - Describe the differences and use cases for ClusterIP, NodePort, and LoadBalancer.
- 4.2 Working Principles of Services
  - Deep dive into how Kubernetes implements service discovery and load balancing.
- 4.3 Headless Services and DNS
  - Discuss the concept of headless services and their application in service discovery.

## [Chap.5：Kubernetes DNS](docs/05-chapter_5.md)

- 5.1 Role of DNS in Kubernetes
  - Describe the functions and importance of built-in DNS in Kubernetes.
- 5.2 DNS Configuration and Usage
  - Show how to configure and use Kubernetes DNS.
- 5.3 Common Issues and Troubleshooting
  - List common DNS issues and their solutions.

## [Chap.6：Board Gateway Protocol](docs/06-chapter_6.md)

- 6.1 Overview of BGP
  - Define the basic concepts of BGP and its role in the internet.
- 6.2 Working Principles of BGP
  - Explore the BGP routing selection process and its algorithms.
- 6.3 Using BGP in Kubernetes
  - Describe how to configure BGP in a Kubernetes cluster for cross-node routing.

## [Chap.7：Gateway API](docs/07-chapter_7.md)

- 7.1 Introduction to Gateway API
  - Introduce the Gateway API, its purpose, and its relationship with other networking solutions.
- 7.2 Gateway API Architecture
  - Discuss the architecture and components of the Gateway API.

## [Chap.8：Kubernetes Architecture](docs/08-chapter_8.md)

- 8.1 Scheduler
  - Describe the role and functions of the Kubernetes scheduler.
- 8.2 Client-go
  - Describe the role and functions of the Kubernetes client-go.

## [Chap.9：Golang](docs/09-chapter_9.md)

- 9.1 Introduction to Golang Scheduling
  - The basic concepts of Golang scheduling and its implementation.
- 9.2 The Go Net Poll
  - Deep dive into the Go net poller and its role in network communication.

## [Appendix](docs/appendix.md)

- Appendix A: Summary of Common Commands
- Appendix B: Sample Configuration Files
- Appendix C: Troubleshooting Guide
