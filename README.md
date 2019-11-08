# Ansible Roles for KVM based local stand
* Prepared for Ubuntu host with CPU supporting hardware virtualization
* It ensures Virtual Machines (necessary number), TOR on host (based on bird) and setup BGP overlay network

```bash
PASS=xxx make local_stand           # create local stand
PASS=xxx make local_stand_destroy   # destroy local stand
```
