# Agentic Stacks

**Composed domain expertise for AI coding agents.**

Pull a stack into your project and your agent instantly knows how to deploy, operate, troubleshoot, and upgrade the target software — with verified commands, safety rules, and version-specific knowledge. Every stack also includes a training mode — ask the agent to teach you the domain and it builds an interactive curriculum from the stack's skills.

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

### Learn from Your Stacks

Every stack ships with a training skill. Ask the agent to teach you and it switches to interactive tutor mode:

```
> train me on this stack
> train me on RAID management
> quiz me
> what should I learn next?
```

Stacks teach agents *and* humans — useful for onboarding, cross-training, and learning new domains.

### Available Stacks

<!-- STACKS-TABLE-START -->
| Stack | Category | Description |
|-------|----------|-------------|
| [docker](https://github.com/agentic-stacks/docker) | Platform | Complete operational knowledge for building, deploying, managing, and troubleshooting production containerized applications using Docker Engine |
| [kubernetes-talos](https://github.com/agentic-stacks/kubernetes-talos) | Platform | Complete operational knowledge for deploying, managing, and operating production Kubernetes clusters using Talos Linux |
| [openstack-core](https://github.com/agentic-stacks/openstack-core) | Platform | Comprehensive operational knowledge for all major OpenStack services |
| [openstack-kolla](https://github.com/agentic-stacks/openstack-kolla) | Platform | Agent-driven OpenStack cloud deployment and operations using kolla-ansible |
| [ceph](https://github.com/agentic-stacks/ceph) | Storage | Complete operational knowledge for deploying, managing, and operating production Ceph storage clusters using cephadm on bare metal |
| [hardware-dell](https://github.com/agentic-stacks/hardware-dell) | Hardware | Teaches AI agents to manage Dell PowerEdge server hardware — BIOS configuration, iDRAC remote management, RAID setup, firmware updates, and hardware inventory |
| [hardware-hpe](https://github.com/agentic-stacks/hardware-hpe) | Hardware | Complete operational knowledge for administering HPE ProLiant Gen10 and Gen11 servers |
| [hardware-supermicro](https://github.com/agentic-stacks/hardware-supermicro) | Hardware | Teaches AI agents to manage Supermicro server hardware — BMC configuration, BIOS management, RAID setup, firmware updates, and hardware inventory |
| [frr](https://github.com/agentic-stacks/frr) | Networking | Teaches AI agents to deploy, configure, operate, troubleshoot, and develop FRR (Free Range Routing) |
| [ipxe](https://github.com/agentic-stacks/ipxe) | Networking | Teaches agents to build, deploy, and operate iPXE network boot infrastructure across bare metal, virtual, and cloud environments |
| [ansible](https://github.com/agentic-stacks/ansible) | Automation | Fleet automation — teaches agents to write, deploy, test, and troubleshoot Ansible automation |
| [terraform](https://github.com/agentic-stacks/terraform) | Automation | Infrastructure as Code provisioning — teaches AI agents to operate Terraform and OpenTofu across the full lifecycle: project setup, provider configuration, state management, modules, CI/CD integration, upgrades, and troubleshooting |
| [prometheus-grafana](https://github.com/agentic-stacks/prometheus-grafana) | Observability | Monitoring stack — teaches AI agents to deploy, configure, operate, and troubleshoot Prometheus metrics collection, Grafana dashboards, Alertmanager notifications, and the exporter ecosystem |
| [linux](https://github.com/agentic-stacks/linux) | Other | Comprehensive Linux systems administration — from installation through day-two operations |
| [rails](https://github.com/agentic-stacks/rails) | Other | Ruby on Rails full-stack and API-only web application framework |
<!-- STACKS-TABLE-END -->

### Links

- [Browse Stacks](https://www.agentic-stacks.com/stacks) — search and discover
- [Getting Started](https://www.agentic-stacks.com/docs/getting-started) — install and first project
- [Author a Stack](https://www.agentic-stacks.com/docs/authoring) — build your own
- [Stack Factory](https://github.com/agentic-stacks/stack-factory) — automated stack creation pipeline
