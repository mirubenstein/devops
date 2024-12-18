# Tools Overview

## Infrastructure & Platform

### Cloud Platforms
Public and Private Cloud Platforms.
- **Azure**
- **AWS**
- **Google Cloud Platform**

### Operating Systems
Server Operating Systems.
- **Azure Virtual Machines**

### Server Access
Secure remote access solutions for network access IE DB migrations?
- **Azure Bastion**

### Distributed Filesystems
Networked Distributed Filesystems.
- **Azure Files**
- **GlusterFS**
- **Ceph**

### Infrastructure as Code (IaC)
Provisioning cloud infrastructure declaratively.
- **Azure Resource Manager**
- **Microsoft Bicep**
- **Terraform**
- **Pulumi**
- **AWS CDK**
#### Shared Terraform Library
#### Configuration Drift Management

### Private Networks
Establishing private network connections to Azure.
- **Azure ExpressRoute**
- **AWS Direct Connect**
- **Google Cloud Interconnect**

### Cost Management
Monitoring and optimizing cloud costs.
- **Azure Cost Management**
- **AWS Cost Explorer**
- **Google Cloud Cost Management**

### DNS Management
Managing DNS records and domains.
- **Azure DNS**
- **Cloudflare DNS**
- **Amazon Route 53**

### Configuration Management
Automating system configurations and deployments.
- **Azure Automation**
- **Ansible**

### Artifact Repository
Managing build artifacts and dependencies.
- **Azure Artifacts**
- **JFrog Artifactory**
- **Nexus Repository**

### Test Environment Spin-up
Creating temporary test environments.
- **Azure DevTest Labs**
- **Azure SDK**
- **Kubernetes**
- **Docker Compose**
- **Terraform**

### Task Scheduling
Automating and scheduling repetitive tasks.
- **Azure Automation**
- **Cron**
- **Apache Airflow**

### Task Automation
Connecting and automating workflows across apps.
- **Microsoft Power Automate**
- **Zapier**
- **IFTTT**

### Collaborative Infrastructure
Managing and deploying infrastructure as code.
- **Azure DevOps**
- **Env0**
- **Terraform Cloud**
- **Pulumi**
- **AWS CDK**

### Immutable Infrastructure Management
Automating the creation of machine images for cloud platforms to support immutable deployments.
- **Packer**
- **HashiCorp Nomad**
- **Immutable Server Patterns**

### Service Catalog Management
Maintains a catalog of available services
- **Azure Marketplace**
- **ServiceNow Service Catalog**
- **AWS Service Catalog**

### Infrastructure Discovery and Inventory
Automates the discovery and inventory of existing infrastructure.
- **Azure Resource Graph**
- **HashiCorp Consul**
- **AWS Config**

### Edge Computing
Deploying applications closer to data sources to reduce latency and improve performance.
- **Azure Stack Edge**
- **AWS Outposts**
- **Google Anthos**
- **Cloudflare Workers**

## Container & Application Management

### Orchestration
Managing containerized applications across clusters.
- **Azure Kubernetes Service**
- **Kubernetes**

### Containerization
Ensuring consistent environments for applications.
- **Azure Container Instances**
- **Docker**
- **[LXC](https://linuxcontainers.org/)**

### Container Registry
Managing container images.
- **Azure Container Registry**
- **Docker Hub**
- **Google Container Registry**
- **[Github Packages](https://docs.github.com/en/packages)**

### Container Security
Scanning container images for vulnerabilities, misconfigurations, and compliance issues before deployment.
- **Microsoft Defender for Containers**
- **Trivy**
- **Aqua Security**
- **Anchore**

### Service Discovery
Managing service discovery and configuration.
- **Azure Service Fabric**
- **Consul**
- **Eureka**

### Service Mesh
Managing microservices communication and security.
- **Azure Service Fabric**
- **Istio**
- **Linkerd**
- **Consul Connect**

### Storage Orchestration
Enabling Kubernetes-native storage orchestration and provisioning.
- **Rook**
- **StorageOS**
- **Portworx**

### Container Networking
Securing and monitoring container network communications using eBPF-based solutions.
- **Azure CNI**
- **Cilium**
- **Calico**
- **Weave Net**

### Container Lifecycle Management
- **Azure Kubernetes Service**
- **Rancher**
- **Portainer**
- **Kubernetes Operators**

## Deployment & Release

### CI/CD
Automating build, test, and deploy workflows.
- **Azure Pipelines**
- **GitHub Actions**

### CI/CD Pipelines
Simplifying CI/CD pipelines by enabling developers to construct and test them locally.
- **Azure DevOps Pipelines**
- **Dagger.io**
- **Tekton**
- **Buddy**

### Pipeline Observability
Monitoring and scaling CI pipelines for high-performance build and deployment workflows.
- **Azure DevOps Analytics**
- **Buildkite**
- **CircleCI Insights**
- **Datadog CI Visibility**

### Blue-Green Deployments
Switching traffic between environments.
- **Azure App Service Slots**
- **AWS Elastic Beanstalk**
- **Heroku Pipelines**

### Canary Releases
Gradually rolling out updates.
- **Spinnaker**
- **Istio**
- **LaunchDarkly**

### A/B Testing
Comparing versions in production.
- **Azure Application Insights**
- **LaunchDarkly**
- **Optimizely**

### Release Orchestration
Coordinates and automates the release process across multiple environments and teams.
- **Azure DevOps Release Pipelines**
- **XL Release**
- **ElectricFlow**

### Release Management
Deploying software versions reliably.
- **Azure DevOps Release Pipelines**
- **Octopus Deploy**
- **Jenkins X**
- **GoCD**
- **Harness**
- **Flux CD**
- **Spinnaker**

### Feature Flagging
Managing feature rollouts without redeploying code.
- **Azure App Configuration**
- **LaunchDarkly**
- **Split.io**
- **Flagsmith**

### GitOps
Declarative, GitOps continuous delivery tool for Kubernetes, facilitating automated deployment of applications.
- **Argo CD**
- **Flux**
- **GitLab CI/CD**
- **Weave GitOps**

## Testing & Quality

### Frontend Testing
Automated UI testing.
- **Microsoft Playwright**
- **Selenium**
- **Cypress**
- **Puppeteer**

### Backend Testing
API endpoint validation.
- **Azure Test Plans**
- **Postman**
- **SoapUI**
- **Insomnia**

### Performance Testing (Load, Stress, Volume)
Assessing application performance under load.
- **Azure Load Testing**
- **JMeter**
- **Locust**
- **Gatling**
- **k6**

### Unit Testing
Testing individual components for correctness.
- **Microsoft xUnit**
- **Microsoft MSTest**
- **Pytest**
- **JUnit**
- **Mocha**

### Integration Testing
Testing component interactions.
- **Azure Test SDK**
- **TestRail**
- **Postman**

### UI Component Testing
Developing and testing UI components in isolation.
- **Storybook**
- **Bit**
- **Styleguidist**

### Chaos Engineering
Testing system resilience by introducing failures.
- **Azure Chaos Studio**
- **Chaos Monkey**
- **Gremlin**
- **Litmus**

## Security & Compliance

### Vulnerabilities scanning
Scanning for vulnerabilities and ensuring compliance.
- **Microsoft Defender Vulnerability Management**
- **Snyk**
- **Qualys**

### Business Continuity and Disaster Recovery
Comprehensive readiness against catastrophic events.
- **Azure Site Recovery**
- **Zerto**
- **Veeam**

### Identity and Access Management (IAM)
Managing user authentication, authorization, and identity.
- **Azure AD B2C**
- **AWS Cognito**
- **Auth0**
- **Okta**
- **Keycloak**
- **OneLogin**

### Multi-Factor Authentication (MFA)
Securing access with multiple authentication factors.
- **Azure AD MFA**
- **Duo Security**
- **Google Authenticator**
- **Okta Verify**

### Secret Management
Securely managing sensitive information.
- **Azure Key Vault**
- **HashiCorp Vault**
- **AWS Secrets Manager**

### Data Encryption
Encrypting data in transit and at rest.
- **TLS/SSL Azure App Service**
- **Let's Encrypt**
- **HashiCorp Vault**

### Compliance as Code
Automating compliance checks via code.
- **Azure Policy**
- **Open Policy Agent**
- **Chef InSpec**
- **Terraform Compliance**

### Compliance Reporting and Auditing
Automates compliance reporting and auditing processes.
- **Azure Policy**
- **Splunk Enterprise Security**
- **AWS Audit Manager**

### Governance & Policy Management
Ensures that organizational policies.
- **Azure Policy**
- **HashiCorp Sentinel**
- **Open Policy Agent (OPA)**
- **Terraform Cloud Governance**

### VPN
Managing VPN routing and firewall.
- **Azure VPN Gateway**
- **OpenVPN**
- **WireGuard**
- **Cisco AnyConnect**

### Cloud Security Posture Management
Managing and improving the security posture across cloud environments by identifying and mitigating vulnerabilities, ensuring compliance, and maintaining a secure infrastructure.
- **Microsoft Defender for Cloud**
- **Wiz**
- **Orca Security**
- **Lacework**
- **Prisma Cloud**

### API Security
Testing and monitoring API security to protect APIs from threats.
- **Azure API Management**
- **Salt Security**
- **42Crunch**
- **Noname Security**
- **Akamai API Security**

## Monitoring & Observability

### Monitoring and Logging
Platform and application monitoring.
- **Azure Monitor**
- **Datadog**
- **New Relic**
- **Prometheus**
- **Grafana**

### APM (Application Performance Monitoring)
End-to-end application performance monitoring.
- **Azure Application Insights**
- **Dynatrace**
- **AppDynamics**
- **Elastic APM**

### Database Observability
Monitoring database performance and health.
- **Azure Database Insights**
- **SolarWinds Database Performance Analyzer**
- **Datadog Database Monitoring**
- **Percona Monitoring and Management (PMM)**
- **Datadog Database Monitoring**
- **New Relic Database Explorer**

### Distributed Tracing
Tracking requests across microservices.
- **Azure Application Insights**
- **Jaeger**
- **Zipkin**
- **OpenTelemetry**

### Log Aggregation
Centralizing and analyzing logs.
- **Azure Log Analytics**
- **ELK Stack**
- **Splunk**
- **Graylog**
- **Grafana Loki**
- **Fluentd**

### SLA/RPO/RTO
Service level monitoring and reporting.
- **Azure Service Health**
- **StatusPage**
- **Better Uptime**
- **Service Documentation**
- **PagerDuty**

### Unified Dashboards and Reporting
- **Azure Dashboards**
- **Grafana Loki**
- **Datadog Dashboards**
- **Kibana**

## Development Tools & Environment

### IDE
Integrated Development Environments.
- **Microsoft Visual Studio Code**
- **JetBrains Suite**
- **Eclipse**
- **IntelliJ IDEA**
- **JetBrains WebStorm**
#### IDE Shared Config
##### IDE share
- **Microsoft Visual Studio Live Share**
#### Pair Programming

### Remote Development Environments
Cloud-based development environments.
- **Microsoft GitHub Codespaces**
- **GitPod**
- **Cloud9**
- **AWS Cloud9**

### Environment Management
Managing development environments.
- **Azure Dev Box**
- **Docker**
- **Vagrant**
- **Pipenv**
- **Virtualenv**
- **Conda**
#### Environment Provisioning Templates

### Version Manager
Managing multiple versions of languages and tools.
- **nvm**
- **pyenv**
- **sdkman**
- **asdf**
- **[uv](https://github.com/astral-sh/uv)**

### Build Tools
Compiling and building applications.
- **Microsoft MSBuild**
- **Maven**
- **Gradle**
- **npm**
- **webpack**

### AI Code Completion
AI-powered coding assistance.
- **Microsoft GitHub Copilot**
- **Amazon CodeWhisperer**
- **Tabnine**
- **Kite**

### Code Documentation
Documenting code and APIs.
- **Microsoft DocFX**
- **Swagger/OpenAPI**
- **JSDoc**
- **Sphinx**
- **Doxygen**
- **Heredoc**
- **asyncdocs**

### API Documentation
Managing API documentation.
- **Azure API Management**
- **Postman**
- **Swagger UI**
- **ReadMe**
- **Stoplight**
- **Redoc**
- **API Blueprint**

### Developer Productivity Analytics
Improving developer productivity by understanding workflow efficiencies, identifying bottlenecks, and enhancing overall development performance.
- **Microsoft GitHub Insights**
- **LinearB**
- **Waydev**
- **GitPrime**
- **Code Climate Velocity**

## Code Quality & Review

### Code Review
Code review platforms and tools.
- **Azure DevOps Pull Requests**
- **Microsoft GitHub Pull Requests**
- **Gerrit**
- **GitLab Merge Requests**
- **Bitbucket**
#### Git Review Template

### Linting
Code style and error checking.
- **Microsoft StyleCop**
- **ESLint**
- **Pylint**
- **SonarLint**
- **Rubocop**

### Security Checks
Code security scanning.
- **Microsoft Defender for Cloud**
- **SonarQube**
- **Checkmarx**
- **Fortify**
- **Snyk**
- **Dependabot**

### Code Review Automation
Automated code review tools.
- **Microsoft GitHub Actions**
- **Codecov**
- **CodeClimate**
- **DeepSource**
- **DeepCode**
- **Codacy**
- **Reviewdog**

### Code Analysis
Static and dynamic code analysis.
- **Microsoft CodeQL**
- **SonarQube**
- **Coverity**
- **PMD**

### License Management
Managing software licenses.
- **WhiteSource**
- **Black Duck**
- **FOSSA**
- **Sourcetrail**

### Shared Libraries
- **Core libraries and utilities**
- **Design systems and UI components**
- **Configuration and standards**
- **Data models and schemas**
- **API definitions and documentation**
- **Build and deployment scripts**
- **Security and authentication modules**
- **Logging and monitoring tools**
- **Test frameworks and utilities**
- **Documentation and knowledge base**

## Version Control & Collaboration

### Version Control
Source code version control.
- **Azure Repos**
- **Microsoft GitHub**
- **GitLab**
- **Mercurial**
- **Subversion (SVN)**
#### Git Commit Template

### Version Control Branching
Branch management strategies.
- **GitHub Flow**
- **GitFlow**
- **Trunk Based Development**
- **Rebase**

### Versioning
Managing software versions.
- **Semantic Versioning**
- **Calendar Versioning**
- **GitVersion**
- **CalVer**
- **UUIDs**

### API Versioning
Managing API versions.
- **Azure API Management**
- **Swagger/OpenAPI**
- **URI Versioning**
- **GraphQL**

## Communication & Project Management

### Messaging
Team communication platforms.
- **Microsoft Teams**
- **Slack**
- **Discord**

### ChatOps
Chat-based operations tools.
- **Microsoft Teams Bots**
- **Hubot**
- **Slack Workflows**

### Issue Tracking
Managing tasks and issues.
- **Azure Boards**
- **Microsoft GitHub Issues**
- **Microsoft Project**
- **Jira**
- **Linear**
- **Trello**
- **Asana**

#### Ticket Templates
- **Girkin**

### Documentation
Managing project documentation.
- **Microsoft SharePoint**
- **Confluence**
- **Notion**
- **MkDocs**
- **Sourcetrail**

### Incident Management
Handling operational incidents.
- **PagerDuty**
- **VictorOps**
- **Opsgenie**

### Incident Retrospective Tools
Post-incident analysis tools.
- **Blameless**
- **FireHydrant**
- **Jeli**
- **Post-Mortem by Loom**
- **RTIR**

### Change Management
Managing system changes.
- **Azure DevOps**
- **ServiceNow**
- **Jira Service Management**
- **ChangeGear**

### Diagram Tools
Creating technical diagrams.
- **Microsoft Visio**
- **Draw.io**
- **Lucidchart**
- **Mermaid**
- **PlantUML**

## API & Traffic Management

### Load Balancing
Layer 4 load balancing.
- **Azure Load Balancer**
- **HAProxy**
- **Nginx**
- **Traefik**

### Application Gateway
Layer 7 load balancing.
- **Azure App Gateway**
- **AWS Elastic Load Balancing**
- **Google Cloud Load Balancing**

### API Gateways
Managing API endpoints.
- **Azure API Management**
- **Kong**
- **API Gateway (AWS)**

### Proxy Management
Managing reverse proxies.
- **Azure Front Door**
- **Nginx**
- **Envoy**
- **Traefik**
- **Apache Traffic Server**

### CDN
Content delivery networks.
- **Azure CDN**
- **Cloudflare**
- **Akamai**
- **Fastly**
- **Amazon CloudFront**

## Database & Data Management

### Database Migration
Version control for databases.
- **Azure Database Migration Service**
- **Flyway**
- **Liquibase**
- **Alembic**

### Search and Indexing
Search engine solutions.
- **Azure Cognitive Search**
- **Elasticsearch**
- **Algolia**
- **Solr**

### Cache
Caching solutions.
- **Azure Cache for Redis**
- **Redis**
- **Memcached**
- **[ValKey](https://valkey.io/)**
- **Varnish Cache**

### Backup and Recovery
Data backup solutions.
- **Azure Backup**
- **Veeam**
- **Commvault**

## Integration & Messaging

### Distributed Messaging
Message queues and event streaming.
- **Azure Service Bus**
- **Azure Event Grid**
- **Azure Event Hubs**
- **RabbitMQ**
- **Apache Kafka**
- **Redis Pub/Sub**

## Analytics & Business Intelligence

### BI and Analytics
Business intelligence tools.
- **Microsoft Power BI**
- **Tableau**
- **Looker**
- **Metabase**

## Internationalization

### Localization
Translation and localization management.
- **Microsoft Translator**
- **Lokalise**
- **Crowdin**
- **Phrase**
- **Tolgee**
- **i18next**
- **Transifex**

## DataOps

### Data Pipeline Orchestration
Managing and automating data workflows to coordinate complex data processing tasks, ensuring data is reliably collected, transformed, and delivered to the right destinations.
- **Azure Data Factory**
- **Apache Airflow**
- **Dagster**
- **Prefect**

### Data Quality Management
Validating, cleansing, and monitoring data to maintain its integrity and reliability.
- **Azure Purview**
- **Great Expectations**
- **Apache Griffin**
- **Soda Core**
- **Monte Carlo**

### Data Version Control
Version control systems designed for data and machine learning models.
- **DVC (Data Version Control)**
- **LakeFS**
- **Pachyderm**

### Data Governance
Managing data policies, quality, and compliance to ensure data integrity and security across all systems.
- **Azure Purview**
- **Collibra**
- **Talend Data Governance**
- **Alation**

## MLOps

### Model Training & Experimentation
Facilitate the management of machine learning experiments, track performance metrics, and streamline the training process for developing robust models.
- **Azure Machine Learning**
- **MLflow**
- **Weights & Biases**
- **Kubeflow**
- **Amazon SageMaker**

### Model Serving
Platforms for deploying and serving machine learning models in production, ensuring that models are accessible, scalable, and can handle real-time inference requests.
- **Azure Machine Learning**
- **TensorFlow Serving**
- **Seldon Core**
- **BentoML**
- **Cortex**

### Model Monitoring
Tools for tracking machine learning model performance, detecting drift, and ensuring models continue to deliver accurate predictions over time.
- **Azure Machine Learning Model Monitoring**
- **Evidently AI**
- **WhyLabs**
- **Arize AI**
- **Neptune.ai**
