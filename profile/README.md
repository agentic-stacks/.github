# Agentic Stacks

**Composed domain expertise for AI coding agents.**

Pull a stack into your project and your agent instantly knows how to deploy, operate, troubleshoot, and upgrade the target software — with verified commands, safety rules, and version-specific knowledge. Skills live on your machine, reducing token usage by skipping research every session.

Works with Claude Code, Codex CLI, Gemini, Cursor, and any agent that reads markdown.

### How It Works

```bash
pipx install agentic-stacks
agentic-stacks init my-deployment
cd my-deployment
agentic-stacks pull kubernetes-talos
agentic-stacks pull hardware-dell
claude
```

Your agent reads `.stacks/*/CLAUDE.md` and combines expertise from every stack you've pulled.

### Available Stacks

<!-- STACKS-TABLE-START -->
| Stack | Category | Description |
|-------|----------|-------------|
| [docker](https://github.com/agentic-stacks/docker) | Platform | Complete operational knowledge for building, deploying, managing, and troubleshooting production containerized applications using Docker Engine |
| [kubernetes-talos](https://github.com/agentic-stacks/kubernetes-talos) | Platform | Complete operational knowledge for deploying, managing, and operating production Kubernetes clusters using Talos Linux |
| [openstack-kolla](https://github.com/agentic-stacks/openstack-kolla) | Platform | Agent-driven OpenStack cloud deployment and operations using kolla-ansible |
| [proxmox](https://github.com/agentic-stacks/proxmox) | Platform | Hypervisor management — VM lifecycle, storage, networking, clustering |
| [ceph](https://github.com/agentic-stacks/ceph) | Storage | Complete operational knowledge for deploying, managing, and operating production Ceph storage clusters using cephadm on bare metal |
| [minio](https://github.com/agentic-stacks/minio) | Storage | S3-compatible object storage — deployment, buckets, replication, monitoring |
| [hardware-dell](https://github.com/agentic-stacks/hardware-dell) | Hardware | Teaches AI agents to manage Dell PowerEdge server hardware — BIOS configuration, iDRAC remote management, RAID setup, firmware updates, and hardware inventory |
| [hpe-hardware](https://github.com/agentic-stacks/hpe-hardware) | Hardware | Complete operational knowledge for administering HPE ProLiant Gen10 and Gen11 servers |
| [supermicro-hardware](https://github.com/agentic-stacks/hardware-supermicro) | Hardware | Teaches AI agents to manage Supermicro server hardware — BMC configuration, BIOS management, RAID setup, firmware updates, and hardware inventory |
| [frr](https://github.com/agentic-stacks/frr) | Networking | Teaches AI agents to deploy, configure, operate, troubleshoot, and develop FRR (Free Range Routing) |
| [ipxe](https://github.com/agentic-stacks/ipxe) | Networking | Teaches agents to build, deploy, and operate iPXE network boot infrastructure across bare metal, virtual, and cloud environments |
| [ansible](https://github.com/agentic-stacks/ansible) | Automation | Fleet automation — teaches agents to write, deploy, test, and troubleshoot Ansible automation |
| [terraform](https://github.com/agentic-stacks/terraform) | Automation | Infrastructure as Code provisioning — teaches AI agents to operate Terraform and OpenTofu across the full lifecycle: project setup, provider configuration, state management, modules, CI/CD integration, upgrades, and troubleshooting |
| [prometheus-grafana](https://github.com/agentic-stacks/prometheus-grafana) | Observability | Monitoring stack — teaches AI agents to deploy, configure, operate, and troubleshoot Prometheus metrics collection, Grafana dashboards, Alertmanager notifications, and the exporter ecosystem |
| [linux](https://github.com/agentic-stacks/linux) | Other | OS-level operations — systemd, networking, storage, performance tuning |
| [rails](https://github.com/agentic-stacks/rails) | Other | Ruby on Rails full-stack and API-only web application framework |
<!-- STACKS-TABLE-END -->

### Links

- [Browse Stacks](https://www.agentic-stacks.com/stacks) — search and discover
- [Getting Started](https://www.agentic-stacks.com/docs/getting-started) — install and first project
- [Author a Stack](https://www.agentic-stacks.com/docs/authoring) — build your own
- [Stack Factory](https://github.com/agentic-stacks/stack-factory) — automated stack creation pipeline
