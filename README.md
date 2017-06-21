# Contention and perfromance degradation examples

A very simple Keystone DDoS Rally jobs is in this repository. 

Another examples of performance problems are described here:

https://rally.readthedocs.io/en/0.0.4/stories/keystone/authenticate.html

https://rally.readthedocs.io/en/0.0.4/stories/nova/boot_server.html

However, it seems like in the latest versions of Openstack 
some functionaluty associated with eventlet_server is deprecated. So it's not possible to repear the tutorial part that says
'''
1. increasing public_workers/admin_workers values in keystone.conf file
'''
exactly.

