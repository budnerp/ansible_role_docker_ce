# Ansible role for Docker CE
Ansible role for Docker CE for CentOS 7

## What's inside?
1. Interesting Docker CE dirs and files: 
    ```
    ...
    ```
2. `vagrant` user is added to `docker` group allowing him to operate with docker without sudo
   
## Tested on
docker-ce 17.03.2-ce, build f5ec1e2

## Installation
1. Navigate to Ansible's roles folder
2. Add the repo to git modules
    ```
    git submodule add https://github.com/budnerp/ansible_role_docker_ce.git ansible_role_docker_ce
    ```
3. Add the role to Ansible's playbook file
    ```    
    roles:
    [...]
        - ansible_role_docker_ce
    [...]
    ```

## Other links
- Get Docker CE for CentOS [https://docs.docker.com/install/linux/docker-ce/centos/]()
- Getting started [https://docs.docker.com/get-started/]()

## TO DO
-[ ] add dependencies 
-[ ] The overlay2 storage driver is recommended (`overlay` is used right after installation)

## License
Copyright (c) We Are Interactive under the MIT license.