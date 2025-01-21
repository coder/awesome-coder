# Awesome Coder [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of resources on [Coder](https://www.coder.com/).
[<img src="https://github.com/coder/presskit/blob/7b1ae316de8b78cbdd8ef6b6352ef9f32be51504/logos/coder_logo_white_square.png?raw=true" align="right" width="100">](https://coder.com)
Your [contributions](https://github.com/coder/awesome-coder/blob/main/CONTRIBUTING.md) are welcome!

**Software development on _your infrastructure_**. Offload your team's development from local workstations to cloud servers. Onboard developers in minutes. Build, test and compile at the speed of the cloud. Keep your source code and data behind your firewall.

> "By leveraging Terraform, Coder lets developers run an IDE on any compute platform including on-prem, AWS, Azure, GCP, DigitalOcean, Kubernetes, Docker, and more, with workspaces running on Linux, Windows, or Mac." - **[Kevin Fishner](https://www.linkedin.com/in/kevinfishner) Chief of Staff at [HashiCorp](https://hashicorp.com/)**


## Contents

* [Official Resources](#official-resources)
* [Books](#books)
* [Tutorials and Blog Posts](#tutorials-and-blog-posts)
* [IDEs](#ides)
* [Templates](#templates)
* [Talks and Videos](#talks-and-videos)
* [Companies using Coder](#companies-using-coder)

## Official Resources

- Case Studies ([Palantir](https://blog.palantir.com/the-benefits-of-remote-ephemeral-workspaces-1a1251ed6e53), [Forrester](https://coder.com/forrester?utm_source=github.com/coder/awesome-coder&utm_medium=github&utm_campaign=readme.md)) 
- [Documentation](https://coder.com/docs/coder-oss/latest?utm_source=github.com/coder/awesome-coder&utm_medium=github&utm_campaign=readme.md)
- [Blog](https://coder.com/blog?utm_source=github.com/coder/awesome-coder&utm_medium=github&utm_campaign=readme.md)
- [Press kit & Brand styleguide](https://github.com/coder/presskit)
- [Presentations](https://github.com/coder/presentations)
- [Discord](https://coder.com/chat?utm_source=github.com/coder/awesome-coder&utm_medium=github&utm_campaign=readme.md)
- [Twitter](https://twitter.com/CoderHQ)
- [Mastodon](https://fosstodon.org/web/@coderhq)

<!-- ## Books -->

## Tutorials and Blog Posts

- [The Benefits of Remote Ephemeral Workspaces](https://blog.palantir.com/the-benefits-of-remote-ephemeral-workspaces-1a1251ed6e53)
- [Laptop development is dead: why remote development is the future](https://medium.com/@elliotgraebert/laptop-development-is-dead-why-remote-development-is-the-future-f92ce103fd13)
- [Coder OSS on GKE with Terraform in <20 minutes](https://github.com/ElliotG/coder-oss-gke-tf)

### Beginner Guides

- [Coder 101: How Coder Works At A Higher Level](https://coder.com/blog/coder-101-how-coder-works-at-a-higher-level?utm_source=github.com/coder/awesome-coder&utm_medium=github&utm_campaign=readme.md)

### What is Coder?

- [What Coder is not](https://coder.com/docs/v2/latest#what-coder-is-not)

<!-- ### AWS  -->

<!-- ### Azure -->

<!-- ### DigitalOcean -->

<!-- ### Google Cloud -->

<!-- ### ARM -->

<!-- ### macOS -->

### Comparison

Coder maintains an official list of comparisons in the [coder/coder README.md](https://github.com/coder/coder#comparison). Please [file an issue](https://github.com/coder/coder/issues/new) if any of the information in that section is out of date. See also: [what Coder is not](https://coder.com/docs/coder-oss/latest/index#what-coder-is-not?utm_source=github.com/coder/awesome-coder&utm_medium=github&utm_campaign=readme.md)

### Miscellaneous

## IDEs

- [Running a private VS Code Extension Marketplace](https://coder.com/blog/running-a-private-vs-code-extension-marketplace)

## Automation

- [Provision Coder with Terraform](https://github.com/ElliotG/coder-oss-tf) - Coder OSS on GKE with Terraform in <20 minutes.
- [Update Coder Template](https://github.com/marketplace/actions/update-coder-template) - A GitHub action to automate coder template changes.
- [Provision Coder with Lima](https://github.com/coder/coder/tree/main/examples/lima) - Linux virtual machines, typically on macOS, for running containerd.
- [Coder on Hetzner Cloud](https://github.com/tmsmr/coder-hcloud) - One-shot deployment for Coder on Hetzner Cloud

## Templates

- [Official templates](https://github.com/coder/coder/tree/main/examples/templates)
- [Community templates](https://github.com/coder/coder/blob/main/examples/templates/community-templates.md)

- [sharkymark/v2-templates](https://github.com/sharkymark/v2-templates) - A large collection of templates.
- [ntimo/coder-hetzner-cloud-template](https://github.com/ntimo/coder-hetzner-cloud-template) - Setup a Hetzner Cloud instance as dev environment with or without vscode.
- [matifali/coder-templates](https://github.com/matifali/coder-templates) - Deeplearning with Jupyter Notebook/Lab and Matlab in browser. 
- [m.lan/coder-templates](https://gitlab.com/m.lan/coder-templates) - Kubernetes template with Docker in Docker (DinD)
- [bpmct/coder-templates/proxmox-vm](https://github.com/bpmct/coder-templates/tree/main/proxmox-vm) - Develop in a Proxmox VM.
- [bpmct/coder-templates/shared-mac](https://github.com/bpmct/coder-templates/tree/main/shared-mac) - Connect a pre-provisioned Mac device and provision system users as workspaces
- [denbeigh2000/coder-templates/aws-nixos](https://github.com/denbeigh2000/coder-templates/tree/master/aws-nixos) - Manage a NixOS development workspace on EC2.
- [denbeigh2000/coder-templates/aws-spot-nixos-graviton](https://github.com/denbeigh2000/coder-templates/tree/master/aws-spot-nixos-graviton) - Manage a NixOS development workspace on EC2 with Graviton Spot Instances.
- [denbeigh2000/coder-templates/aws-spot-nixos](https://github.com/denbeigh2000/coder-templates/tree/master/aws-spot-nixos) - Manage a NixOS development workspace on EC2 with Spot Instances.
- [8Bitz0/coder-rust-template](https://gitlab.com/8Bitz0/coder-rust-template) - Coder templates with various Linux distros for out-of-the-box Rust development.
- [uwu/basic-env](https://github.com/uwu/basic-env) - Docker-based NodeJS development environment with code-server, NoVNC and dotfiles support out of the box
- [sulo1337/coder-kubevirt-template](https://github.com/sulo1337/coder-kubevirt-template) - Kubevirt-based development environment which provisions KVM virtual machines as coder workspaces on top of a Kubernetes cluster.

## Talks and Videos

- [Your Next Workstation Is In The Cloud](https://www.youtube.com/watch?v=C4fQvIHCVzw&t=748s)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Coder has waived all copyright and related or neighboring rights to this work.

