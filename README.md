# Ansible Monitoring Lab – Prometheus + Grafana

## 🧩 Topology

| Server      | Role                       |
|-------------|----------------------------|
| server1     | Ansible Control Node       |
| server2     | Node Exporter Target       |
| server3     | Node Exporter Target       |
| server4     | Prometheus + Grafana Host  |

---

## 🔧 Setup Steps

### 1. Clone Repo
```bash
git clone https://github.com/<your-username>/ansible-monitoring-lab.git
cd ansible-monitoring-lab

