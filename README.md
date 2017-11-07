# inventory-load

Ansible doesn't let you define anything with variable ordering, for example you may need two sets of overlapping group vars, or perhaps you have a very specific built up data set which needs to happen in a particular order.

This role allows you to define an additional ordered list of locations which ansible will use to load in data from.

## Requirements

This module requires Ansible 2.4


Example Playbook
----------------

Example to call:

    - hosts: all
      roles:
         - { role: inventory-load }
