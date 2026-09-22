# JinWloc

个人 WLOC 模块仓库（仅保留 4 个 MITM 主机名）

## MITM 主机名

```
gs-loc.apple.com
gs-loc-cn.apple.com
bluedot.is.autonavi.com
bluedot.is.autonavi.com.gds.alibabadns.com
```

## 订阅地址

| 客户端 | 订阅地址 |
| --- | --- |
| Shadowrocket | https://raw.githubusercontent.com/SalvationJin/JinWloc/refs/heads/main/modules/wloc.module |
| Surge / Egern | https://raw.githubusercontent.com/SalvationJin/JinWloc/refs/heads/main/modules/wloc.sgmodule |
| Quantumult X | https://raw.githubusercontent.com/SalvationJin/JinWloc/refs/heads/main/modules/wloc.conf |
| Loon | https://raw.githubusercontent.com/SalvationJin/JinWloc/refs/heads/main/modules/wloc.lpx |
| Stash | https://raw.githubusercontent.com/SalvationJin/JinWloc/refs/heads/main/modules/wloc.stoverride |

## 快捷指令

| 用途 | 链接 |
| --- | --- |
| 设置位置 | https://www.icloud.com/shortcuts/825cf916624d421ea5cf9108dd26a8d8 |
| 恢复位置 | https://www.icloud.com/shortcuts/18fe8a25ca9f4800a0bf450da5f36d15 |

## 说明

- 只包含模块定义
- 脚本从 `SalvationJin/wloc` 的 dist 加载（同为你的公开仓库）
- MITM 已按要求只保留上面 4 个域名
- 快捷指令精度已设为 `acc=10`，与模块一致
