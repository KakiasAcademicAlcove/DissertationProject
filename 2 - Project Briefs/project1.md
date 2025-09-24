# Project Brief 1: Resilience Testing with Chaos Engineering in Cloud-Native Systems

## Applies to Students in: MSc Computer Science   
**Can be completed in**: 6 Weeks  
**Supervisor**: Dr. Kakia Chatsiou

**Prerequisites**: Students should be well versed in DevOps principles, Docker, Kubernetes, AWS Microservices

## Project Aim

To explore and apply Chaos Engineering principles by simulating failures in a cloud-native application and evaluating its resilience using observability tools and fault injection frameworks.



## Learning Outcomes

By the end of this project, students will be able to:

- Understand the theoretical foundations of Chaos Engineering.
- Deploy and manage cloud-native applications using container orchestration.
- Integrate chaos tools to simulate real-world failure scenarios.
- Monitor system behaviour and evaluate resilience metrics.
- Propose architectural improvements based on experimental findings.

## Background and Rationale

Modern software systems are increasingly distributed, complex, and deployed in dynamic cloud-native environments. As organisations adopt microservices architectures, containerisation, and continuous delivery pipelines, ensuring system reliability becomes both more critical and more challenging.

Chaos Engineering has emerged as a proactive discipline aimed at improving system resilience by deliberately introducing faults and observing how systems respond. Originally popularised by Netflix through tools like Chaos Monkey, Chaos Engineering has evolved into a broader practice supported by open-source frameworks such as Chaos Mesh and LitmusChaos, and commercial platforms like Gremlin.

The rationale for this project lies in the growing need to understand and mitigate the risks associated with unpredictable failures in production environments. Rather than waiting for outages to occur, Chaos Engineering enables teams to simulate real-world failure scenarios—such as network latency, resource exhaustion, or service crashes—and evaluate how well their systems recover.

This project provides students with the opportunity to explore Chaos Engineering in a controlled, academic setting. It bridges theory and practice by combining fault injection techniques with observability tools, allowing students to measure key reliability metrics such as Mean Time to Recovery (MTTR), error rates, and service availability. 

## Related Literature



## Potential Tools & Technologies

- **Cloud Platform**: AWS / Azure / GCP / Local Kubernetes (Minikube, Kind)
- **Containerisation**: Docker
- **Orchestration**: Kubernetes
- **Chaos Tools**: Chaos Monkey, Gremlin, Chaos Mesh, LitmusChaos
- **Monitoring**: Prometheus, Grafana
- **Languages**: YAML, Python, Bash


## Suggested Sample Applications

- [Sock Shop](http) Weaveworks: Simulates an e-commerce site.
- [Online Boutique](https://github.com/GoogleCloudPlatforming): Google Cloud: Cloud-native microservices demo.
- PetClinic Microservices – Veterinary clinic system.
- Bookshelf App – Simple CRUD app.


## Suggested Datasets (Optional for Observability or Load Testing)

- Synthetic Load: Use tools like Locust, Apache JMeter, or K6 to generate traffic.
- Realistic Data: Use anonymized e-commerce datasets (e.g., UCI Online Retail) to simulate user behavior.
- IoT or Sensor Data: For edge/fog scenarios, use Intel Lab Data.


## Tentative Breakdown of work

### Week 1: Research & Planning
- Conduct a literature review on Chaos Engineering and system resilience.
- Select application and deployment environment.
- Define project scope, goals, and reliability metrics (SLOs/SLIs).

### Week 2: Environment Setup
- Deploy selected sample application using Docker and Kubernetes.
- Set up monitoring stack (Prometheus + Grafana).
- Document architecture and baseline performance.

### Week 3: Chaos Tool Integration
- Choose and configure chaos tools (e.g., Chaos Mesh, Gremlin).
- Design failure scenarios (e.g., pod crash, network latency).
- Test chaos tool setup in a controlled environment.

### Week 4: Experimentation
- Run chaos experiments and simulate failures.
- Monitor system behaviour and collect metrics.
- Record MTTR, error rates, and system recovery patterns.

### Week 5: Analysis & Optimisation
- Analyse experiment results and compare against SLOs.
- Identify bottlenecks and propose architectural improvements.
- Optionally, re-run experiments after applying optimisations.

### Week 6: Reporting & Presentation
- Compile findings into a structured report (3,000–5,000 words).
- Include visualisations (Grafana dashboards, charts).
- Prepare a short presentation or demo (optional).
- Submit code, configuration files, and documentation.

---

## Make sure to include in your submission

- Source code and configuration files
- Experiment logs and dashboards


