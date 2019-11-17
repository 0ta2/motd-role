[![GitHub issues](https://img.shields.io/github/issues/0ta2/motd-role)](https://github.com/0ta2/motd-role/issues)
[![GitHub stars](https://img.shields.io/github/stars/0ta2/motd-role)](https://github.com/0ta2/motd-role/stargazers)
[![CircleCI](https://img.shields.io/circleci/build/github/0ta2/motd-role/master)](https://circleci.com/gh/0ta2/motd-role)
[![Ansible Role](https://img.shields.io/ansible/role/43413)](https://galaxy.ansible.com/0ta2/motd_role)

motd-role
=========

ログイン時に表示する `/etc/motd` を設定するロールです｡

Requirements
------------

特になし｡

Installation
--------------

ansible galaxy コマンドでインストールする場合

```
$ ansible-galaxy install 0ta2.motd_role
```

Example Playbook
--------------

```
    - hosts: servers
      roles:
         - { role: 0ta2.motd_role }
```

下記の様な情報が表示されるようになります。

```
   ______     __   __     ______     __     ______     __         ______
  /\  __ \   /\ "-.\ \   /\  ___\   /\ \   /\  == \   /\ \       /\  ___\
  \ \  __ \  \ \ \-.  \  \ \___  \  \ \ \  \ \  __<   \ \ \____  \ \  __\
   \ \_\ \_\  \ \_\\"\_\  \/\_____\  \ \_\  \ \_____\  \ \_____\  \ \_____\
    \/_/\/_/   \/_/ \/_/   \/_____/   \/_/   \/_____/   \/_____/   \/_____/


 FQDN:    instance
 Distro:  CentOS 7.7
 CPUs:    2
 RAM:     2.0GB
```

Role Variables
--------------

None.

License
-------

![GitHub](https://img.shields.io/github/license/0ta2/motd-role)
