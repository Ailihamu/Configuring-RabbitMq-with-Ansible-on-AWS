# Configuring-RabbitMq-with-Ansible-on-AWS
Configuring RabbitMq with Ansible on AWS EC2

## Table of Contents

1. [Prerequisite and Installation](#installation)
2. [Overview](#overview)
3. [File Descriptions](#files)
4. [Results](#results)

## Prerequisite and Installation <a name="installation"></a>
- AWS Account
- Ansible 
- AWS CloudFormation

## Overview<a name="overview"></a>
#### 1. Creating three RabbitMq nodes with EC2 using Cloudformation Template

#### 2. Using Ansible configure RabbitMq clusters with 3 nodes (EC2), tasks include
   - Set up host names for RabbitMq nodes communication
   - Import GPG keys, set up Rabbit-server and Erlang repository
   - Yum install Rabbit-server, Erlang and related packages
   - Setting Erlang Cookie for all nodes
   - Join nodes to the cluster
   - Checking cluster status
 
## File Descriptions <a name="files"></a>

![File tree](https://github.com/Ailihamu/Configuring-RabbitMq-with-Ansible-on-AWS/blob/main/Pics/File_tree.png)

## Results<a name="results"></a>
### 1. Creating three EC2 instances by using cloudformation template.

![EC2 nodes](https://github.com/Ailihamu/Configuring-RabbitMq-with-Ansible-on-AWS/blob/main/Pics/EC2_Node_IPs.png)


### 2. Running Ansible playbook.

![EC2 nodes](https://github.com/Ailihamu/Configuring-RabbitMq-with-Ansible-on-AWS/blob/main/Pics/Cluster_stat.png)


### 3. RabbitMq Cluster Dashboard

![EC2 nodes](https://github.com/Ailihamu/Configuring-RabbitMq-with-Ansible-on-AWS/blob/main/Pics/Rabbit_cluster_dash.png)

