30 janvier,  - event

1. Docker on GCE

Hubot - like github
squid

Deployment - with "ansible"

Strategy: One component at a time

simpler ansible scripts: deploys configuration

Every can build and run like in production

Build can archived, isolated, can fail safely.

The web is stopped 1s - deployment

Incremental build:
    - Build version N-1 from tar.gz
    - add sources
    - build version N

Rollback:
    - recover already builted image
    - OR redeploy the previous tag

[before deploy]
Test Ansible against a container

Build the docker image with jenkins:
    - Slower CI, not useful

Use fig for Nginx/java
    - Ansible can do that.

Use Ansible Docker's module:

Might do:
    - Run Jenkins in Docker


2. Google Cloud Platform: Container, Cluster and Services
by Greg DeMichillie

Containers create a better abstraction layer

## Kubernetes (helmsman of a ship)

df: Open source cluster management
 - extensible
 - portable
 - run anywhere
 - launched july in 2014

VM centric development:
    - Everything gathered up in VM images
    - Fragile, tightly coupled apps
    
Docker: 
    - safe, reliable, 
    - portable
    - efficient isolation and resource use

Clustering (Kubernetes):
  - declarative app model
  - agile, decoupled app architecture
  - smart (ML enhanced) active managemenent
  - Portable management framework is a must

Pod:
    - Co-scheduled containers
    - can be labeled
    - Replica managers: managing the lifecycle of containers
    - Service: a way to find and consume distributed system (collection of pods)

cloud.google.com/startercredit
code: par-dock


Container based development

3. Google cloud engine - demo
by @proppy

nc
