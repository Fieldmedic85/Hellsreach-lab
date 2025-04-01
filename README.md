# Hellsreach-lab

Welcome to my homelab repository! 

This space documents the design, infrastructure, and automation workflows behind my personal lab environment. I built this homelab to deepen my understanding of enterprise-level technologies, network security, container orchestration, and CI/CD pipeline automation.

Core Objectives

Continuous Learning: Experiment with enterprise tools, virtualization, and automation.

Automation First: Build and refine CI/CD pipelines, infrastructure management, and network configurations.

Security & Scalability: Design a robust and segmented network to ensure isolation, security, and reliability.

Experimentation: Explore new technologies, integrate monitoring solutions, and optimize system performance.



---

📡 Network and Infrastructure

Network Topology

Core Switch: Cisco Catalyst 3850

Router: MikroTik RB3011 (handling Wireless, Guest Wireless, and IoT VLANs)

Trunk Link: Established between Cisco and MikroTik for VLAN management


VLANs and Network Segmentation

Infrastructure VLAN: For critical services and core infrastructure

Servers VLAN: Isolated environment for VMs, Docker containers, and back-end services

Desktops VLAN: For workstations and development machines

WAPS VLAN: Segregated VLAN for wireless access points

Cameras VLAN: Dedicated network for IP surveillance devices

IoT VLAN: Isolated for smart home and IoT devices, restricting local access



---

🗄️ Servers and Services

Current Infrastructure

Truenas Scale & Windows 2022

File Server: Dell PowerEdge R710. File server with a windows domain controller.

Study Server: Dell PowerEdge R610 for automation testing and CCNP research

Minecraft Server: Fabric-based server managed with Portainer

*Decommissioned*Offline Storage: Dell NX400 for offline storage and cold backups

DNS Server: Lenovo m710q, ensuring internal name resolution


Container and Virtualization Setup

Portainer Stack: Manages Docker containers and service orchestration

Ansible Automation: Used for managing VM configurations and network updates

TrueNAS Scale: Manages file services and local storage



---

🎮 VR and Gaming

Minecraft Fabric Server: Hosting and managing modded dimensions across physical servers

Meta Quest Automation: Building and research for automated APK/OBB deployment pipelines using ADB and OVR tools

---

🕹️ Projects and Experiments

Active Projects

Shiny Python Dashboard: Real-time Jenkins and SVN log monitoring with 5-second refresh intervals.

SVN and Jenkins Pipeline Automation: Automating Unreal Engine build and deployment pipelines.

VLAN Optimization and Segmentation: Fine-tuning MikroTik and Cisco VLAN handling.

Containerization and Portainer Transition: Exploring migration to a Python/React-based self-hosted web interface.


Future Ideas

Grafana & Prometheus Integration: Centralized monitoring and alerting for Ansible logs, network configurations, and VMs.

Pi-Based Applications: Exploring the potential of Pi-based AI and IoT applications for home automation.

AI-Enhanced Log Analysis: Implementing machine learning models to identify and predict system anomalies.

Dynamic DNS and Security Rules: Automated DNS updates and security policy management.

---

🔧 Automation and DevOps

Jenkins Pipelines: Extensive use of Jenkins to automate Unreal Engine builds, package deployment, and version control.

PowerShell and Bash Automation: Ensuring fault-tolerant configurations, error-handling, and continuous task management.

SVN & Confluence Documentation: Automated updates and documentation using Python and Confluence API.



---

📚 Personal Development Goals

Why I Built This Lab

My homelab is more than just a sandbox—it's an evolving environment designed to refine my technical knowledge, troubleshoot complex systems, and experiment with automation frameworks. This hands-on approach allows me to:

Develop DevOps Skills: Master Jenkins, Ansible, Docker, and GitLab CI/CD practices.

Enhance Network Security Knowledge: Gain expertise in VLAN segmentation, firewall configuration, and wireless security.

Gain Cloud and Infrastructure Proficiency: Explore hybrid cloud solutions, container orchestration, and scalable deployments.


Certifications and Career Aspirations

Current Certifications: CCNA, Diploma I.T Administration

Future Goals: CCNP, possibly PRINCE2

Other goal:
Enhance DevOps expertise, explore Terraform and GitLab for managing infrastructure as code, and contribute to open-source projects related to automation and monitoring.



---

⚡ How to Use This Repository

This repository contains scripts, documentation, and configurations related to my homelab. Feel free to explore, adapt, and provide feedback. I aim to continually refine my automation and networking skills while sharing insights and lessons learned along the way.


---

🤝 Contributing

Although this is a personal repository, suggestions and ideas for improvement are always welcome! If you'd like to share feedback or collaborate on similar projects, feel free to reach out.


---

📧 Contact

For inquiries, discussions, or collaboration opportunities, please contact me via GitHub or through my professional channels.



I've created a detailed README.md document for your homelab public repository. It includes an overview of your infrastructure, projects, automation workflows

