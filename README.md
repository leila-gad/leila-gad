```console
leila@inpt:~$ terraform plan
```

```hcl
resource "engineer" "leila_gadal" {
  school   = "INPT, Rabat — Smart ICT (Cloud & Infrastructure)"
  year     = 4
  origin   = "Morocco"
  focus    = ["cloud", "networks", "automation", "AIOps"]
  curious  = true

  looking_for = "final-year engineering internship (PFE)"
}
```

```diff
+ builds infrastructure with Terraform and Ansible
+ watches it with Prometheus and Grafana
+ teaches Python to notice when something looks wrong
- does not enjoy unmonitored servers
```

---

### `modules/`  what I've built

| module | what it does | stack |
|---|---|---|
| [**aiops-hybrid-cloud**](https://github.com/leila-gad/AIOps-Hybrid-Cloud-Infrastructure) | A local VM and an AWS EC2 instance, provisioned as code, monitored, with ML flagging anomalies | Terraform · Vagrant · Ansible · Prometheus · Grafana · Python |
| [**netguard**](https://github.com/leila-gad/NETGUARD-for-DOS-DDOS) | Detects DoS/DDoS traffic with a model served over a REST API | Python · XGBoost · Flask · Docker |
| [**camunda7-to-kogito**](https://github.com/leila-gad/PoC-cammunda7-vers-kogito) | PoC: moving BPMN workflows from Camunda 7 to cloud-native Kogito | Kogito · Kubernetes · REST · Scrum |
| **microsoft-infra-lab** | Active Directory, GPO, DNS/DHCP, Entra ID and Microsoft 365 identity | Windows Server · Entra ID · Intune |

---

### `logs/`  where I've run things

```text
2026-07 → 2026-09  Ministry of Digital Transition   IT systems audit & governance
2026-02 → 2026-05  Orange Business Morocco          cloud-native platform transformation
2025-summer        OCP Group                        network diagnostics & access security
```

---

### `providers.tf`

```hcl
provider "aws"        {}  # Cloud Practitioner
provider "cisco"      {}  # CCNA: Introduction to Networks
provider "linux"      {}
provider "docker"     {}
provider "python"     {}  # pandas, scikit-learn, XGBoost
provider "microsoft"  {}  # AD, Entra ID, M365
provider "english"    {}  # TOEIC
```

---

```text
Plan: 1 to add, 0 to change, 0 to destroy.

Do you want to perform these actions?
  Only 'yes' will be accepted to approve.

  Enter a value:
```

**yes** → [leilagadal653@gmail.com](mailto:leilagadal653@gmail.com) · [LinkedIn](https://www.linkedin.com/in/leila-gadal-64745632b)
