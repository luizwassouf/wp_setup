# wp_setup

**Ansible recipe to set up a wordpress installation with the following features:**
```
- set a random hostname
- manage the apt package manager to force ipv4 and enable auto updates for security packages
- install a webserver and a php processor
- install wordpress
```

**Notes:**

```
- this recipe was made to run in a Ubuntu 16.04 distro
- make sure you edit the ansible.cfg file with your credentials
- make sure you edit the hosts file with your target servers and your ssh user to be connecting
- execution log will be saved to ./wp_setup.log file
```
