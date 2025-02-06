# DevOps Development Lifecycle

---

## 1. Planning, Communication & Collaboration

### Communication/ChatOps
- **Platforms:** Microsoft Teams, Slack, Discord
- **ChatOps:** Microsoft Teams Bots, Hubot, Slack Workflows
    - Automated messaging groups/users on fail/pass ci/cd pipeline

### Project/Change Management
- **Issue Tracking:** Azure Boards, GitHub Issues, Microsoft Project, Jira, Linear, Trello, Asana
    - Linked to git repository
    - Ticket Template - bug, feature, etc Girkin?
    - Workflow template
- **Documentation:** SharePoint, Confluence, Notion, MkDocs, Sourcetrail
    - Consolidate to single source of truth enable linking so no duplication
- **Incident Management:** PagerDuty, VictorOps, Opsgenie, Blameless, FireHydrant, Jeli, Post-Mortem by Loom, RTIR
- **Change Management:** Azure DevOps, ServiceNow, Jira Service Management, ChangeGear

### Diagrams
- **Diagram Tools:** Microsoft Visio, Draw.io, Lucidchart, Mermaid, PlantUML
---

## 2. Development Environments & Tools

### IDEs
- **IDEs:** Visual Studio Code, JetBrains Suite (IntelliJ IDEA, WebStorm), Eclipse
    - Shared confgs and internal tooling for standardization

### Remote & Collaborative Development
- **Remote Environments:** GitHub Codespaces, GitPod, Cloud9, AWS Cloud9
- **Collaboration:** Visual Studio Live Share

### Environment & Build Management
- **Environment Management:** Azure Dev Box, Docker, Vagrant, Pipenv, Virtualenv, Conda
- **Version Managers:** nvm, pyenv, sdkman, asdf, [uv](https://github.com/astral-sh/uv)
- **Build Tools:** MSBuild, Maven, Gradle, npm, webpack

### Documentation
- **Code Documentation:** DocFX, JSDoc, Sphinx, Doxygen, Heredoc, asyncdocs
- **API Documentation:** Postman, Swagger UI, ReadMe, Stoplight, Redoc, API Blueprint

### Code Assistance
- **AI Code Completion:** GitHub Copilot, Amazon CodeWhisperer, Tabnine, Kite
- **Productivity Analytics:** GitHub Insights, LinearB, Waydev, GitPrime, Code Climate Velocity
---

## 3. Version Control & Code Quality

### Version Control & Branching
- **Systems:** Azure Repos, GitHub, GitLab, Mercurial, Subversion (SVN)
- **Branch Strategies:** GitHub Flow, GitFlow, Trunk Based Development, Rebase
- **Versioning Schemes:** Semantic Versioning, Calendar Versioning, GitVersion, CalVer, UUIDs
    - Automated changelog versioning
- **Default project structure:**
    - Gitignore
    - Readme template
    - ETC

### Code Review & Analysis
- **Defatult Commit Template:** Conventional commits, Commitizen, commitlint
- **Defatult PR Template:** Bitbucket, Github, Gitlab examples
- **Code Review Platforms:** Azure DevOps Pull Requests, GitHub Pull Requests, Gerrit, GitLab Merge Requests, Bitbucket
- **Linting & Static Analysis:** StyleCop, ESLint, Pylint, SonarLint, Rubocop, CodeQL, SonarQube, Coverity, PMD
- **Security Checks:** Microsoft Defender for Cloud, Checkmarx, Fortify, Snyk, Dependabot
- **Automated Review Tools:** GitHub Actions (for reviews), Codecov, CodeClimate, DeepSource, DeepCode, Codacy, Reviewdog

### License
- **License Management:** WhiteSource, Black Duck, FOSSA, Sourcetrail

### Shared Libraries/APIs:
#### 1. Security & Authentication
- **User Authentication:**
- **Single Sign-On (SSO):**
- **Access Control:**
- **Encryption/Decryption:**
- **Input Validation:**

#### 2. Logging, Monitoring & Metrics
- **Logging Libraries:**
- **Metrics & Telemetry:**

#### 3. Error Handling & Communication
- **Error Handling & Exceptions:**
- **Communication Libraries:**
  - **API Clients:**
  - **Message Queues:**

#### 4. Configuration & Data Access
- **Configuration Management:**
- **Database Access:**

#### 5. Testing & Utilities
- **Testing Frameworks:**
- **Utility Functions:**

#### 6. Core & Design Components
- **Core Libraries and Utilities:**
- **Design Systems & UI Components:**
- **Data Models & Schemas:**
- **Internationalization**
    - **Localization Tools:** Microsoft Translator, Lokalise, Crowdin, Phrase, Tolgee, i18next, Transifex
- **Accessibility:**
- **API Definitions & Documentation:**
- **Build and Deployment Scripts:**
- **Documentation & Knowledge Base:**


---

## 4. Continuous Integration / Delivery & Release

### CI/CD & Pipeline Management
- **CI/CD Platforms:** Azure Pipelines, GitHub Actions, Jenkins
- **Pipeline Tools:** Azure DevOps Pipelines, Dagger.io, Tekton, Buddy
- **Pipeline Observability:** Azure DevOps Analytics, Buildkite, CircleCI Insights, Datadog CI Visibility

### Deployment & Release Strategies
- **Blue-Green Deployments:** Azure App Service Slots, AWS Elastic Beanstalk, Heroku Pipelines
- **Canary Releases:** Spinnaker, Istio, LaunchDarkly
- **A/B Testing:** Application Insights, LaunchDarkly, Optimizely
- **Release Orchestration:** Azure DevOps Release Pipelines, XL Release, ElectricFlow
- **Feature Flagging:** Azure App Configuration, LaunchDarkly, Split.io, Flagsmith
- **GitOps:** Argo CD, Flux, GitLab CI/CD, Weave GitOps

---

## 5. Infrastructure, Deployment & Application Management

### Core Infrastructure
- **Cloud Providers:** Azure, AWS, Google Cloud Platform (public & private clouds)
- **Cloud Management:** Cloud Management Platforms (CMP), Hybrid Cloud Gateways
- **Cloud-Based Compute Services:** Azure Virtual Machines, AWS EC2, Google Compute Engine
- **Serverless Computing:** Azure Functions, AWS Lambda, Google Cloud Functions, IBM Cloud Functions
- **Network Connectivity:** Azure ExpressRoute, AWS Direct Connect, Google Cloud Interconnect
- **Virtual Networks & VPC:** Azure Virtual Network, AWS VPC, Google Cloud VPC
- **Cost Management:** Azure Cost Management, AWS Cost Explorer, Google Cloud Cost Management
- **DNS Management:** Azure DNS, Cloudflare DNS, Amazon Route 53
- **Messaging & Event Streaming:** Azure Service Bus, Azure Event Grid, Azure Event Hubs, RabbitMQ, Apache Kafka, Redis Pub/Sub

### Infrastructure as Code & Configuration Management
- **Infrastructure as Code:** Azure Resource Manager, Microsoft Bicep, Terraform, Pulumi, AWS CDK
    - Centralized repositories and modular libraries that standardize and accelerate deployments.
    - Collaborative Infrastructure tools Terraform Cloud etc?
- **Configuration Management:** Azure Automation, Ansible, Chef, Saltstack
    - Centralized repositories and modular libraries that standardize and accelerate deployments.

### Storage, Filesystems & Artifacts
- **Distributed Filesystems:** Azure Files, GlusterFS, Ceph
- **Artifact Repositories:** Azure Artifacts, JFrog Artifactory, Nexus Repository

### Containerization & Orchestration
- **Containers & Runtimes:** Docker, LXC, Azure Container Instances
- **Orchestration Platforms:** Azure Kubernetes Service, Kubernetes, Rancher, Kubernetes Operators
- **Container Registries:** Azure Container Registry, Docker Hub, Google Container Registry, GitHub Packages
- **Container Security:** Microsoft Defender for Containers, Trivy, Aqua Security, Anchore
- **Service Discovery & Mesh:** Consul, Eureka, Istio, Linkerd, Consul Connect
- **Storage Orchestration:** Rook, StorageOS, Portworx
- **Container Networking:** Azure CNI, Cilium, Calico, Weave Net

### Environment Provisioning & Task Automation
- **Test Environment Spin-up:** Azure DevTest Labs, Docker Compose, Kubernetes, Terraform
- **Task Scheduling:** Cron, Apache Airflow, UiPath, Automation Anywhere, Blue Prism
- **Task Automation:** Microsoft Power Automate, Zapier, IFTTT
- **Immutable Infrastructure:** Packer, HashiCorp Nomad, Immutable Server Patterns

### Collaborative Infrastructure & Discovery
- **Service Catalogs:** Azure Marketplace, ServiceNow Service Catalog, AWS Service Catalog
- **Infrastructure Discovery:** Azure Resource Graph, AWS Config
- **Edge Computing:** Azure Stack Edge, AWS Outposts, Google Anthos, Cloudflare Workers
- **Server Access:** Azure Bastion

---

## 6. API & Traffic Management

- **Load Balancing:** Azure Load Balancer, HAProxy, Nginx, Traefik
- **Application Gateways:** Azure App Gateway, AWS Elastic Load Balancing, Google Cloud Load Balancing
- **API Gateways & Versioning:** Azure API Management, Kong, AWS API Gateway (*plus best practices for API versioning*)
- **GraphQL Gateways:** Apollo, Hasura
- **Proxy Management:** Azure Front Door, Nginx, Envoy, Traefik, Apache Traffic Server
- **CDN:** Azure CDN, Cloudflare, Akamai, Fastly, Amazon CloudFront

---

## 7. Security & Compliance

- **Vulnerability Scanning:** Microsoft Defender Vulnerability Management, Snyk, Qualys
- **Security Testing & Penetration:** Burp Suite, OWASP ZAP, Nmap, Metasploit
- **Business Continuity & Disaster Recovery:** Azure Site Recovery, Zerto, Veeam
- **Identity & Access Management:** Azure AD B2C, AWS Cognito, Auth0, Okta, Keycloak, OneLogin
- **Multi-Factor Authentication:** Azure AD MFA, Duo Security, Google Authenticator, Okta Verify
- **Secret Management:** Azure Key Vault, HashiCorp Vault, AWS Secrets Manager
- **Data Encryption:** TLS/SSL, Let's Encrypt, HashiCorp Vault
- **Compliance & Governance:** Azure Policy, Open Policy Agent, Chef InSpec, Terraform Compliance
- **Network Security:** VPN solutions (Azure VPN Gateway, OpenVPN, WireGuard, Cisco AnyConnect)
- **Cloud Security Posture:** Microsoft Defender for Cloud, Wiz, Orca Security, Lacework, Prisma Cloud
- **API Security:** Salt Security, 42Crunch, Noname Security, Akamai API Security

---

## 8. Testing & Quality Assurance

- **Frontend Testing:** Microsoft Playwright, Selenium, Cypress, Puppeteer
- **Backend/API Testing:** Azure Test Plans, Postman, SoapUI, Insomnia
- **Unit Testing:** xUnit, MSTest, Pytest, JUnit, Mocha
    - at least 70% coverage idealy closer to 80%
- **Integration Testing:** Azure Test SDK, TestRail, Postman
- **UI Component Testing:** Storybook, Bit, Styleguidist
- **Performance Testing:** Azure Load Testing, JMeter, Locust, Gatling, k6
- **Chaos Engineering:** Azure Chaos Studio, Chaos Monkey, Gremlin, Litmus

---

## 9. Monitoring, Observability & Incident Response

### Infrastructure & Application Monitoring
- **Monitoring Tools:** Azure Monitor, Datadog, New Relic, Prometheus, Grafana
- **APM Solutions:** Azure Application Insights, Dynatrace, AppDynamics, Elastic APM
- **Database Observability:** Azure Database Insights, SolarWinds Database Performance Analyzer, Datadog Database Monitoring, Percona Monitoring and Management, New Relic Database Explorer

### Tracing & Logging
- **Distributed Tracing:** Jaeger, Zipkin, OpenTelemetry
- **Log Aggregation:** Azure Log Analytics, ELK Stack, Splunk, Graylog, Grafana Loki, Fluentd, OpenTelemetry

### Service Levels & Dashboards
- **SLA/RPO/RTO Monitoring:** Azure Service Health, StatusPage, Better Uptime, PagerDuty
- **Unified Dashboards:** Azure Dashboards, Grafana, Datadog Dashboards, Kibana

---

## 10. Database & Data Management

- **Database Automation & Migration:** Azure Database Migration Service, Flyway, Liquibase, Alembic
- **Search & Indexing:** Azure Cognitive Search, Elasticsearch, Algolia, Solr
- **Caching Solutions:** Azure Cache for Redis, Redis, Memcached, ValKey, Varnish Cache
- **Backup & Recovery:** Azure Backup, Veeam, Commvault

---

## 11. Analytics, Business Intelligence & Data Visualization

- **BI & Analytics Platforms:** Microsoft Power BI, Tableau, Looker, Metabase
    - Data lake etc let BI make own reports
- **Data Visualization Libraries:** Plotly, D3.js, Apache Superset, Grafana

---

## 12. DataOps

- **Pipeline Orchestration:** Azure Data Factory, Apache Airflow, Dagster, Prefect
- **Data Quality Management:** Azure Purview, Great Expectations, Apache Griffin, Soda Core, Monte Carlo
- **Data Version Control:** DVC, LakeFS, Pachyderm
- **Data Governance:** Azure Purview, Collibra, Talend Data Governance, Alation

---

## 13. MLOps

- **Model Training & Experimentation:** Azure Machine Learning, MLflow, Weights & Biases, Kubeflow, Amazon SageMaker
- **Model Serving:** TensorFlow Serving, Seldon Core, BentoML, Cortex, Azure Machine Learning
- **Model Monitoring:** Azure Machine Learning Model Monitoring, Evidently AI, WhyLabs, Arize AI, Neptune.ai
- **Experiment Tracking:** Comet.ml, Polyaxon

---
