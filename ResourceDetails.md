# 🚀 Mandatory Azure Cloud Resources for DevOps Engineers

## 🧱 Compute (Running Workloads)

* **Azure Virtual Machine (VM):** Run Windows/Linux workloads.
* **Azure App Service (for Containers):** Platform to run web apps or APIs in containers.
* **Azure Kubernetes Service (AKS):** Managed Kubernetes cluster.
* **Azure Container Registry (ACR):** Secure storage for container images.
* **Azure Resource Manager (ARM):** Infrastructure as Code (IaC) tool for Azure.
* **Azure Container Instances (ACI):** Run containers without managing servers.
* **Azure Functions:** Serverless compute (event-driven).

## 🗃️ Storage (Data & Artifacts)

* **Azure Blob Storage:** Store logs, backups, and Terraform state files.
* **Azure Files:** Managed file shares for applications.
* **Azure Disks:** Persistent storage for VMs.

## 🌐 Networking (Connectivity & Security)

* **Virtual Network (VNet):** Private network for Azure resources.
* **Subnet & NSG (Network Security Group):** Segment and secure traffic.
* **Load Balancer / Application Gateway:** Distribute and secure inbound traffic.
* **Azure DNS:** Manage internal and external DNS zones.

## 🔐 Security & Identity

* **Azure Active Directory (AAD):** Central identity management and RBAC.
* **Managed Identities:** Secure app access to Azure resources.
* **Azure Key Vault:** Store secrets, certificates, and tokens securely.
* **RBAC:** Role-based access control to enforce least privilege.

## 🧰 DevOps & Automation

* **Azure DevOps:** CI/CD pipelines, repos, and release management.
* **GitHub Actions:** Workflow automation and CI/CD integration.
* **ARM Templates / Bicep:** Azure-native Infrastructure as Code (IaC) tools.
* **Terraform (AzureRM Provider):** Cloud-agnostic IaC tool for provisioning.
* **Azure CLI / PowerShell:** Command-line tools for automation.

## 📈 Monitoring & Logging

* **Azure Monitor:** Collect metrics and logs across resources.
* **Log Analytics Workspace:** Centralized log storage and query analysis.
* **Application Insights:** App-level performance and telemetry monitoring.
* **Alerts & Dashboards:** Real-time visibility and health tracking.

## 🔄 Governance & Management

* **Azure Policy:** Enforce governance and compliance rules.
* **Azure Blueprints:** Combine templates and policies for standardized environments.
* **Azure Automation Account:** Automate scripts and maintenance tasks.
* **Azure Arc:** Manage hybrid or multi-cloud infrastructure.

## 🧩 Typical DevOps Flow

1. Code → GitHub/Azure Repos
2. Build → Azure DevOps Pipeline
3. Image → Pushed to ACR
4. Infra → Provisioned via Terraform/Bicep
5. Deploy → To AKS/App Service
6. Monitor → Azure Monitor + App Insights
7. Secure → Key Vault + RBAC
