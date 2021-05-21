# Documentation Layout

This page is useful for tracking content changes across versions.

Oftentimes, well want to trim or combine content.

It also describes all article subsections and video content in one quick view to make planning easier.

## Blogs and READMEs

- Blogs live in https://github.com/gravitational/web and are hosted live at https://goteleport.com/blog/.
- READMEs live in the root directory of each GitHub repository.

## Meta-Documentation

- Meta Documentation Section
  - [Documentation Quicks Start](https://goteleport.com/docs/docs/)
  - [Documentation Best Practices](https://goteleport.com/docs/docs/best-practices/)

## Products Supported

Our current Product and Reference Documentation topics are divided into thirteen (13) sections supporting the four (4) main products: 

1. Teleport Application Access
2. Teleport Server Access
3. Teleport Database Access
4. Teleport Kubernetes Access 

Along with a fifth for:

5. Teleport Cloud

## Product and Reference Documentation

The documentation layout and structure is presently:

- [ ] Home Section
    - [ ]  Introduction
        - [ ] What is Teleport
        - w/ Demo video
        - w/ Tile landing

    - [ ] Adopters
        - [ ] Who is using Teleport

    - [ ] Getting Started
        - [ ] Prerequisites
        - [ ] Follow along with our video guide
        - [ ] Step 1/4. Install Teleport on a Linux machine
        - [ ] Step 2/4. Create a Teleport user and set up two-factor authentication
        - [ ] Step 3/4. Log in using tsh
        - [ ] Step 4/4. Have fun with Teleport!
        - [ ] Guides
 
    - [ ] Installation
        - [ ] Linux
        - [ ] Docker
        - [ ] Helm
        - [ ] MacOs
        - [ ] Windows (tsh client only)
        - [ ] Installing from source
        - [ ] Checksums
        - [ ] Operating System support

    - [ ] User Manual
        - [ ] Introduction
        - [ ] Installing tsh
        - [ ] User identities
        - [ ] Logging in
        - [ ] Explorign the cluster
        - [ ] Interactive shell
        - [ ] Copying files
        - [ ] Sharing sesssions
        - [ ] Connecting to SSH clusters behind a load balancer
        - [ ] Web UI
        - [ ] Using OpenSSH client
        - [ ] Troubleshooting
        - [ ] Getting help

    - [ ] Admin Manual
        - [ ] Installing
        - [ ] Definitions
        - [ ] Teleport Daemon
        - [ ] Configuration
        - [ ] Authentication
        - [ ] Adding and deleting users
        - [ ] Editing users
        - [ ] Adding Nodes to the cluster
        - [ ] Revoking invitations
        - [ ] Adding a Node located behind NAT
        - [ ] Labeling Nodes and applications
        - [ ] Auding Log
        - [ ] Resources
        - [ ] Trusted Clusters
        - [ ] GitHub Oath 2.0
        - [ ] HTTP CONNECT proxies
        - [ ] PAM integration
        - [ ] Using Teleport with OpenSSH
        - [ ] Certificate rotation
        - [ ] Ansible integration
        - [ ] Kubernetes integration
        - [ ] Storage backeneds
        - [ ] High Availability
        - [ ] Upgrading Teleport
        - [ ] Backing up Teleport
        - [ ] GitOps
        - [ ] Migrating backends
        - [ ] License file
        - [ ] Troubleshooting
        - [ ] Getting help

    - [ ] Production Guide
        - [ ] Prerequisites
        - [ ] Designing your cluster
        - [ ] Firewall configuration
        - [ ] Installation
        - [ ] Running Teleport in production
        - [ ] Security considerations

    - [ ] FAQ
        - Section-specific FAQ
        - [ ] Community FAQ
        - [ ] Whcih version of Teleport is supported
        - [ ] Commercial Teleport Editions

    - [ ] Changelog
        - Teleport repository README is injected here.

- [ ] Application Access Section

    - [ ] Introduction
        - [ ] Application Access
        - [ ] Demo
        - [ ] Getting started
        - [ ] Guides
        - [ ] Example legacy apps
        - [ ] Example modern apps
        - w/ Tiles
        - w/ Video

   - [ ] Getting Started
        - [ ] Follow along with our video guide
        - [ ] Prerequisites
        - [ ] Step 1/3. Start Grafna
        - [ ] Step 2/3. Install and configure Teleport
        - [ ] Step 3/3. Access the application
        - [ ] Next steps

    - [ ] Guides
        - w/ Tiles
        - [ ] Connecting Web Apps
            - [ ] Connecting Web Applications
            - [ ] Start Auth/Proxy service
            - [ ] Start application service with CLI
            - [ ] Start application service with a config file
            - [ ] Advanced options
            - [ ] View applications in Teleport
            - [ ] Logging out of applications
        - [ ] Integrating with JWTs
            - [ ] Integrating with JWTs
            - [ ] Introduction to JWTs
            - [ ] Validate JWT
        - [ ] Applciation API Access
            - [ ] Application API Acces
            - [ ] Prequisites
            - [ ] Accessing the API
            - [ ] Application information

    - [ ] Access Controls
        - [ ] Assinging labels to applications
        - [ ] Configuring application labels in roles
        - [ ] Integrating with identity providers
        - [ ] Next steps

    - [ ] Reference
        - [ ] Configuration
        - [ ] CLI

- [ ] Server Access Section
    - [ ] Introduction
        - [ ] Server Access
        - [ ] Demo
        - [ ] Getting started
        - [ ] Guides
        - w/ Demo video
        - w/ Tile landing

    - [ ] Getting Started
        - [ ] Getting Started
        - [ ] Prerequisites
        - [ ] Step 1/4. Create a cluster
        - [ ] Step 2/4. Add a Node to the cluster
        - [ ] Step 3/4. SSH into the server
        - [ ] Step 4/4. Use tsh and the unified resource catalog
        - [ ] Conclusion
        - [ ] Next steps
        - [ ] Resources
        - w/ Diagrams
        - w/ Screenshots

    - [ ] Guides
        - [ ] Using Teleport with PAM
        - [ ] OpenSSH Guide

- [ ] Kubernetes Access Section

- [ ] Database Access Section

- [ ] Access Controls Section

- [ ] Preview Section
    - [ ] Upcoming Releases
        - [ ] Teleport 6.2 "Buffalo"
        - [ ] Teleport 7.0 "Stockholm"
        - [ ] Teleport Cloud "Washington"
        - [ ] Semantic Versioning

- [ ] Infrastructure Guides Section

- [ ] Teleport Enterprise Section

- [ ] Cloud Section

- [ ] Architecture Section

- [ ] Advanced Features Section

- [ ] Reference Section
    - [ ] YAML
        - [ ] teleport.yaml