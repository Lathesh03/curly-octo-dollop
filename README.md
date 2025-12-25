# 📊 Kubernetes Observability Stack

## Architecture
* **Platform:** AWS EKS (Managed Kubernetes)
* **IaC:** Terraform (Infrastructure provisioning)
* **Monitoring:** Prometheus (Metrics Collection)
* **Visualization:** Grafana (Dashboards)
* **Package Manager:** Helm

## 📸 Proof of Implementation
![Grafana Dashboard]

![CPU_Utilisation_Grafana](https://github.com/user-attachments/assets/db8c0f96-bec7-4d6a-ab6b-0f87e84c6713)

![Memory_Utilisation_Grafana](https://github.com/user-attachments/assets/2d25d441-f5c6-496f-8601-f211cc174c9a)



*Real-time monitoring of Cluster CPU and Memory usage.*

## 🔧 Key Challenges Solved
* **Networking:** Diagnosed and resolved AWS Security Group `Ingress` blocks preventing Pod-to-Pod communication.
* **Automation:** Integrated the monitoring stack deployment into the post-provisioning workflow using Helm.
