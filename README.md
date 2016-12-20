# Zookeeper

## Variables

### zookeeper_myid
Set `zookeeper_myid` if you want to set up `$ZOOKEEPER_CONF/myid` configuration file manually to specific value. If `zookeeper_myid` is not given, Ansible automatically assign `myid` value based on client order given by `zookeeper_host_[1-3]`.

### zookeeper_host
Set IP addresses for hosts `zookeeper_host_1`, `zookeeper_host_2` and `zookeeper_host_3`. Ansible will propagate setup into `$ZOOKEEPER_CONF/zoo.cfg` configuration file.

## License
Apache

## Author Information
Tim Kuhlman
Monasca Team email monasca@lists.launchpad.net
