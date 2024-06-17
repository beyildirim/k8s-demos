# k8s-demos

Welcome to the k8s-demos repository! This repository contains various Kubernetes YAML files that I have created while learning Kubernetes. These files include configurations for deployments and pods.

## Table of Contents
- [Introduction](#introduction)
- [Contents](#contents)
- [Usage](#usage)

## Introduction
This repository serves as a collection of Kubernetes YAML files that I created during my learning journey. The goal is to provide a reference and starting point for others who are also learning Kubernetes.

## Contents
- **deployments/**
  - `apache-web-server.yaml`: Deployment for Apache Web Server.
  - `jenkins-deployment.yaml`: Deployment for Jenkins.
  - `mysql-deployment.yaml`: Deployment for MySQL.
  - `node-deployment.yaml`: Deployment for Node.js.
  - `redis-deployment.yaml`: Deployment for Redis.
  - `tomcat-deployment.yaml`: Deployment for Tomcat.
  - `grafana-deployment.yaml`: Deployment for Grafana.
  - `initContainers-deployment.yaml`: Deployment utilizes initContainers.
  - `iron-gallery-deployment.yaml`: Deployment for Iron Gallery app.
  - `lamp-deployment.yaml`: Deployment for LAMP.
  - `lemp-deployment.yaml`: Deployment for LEMP.
  - `rollback-plan-deployment.yaml`: Deployment for playing with rollback options.
- **pods/**
  - `environment-checker.yaml`: Pod for checking the environment.
  - `time-check.yaml`: Pod for checking the current time.
  - `print-env-vars.yaml`: Pod to print environment variables.
  - `persistent-volume-pod.yaml`: Pod that uses a persistent volume
  - `secrets-pod.yaml`: Pod mounts secret volume
## Usage
To use these files, you can clone the repository and apply the configurations to your Kubernetes cluster. Modify the files as needed to fit your specific requirements.

```bash
git clone https://github.com/beyildirim/k8s-demos.git
cd k8s-demos

# Apply a deployment file
kubectl apply -f deployments/apache-web-server.yaml

# Apply a pod file
kubectl apply -f pods/environment-checker.yaml

```
