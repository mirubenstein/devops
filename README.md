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
- **Terraform**
- **Pulumi**
- **Azure Resource Manager**
- **Microsoft Bicep**
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
- **Ansible**
- **Azure Automation**

### Artifact Repository
Managing build artifacts and dependencies.
- **Azure Artifacts**
- **JFrog Artifactory**
- **Nexus Repository**

### Test Environment Spin-up
Creating temporary test environments.
- **Kubernetes**
- **Docker Compose**
- **Terraform**
- **Azure SDK**

### Task Scheduling
Automating and scheduling repetitive tasks.
- **Azure Automation**
- **Cron**
- **Apache Airflow**

### Task Automation
Connecting and automating workflows across apps.
- **Zapier**
- **IFTTT**
- **Microsoft Power Automate**

### Collaborative Infrastructure
Managing and deploying infrastructure as code.
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
- **ServiceNow Service Catalog**
- **AWS Service Catalog**

### Infrastructure Discovery and Inventory
Automates the discovery and inventory of existing infrastructure.
- **HashiCorp Consul**
- **Azure Resource Graph**
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
- **Kubernetes**
- **Azure Kubernetes Service**

### Containerization
Ensuring consistent environments for applications.
- **Docker**
- **Azure Container Instances**
- **[LXC](https://linuxcontainers.org/)**

### Container Registry
Managing container images.
- **Azure Container Registry**
- **Docker Hub**
- **Google Container Registry**
- **[Github Packages](https://docs.github.com/en/packages)**

### Container Security
Scanning container images for vulnerabilities, misconfigurations, and compliance issues before deployment.
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
- **Cilium**
- **Calico**
- **Weave Net**

### Container Lifecycle Management
- **Rancher**
- **Portainer**
- **Kubernetes Operators**

## Deployment & Release

### CI/CD
Automating build, test, and deploy workflows.
- **GitHub Actions**
- **Azure Pipelines**

### CI/CD Pipelines
Simplifying CI/CD pipelines by enabling developers to construct and test them locally.
- **Dagger.io**
- **Tekton**
- **Buddy**

### Pipeline Observability
Monitoring and scaling CI pipelines for high-performance build and deployment workflows.
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
- **LaunchDarkly**
- **Optimizely**

### Release Orchestration
Coordinates and automates the release process across multiple environments and teams.
- **XL Release**
- **Azure DevOps Release Pipelines**
- **ElectricFlow**

### Release Management
Deploying software versions reliably.
- **Octopus Deploy**
- **Jenkins X**
- **GoCD**
- **Harness**
- **Flux CD**
- **Spinnaker**

### Feature Flagging
Managing feature rollouts without redeploying code.
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
- **Selenium**
- **Cypress**
- **Puppeteer**
- **MS Playwright**

### Backend Testing
API endpoint validation.
- **Postman**
- **SoapUI**
- **Insomnia**

### Performance Testing (Load, Stress, Volume)
Assessing application performance under load.
- **JMeter**
- **Locust**
- **Gatling**
- **k6**

### Unit Testing
Testing individual components for correctness.
- **Pytest**
- **JUnit**
- **Mocha**
- **xUnit**

### Integration Testing
Testing component interactions.
- **Azure Test SDK**
- **TestRail**
- **Postman**

### Regression Testing
Ensuring existing functionality remains intact.
- **Selenium**
- **TestCafe**
- **Ranorex**

### UI Component Testing
Developing and testing UI components in isolation.
- **Storybook**
- **Bit**
- **Styleguidist**

### Chaos Engineering
Testing system resilience by introducing failures.
- **Chaos Monkey**
- **Gremlin**
- **Litmus**

## Security & Compliance

### Vulnerabilities scanning
Scanning for vulnerabilities and ensuring compliance.
- **Snyk**
- **Microsoft Defender Vulnerability Management**
- **Qualys**

### Business Continuity and Disaster Recovery
Comprehensive readiness against catastrophic events.
- **Azure Site Recovery**
- **Zerto**
- **Veeam**

### Identity and Access Management (IAM)
Managing user authentication, authorization, and identity.
- **AWS Cognito**
- **Azure AD B2C**
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
- **Open Policy Agent**
- **Chef InSpec**
- **Terraform Compliance**

### Compliance Reporting and Auditing
Automates compliance reporting and auditing processes.
- **Splunk Enterprise Security**
- **Azure Policy**
- **AWS Audit Manager**

### Governance & Policy Management
Ensures that organizational policies.
- **HashiCorp Sentinel**
- **Open Policy Agent (OPA)**
- **Terraform Cloud Governance**

### VPN
Managing VPN routing and firewall.
- **OpenVPN**
- **WireGuard**
- **Cisco AnyConnect**

### Cloud Security Posture Management
Managing and improving the security posture across cloud environments by identifying and mitigating vulnerabilities, ensuring compliance, and maintaining a secure infrastructure.
- **Wiz**
- **Orca Security**
- **Lacework**
- **Prisma Cloud**

### API Security
Testing and monitoring API security to protect APIs from threats.
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
- **Jaeger**
- **Zipkin**
- **Azure Application Insights**
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
- **Grafana Loki**
- **Datadog Dashboards**
- **Kibana**

## Development Tools & Environment

### IDE
Integrated Development Environments.
- **Visual Studio Code**
- **JetBrains Suite**
- **Visual Studio**
- **Eclipse**
- **IntelliJ IDEA**
- **JetBrains WebStorm**
#### IDE Shared Config
##### IDE share
- **Visual Studio Live Share**
#### Pair Programming

### Remote Development Environments
Cloud-based development environments.
- **GitHub Codespaces**
- **GitPod**
- **Cloud9**
- **AWS Cloud9**

### Environment Management
Managing development environments.
- **Docker**
- **Vagrant**
- **Azure Dev Box**
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
- **Maven**
- **Gradle**
- **npm**
- **webpack**

### AI Code Completion
AI-powered coding assistance.
- **GitHub Copilot**
- **Amazon CodeWhisperer**
- **Tabnine**
- **Kite**

### Code Documentation
Documenting code and APIs.
- **Swagger/OpenAPI**
- **JSDoc**
- **Sphinx**
- **Doxygen**
- **Heredoc**
- **asyncdocs**

### API Documentation
Managing API documentation.
- **Postman**
- **Swagger UI**
- **ReadMe**
- **Stoplight**
- **Redoc**
- **API Blueprint**

### Developer Productivity Analytics
Improving developer productivity by understanding workflow efficiencies, identifying bottlenecks, and enhancing overall development performance.
- **LinearB**
- **Waydev**
- **GitPrime**
- **Code Climate Velocity**

## Code Quality & Review

### Code Review
Code review platforms and tools.
- **GitHub Pull Requests**
- **Azure DevOps Pull Requests**
- **Gerrit**
- **GitLab Merge Requests**
- **Bitbucket**
#### Git Review Template

### Linting
Code style and error checking.
- **ESLint**
- **Pylint**
- **SonarLint**
- **StyleCop**
- **Rubocop**

### Security Checks
Code security scanning.
- **SonarQube**
- **Checkmarx**
- **Fortify**
- **Snyk**
- **Dependabot**

### Code Review Automation
Automated code review tools.
- **Codecov**
- **CodeClimate**
- **DeepSource**
- **DeepCode**
- **Codacy**
- **Reviewdog**

### Code Analysis
Static and dynamic code analysis.
- **SonarQube**
- **Coverity**
- **CodeQL**
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
- **Git**
- **Azure Repos**
- **GitHub**
- **GitLab**
- **Mercurial**
- **Subversion (SVN)**
#### Git Commit Template

### Version Control Branching
Branch management strategies.
- **GitFlow**
- **Trunk Based Development**
- **GitHub Flow**
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
- **Hubot**
- **Slack Workflows**
- **Microsoft Teams Bots**

### Issue Tracking
Managing tasks and issues.
- **Azure Boards**
- **Jira**
- **GitHub Issues**
- **Linear**
- **Trello**
- **Asana**
- **Microsoft Project**
#### Ticket Templates
- **Girkin**

### Documentation
Managing project documentation.
- **Confluence**
- **Notion**
- **MkDocs**
- **Microsoft SharePoint**
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
- **ServiceNow**
- **Jira Service Management**
- **Azure DevOps**
- **ChangeGear**

### Diagram Tools
Creating technical diagrams.
- **Draw.io**
- **Lucidchart**
- **Mermaid**
- **PlantUML**
- **Microsoft Visio**
- **Lucid**
- **Microsoft Visio**

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
- **Flyway**
- **Liquibase**
- **Alembic**

### Search and Indexing
Search engine solutions.
- **Elasticsearch**
- **Azure Cognitive Search**
- **Algolia**
- **Solr**

### Cache
Caching solutions.
- **Redis**
- **Memcached**
- **Azure Cache for Redis**
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
- **RabbitMQ**
- **Apache Kafka**
- **Redis Pub/Sub**
- **Event Grid**
- **Event Hubs**

## Analytics & Business Intelligence

### BI and Analytics
Business intelligence tools.
- **Power BI**
- **Tableau**
- **Looker**
- **Metabase**

## Internationalization

### Localization
Translation and localization management.
- **Lokalise**
- **Crowdin**
- **Phrase**
- **Tolgee**
- **i18next**
- **Transifex**

## DataOps

### Data Pipeline Orchestration
Managing and automating data workflows to coordinate complex data processing tasks, ensuring data is reliably collected, transformed, and delivered to the right destinations.
- **Apache Airflow**
- **Dagster**
- **Prefect**
- **dbt (data build tool)**

### Data Quality Management
Validating, cleansing, and monitoring data to maintain its integrity and reliability.
- **Great Expectations**
- **Apache Griffin**
- **Soda Core**
- **Monte Carlo**

### Data Version Control
Version control systems designed for data and machine learning models.
- **DVC (Data Version Control)**
- **LakeFS**
- **Pachyderm**

## MLOps

### Model Training & Experimentation
Facilitate the management of machine learning experiments, track performance metrics, and streamline the training process for developing robust models.
- **MLflow**
- **Weights & Biases**
- **Kubeflow**
- **Amazon SageMaker**

### Model Serving
Platforms for deploying and serving machine learning models in production, ensuring that models are accessible, scalable, and can handle real-time inference requests.
- **TensorFlow Serving**
- **Seldon Core**
- **BentoML**
- **Cortex**

### Model Monitoring
Tools for tracking machine learning model performance, detecting drift, and ensuring models continue to deliver accurate predictions over time.
- **Evidently AI**
- **WhyLabs**
- **Arize AI**
- **Neptune.ai**
