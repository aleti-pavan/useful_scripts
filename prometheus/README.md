# Prometheus Installation

These scripts are tested on ubuntu 18.04 aws EC2 instances.

Steps:

```
1. git clone https://github.com/aleti-pavan/useful_scripts.git

2. cd useful_scripts/prometheus

3. ./1-install.sh

4. ./3-install-grafana.sh
```

Access Points:

`http://hostname:9090` - prometheus url

`http://hostname:3000` - grafana url (both username and password is `admin`)
