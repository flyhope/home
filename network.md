# 网络图

```mermaid
graph TD;

M[光猫] -->|墙线客厅| IPTV(IPTV)
M --> R[有线路由]

R --> AP[无线AP]
R -->|墙线客厅| TV(电视)
R -->|墙线书房| PC(电脑)
R --> NAS[NAS]
```
