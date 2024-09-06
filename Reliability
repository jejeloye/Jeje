# Azure Reliability Documentation

Reliability in cloud architecture consists of two primary principles: **resiliency** and **availability**.

- **Resiliency**: The goal of resiliency is to avoid failures, and if they occur, to return your application to a fully functioning state.
- **Availability**: Availability aims to provide consistent access to your application or workload, ensuring accessibility at all times.

## Types of Failure and Built-In Solutions from Azure

1. **Single Hardware Node Failure**  
   Azure provides **Availability Sets** to ensure that virtual machines deployed on Azure are distributed across multiple isolated hardware nodes in a cluster, mitigating the impact of a single node failure.

2. **Rack-Level Failure or Datacenter Outage**  
   Azure offers **Availability Zones** to protect customers' applications and data from datacenter failures by distributing resources across multiple physical locations within a region.

3. **Large-Scale Regional Outage**  
   In the event of a regional outage, **Region Pairs** safeguard customers' applications and data by replicating them across multiple regions within a geography, thus helping to prevent data loss.

## Reliability KPIs and SLA

The **Key Performance Indicators (KPIs)** for reliability in Azure solutions depend on multiple factors. Some key KPIs include:

1. **Availability**: Defines how much downtime is acceptable for the application or service.
2. **Latency**: Latency is the time it takes for a data packet to travel from source to destination. A **Latency SLA (Service Level Agreement)** sets the acceptable maximum delay in delivering services between Azure and its clients.

## Shared Responsibility for Reliability

Reliability in Azure is a **shared responsibility** between the cloud provider and the customer. Depending on the type of service used, the division of responsibility may vary:

- **Microsoft**: Responsible for the reliability of the cloud platform, including global network and data centers.
- **Azure Customers and Partners**: Responsible for building resilient cloud applications by adhering to best practices for architecture and workload requirements.

## Considerations for Building Reliable Systems

When designing and building reliable systems on Azure, consider the following:

1. Define availability and recovery targets based on business requirements.
2. Design the reliability features of your applications based on availability needs.
3. Align applications and data platforms to meet your defined reliability requirements.
4. Configure connection paths to promote availability.
5. Use availability zones and disaster recovery plans where applicable to optimize reliability and costs.
6. Ensure your application architecture is resilient to failures.
7. Understand the implications if SLA requirements are not met.
8. Identify potential failure points in the system; ensure that your application can tolerate dependency failures by deploying **circuit breakers**.
9. Build applications that can continue to operate in the absence of their dependencies.

---

**Reference**: [Microsoft Learn](https://learn.microsoft.com)
