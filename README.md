Designing **a complete multi-cloud FinOps** leveraging on Terraform to setup all environments **(AWS, Azure, GCP)** and **modules (budget, cost monitoring, security, storage, optimization)**.

---

### More to Come ...!

---

## Project Structure
```plaintext
T2S-FINOPS-MULTICLOUD/
├── environments/
│   ├── aws/
│   │   ├── dev/
│   │   ├── stage/
│   │   ├── prod/
│   ├── azure/
│   │   ├── dev/
│   │   ├── stage/
│   │   ├── prod/
│   ├── gcp/
│   │   ├── dev/
│   │   ├── stage/
│   │   ├── prod/
├── modules/
│   ├── aws_budget/
│   ├── aws_cost_monitoring/
│   ├── aws_security/
│   ├── aws_storage/
│   ├── aws_auto_optimizer/
│   ├── azure_budget/
│   ├── azure_cost_monitoring/
│   ├── azure_security/
│   ├── azure_storage/
│   ├── azure_auto_optimizer/
│   ├── gcp_budget/
│   ├── gcp_cost_monitoring/
│   ├── gcp_security/
│   ├── gcp_storage/
│   ├── gcp_auto_optimizer/
└── README.md
```

