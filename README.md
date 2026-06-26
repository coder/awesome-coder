# Awesome Coder [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<a href="https://coder.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/coder-mark-white.svg">
    <img src="./assets/coder-mark-black.svg" alt="Coder logo" align="right" width="120">
  </picture>
</a>

> A curated list of resources for [Coder](https://coder.com), the self-hosted platform for cloud development environments and AI coding agents.

Define workspaces in Terraform, run them on your own infrastructure, and let developers and AI agents work in identical, ephemeral environments.

Your [contributions](CONTRIBUTING.md) are welcome!

## Contents

- [Official Resources](#official-resources)
- [Tutorials and Blog Posts](#tutorials-and-blog-posts)
- [IDEs](#ides)
- [Automation](#automation)
- [Templates](#templates)
- [Talks and Videos](#talks-and-videos)

## Official Resources

- [Documentation](https://coder.com/docs) - Official Coder documentation, including install, admin, and contributor guides.
- [Blog](https://coder.com/blog) - Posts from the Coder team covering product updates, deployments, and technical deep dives.
- [Press kit & brand style guide](https://coder.com/brand) - Logos, brand assets, and brand guidelines.
- [Discord](https://cdr.co/discord-Y6fMxGdNRg) - Community chat for developers and operators using Coder.
- [X](https://x.com/CoderHQ) - Official Coder account on X.

## Tutorials and Blog Posts

- [The Benefits of Remote Ephemeral Workspaces](https://blog.palantir.com/the-benefits-of-remote-ephemeral-workspaces-1a1251ed6e53) - Palantir on running ephemeral, remote development environments at scale.
- [Laptop development is dead: why remote development is the future](https://medium.com/@elliotgraebert/laptop-development-is-dead-why-remote-development-is-the-future-f92ce103fd13) - Argument for moving developer environments off laptops.

## IDEs

- [Workspace access](https://coder.com/docs/user-guides/workspace-access) - Connect to Coder workspaces from VS Code, JetBrains, Cursor, code-server, and the CLI.
- [Running a private VS Code Extension Marketplace](https://coder.com/blog/running-a-private-vs-code-extension-marketplace) - Host an internal extension marketplace for code-server and VS Code workspaces.

## Automation

- [Validated architectures](https://coder.com/docs/admin/infrastructure/validated-architectures) - Reference architectures for deploying Coder in production on Kubernetes and other platforms.
- [Update Coder Template](https://github.com/marketplace/actions/update-coder-template) - A GitHub Action to automate Coder template changes.
- [Provision Coder with Lima](https://github.com/coder/coder/tree/main/examples/lima) - Linux virtual machines, typically on macOS, for running containerd.

## Templates

- [Coder Registry](https://registry.coder.com/templates) - Official and community templates published to the Coder Registry.
- [sharkymark/v2-templates](https://github.com/sharkymark/v2-templates) - A large collection of templates.
- [ntimo/coder-hetzner-cloud-template](https://github.com/ntimo/coder-hetzner-cloud-template) - Set up a Hetzner Cloud instance as a dev environment, with or without VS Code.
- [matifali/coder-templates](https://github.com/matifali/coder-templates) - Deep learning with Jupyter Notebook/Lab and MATLAB in the browser.
- [m.lan/coder-templates](https://gitlab.com/m.lan/coder-templates) - Kubernetes template with Docker in Docker (DinD).
- [bpmct/coder-templates/proxmox-vm](https://github.com/bpmct/coder-templates/tree/main/proxmox-vm) - Develop in a Proxmox VM.
- [bpmct/coder-templates/shared-mac](https://github.com/bpmct/coder-templates/tree/main/shared-mac) - Connect a pre-provisioned Mac device and provision system users as workspaces.
- [denbeigh2000/coder-templates](https://github.com/denbeigh2000/coder-templates) - Manage NixOS development workspaces on EC2, including spot and Graviton variants.
- [8Bitz0/coder-rust-template](https://gitlab.com/8Bitz0/coder-rust-template) - Coder templates with various Linux distros for out-of-the-box Rust development.
- [uwu/basic-env](https://github.com/uwu/basic-env) - Docker-based Node.js development environment with code-server, NoVNC, and dotfiles support out of the box.
- [sulo1337/coder-kubevirt-template](https://github.com/sulo1337/coder-kubevirt-template) - KubeVirt-based development environment that provisions KVM virtual machines as Coder workspaces on top of a Kubernetes cluster.

## Talks and Videos

- [Introduction to Coder Workspaces](https://www.youtube.com/watch?v=KNnNREoizOM) - Overview of Coder workspaces and how they fit into a developer workflow.
- [Building the IDE Golden Path](https://www.youtube.com/watch?v=F6D-cXl_xUA) - Ben Potter on building a consistent IDE experience across teams with Coder.
- [Your Next Workstation Is In The Cloud](https://www.youtube.com/watch?v=C4fQvIHCVzw&t=748s) - Ketan Gangatirkar on moving developer workstations to the cloud with Coder.

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Coder has waived all copyright and related or neighboring rights to this work.
