# prov__kvm
ansible role for kvm provisioning
# requirements
# variables
# dependencies
# examples
```
---

- name: usage example
  hosts: target_hosts

  tasks:

    - name: provision libvirt
      ansible.builtin.include_role:
        name: prov__kvm
        tasks_from: libvirt.yml

    - name: provision network bridge
      ansible.builtin.include_role:
        name: prov__kvm
        tasks_from: bridge.yml

...
```
