[![GitHub issues](https://img.shields.io/github/issues/0ta2/motd-role)](https://github.com/0ta2/motd-role/issues)
[![GitHub stars](https://img.shields.io/github/stars/0ta2/motd-role)](https://github.com/0ta2/motd-role/stargazers)
[![CircleCI](https://img.shields.io/circleci/build/github/0ta2/motd-role/master?token=2df5d802de684ea6d2e04972e018a60091755d80)](https://circleci.com/gh/0ta2/motd-role)
[![Ansible Role](https://img.shields.io/ansible/role/43413)](https://galaxy.ansible.com/0ta2/motd_role)

motd-role
=========

ログイン時に表示する `/etc/motd` を設定するロールです｡

Requirements
------------

特になし｡

Role Variables
--------------

`env` という変数名によって､ログイン時に表示する文字を変えています｡

指定していない場合

```
 █████╗ ███╗   ██╗███████╗██╗██████╗ ██╗     ███████╗
██╔══██╗████╗  ██║██╔════╝██║██╔══██╗██║     ██╔════╝
███████║██╔██╗ ██║███████╗██║██████╔╝██║     █████╗
██╔══██║██║╚██╗██║╚════██║██║██╔══██╗██║     ██╔══╝
██║  ██║██║ ╚████║███████║██║██████╔╝███████╗██████
╚═╝  ╚═╝╚═╝  ╚═══╝╚══════╝╚═╝╚═════╝ ╚══════╝╚══════╝
```

dev の場合

```
██████╗ ███████╗██╗   ██╗
██╔══██╗██╔════╝██║   ██║
██║  ██║█████╗  ██║   ██║
██║  ██║██╔══╝  ╚██╗ ██╔╝
██████╔╝███████╗ ╚████╔╝
╚═════╝ ╚══════╝  ╚═══╝
```

stg の場合

```
███████╗████████╗ ██████╗
██╔════╝╚══██╔══╝██╔════╝
███████╗   ██║   ██║  ███╗
╚════██║   ██║   ██║   ██║
███████║   ██║   ╚██████╔╝
╚══════╝   ╚═╝    ╚═════╝
```

prd の場合

```
██████╗ ██████╗ ██████╗
██╔══██╗██╔══██╗██╔══██╗
██████╔╝██████╔╝██║  ██║
██╔═══╝ ██╔══██╗██║  ██║
██║     ██║  ██║██████╔╝
╚═╝     ╚═╝  ╚═╝╚═════╝
```

License
-------

![GitHub](https://img.shields.io/github/license/0ta2/motd-role)
