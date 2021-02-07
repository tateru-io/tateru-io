![Tateru logo](tateru-web-small.png)

Tateru is a collection of services that offers a framework for building Ansible-based OS
installation playbooks to install bare-metal or virtual machines.

**State: Early prototyping**

## Objective

 * Create a system for handling the server lifecycle related to initial OS deployment
as well as OS re-deployment on failure or repurposing based on Ansible.
 * Support common server Linux distributions initially, grow as needed.
 * Be reasonably opinionated, but do not interfere too much with existing infrastructure.

# Tateru API definitions

These links point to the latest commit on the `main` branch:

 * [Manager API](https://tateru.github.io/tateru/api/manager.api.html)
 * [Machine Service API](https://tateru.github.io/tateru/api/machine-service.api.html)
