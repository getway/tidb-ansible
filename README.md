# Ansible Playbook for TiDB
## Overview
Ansible is an IT automation tool. It can configure systems, deploy software, and orchestrate more advanced IT tasks such as continuous deployments or zero downtime rolling updates.

[TiDB-Ansible](https://github.com/pingcap/tidb-ansible) is a TiDB cluster deployment tool developed by PingCAP, based on Ansible playbook. TiDB-Ansible enables you to quickly deploy a new TiDB cluster which includes PD, TiDB, TiKV, and the cluster monitoring modules.
 
You can use the TiDB-Ansible configuration file to set up the cluster topology, completing all operation tasks with one click, including:
	
- Initializing the system, including creating user for deployment, setting up hostname, etc.
- Deploying the components
- Rolling upgrade, including module survival detection
- Cleaning data
- Cleaning environment
- Configuring monitoring modules

## Tutorial
[English](https://github.com/pingcap/docs/blob/master/op-guide/ansible-deployment.md)
[简体中文](https://github.com/pingcap/docs-cn/blob/master/op-guide/ansible-deployment.md)

## License
TiDB-Ansible is under the Apache 2.0 license. 