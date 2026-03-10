# Master Microservices with Spring Boot, Docker, Kubernetes

> Course: [Master Microservices with SpringBoot, Docker, Kubernetes](https://www.udemy.com/course/master-microservices-with-spring-docker-kubernetes/) by Eazy Bytes / Madan Reddy
>
> 283 lectures | 40h 24m | 21 sections
>
> **Goal:** 10 videos per day | Each video = 1 commit

---

## Progress Overview

| Metric | Value |
|---|---|
| Total Lectures | 283 |
| Start Date | March 7, 2026 |
| Target End Date | April 4, 2026 |
| Daily Target | 10 videos/day |
| Total Days | 29 |

---

## Tech Stack Covered

| Topic | Technologies |
|---|---|
| Core | Java, Spring Boot, Spring MVC, Spring Data JPA |
| Databases | H2 (dev), MySQL (prod) |
| Documentation | SpringDoc OpenAPI, Swagger |
| Containerization | Docker, Dockerfile, Buildpacks, Google Jib |
| Orchestration | Docker Compose, Kubernetes, GKE |
| Config Management | Spring Cloud Config, Spring Cloud Bus |
| Service Discovery | Netflix Eureka, Feign Client, Spring Cloud Kubernetes |
| API Gateway | Spring Cloud Gateway |
| Resiliency | Resilience4J (Circuit Breaker, Retry, Rate Limiter, Bulkhead), Redis |
| Observability | Prometheus, Loki, Promtail, Tempo, Grafana, OpenTelemetry, Micrometer |
| Security | OAuth2, OpenID Connect, Spring Security, KeyCloak |
| Messaging | RabbitMQ, Kafka, Spring Cloud Functions, Spring Cloud Stream |
| Package Manager | Helm |
| Advanced | Service Mesh, mTLS, Kubernetes Ingress, Spring Boot BOM, Shared Libraries |
| IDE | IntelliJ IDEA Ultimate |

---

## Daily Planner & Checklist

---

### Day 1 — Saturday, March 7, 2026
**Section: Introduction & Microservices Architecture**

- [X] 1. Introduction to the course & Agenda *(6:24)*
- [X] 2. Details of Source Code, PDF Content & other instructions for the course *(1:01)*
- [X] 3. Evolution of Microservices architecture *(17:27)*
- [X] 4. Comparisons between Monolithic, SOA & Microservices architecture *(7:22)*
- [X] 5. Definition of Microservices *(1:51)*
- [X] 6. How to build microservices *(3:59)*
- [X] 7. Introduction to SpringBoot framework *(7:52)*
- [X] 8. Funny memes of SpringBoot framework *(4:25)*
- [X] 9. Introduction to REST APIs & best practices *(7:16)*
- [X] 10. IntelliJ IDEA Ultimate *(0:59)*

---

### Day 2 — Sunday, March 8, 2026
**Section: Building Accounts Microservice**

- [X] 11. Creating a Spring Boot project *(12:37)*
- [X] 12. Creating Hello World REST API using @RestController *(8:09)*
- [X] 13. Configuring H2 DB & YAML properties *(14:45)*
- [X] 14. IMPORTANT: Issue related to Lombok in IntelliJ IDEA *(0:41)*
- [X] 15. Writing Spring Data JPA entities & repositories to interact with DB tables *(17:50)*
- [X] 16. Introduction to DTO (Data Transfer Object) pattern *(6:35)*
- [X] 17. Creating DTOs inside accounts microservice *(9:19)*
- [X] 18. CREATE API inside accounts microservice - Part 1 *(16:39)*
- [X] 19. CREATE API inside accounts microservice - Part 2 *(22:07)*
- [ ] 20. READ API inside accounts microservice *(14:54)*

---

### Day 3 — Monday, March 9, 2026
**Section: Building Accounts Microservice (continued)**

- [ ] 21. UPDATE API inside accounts microservice *(9:37)*
- [ ] 22. DELETE API inside accounts microservice *(7:59)*
- [ ] 23. Handle all types of runtime exceptions using global logic inside accounts *(4:52)*
- [ ] 24. Perform input data validations inside accounts microservice *(14:49)*
- [ ] 25. Update audit columns using Spring Data *(7:31)*
- [ ] 26. Introduction to documentation of REST APIs using springdoc openapi *(11:03)*
- [ ] 27. Enhancing documentation of REST APIs using @OpenAPIDefinition *(8:09)*
- [ ] 28. Enhancing documentation of REST APIs using @Tag, @Operation, @ApiResponse *(7:45)*
- [ ] 29. Enhancing documentation of REST APIs using @Schema & example data - Part 1 *(9:15)*
- [ ] 30. Enhancing documentation of REST APIs using @Schema & example data - Part 2 *(4:23)*

---

### Day 4 — Tuesday, March 10, 2026
**Section: Loans & Cards Microservices + Sizing Boundaries**

- [ ] 31. Important Annotations & Classes that supports building REST services *(6:48)*
- [ ] 32. Assignment to build Loans & Cards microservices *(3:37)*
- [ ] 33. Deep dive and demo of Loans microservice *(16:31)*
- [ ] 34. Deep dive and demo of Cards microservice *(10:12)*
- [ ] 35. Approaches to identify boundaries & right size microservices *(13:04)*
- [ ] 36. Sizing & identifying boundaries with a Bank App use case *(6:05)*
- [ ] 37. Sizing & identifying boundaries with a ecommerce migration use case *(7:57)*
- [ ] 38. Strangler Fig pattern *(8:03)*
- [ ] 39. Introduction to challenges while building, deploying microservices *(9:12)*
- [ ] 40. What are Containers & how they are different from VMs *(11:23)*

---

### Day 5 — Wednesday, March 11, 2026
**Section: Docker**

- [ ] 41. Definition of Containers, Containerization, Docker *(10:59)*
- [ ] 42. Introduction to Docker components & its architecture *(7:04)*
- [ ] 43. Docker installation & docker hub introduction *(7:18)*
- [ ] 44. Introduction to the three approaches for Docker image generation *(3:22)*
- [ ] 45. Generate Docker Image of Accounts microservice with Dockerfile - Part 1 *(10:22)*
- [ ] 46. Generate Docker Image of Accounts microservice with Dockerfile - Part 2 *(7:42)*
- [ ] 47. Generate Docker Image of Accounts microservice with Dockerfile - Part 3 *(7:14)*
- [ ] 48. Running accounts microservice as a Docker container *(15:37)*
- [ ] 49. Challenges with Dockerfile approach to generate a Docker image *(4:41)*
- [ ] 50. Generate Docker Image of Loans microservice with Buildpacks *(12:10)*

---

### Day 6 — Thursday, March 12, 2026
**Section: Docker (continued)**

- [ ] 51. Generate Docker Image of Cards microservice with Google Jib *(11:58)*
- [ ] 52. Compare Dockerfile, Buildpacks, Jib approaches *(6:36)*
- [ ] 53. Pushing Docker images from your local to remote Docker hub repository *(8:28)*
- [ ] 54. Introduction to Docker Compose *(12:34)*
- [ ] 55. Running all microservice containers using Docker Compose command *(4:57)*
- [ ] 56. Demo of docker compose commands *(2:58)*
- [ ] 57. Deep dive on Docker commands *(10:45)*
- [ ] 58. Introduction to Docker extensions and LogsExplorer *(3:11)*
- [ ] 59. Funny memes of Docker *(6:35)*
- [ ] 60. Introduction to Cloud-native applications *(4:35)*

---

### Day 7 — Friday, March 13, 2026
**Section: Cloud-Native Applications & 15-Factor Methodology**

- [ ] 61. Important characteristics of cloud-native applications *(5:29)*
- [ ] 62. Differences between cloud-native Apps & Traditional enterprise Apps *(3:25)*
- [ ] 63. Introduction to 12-factor & 15-factor methodologies *(4:43)*
- [ ] 64. Deepdive on 15-factor methodology - Part 1 *(15:04)*
- [ ] 65. Deepdive on 15-factor methodology - Part 2 *(12:33)*
- [ ] 66. Deepdive on 15-factor methodology - Part 3 *(14:55)*
- [ ] 67. Introduction to Configurations Management challenges inside microservices *(6:54)*
- [ ] 68. How Configurations work in Spring Boot *(10:06)*
- [ ] 69. Reading configurations using @Value annotation *(13:26)*
- [ ] 70. Reading configurations using Environment interface *(7:03)*

---

### Day 8 — Saturday, March 14, 2026
**Section: Configuration Management**

- [ ] 71. Reading configurations using @ConfigurationProperties *(12:49)*
- [ ] 72. Introduction to Spring Boot profiles *(5:26)*
- [ ] 73. Demo of Spring Boot profiles inside accounts microservice *(10:05)*
- [ ] 74. Externalizing configurations using command-line, JVM & environment options *(6:01)*
- [ ] 75. Activating the profile using command-line, JVM & environment options *(9:39)*
- [ ] 76. Assignment to make SpringBoot profile changes inside loans & cards microservices *(2:07)*
- [ ] 77. Demo of Spring Boot profile changes inside loans & cards microservices *(8:32)*
- [ ] 78. Drawbacks of externalized configurations using SpringBoot alone *(6:30)*
- [ ] 79. Introduction to Spring Cloud Config *(6:33)*
- [ ] 80. Building Config Server using Spring Cloud Config *(10:02)*

---

### Day 9 — Sunday, March 15, 2026
**Section: Configuration Management (Spring Cloud Config)**

- [ ] 81. Reading configurations from the class path location of Config Server *(11:27)*
- [ ] 82. Updating Accounts Microservice to read properties from Config Server *(9:31)*
- [ ] 83. Updating Loans & Cards Microservice to read properties from Config Server *(5:24)*
- [ ] 84. Reading configurations from a file system location *(5:08)*
- [ ] 85. Reading configurations from a GitHub repository *(11:41)*
- [ ] 86. Encryption & Decryption of properties inside Config server *(8:52)*
- [ ] 87. Refresh configurations at runtime using refresh actuator path *(17:41)*
- [ ] 88. Refresh configurations at runtime using Spring Cloud Bus *(15:45)*
- [ ] 89. Refresh config at runtime using Spring Cloud Bus & Spring Cloud Config monitor *(15:29)*
- [ ] 90. Updating Docker Compose file to adapt Config Server changes - Part 1 *(12:15)*

---

### Day 10 — Monday, March 16, 2026
**Section: Config Server + MySQL DB Integration**

- [ ] 91. Introduction to Liveness and Readiness probes *(10:13)*
- [ ] 92. Updating Docker Compose file to adapt Config Server changes - Part 2 *(11:32)*
- [ ] 93. Optimizing Docker Compose file *(8:37)*
- [ ] 94. Generating Docker images and pushing them into Docker Hub *(6:47)*
- [ ] 95. Testing Config Server changes end to end using Docker compose & default profile *(12:17)*
- [ ] 96. Preparing Docker Compose files for QA & prod profiles *(6:05)*
- [ ] 97. Create MySQL DB containers for microservices *(18:30)*
- [ ] 98. Update microservices code to replace H2 DB with MySQL DB *(14:58)*
- [ ] 99. Update docker compose file to create & use MySQL DB *(14:53)*
- [ ] 100. Running microservices & MySQL DB containers using docker compose file *(7:51)*

---

### Day 11 — Tuesday, March 17, 2026
**Section: Service Discovery & Registration (Eureka)**

- [ ] 101. Demo of Docker network concept *(7:05)*
- [ ] 102. Brief introduction about microservices traffic *(4:55)*
- [ ] 103. Introduction to the Service Discovery & Registration inside microservices *(5:07)*
- [ ] 104. Why not traditional load balancers for Microservices *(11:29)*
- [ ] 105. Service Discovery & Registration inside microservices *(5:58)*
- [ ] 106. How Client side Service Discovery & Load-balancing works *(13:19)*
- [ ] 107. Spring Cloud support for Service Discovery & Registration *(8:27)*
- [ ] 108. Setup Service Discovery agent using Eureka server *(14:32)*
- [ ] 109. Make code changes in Accounts microservice to connect Eureka Server *(11:02)*
- [ ] 110. Make code changes in Loans & Cards microservice to connect Eureka Server *(6:53)*

---

### Day 12 — Wednesday, March 18, 2026
**Section: Service Discovery (continued)**

- [ ] 111. De-registration from Eureka server when microservices shutdown *(5:31)*
- [ ] 112. Demo of heartbeats mechanism to Eureka server from clients *(3:22)*
- [ ] 113. Feign Client code changes to invoke other microservices - Part 1 *(10:55)*
- [ ] 114. Feign Client code changes to invoke other microservices - Part 2 *(18:58)*
- [ ] 115. Eureka Self-Preservation mode to avoid network trap issues *(12:55)*
- [ ] 116. Generating Docker images with Service Discovery changes & push them into Docker Hub *(5:55)*
- [ ] 117. Updating Docker Compose file to adapt Service Discovery changes *(6:29)*
- [ ] 118. Starting all the microservices using docker compose file *(7:58)*
- [ ] 119. Demo of Client Side Service Discovery & Load balancing *(6:00)*
- [ ] 120. IMPORTANT NOTE ON GRAALVM *(0:18)*

---

### Day 13 — Thursday, March 19, 2026
**Section: API Gateway (Spring Cloud Gateway)**

- [ ] 121. Challenges while dealing external communication in microservices *(4:59)*
- [ ] 122. Why we need a Edge Server or API Gateway inside microservices *(9:45)*
- [ ] 123. Introduction to Spring Cloud Gateway *(5:53)*
- [ ] 124. Deep dive on Spring Cloud Gateway internal architecture *(7:37)*
- [ ] 125. Building Edge Server using Spring Cloud Gateway *(11:36)*
- [ ] 126. Demo of Edge Server with default routing configs *(9:40)*
- [ ] 127. Make changes inside Gateway server to accept service names with lower case *(2:27)*
- [ ] 128. Implementing Custom Routing using Spring Cloud Gateway *(12:02)*
- [ ] 129. Demo of addResponseHeader filter *(7:02)*
- [ ] 130. Implementing Cross cutting concerns Tracing & Logging using Gateway - Part 1 *(13:12)*

---

### Day 14 — Friday, March 20, 2026
**Section: API Gateway (continued) + Resiliency intro**

- [ ] 131. Implementing Cross cutting concerns Tracing & Logging using Gateway - Part 2 *(14:12)*
- [ ] 132. Design patterns around API Gateway *(9:39)*
- [ ] 133. Generating and pushing Docker images with Spring Cloud Gateway changes *(6:42)*
- [ ] 134. Updating Docker Compose file to adapt Spring Cloud Gateway changes *(9:00)*
- [ ] 135. Introduction to the need of Resiliency inside microservices *(9:03)*
- [ ] 136. Typical use case or scenario for the need of Resiliency *(4:29)*
- [ ] 137. Deepdive on Circuit Breaker pattern *(7:20)*
- [ ] 138. Three states of Circuit Breaker pattern *(4:50)*
- [ ] 139. Implementing Circuit Breaker pattern in Gateway - Part 1 *(17:06)*
- [ ] 140. Implementing Circuit Breaker pattern in Gateway - Part 2 *(5:30)*

---

### Day 15 — Saturday, March 21, 2026
**Section: Resiliency (RESILIENCE4J)**

- [ ] 141. Implementing Circuit Breaker pattern with Feign Client - Part 1 *(9:42)*
- [ ] 142. Implementing Circuit Breaker pattern with Feign Client - Part 2 *(7:21)*
- [ ] 143. Http timeout configurations *(10:28)*
- [ ] 144. Introduction to Retry pattern *(4:13)*
- [ ] 145. Implementing Retry pattern in Gateway *(10:48)*
- [ ] 146. Implementing Retry pattern in accounts - Part 1 *(13:06)*
- [ ] 147. Implementing Retry pattern in accounts - Part 2 *(8:48)*
- [ ] 148. Introduction to Rate Limitter pattern *(4:51)*
- [ ] 149. Introduction to Redis RateLimiter in Gateway Server *(9:32)*
- [ ] 150. Implementing Redis RateLimiter in Gateway Server *(9:50)*

---

### Day 16 — Sunday, March 22, 2026
**Section: Resiliency (continued) + Observability begins**

- [ ] 151. Implementing RateLimiter pattern in accounts *(8:20)*
- [ ] 152. Introduction to Bulkhead pattern *(6:55)*
- [ ] 153. Aspect order of Resiliency patterns *(2:30)*
- [ ] 154. Demo of Resiliency patterns using Docker containers & Docker compose *(7:25)*
- [ ] 155. Introduction to Observability And Monitoring Of Microservices *(5:48)*
- [ ] 156. Observability vs. Monitoring *(9:28)*
- [ ] 157. Introduction to centralized logging or Log Aggregation in microservices *(4:56)*
- [ ] 158. Introduction to managing logs with Grafana, Loki & Promtail *(6:50)*
- [ ] 159. IMPORTANT NOTE ON PROMTAIL *(0:36)*
- [ ] 160. Sample demo of logging using Grafana, Loki & promtail - Theory *(5:39)*

---

### Day 17 — Monday, March 23, 2026
**Section: Observability & Monitoring (Loki, Prometheus, Grafana, Tempo)**

- [ ] 161. Implementing logging using Grafana, Loki & promtail - Part 1 *(16:15)*
- [ ] 162. Implementing logging using Grafana, Loki & promtail - Part 2 *(6:49)*
- [ ] 163. Implementing logging using Grafana, Loki & promtail - Part 3 *(13:21)*
- [ ] 164. Managing metrics & monitoring with Actuator, Micrometer, Prometheus & Grafana *(8:32)*
- [ ] 165. Setup of micrometer inside microservices *(7:11)*
- [ ] 166. Setup of prometheus inside microservices *(7:51)*
- [ ] 167. Demo of Prometheus *(9:59)*
- [ ] 168. Demo of Prometheus & Grafana integration *(3:42)*
- [ ] 169. Demo of Grafana inbuilt & custom Dashboards *(9:31)*
- [ ] 170. Create Alerts & Send notifications using Grafana - Approach 1 *(11:19)*

---

### Day 18 — Tuesday, March 24, 2026
**Section: Observability (continued) + Security intro**

- [ ] 171. Create Alerts & Send notifications using Grafana - Approach 2 *(7:38)*
- [ ] 172. Introduction to Distributed Tracing in microservices *(9:47)*
- [ ] 173. Introduction to OpenTelemetry *(6:08)*
- [ ] 174. Implement OpenTelemetry changes inside microservices *(9:19)*
- [ ] 175. Implementing Tracing using Grafana, Tempo & OpenTelemetry - Part 1 *(7:28)*
- [ ] 176. Implementing Tracing using Grafana, Tempo & OpenTelemetry - Part 2 *(4:54)*
- [ ] 177. Implementing Tracing using Grafana, Tempo & OpenTelemetry - Part 3 *(5:31)*
- [ ] 178. Navigating to Tempo from Loki logs *(5:04)*
- [ ] 179. Conclusion of Observability and Monitoring *(2:53)*
- [ ] 180. Introduction to Microservices Security *(5:29)*

---

### Day 19 — Wednesday, March 25, 2026
**Section: Microservices Security (OAuth2, OpenID Connect, KeyCloak)**

- [ ] 181. Problems that OAuth2 solves *(9:28)*
- [ ] 182. Introduction to OAuth2 *(5:24)*
- [ ] 183. OAuth2 jargons or terminologies or roles *(8:43)*
- [ ] 184. What is OpenID Connect & why it is important *(9:01)*
- [ ] 185. Introduction to IAM products & why KeyCloak *(3:34)*
- [ ] 186. Deep dive of Client Credentials grant type flow *(7:42)*
- [ ] 187. Securing Gateway server using Client Credentials grant type flow - Theory *(10:31)*
- [ ] 188. Setup Auth server using KeyCloak *(5:14)*
- [ ] 189. Register client details inside KeyCloak for Client credentials grant flow *(5:18)*
- [ ] 190. Getting Access token from Auth Server in Client credentials grant flow *(8:02)*

---

### Day 20 — Thursday, March 26, 2026
**Section: Security (continued)**

- [ ] 191. Securing Gateway server as a Resource server - Part 1 *(13:47)*
- [ ] 192. Securing Gateway server as a Resource server - Part 2 *(7:30)*
- [ ] 193. Implement Authorization inside Gateway server using Roles - Part 1 *(11:26)*
- [ ] 194. Implement Authorization inside Gateway server using Roles - Part 2 *(4:18)*
- [ ] 195. Deep dive of Authorization Code grant type flow *(12:11)*
- [ ] 196. Securing Gateway server using Authorization Code grant type flow - Theory *(6:38)*
- [ ] 197. Register client & end user inside KeyCloak for Authorization code grant flow *(7:05)*
- [ ] 198. Demo of Authorization code grant type flow *(9:07)*
- [ ] 199. Demo of Microservices Security using Docker containers & Docker compose - Part 1 *(6:01)*
- [ ] 200. Demo of Microservices Security using Docker containers & Docker compose - Part 2 *(12:17)*

---

### Day 21 — Friday, March 27, 2026
**Section: Event-Driven Microservices (RabbitMQ, Spring Cloud Functions & Stream)**

- [ ] 201. Introduction to Event-driven microservices *(7:38)*
- [ ] 202. Introduction to Event-driven models *(3:26)*
- [ ] 203. What we are going to build using a pub sub model *(6:01)*
- [ ] 204. Introduction to RabbitMQ *(7:31)*
- [ ] 205. Why to use Spring Cloud Function *(9:44)*
- [ ] 206. Develop message microservice using Spring Cloud Functions - Part 1 *(6:05)*
- [ ] 207. Develop message microservice using Spring Cloud Functions - Part 2 *(9:34)*
- [ ] 208. Develop message microservice using Spring Cloud Functions - Part 3 *(9:58)*
- [ ] 209. Why to use Spring Cloud Stream *(8:10)*
- [ ] 210. Update message & accounts microservices to stream & process the events - Part 1 *(14:29)*

---

### Day 22 — Saturday, March 28, 2026
**Section: Event-Driven (RabbitMQ continued) + Kafka**

- [ ] 211. Demo of Async communication or event streaming using Rabbit MQ - Part 1 *(11:47)*
- [ ] 212. Update message & accounts microservices to stream & process the events - Part 2 *(14:09)*
- [ ] 213. Demo of Async communication or event streaming using Rabbit MQ - Part 2 *(4:04)*
- [ ] 214. Demo of Async comm or event streaming using Docker containers & Docker compose *(8:33)*
- [ ] 215. Apache Kafka Vs RabbitMQ *(4:18)*
- [ ] 216. Introduction to Apache Kafka *(15:27)*
- [ ] 217. Producer and Consumer side stories *(9:43)*
- [ ] 218. Installation of Apache Kafka *(2:14)*
- [ ] 219. Implement & Demo of Async communication or event streaming using Kafka *(11:06)*
- [ ] 220. Demo of Async comm or event streaming using Docker containers & Docker Compose *(11:07)*

---

### Day 23 — Sunday, March 29, 2026
**Section: Kubernetes**

- [ ] 221. Introduction to the challenges related to container orchestration *(8:40)*
- [ ] 222. Introduction to Kubernetes *(5:30)*
- [ ] 223. Deep dive on Kubernetes internal architecture *(14:35)*
- [ ] 224. Setup a local Kubernetes cluster using Docker Desktop *(10:03)*
- [ ] 225. Deploying the Kubernetes Dashboard UI *(22:06)*
- [ ] 226. Deep dive on Kubernetes YAML configurations to deploy a microservice *(16:57)*
- [ ] 227. Deploying ConfigServer into Kubernetes Cluster *(6:41)*
- [ ] 228. Create environment variables inside Kubernetes Cluster using ConfigMap *(7:20)*
- [ ] 229. Preparing Kubernetes manifest files for remaining microservices *(9:29)*
- [ ] 230. Deploying remaining microservices into Kubernetes Cluster *(11:50)*

---

### Day 24 — Monday, March 30, 2026
**Section: Kubernetes (continued) + Helm intro**

- [ ] 231. Automatic Self healing inside Kubernetes cluster *(6:01)*
- [ ] 232. Automatic Rollout & Rollback inside Kubernetes cluster *(13:26)*
- [ ] 233. Introduction to Kubernetes Service types *(11:10)*
- [ ] 234. Demo of Kubernetes Service types *(6:50)*
- [ ] 235. Problems with manually created Kubernetes manifest files *(5:48)*
- [ ] 236. Introduction to Helm & the problems that it solves *(10:05)*
- [ ] 237. Installing Helm *(5:35)*
- [ ] 238. IMPORTANT NOTE ON BITNAMI IMAGES & HELM CHARTS *(1:07)*
- [ ] 239. Installing a sample Helm Chart *(11:34)*
- [ ] 240. Understanding Helm Chart structure *(8:23)*

---

### Day 25 — Tuesday, March 31, 2026
**Section: Helm**

- [ ] 241. Creating our own Helm chart & template files *(17:00)*
- [ ] 242. Creating Helm chart for Accounts microservice *(11:09)*
- [ ] 243. Creating Helm charts for other microservices *(7:01)*
- [ ] 244. Creating Helm charts for Dev, QA and Prod environment *(8:41)*
- [ ] 245. Demo of helm template command *(5:34)*
- [ ] 246. Install KeyCloak in Kubernetes Cluster using Helm Chart *(12:10)*
- [ ] 247. Install Kafka in Kubernetes Cluster using Helm Chart *(7:22)*
- [ ] 248. Install Prometheus in Kubernetes Cluster using Helm Chart *(6:06)*
- [ ] 249. Install Grafana Loki & Tempo in Kubernetes Cluster using Helm Chart *(5:44)*
- [ ] 250. Install Grafana in Kubernetes Cluster using Helm Chart *(7:01)*

---

### Day 26 — Wednesday, April 1, 2026
**Section: Helm (continued) + Spring Cloud Kubernetes**

- [ ] 251. Install eazybank microservices in Kubernetes Cluster using Helm Chart *(10:12)*
- [ ] 252. Demo of helm upgrade command *(5:24)*
- [ ] 253. Demo of helm history and rollback commands *(3:39)*
- [ ] 254. Demo of helm uninstall command *(4:30)*
- [ ] 255. Quick revision of important helm commands *(3:34)*
- [ ] 256. Introduction to Server-side service discovery and load balancing *(7:52)*
- [ ] 257. How to setup discovery server in K8s cluster using spring cloud kubernetes *(10:58)*
- [ ] 258. Install spring cloud kubernetes discovery server in K8s cluster *(4:10)*
- [ ] 259. Making Kubernetes Discovery Client changes in microservices - Part 1 *(9:30)*
- [ ] 260. Making Kubernetes Discovery Client changes in microservices - Part 2 *(5:45)*

---

### Day 27 — Thursday, April 2, 2026
**Section: GKE (Google Kubernetes Engine) + Kubernetes Ingress**

- [ ] 261. Updating Helm charts for Kubernetes Discovery Server changes *(11:39)*
- [ ] 262. Demo of Server-side service discovery and load balancing *(5:22)*
- [ ] 263. Kubernetes support by Cloud providers *(2:55)*
- [ ] 264. Set up Google Cloud account & install Google Cloud SDK *(8:01)*
- [ ] 265. Create a Kubernetes cluster in Google Cloud *(3:18)*
- [ ] 266. Installing all our microservices and supporting components in Google Cloud K8s *(9:56)*
- [ ] 267. Demo of eazybank microservices using Google Cloud Kubernetes Cluster *(9:23)*
- [ ] 268. Validate Grafana components in Google Cloud Kubernetes Cluster *(4:15)*
- [ ] 269. Deleting the Google Cloud Kubernetes Cluster *(4:47)*
- [ ] 270. Quick introduction to Kubernetes Ingress *(3:43)*

---

### Day 28 — Friday, April 3, 2026
**Section: Ingress + Service Mesh + mTLS + Spring Boot BOM**

- [ ] 271. Deep dive on Kubernetes Ingress & Ingress Controller *(11:00)*
- [ ] 272. Benefits of Kubernetes Ingress & the kind of traffic it handles *(7:33)*
- [ ] 273. Introduction to Service Mesh & it's capabilities *(11:40)*
- [ ] 274. Introduction to Service mesh components *(6:55)*
- [ ] 275. Introduction to mTLS & deep dive on how TLS works *(14:48)*
- [ ] 276. How does mTLS works *(11:35)*
- [ ] 277. Optimizing Microservices Development with Spring Boot BOM - Part 1 *(3:41)*
- [ ] 278. Optimizing Microservices Development with Spring Boot BOM - Part 2 *(9:00)*
- [ ] 279. Optimizing Microservices Development with Spring Boot BOM - Part 3 *(13:39)*
- [ ] 280. Optimizing Microservices Development with Spring Boot BOM - Part 4 *(7:35)*

---

### Day 29 — Saturday, April 4, 2026
**Section: Shared Libraries + Course Wrap-up**

- [ ] 281. Shared Libraries in Microservices - Part 1 *(6:54)*
- [ ] 282. Shared Libraries in Microservices - Part 2 *(8:53)*
- [ ] 283. Congratulations & Thank You *(2:25)*

---

## Notes

- Each video = 1 git commit. Suggested commit format: `feat(section-name): video title`
- The 29-day schedule runs every day including weekends. Adjust the end date if you take days off.
- Days 1-15 are heavier sections (complex coding); days 23-28 are Kubernetes/Helm heavy — plan accordingly.
