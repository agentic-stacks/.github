# Agentic Stacks

Installable skill packs that give AI agents deep domain expertise.

Pull a stack into your project and your AI agent instantly knows how to deploy OpenStack, manage server hardware, operate Kubernetes clusters, and more. Stacks teach agents *and* humans — amplifying what you can accomplish together.

### Available Stacks

<!-- STACKS-TABLE-START -->
| Stack | Category | Description |
|-------|----------|-------------|
| [openstack-kolla](https://github.com/agentic-stacks/openstack-kolla) | Platform | OpenStack deployment and operations via kolla-ansible |
| [kubernetes-talos](https://github.com/agentic-stacks/kubernetes-talos) | Platform | Production Kubernetes on Talos Linux |
| [docker](https://github.com/agentic-stacks/docker) | Platform | Docker Engine lifecycle and operations |
| [ceph](https://github.com/agentic-stacks/ceph) | Storage | Ceph storage cluster deployment and operations |
| [hardware-dell](https://github.com/agentic-stacks/hardware-dell) | Hardware | Dell PowerEdge / iDRAC management |
| [hardware-hpe](https://github.com/agentic-stacks/hardware-hpe) | Hardware | HPE ProLiant / iLO management |
| [hardware-supermicro](https://github.com/agentic-stacks/hardware-supermicro) | Hardware | Supermicro BMC management |
| [ipxe](https://github.com/agentic-stacks/ipxe) | Networking | iPXE network boot |
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
