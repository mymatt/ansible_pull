## Overview

- This ansible pull playbook is used by terraform in the repo Terraform-AWS-Canary.
- It retrieves Ansible roles from an S3 bucket and executes them. The roles are: Golang Web Server, Nginx Proxy, Consul, Consul Template and a KV role that installs KV pairs on the Consul KV store.
- Variables are passed from terraform to each Ansible role
- See the Terraform-AWS-Canary repo for more details


#### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
