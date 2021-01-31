# Benchmarking with Ansible

This project is a basic Ansible playbook for benchmarking Linux machines.  

## Caddy

The Caddy benchmark installs the [Caddy HTTP server](https://caddyserver.com/)
on each target machine, creates some random files of various sizes, then has
the Ansible host machine run the [hey HTTP load-tester](https://github.com/rakyll/hey)
against each target machine in turn.
