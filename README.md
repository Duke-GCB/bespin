# Bespin

Computational genomic workflows in the cloud

### Index

Several software components work together to compose a Bespin system. This repository serves as an index for those components, linked below.

- [bespin-api](https://github.com/Duke-GCB/bespin-api) - Web service for running workflows in the cloud (Python, Django)
- [bespin-ui](https://github.com/Duke-GCB/bespin-ui) - Web application frontend for bespin-api (JavaScript, Ember)
- [lando](https://github.com/Duke-GCB/lando) - Service that runs workflows on VMs in a openstack cloud (Python)
- [lando-messaging](https://github.com/Duke-GCB/lando-messaging) - Shared library code for lando<->bespin communication (Python)
- [bespin-mailer](https://github.com/Duke-GCB/bespin-mailer) - Service that notifies users of bespin job actions (Python)
- [bespin-job-watcher](https://github.com/Duke-GCB/bespin-job-watcher) - Websocket server that pushes notifications to bespin-ui (JavaScript, Node)
- [bespin-cwl](https://github.com/Duke-GCB/bespin-cwl) - Curated CWL workflows to run on Bespin (Common Workflow Language)
- [GCB-Dockerfiles](https://github.com/Duke-GCB/GCB-Dockerfiles) - Docker image descriptions for tools used in CWL workflows (Docker)
- [gcb-ansible-roles](https://github.com/Duke-GCB/gcb-ansible-roles) - Ansible roles for deploying bespin components
