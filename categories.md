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


## Container & Application Management
### Orchestration
Managing containerized applications across clusters.
- **Kubernetes**
- **Azure Kubernetes Service**

### Containerization
Ensuring consistent environments for applications.
- **Docker**
- **Azure Container Instances**
- ** [LXC](https://linuxcontainers.org/) **

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


## Deployment & Release
### CI/CD
Automating build, test, and deploy workflows.
- **GitHub Actions**
- **Azure Pipelines**

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

### Release Management
Deploying software versions reliably.
- **Octopus Deploy**
- **Jenkins X**
- **GoCD**

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

### Performance Testing(Load, Stress, Volume)
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
### Security and Compliance
Scanning for vulnerabilities and ensuring compliance.
- **Snyk**
- **Microsoft Defender Vulnerability Management**
- **Qualys**

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

### VPN
Managing VPN routing and firewall.
- **OpenVPN**
- **WireGuard**
- **Cisco AnyConnect**


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

### Distributed Tracing
Tracking requests across microservices.
- **Jaeger**
- **Zipkin**
- **Azure Application Insights**
- **OpenTelemetry**

### Log Aggregatio
Centralizing and analyzing logs.
- **Azure Log Analytics**
- **ELK Stack**
- **Splunk**
- **Graylog**

### SLA/RPO/RTO
Service level monitoring and reporting.
- **Azure Service Health**
- **StatusPage**
- **Better Uptime**


## Development Tools & Environment
### IDE
Integrated Development Environments.
- **Visual Studio Code**
- **JetBrains Suite**
- **Visual Studio**
- **Eclipse**

### Remote Development Environments
Cloud-based development environments.
- **GitHub Codespaces**
- **GitPod**
- **Cloud9**

### Environment Management
Managing development environments.
- **Docker**
- **Vagrant**
- **Azure Dev Box**

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

### Code Documentation
Documenting code and APIs.
- **Swagger/OpenAPI**
- **JSDoc**
- **Sphinx**
- **Doxygen**

### API Documentation
Managing API documentation.
- **Postman**
- **Swagger UI**
- **ReadMe**
- **Stoplight**


## Code Quality & Review
### Code Review
Code review platforms and tools.
- **GitHub Pull Requests**
- **Azure DevOps Pull Requests**
- **Gerrit**
- **GitLab Merge Requests**

### Linting
Code style and error checking.
- **ESLint**
- **Pylint**
- **SonarLint**
- **StyleCop**

### Security Checks
Code security scanning.
- **SonarQube**
- **Checkmarx**
- **Fortify**
- **Snyk**

### Code Review Automation
Automated code review tools.
- **Codecov**
- **CodeClimate**
- **DeepSource**

### Code Analysis
Static and dynamic code analysis.
- **SonarQube**
- **Coverity**
- **CodeQL**

### License Management
Managing software licenses.
- **WhiteSource**
- **Black Duck**
- **FOSSA**


## Version Control & Collaboration
### Version Control
Source code version control.
- **Git**
- **Azure Repos**
- **GitHub**
- **GitLab**

### Version Control Branching
Branch management strategies.
- **GitFlow**
- **Trunk Based Development**
- **GitHub Flow**

### Versioning
Managing software versions.
- **Semantic Versioning**
- **Calendar Versioning**
- **GitVersion**

### API Versioning
Managing API versions.
- **Azure API Management**
- **Swagger/OpenAPI**
- **URI Versioning**


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

### Documentation
Managing project documentation.
- **Confluence**
- **Notion**
- **MkDocs**
- **Microsoft SharePoint**

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

### Change Management
Managing system changes.
- **ServiceNow**
- **Jira Service Management**
- **Azure DevOps**

### Diagram Tools
Creating technical diagrams.
- **Draw.io**
- **Lucidchart**
- **Mermaid**
- **PlantUML**
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

### CDN
Content delivery networks.
- **Azure CDN**
- **Cloudflare**
- **Akamai**
- **Fastly**


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

### Cache
Caching solutions.
- **Redis**
- **Memcached**
- **Azure Cache for Redis**
- **[ValKey](https://valkey.io/)**

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
