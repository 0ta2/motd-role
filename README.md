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

MIT
