# Agentic Stacks

Installable skill packs that give AI agents deep domain expertise.

Pull a stack into your project and your AI agent instantly knows how to deploy OpenStack, manage server hardware, operate Kubernetes clusters, and more. Stacks teach agents *and* humans — amplifying what you can accomplish together.

### Available Stacks

<!-- STACKS-TABLE-START -->
| Stack | Category | Description |
|-------|----------|-------------|
| [docker](https://github.com/agentic-stacks/docker) | Platform | Complete operational knowledge for building, deploying, managing, and troubleshooting production containerized applications using Docker Engine |
| [kubernetes-talos](https://github.com/agentic-stacks/kubernetes-talos) | Platform | Complete operational knowledge for deploying, managing, and operating production Kubernetes clusters using Talos Linux |
| [openstack-kolla](https://github.com/agentic-stacks/openstack-kolla) | Platform | Agent-driven OpenStack cloud deployment and operations using kolla-ansible |
| [ceph](https://github.com/agentic-stacks/ceph) | Storage | Complete operational knowledge for deploying, managing, and operating production Ceph storage clusters using cephadm on bare metal |
| [hardware-dell](https://github.com/agentic-stacks/hardware-dell) | Hardware | Teaches AI agents to manage Dell PowerEdge server hardware — BIOS configuration, iDRAC remote management, RAID setup, firmware updates, and hardware inventory |
| [hardware-hpe](https://github.com/agentic-stacks/hardware-hpe) | Hardware | Complete operational knowledge for administering HPE ProLiant Gen10 and Gen11 servers |
| [hardware-supermicro](https://github.com/agentic-stacks/hardware-supermicro) | Hardware | Teaches AI agents to manage Supermicro server hardware — BMC configuration, BIOS management, RAID setup, firmware updates, and hardware inventory |
| [frr](https://github.com/agentic-stacks/frr) | Networking | Teaches AI agents to deploy, configure, operate, troubleshoot, and develop FRR (Free Range Routing) |
| [ipxe](https://github.com/agentic-stacks/ipxe) | Networking | Teaches agents to build, deploy, and operate iPXE network boot infrastructure across bare metal, virtual, and cloud environments |
<!-- STACKS-TABLE-END -->

### Get Started

```bash
pip install agentic-stacks
agentic-stacks init agentic-stacks/openstack-kolla my-deployment
cd my-deployment
agentic-stacks pull hardware-dell
```

### Links

- [Browse Stacks](https://www.agentic-stacks.com/stacks)
- [Getting Started](https://www.agentic-stacks.com/docs/getting-started)
- [Author a Stack](https://www.agentic-stacks.com/docs/authoring)
