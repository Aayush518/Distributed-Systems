# Distributed Systems: An Introduction

## Introduction
A **distributed system** is a collection of independent computers that work together to achieve a common goal. The computers communicate with each other through message passing or events.

**Distributed computing** is a type of computing that takes place on distributed systems. It involves building and designing computing models for distributed systems and developing algorithms to solve problems related to such systems.

## Characteristics of Distributed Systems
- No shared clock: Each computer has its own clock, making coordination difficult.
- No shared memory: Each computer has its own memory, preventing direct memory access.
- Concurrency: Multiple tasks can be executed simultaneously.
- Heterogeneity: Computers in the system can be different from each other.
- Loose coupling: Computers are loosely coupled and not tightly integrated.

## Basic Concepts of Distributed Computing
- **Nodes:** The individual computers in a distributed system.
- **Resources:** Assets that can be accessed remotely by nodes (e.g., data, storage).
- **Distribution Transparency:** Hiding the complexities of the system from users.
- **Middleware:** Software layer facilitating communication and management between nodes.
- **Concurrency:** Ability of the system to execute multiple tasks simultaneously.
- **Coordination & Synchronization:** Techniques to ensure cooperation between tasks.
- **Architectural Models:** Define how nodes are organized (e.g., client-server, peer-to-peer).
- **Global State:** The collective state of all nodes in the system.

## Advantages of Distributed Systems
- Reliability: Can continue operating even if one or more computers fail.
- Scalability: Can easily scale by adding more computers.
- Resource sharing: Resources can be shared between computers.
- Increased performance: Tasks can be distributed among multiple computers.

## Disadvantages of Distributed Systems
- Failure detection: Difficult to detect failures in the system.
- Redundancy: Multiple computers may have copies of the same data.
- Consistency: Difficult to ensure all computers have the same data.
- Performance bottlenecks: Can occur due to slow network or resource competition.
