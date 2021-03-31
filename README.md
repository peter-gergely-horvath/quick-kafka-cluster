
# Quick local Kafka development cluster

This repository contains Vagrant and Ansbile configuration for quickly 
setting up a small Kafka cluster on a local machine.

Use the shell script `vagrant-up.sh` to start it.

## Prerequisites: 

Install the following software:
 * HashiCorp Vagrant
 * Ansible
 * Oracle VirtualBox 
 * `bsdtar` utility

## Shell scripts 

### Basic Vagrant scripts

 * `vagrant-up.sh`: Start the cluster
 * `vagrant-halt.sh`: Shutdown the cluster 
 * `vagrant-destroy.sh`: Destroy the cluster (deletes all data)
 

### Ansible

 * `ansible-provision.sh`: runs Ansible provision only (use when the cluster is up)  


### SSH

 * `ssh-kafkanode1.sh`: SSH to Kafka Node #1  
 * `ssh-kafkanode2.sh`: SSH to Kafka Node #2  
 * `ssh-kafkanode3.sh`: SSH to Kafka Node #2  

