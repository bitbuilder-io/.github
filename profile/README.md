# BitBuilder Cloud

**A Distributed, Vendor Agnostic, E2E Encrypted, Multi-Cloud Infrastructure Platform**

BitBuilder Cloud is a next-generation infrastructure platform built on systemd's proven virtualization and containerization capabilities. We provide secure, isolated multi-tenant environments that work seamlessly across any cloud provider.

## 📁 Organization Repository Structure

```
github.com/bitbuilder-io/
├── .github/              # Organization profile and shared configurations
├── bbctl/                # CLI tool for infrastructure management (Rust)
├── bitboot/              # Boot and initialization utilities
├── brand/                # Brand assets and guidelines (HTML)
└── codelab-templates/    # VibeSDK template catalog (TypeScript)
```

## 🚀 Key Features

### Distributed Architecture
- Horizontally scalable infrastructure designed for global deployment
- Decentralized control plane for enhanced reliability and performance
- Built-in load balancing and service discovery

### Vendor Agnostic
- Deploy on any cloud provider: AWS, Azure, GCP, DigitalOcean, or on-premises
- Avoid vendor lock-in with portable workloads
- Unified management interface across all environments

### End-to-End Encryption
- Encrypted data at rest and in transit
- Zero-trust security model
- Secure key management and rotation
- Privacy-first design principles

### Multi-Cloud Native
- Seamless workload distribution across multiple clouds
- Intelligent placement and orchestration
- Cross-cloud networking and service mesh
- Unified billing and cost management

### systemd-Powered
- Built on battle-tested systemd virtualization (systemd-nspawn, systemd-machined)
- Leverages systemd containerization for lightweight, secure workloads
- Native integration with Linux kernel security features
- Resource management through systemd cgroups and namespaces

### Secure Multi-Tenancy
- Strong isolation boundaries between tenants
- Per-tenant encryption keys and security policies
- Resource quotas and quality of service guarantees
- Comprehensive audit logging and compliance support

## 🔧 Technology Stack

- **Virtualization**: systemd-nspawn, systemd-machined
- **Containerization**: systemd containers with cgroups v2
- **Security**: SELinux, AppArmor, seccomp, encryption at rest
- **Networking**: systemd-networkd, WireGuard VPN, service mesh
- **Storage**: Encrypted volumes, distributed storage integration
- **Orchestration**: Custom control plane with systemd units

## 🎯 Use Cases

- **Enterprise Workloads**: Run critical applications with enhanced security and isolation
- **SaaS Platforms**: Build multi-tenant applications with strong security boundaries
- **Edge Computing**: Distribute workloads closer to users with consistent management
- **Hybrid Cloud**: Bridge on-premises infrastructure with public cloud resources
- **Development Environments**: Spin up isolated, reproducible development environments

## 🔒 Security First

Security is at the core of BitBuilder Cloud. Every component is designed with security in mind:

- End-to-end encryption for all data
- Zero-knowledge architecture where possible
- Regular security audits and updates
- Compliance with industry standards (SOC 2, GDPR, HIPAA-ready)
- Transparent security practices and vulnerability disclosure

## 🌐 Community

We believe in open collaboration and building in public. Join our community:

- **Documentation**: Coming soon
- **Support**: Coming soon
- **Contributing**: We welcome contributions! Check back for contribution guidelines

## 📫 Get Started

BitBuilder Cloud is currently in development. Stay tuned for updates on availability and early access programs.

---

## 📦 Repository Details

### [bbctl](https://github.com/bitbuilder-io/bbctl)

BitBuilder Cloud CLI is an all-in-one tool for provisioning and managing multi-tenant infrastructure on bare metal servers running VyOS v1.5 or Proxmox. Similar to fly.io's flyctl, bbctl provides a seamless experience for deploying, scaling, and managing your applications across distributed infrastructure.

**Features:**
- Manage VMs: Create, configure, and manage virtual machines across your infrastructure
- Storage Management: Provision and attach volumes to your applications
- Network Configuration: Set up and manage virtual networks with secure connectivity
- Multi-provider Support: Works with VyOS v1.5 and Proxmox
- Bare Metal Efficiency: Optimized for bare metal server deployment
- Future Public Cloud Integration: Scale out to public clouds with E2E encryption (coming soon)

**Directory Layout:**
```
bbctl/
├── .dprint.json
├── .eslintrc.json
├── .gitignore
├── CLAUDE.md
├── Cargo.lock
├── Cargo.toml
├── PLAN.md
├── README.md
├── bun.lock
├── bunfig.toml
├── docs/
├── examples/
├── package.json
├── schema.ts
├── scripts/
├── src/
├── tests/
├── tsconfig.json
└── vyos-lab/
```

---

### [bitboot](https://github.com/bitbuilder-io/bitboot)

Boot and initialization utilities for BitBuilder Cloud infrastructure.

**Directory Layout:**
```
bitboot/
├── .gitignore
├── LICENSE
└── README.md
```

---

### [brand](https://github.com/bitbuilder-io/brand)

The complete BitBuilder Cloud brand identity system. This package contains everything you need to represent the BitBuilder Cloud brand professionally and consistently across all media.

**Live Preview**: [bitbuilder-io.github.io/bitbuilder](https://bitbuilder-io.github.io/bitbuilder/)

**Package Contents:**
- 12 unique logo variations for different use cases
- SVG, PNG, and ICO formats
- Square and circular versions
- Business card, letterhead, and email signature templates
- Complete brand guidelines
- Social media specifications

**Directory Layout:**
```
brand/
├── .github/
├── BRAND_GUIDELINES.md
├── README.md
├── SOCIAL_MEDIA_ASSETS.md
├── exports/
├── extract-logos.ts
├── index.html
├── logos/
├── optimize-and-export.ts
├── public/
├── svg-to-png-converter.html
└── templates/
```

---

### [codelab-templates](https://github.com/bitbuilder-io/codelab-templates)

Official repository for templates catalog powering VibeSDK — a modern, open source "vibe coding" starter kit where users can build apps with AI agents. The goal of VibeSDK is to let anyone run their own vibe-coding platform on a Cloudflare Workers paid account with a streamlined, one-click deployment.

These templates are the scaffolding that VibeSDK's AI agents use to generate full applications for users. They are kept lightweight, production-minded, and type-safe.

**Key Components:**
- `reference/` - Base reference templates used as starting points
- `definitions/` - YAML definitions and overlay files per template
- `build/` - Output folder for generated templates
- `tools/` - Utility scripts for generation and verification

**Directory Layout:**
```
codelab-templates/
├── .github/
├── .gitignore
├── CLAUDE.md
├── DEPLOYMENT_SETUP.md
├── README.md
├── create_zip.py
├── definitions/
├── deploy_templates.sh
├── generate_template_catalog.py
├── reference/
├── template_catalog.json
└── tools/
```

---

### [.github](https://github.com/bitbuilder-io/.github)

Organization profile and shared GitHub configurations for BitBuilder Cloud.

**Directory Layout:**
```
.github/
├── README.md
└── profile/
```

---

*Built with ❤️ by the BitBuilder team*
