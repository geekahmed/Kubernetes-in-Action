# Chapter 1. Introducing Kubernetes
- Kubernetes abstracts away the hardware infrastructure and exposes your whole data-center as a single enormous computational resource.
## Section 1.1. Understanding the need for a system like Kubernetes
- Moving from monolithic apps to microservices
  - Changing the style of development from one big process on one server to small components on different servers.
- The difference between monolithic and microservices is depicted in the following figure
<p align="center">
  <img src="images/monolithic-vs-microservices.png" alt="Monolithic VS Microservices"/>
</p>

- Microservices communicate syncronously or asyncronounsly.
- When a monolithic application can’t be scaled out because one of its parts is unscalable, splitting the app into microservices allows you to horizontally scale the parts that allow scaling out, and scale the parts that don’t, vertically instead of horizontally.
<p align="center">
  <img src="images/microservices-scaling.png" alt="Each microservice can be scaled individually"/>
</p>

- Deploying dynamically linked applications that require different versions of shared libraries, and/or require other environment specifics, can quickly become a nightmare for the ops team who deploys and manages them on production servers.
<p align="center">
  <img src="images/libraries-dependence.png" alt="Multiple applications running on the same host may have conflicting dependencies"/>
</p>

- Providing a consistent environment to applications.
- Moving to continuous delivery: DevOps and NoOps.
## Section 1.2. Introducing container technologies
## Section 1.3. Introducing Kubernetes