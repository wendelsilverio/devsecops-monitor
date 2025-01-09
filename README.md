# devsecops-monitor
The Monitor phase is critical in DevSecOps, focusing on ensuring the software remains secure, reliable, and compliant in a live environment.

![DevSecOps Monitor](assets/images/devsecops-monitor.png)

## 🛠️ Technology Stack
- **Prometheus**: An open-source systems monitoring and alerting toolkit used to collect and store metrics.
- **Grafana**: An open-source platform for monitoring and observability, used to visualize metrics and create dashboards.
- **Blackbox Exporter**: A Prometheus exporter for probing endpoints such as HTTP, HTTPS, DNS, TCP, ICMP, and gRPC.

## 📅 Activity List

### Define Monitoring Requirements
- [ ] Identify key performance indicators (KPIs) and metrics to be monitored.
- [ ] Determine data collection frequency and necessary alerts.

### Set Up Monitoring Environment
- [ ] Create a `docker-compose.yml` file to configure monitoring services.
- [ ] Configure Prometheus to collect metrics.
- [ ] Configure Blackbox Exporter to monitor URL availability.
- [ ] Configure Grafana to visualize collected metrics.

## 🤝 Contributing

We welcome contributions from the community. Please read our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.