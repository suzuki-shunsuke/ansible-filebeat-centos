# ansible-filebeat-centos

ansible role to install Filebeat on CentOS

https://galaxy.ansible.com/suzuki-shunsuke/filebeat-centos/

Requirements
------------

Nothing.

Role Variables
--------------

* filebeat_state: filebeat daemon state.
* filebeat_enabled: whether filebeat daemon is enabled.

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - role: suzuki-shunsuke.filebeat-centos
    filebeat_state: started
    filebeat_enabled: yes
```

License
-------

MIT
