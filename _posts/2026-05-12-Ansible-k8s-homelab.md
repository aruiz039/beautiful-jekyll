---
layout: post
title: "Kubernetes home lab set up with Ansible" 
subtitle: Orchestrate and Automate
cover-img: /assets/img/Ansible_Kubernetes.png
thumbnail-img: /assets/img/Ansible_Kubernetes.png
share-img: /assets/img/Ansible_Kubernetes.png
tags: [Ansible, Kubernetes, Homelab]
author: Alfredo Ruiz
---


# Ansible And Kubernetes — Let's Build Something

During a recent interview, Ansible came up because the company I was applying to heavily used it. I hadn't used it as much as I would have liked before the interview.

A week later, I had finished a course to refresh my knowledge and was prompting Claude to create a project with steps I could follow for building something with Ansible and Kubernetes.

I dislike using AI to have something completely done for you. I want to resist that as much as I can, so I am still learning and figuring out how to make high-level design decisions when I build.

In the end, I built a set of Ansible playbooks that updated Kubernetes dependencies, installed Kubernetes, configured the control plane and workers, and deployed a Grafana workload alongside a Ghost blog server.

## Goals

My goals generally remain the same from project to project: learn by building to supplement the coursework I do and create work that is good for my portfolio. I also had a new goal after the interview: finding someone else's project and contributing to it.

## Getting Stuck Is Where You Learn

The biggest trouble spot was working with the VirtualBox bridged network. I will probably use Vagrant next time. Setting up linting was completely new to me and was a welcome lesson.

My biggest takeaway from learning Ansible was understanding how all the files and components interact together to get something done.

Well, back to hitting the books. Till the next project.

### Some of the more technical details i leave for Github
[Ansible K8s Homelab ](https://github.com/aruiz039/ansible-k8s-homelab)  

### How it came out looking
![BlogProjectDiagram](/assets/img/k8s_homelab_architecture.svg)

![Kubernetes](/assets/img/Kubernetes_Running.png)

### Running sites  

![Grafana](/assets/img/Grafana.png)

![Ghost](/assets/img/Ghost.png)