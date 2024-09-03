<!-- This file was automatically generated by the `geine`. Make all changes to `README.yaml` and run `make readme` to rebuild this file. -->
![Banner](https://github.com/clouddrove/terraform-module-template/assets/119565952/67a8a1af-2eb7-40b7-ae07-c94cde9ce062)
<h1 align="center">
    DevOps Machine
</h1>

<p align="center" style="font-size: 1.2rem;">
    A comprehensive Docker-based DevOps environment equipped with essential tools like Terraform, Ansible, Helm, and more.
</p>

<p align="center">
<a href='https://facebook.com/sharer/sharer.php?u=https://github.com/clouddrove/devops-machine'>
  <img title="Share on Facebook" src="https://user-images.githubusercontent.com/50652676/62817743-4f64cb80-bb59-11e9-90c7-b057252ded50.png" />
</a>
<a href='https://www.instagram.com/cloud_drove?igsh=cHJqaDY3bGtnYmh3' title="Follow On Instagram">
  <img src="https://github.com/gauravghongde/social-icons/blob/master/SVG/Color/Instagram.svg" width="23" height="23" />
</a>
<a href='https://www.linkedin.com/shareArticle?mini=true&title=devops-machine&url=https://github.com/clouddrove/devops-machine'>
  <img title="Share on LinkedIn" src="https://user-images.githubusercontent.com/50652676/62817742-4e339e80-bb59-11e9-87b9-a1f68cae1049.png" />
</a>
<a href='https://twitter.com/intent/tweet/?text=devops-machine&url=https://github.com/clouddrove/devops-machine'>
  <img title="Share on Twitter" src="https://user-images.githubusercontent.com/50652676/62817740-4c69db00-bb59-11e9-8a79-3580fbbf6d5c.png" />
</a>
</p>

---

This repository provides a Docker-based environment configured with a robust set of DevOps tools, including Terraform, Ansible, Helm, and more. This environment is designed to streamline DevOps workflows, automate tasks, and enhance productivity.

## 🚀 Features

- **Docker-Based Environment**: Run all tools within an isolated Docker container.
- **Phusion/baseimage (jammy-1.0.4)**
- **SSH access enabled**
- **Custom user 'ubuntu' with sudo privileges.**
- **Zsh shell with Oh My Zsh framework and all necessary plugins.**
- **Added aliase for tools command in aliases.conf file.**
- **Mounted volumes in docker-compose file for persistence data.**
- **Added extra shell configuration in extra.conf**
- **Various development and operations and pre-installed tools with the latest version.** 
- **Pre-installed Tools**:
  - **Terraform**: v1.9.0
  - **Ansible**: v10.3.0
  - **Helm**: v3.15.1
  - **Packer**: v1.11.2
  - **Kubectl**: v1.31.0
  - **AWS CLI**: v2.17.33
  - **Azure CLI**: v2.63.0
  - **GCloud CLI**: v489.0.0
  - **K9s**: v0.32.5
  - **TFSwitch**
  - **OpenTofu**
  - **Kubectx**
  - **ZSH**: Pre-configured with Oh My Zsh

## 🛠 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/clouddrove-sandbox/devops-machine.git
   cd devops-machine

##  Prerequisites
- Docker and Docker Compose installed on your host machine.
- Make utility.

## 🛠 Build A Docker Image

2. Copy and paste this command(Dockerfile is located in .docker directory):
   ```bash
   docker build -t devops-machine .docker/  

## 🔧 Running the DevOps Machine

3. To start the DevOps machine, use the following command:

   ```bash
   make up  

4. To access the Dev-ops Machine Run this command:

- You will be login as ubuntu user.
- And no password is required for login.

```bash
   make ssh


