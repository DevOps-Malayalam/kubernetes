# Introduction

- Container runtimes or Docker Runtime.
  - Brief History of Software Container Ecosystem. 
    - [Refer](https://blog.aquasec.com/a-brief-history-of-containers-from-1970s-chroot-to-docker-2016)
    
  - Container vs VMs
    - [Refer](https://www.aquasec.com/cloud-native-academy/docker-container/docker-architecture/)
  - Evolution of container runtimes. 
  
# Part 1: Why we need Kubernetes when we are already having Docker as container runtimes.

  - Did K8s is only container orechestration system available or do we have any? [Refer](https://geekflare.com/container-orchestration-software/)
  - Advantages of using K8s over similar other container orchestration platforms: All things needed for orchestration of container in a large scale can be done by Kubernetes natively and also can provide us with  capability of extending of our own by the means of Controllers, CRDs etc. 
  - Kubernetes Architecture and core components. [Refer](https://kubernetes.io/docs/concepts/overview/components/)
  - Choose mode of Kubernetes clusters with respect to usecases
    - Managed Clusters: Different Type of Providers, eg: GKE, EKS, AKS.
    - Self Managed Clusters
  - Securing Kubernetes Clusters.
  - Much needed components for building a kubernetes platforms including Observability. 
  - Kind clusters for testing

# Part 2: Kubernetes for Developers.

- First app into Kubernetes, All I need is a decently build docker image
  - Container Image Build consideration.
  - Integrate container scanning solutions.
  - Ref: https://www.cncf.io/blog/2021/09/14/how-to-secure-containers-with-cosign-and-distroless-images/
- Stateless Applications
- Stateful Applications. 
- Expose your first pod. 
- Why I need Deployment for my pods? 
  - Expose my first deployment using Services. 
  - Tracing your first request your applications. 
- Solution for running stateful workloads? 
  - Statefulsets.
  - Headless services. 
  
# Part 3: Extending the native capabilities of Kubernetes. 

Will be added soon 
