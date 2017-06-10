# ansible-filebeat-centos

ansible role to install Filebeat on CentOS

https://galaxy.ansible.com/suzuki-shunsuke/filebeat-centos/

Requirements
------------

Nothing.

Role Variables
--------------

* filebeat_state(optional): filebeat daemon state.
* filebeat_version(optional): filebeat version.
* filebeat_enabled(optional): whether filebeat daemon is enabled.

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
    filebeat_version: 5.4.0
```

License
-------

[MIT](LICENSE)
