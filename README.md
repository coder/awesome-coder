# Awesome Coder [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<a href="https://coder.com"><img src="https://github.com/coder/presskit/blob/7b1ae316de8b78cbdd8ef6b6352ef9f32be51504/logos/coder_logo_white_square.png?raw=true" alt="Coder logo" align="right" width="100"></a>

> A curated list of resources for [Coder](https://coder.com), the self-hosted platform for cloud development environments and AI coding agents.

Define workspaces in Terraform, run them on your own infrastructure, and let developers and AI agents work in identical, ephemeral environments.

Your [contributions](CONTRIBUTING.md) are welcome!

## Contents

- [Official Resources](#official-resources)
- [Platform and Tools](#platform-and-tools)
- [AI Coding Agents](#ai-coding-agents)
- [Templates](#templates)
- [Modules](#modules)
- [Terraform Providers](#terraform-providers)
- [IDE Integrations](#ide-integrations)
- [Coder Desktop](#coder-desktop)
- [Automation](#automation)
- [Tutorials and Blog Posts](#tutorials-and-blog-posts)
- [Talks and Videos](#talks-and-videos)

## Official Resources

- [Documentation](https://coder.com/docs) - Official Coder documentation, including install, admin, and contributor guides.
- [Blog](https://coder.com/blog) - Posts from the Coder team covering product updates, deployments, and technical deep dives.
- [Press kit & brand style guide](https://coder.com/brand) - Logos, brand assets, and brand guidelines.
- [Discord](https://cdr.co/discord-Y6fMxGdNRg) - Community chat for developers and operators using Coder.
- [X](https://x.com/CoderHQ) - Official Coder account on X.

## Platform and Tools

- [coder/coder](https://github.com/coder/coder) - The Coder server, agent, and CLI. Self-hosted cloud development environments and AI coding agents defined in Terraform.
- [coder/registry](https://github.com/coder/registry) - Source for the templates and modules published to registry.coder.com.
- [coder/code-server](https://github.com/coder/code-server) - Run VS Code in a browser tab. The default web IDE for many Coder workspaces.
- [coder/envbuilder](https://github.com/coder/envbuilder) - Build workspaces from a Dockerfile or devcontainer.json on Docker, Kubernetes, and OpenShift.
- [coder/envbox](https://github.com/coder/envbox) - Container image for running system-level software like Docker and systemd inside Kubernetes workspaces.
- [coder/preview](https://github.com/coder/preview) - Template preview engine used by the Registry and template authors.

## AI Coding Agents

- [AI Coder documentation](https://coder.com/docs/ai-coder) - Official documentation for running AI coding agents inside Coder workspaces.
- [Coder Agents](https://coder.com/docs/ai-coder/agents) - Coder's built-in chat interface and API for delegating development work to coding agents. It selects a template, provisions a workspace, and runs the agent loop inside your Coder control plane.
- [Tasks](https://coder.com/docs/ai-coder/tasks) - Run AI agent loops in the Coder control plane against your workspaces.

## Templates

Start with the [Coder Registry](https://registry.coder.com/templates) for official and community templates. The repositories below are maintained elsewhere in the community:

- [bpmct/coder-templates/proxmox-vm](https://github.com/bpmct/coder-templates/tree/main/proxmox-vm) - Develop in a Proxmox VM.
- [bpmct/coder-templates/shared-mac](https://github.com/bpmct/coder-templates/tree/main/shared-mac) - Connect a pre-provisioned Mac device and provision system users as workspaces.
- [denbeigh2000/coder-templates](https://github.com/denbeigh2000/coder-templates) - Manage NixOS development workspaces on EC2, including spot and Graviton variants.
- [m.lan/coder-templates](https://gitlab.com/m.lan/coder-templates) - Kubernetes template with Docker in Docker (DinD).
- [matifali/coder-templates](https://github.com/matifali/coder-templates) - Docker-based deep learning templates (PyTorch/TensorFlow with Jupyter, plus an NVIDIA GPU variant) and MATLAB in the browser.
- [ntimo/coder-hetzner-cloud-template](https://github.com/ntimo/coder-hetzner-cloud-template) - Set up a Hetzner Cloud instance as a dev environment, with or without VS Code.
- [sharkymark/v2-templates](https://github.com/sharkymark/v2-templates) - A large collection of Coder Terraform templates and tips.
- [sulo1337/coder-kubevirt-template](https://github.com/sulo1337/coder-kubevirt-template) - KubeVirt-based development environment that provisions KVM virtual machines as Coder workspaces on top of a Kubernetes cluster.
- [uwu/basic-env](https://github.com/uwu/basic-env) - Docker-based dev environment with VS Code, an XFCE + noVNC desktop, dotfiles, and preinstalled language runtimes (Dart, Java, JavaScript/Node).

## Modules

Start with the [Coder Registry](https://registry.coder.com/modules) for modules that extend your templates with tools and integrations: IDE installers, dotfiles support, code-server, JetBrains, and more.

## Terraform Providers

- [coder/terraform-provider-coder](https://github.com/coder/terraform-provider-coder) - Template-side Terraform resources: `coder_agent`, `coder_app`, `coder_parameter`, and friends.
- [coder/terraform-provider-coderd](https://github.com/coder/terraform-provider-coderd) - Manage a Coder deployment itself (templates, groups, organizations) with Terraform.

## IDE Integrations

- [Workspace access](https://coder.com/docs/user-guides/workspace-access) - Connect to Coder workspaces from VS Code, JetBrains, Cursor, code-server, and the CLI.
- [coder/vscode-coder](https://github.com/coder/vscode-coder) - VS Code extension to open any Coder workspace with a single click.
- [coder/jetbrains-coder](https://github.com/coder/jetbrains-coder) - JetBrains Gateway plugin for Coder.
- [coder/coder-jetbrains-toolbox](https://github.com/coder/coder-jetbrains-toolbox) - JetBrains Toolbox plugin for Coder.
- [Running a private VS Code Extension Marketplace](https://coder.com/blog/running-a-private-vs-code-extension-marketplace) - Host an internal extension marketplace for code-server and VS Code workspaces.

## Coder Desktop

- [coder/coder-desktop-macos](https://github.com/coder/coder-desktop-macos) - Native macOS Coder Desktop client.
- [coder/coder-desktop-windows](https://github.com/coder/coder-desktop-windows) - Native Windows Coder Desktop client.

## Automation

- [Validated architectures](https://coder.com/docs/admin/infrastructure/validated-architectures) - Reference architectures for deploying Coder in production on Kubernetes and other platforms.
- [coder/box](https://github.com/coder/box) - NixOS appliance that provisions a single-node Coder server and k3s cluster on a physical machine for self-contained demos and workshops.
- [Update Coder Template](https://github.com/marketplace/actions/update-coder-template) - A GitHub Action to automate Coder template changes.
- [Provision Coder with Lima](https://github.com/coder/coder/tree/main/examples/lima) - Linux virtual machines, typically on macOS, for running containerd.

## Tutorials and Blog Posts

- [Kubernetes namespaces as dev environments](https://coder.com/blog/kubernetes-namespaces-as-dev-environments) - Tutorial for building a template that provisions a namespace, tooling pod, persistent home volume, and scoped ServiceAccount per developer.
- [Four Reference Architectures for CDEs: Kubernetes vs. VMs](https://coder.com/blog/four-reference-architectures-for-cdes-kubernetes-vs-vms) - Trade-offs and reference patterns for running workspaces on Kubernetes versus virtual machines.
- [Coder's Well-Architected Framework](https://coder.com/blog/coder-well-architected-framework) - Reliability, security, and cost best practices for a Coder deployment, from provisioners to RBAC and workspace bin-packing.
- [Enterprise security and governance for software development environments](https://coder.com/blog/enterprise-security-and-governance-for-software-development-environments) - Guide to securing cloud development environments on Kubernetes, covering the PVC model, secrets, and Vault integration.
- [Deploying AI Agents at Scale Without Sacrificing Control & Governance](https://coder.com/blog/deploying-ai-agents-at-scale-without-sacrificing-control-and-governance) - How to roll out autonomous coding agents with guardrails and governance in place.
- [Giving OpenClaw a Secure Workspace Using the Rabbit R1](https://coder.com/blog/giving-openclaw-a-secure-workspace-using-the-rabbit-r1) - Building an OpenClaw skill that lets the Rabbit R1's voice agent spin up isolated, governed Coder Tasks and Workspaces instead of granting it broad access to the host.
- [The Benefits of Remote Ephemeral Workspaces](https://blog.palantir.com/the-benefits-of-remote-ephemeral-workspaces-1a1251ed6e53) - Palantir on running ephemeral, remote development environments at scale.
- [Laptop development is dead: why remote development is the future](https://medium.com/@elliotgraebert/laptop-development-is-dead-why-remote-development-is-the-future-f92ce103fd13) - Argument for moving developer environments off laptops.

## Talks and Videos

- [Introduction to Coder Workspaces](https://www.youtube.com/watch?v=KNnNREoizOM) - Overview of Coder workspaces and how they fit into a developer workflow.
- [Building the IDE Golden Path](https://www.youtube.com/watch?v=F6D-cXl_xUA) - Ben Potter on building a consistent IDE experience across teams with Coder.
- [Your Next Workstation Is In The Cloud](https://www.youtube.com/watch?v=C4fQvIHCVzw&t=748s) - Ketan Gangatirkar on moving developer workstations to the cloud with Coder.

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Coder has waived all copyright and related or neighboring rights to this work.
