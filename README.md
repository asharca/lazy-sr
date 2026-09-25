# lazy-sr

Shadowrocket 配置，镜像自 [johnshall/Shadowrocket-ADBlock-Rules-Forever](https://github.com/johnshall/Shadowrocket-ADBlock-Rules-Forever) 的 `lazy_group.conf`（2026-09-16 版）。

- `lazy.conf`：主配置，规则集地址已全部改为指向本仓库 `rules/` 目录
- `公司隧道` 策略组：公司内网网段（192.168.10.0/23、10.0.0.0/8）走手动选定的公司节点，在 Shadowrocket 首页策略组里选一次公司节点即可
- `rules/`：34 个规则集文件的快照（上游：blackmatrix7/ios_rule_script、iab0x00/ProxyRules）

订阅地址：`https://raw.githubusercontent.com/asharca/lazy-sr/main/lazy.conf`

上游更新后如需同步，重新下载对应 `.list` 文件替换即可。
