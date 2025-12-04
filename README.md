# cloud-platform-case-study

High-Level Summary:

Link: Designing Role-Based Secrets Injection using PAM/AAM APIs. Python script and Kubernetes manifests [Secret Management]

Link: Zero-Downtime Reliability: Architecting the Malina Observability Stack with FluentD and Centralized Parsing. [Logging]

Link: Performance as a Feature: Building and Integrating a Load Testing as a Service (LTaaS) Platform. [Load Testing]

Link: The Intelligent Edge: Offloading Auth and Traffic Management with Apigee in a PaaS. [API Gateway]

--------------------------------------------------------------------------------------------------------------------------------------

/infrastructure-as-code: Terraform/Ansible configuration for deploying core services (Zookeeper, FluentD agents, Apigee setup).

/load-testing-as-a-service: Sample load testing scripts (e.g., K6, Locust) and Kubernetes manifests for deploying the load generator workers.

/observability: FluentD configuration files for parsing logs and sample dashboards (YAML/JSON) for Splunk/ElasticSearch.

/security-automation: Scripts (e.g., Python/Shell) for connecting to the PAM/AAM API to retrieve secrets and inject them into Kubernetes pods.

/ci-cd-pipelines: Example Jenkinsfile showing a basic deployment pipeline that integrates secrets (d) and runs LTaaS (f) before deployment.
