# kubeadm-ansible-ubuntu20.04
Install Kubadm on Ubuntu 20.04

Introduction
Kubernetes is an open source platform, actively developed by a community around the world, which enables the management and orchestration of large-scale application containers.
In the following tutorial its latest version is used, by configuring a Kubernetes cluster from scratch and using the Ansible software for the automation of the procedures and the Kubeadm tool for cluster creation on an Ubuntu 20.04 server.
Provided the servers in the cluster have enough CPU and RAM resources for the applications to run, by the end of this guide you will have a cluster ready to run containerized applications. Before proceeding with this tutorial, make sure you have at least two worker machines, and a master machine with at least 2 CPUs that can work properly with the worker machines.
First, connect to your server via SSH. If you haven't done so yet, following our guide is recommended to  connect securely with the SSH protocol . In case of a local server, go to the next step and open the terminal of your server.