ceph-loop-device
================

This role creates the /dev/loop3 (default) loop device required when you have
ceph services in the deployment.


Role Variables
--------------

ceph_loop_device: /dev/loop3
ceph_loop_device_file: /var/lib/ceph-osd.img

Requirements
------------

 - ansible >= 2.4
 - python >= 2.6

Dependencies
------------

None

Example Playbooks
-----------------

.. code-block::

    - hosts: localhost
      roles:
        - ceph-loop-device

License
-------

Apache 2.0
