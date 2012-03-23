Nova Tools
----------

Various scripts for interacting with openstack nova

Nova Top
--------

Curses cli interface to nova.  Depends on python-novaclient.

  ./nova-top

Nova Debug
----------

Restart a running linux vm with a and connect to the serial console. Gives you an opportunity to reset the root password, and sets up the guest serial console for you. Must be on the compute host where the instance is running.

  ./nova-debug [libvirt instance name or uuid]
