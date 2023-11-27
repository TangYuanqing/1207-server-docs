服务器IP地址与配置
=============
.. hint::

    公网IP不保证随时可用，同时公网IP的带宽较小。除非必要，否则请优先通过内网连接。

node-4090
-------------

IP地址
^^^^^^^^^^^^^^^^^^^^^

- 内网地址: ``172.20.185.100``
- 公网地址: ``47.100.130.127:12070``

.. attention::
    对于1203的同学，请使用如下内网地址：\ ``172.20.185.99:12070``

硬件配置
^^^^^^^^^^^^^^^^^^^^^
.. code-block:: shell

    OS: Debian GNU/Linux 12 (bookworm) x86_64
    Kernel: 6.1.0-13-amd64
    Shell: bash 5.2.15
    CPU: 13th Gen Intel i9-13900K (32) @ 2.995GHz 
    GPU 0: NVIDIA GeForce RTX 4090 
    GPU 1: NVIDIA GeForce RTX 4090 
    Memory: 48168MiB (48 GiB)

node-3090
-------------

IP地址
^^^^^^^^^^^^^^^^^^^^^

- 内网地址: ``172.20.185.101``
- 公网地址: ``47.100.130.127:12071``

.. attention::
    对于1203的同学，请使用如下内网地址：\ ``172.20.185.99:12071``

硬件配置
^^^^^^^^^^^^^^^^^^^^^
.. code-block:: shell

    OS: Debian GNU/Linux 12 (bookworm) x86_64
    Kernel: 6.1.0-13-amd64
    Shell: bash 5.2.15
    CPU: 12th Gen Intel i9-12900K (24) @ 3.187GHz 
    GPU 0: NVIDIA GeForce RTX 3090 
    GPU 1: NVIDIA GeForce RTX 3090 
    Memory: 48170MiB (48 GiB)

各服务器共享一块16T 7200转的机械硬盘作为用户目录。