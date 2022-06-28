# Ansible Role for ZeroUI

![](https://img.shields.io/github/workflow/status/dec0dOS/zero-ui-ansible/Check%20and%20publish)
![](https://img.shields.io/badge/dynamic/json?color=orange&label=Galaxy%20Downloads&query=%24.download_count&url=https%3A%2F%2Fgalaxy.ansible.com%2Fapi%2Fv1%2Froles%2F59586%2F%3Fformat%3Djson)

For detailed documentation, use the [Ansible Docs](https://docs.ansible.com).

Example playbook:

```yaml
- hosts: all
  roles:
    - dec0dos.zero_ui
  vars:
    zero_ui:
      path: /srv/zero-ui
  become: true
```
