# containerlab-arista-vxlan

```
❯ docker import cEOS64-lab-4.30.5M.tar.xz ceos:4.30.5M
sha256:29f9e4250f3743814ba0cfb20d7ff1525ab25c8c04304e02e170036af110699e

❯ docker images ceos
REPOSITORY   TAG       IMAGE ID       CREATED          SIZE
ceos         4.30.5M   29f9e4250f37   19 seconds ago   2.38GB
```

+---+--------------------------+--------------+---------------------------------+-------+---------+----------------+----------------------+
| # | Name | Container ID | Image | Kind | State | IPv4 Address | IPv6 Address |
+---+--------------------------+--------------+---------------------------------+-------+---------+----------------+----------------------+
| 1 | clab-arista-ceos-host01 | 75e8bf78b8c6 | ghcr.io/hellt/network-multitool | linux | running | 172.20.20.5/24 | 2001:172:20:20::5/64 |
| 2 | clab-arista-ceos-host02 | 4c08c743e564 | ghcr.io/hellt/network-multitool | linux | running | 172.20.20.2/24 | 2001:172:20:20::2/64 |
| 3 | clab-arista-ceos-leaf01 | dab0e8f82c99 | ceos:4.30.5M | ceos | running | 172.20.20.6/24 | 2001:172:20:20::6/64 |
| 4 | clab-arista-ceos-leaf02 | 1c0e391b2349 | ceos:4.30.5M | ceos | running | 172.20.20.4/24 | 2001:172:20:20::4/64 |
| 5 | clab-arista-ceos-spine01 | e10fbac75f81 | ceos:4.30.5M | ceos | running | 172.20.20.3/24 | 2001:172:20:20::3/64 |
+---+--------------------------+--------------+---------------------------------+-------+---------+----------------+----------------------+
