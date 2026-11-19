# 订阅格式说明 / Subscription formats

## 中文

| 文件 | 说明 | 适用 |
| --- | --- | --- |
| `subs/base64.txt` | 通用订阅（base64） | v2rayN、v2rayNG、Hiddify、Shadowrocket |
| `subs/all.yaml` | Clash 格式，仅节点，无分流规则 | Clash / mihomo 系，适合自己写规则的人 |
| `subs/mihomo.yaml` | 带分流规则的完整配置 | Clash Verge Rev、FlClash |
| `subs/<地区>.yaml` | 只含某个出口地区的节点：`us` `jp` `sg` `hk` `tw` `other` | 只想用某个地区时 |
| `subs/<解锁>.yaml` | 只含检测到可解锁某服务的节点：`netflix` `chatgpt` `disney-plus` `youtube` `gemini` | 有特定需求时 |
| `subs/singbox.json` | sing-box 格式（如果已启用） | sing-box 客户端 |

说明：
- 所有节点名都带有 `crazygeeky |` 前缀，方便你在客户端里区分。
- 拆分文件**只有存活节点不少于 5 个时才会生成**，数量不足的文件会被自动删除。
- “可解锁”是我们的海外检测结果，仅供参考，不保证你实际使用时一致。
- 每个拆分文件在网站上都有对应的统计页，见根目录 README 的统计表。
- 更新时间约每 6 小时一次，实时数据见 [https://crazygeeky.com/nodes/](https://crazygeeky.com/nodes/)。

## English

| File | Description | For |
| --- | --- | --- |
| `subs/base64.txt` | Universal subscription (base64) | v2rayN, v2rayNG, Hiddify, Shadowrocket |
| `subs/all.yaml` | Clash format, nodes only, no routing rules | Clash/mihomo users who write their own rules |
| `subs/mihomo.yaml` | Full config with routing rules | Clash Verge Rev, FlClash |
| `subs/<region>.yaml` | Nodes exiting in one region: `us` `jp` `sg` `hk` `tw` `other` | When you only want one region |
| `subs/<unlock>.yaml` | Nodes detected as able to reach a service: `netflix` `chatgpt` `disney-plus` `youtube` `gemini` | Specific needs |
| `subs/singbox.json` | sing-box format (if enabled) | sing-box clients |

Notes:
- Every node name carries a `crazygeeky |` prefix so you can tell them apart in your client.
- A split file is **only generated when at least 5 nodes are alive**; files that fall below that are removed automatically.
- "Unlock" results come from our overseas checks. They are for reference only and are not guaranteed to match your own experience.
- Each split file has a matching stats page on the website; see the table in the root README.
- Updated roughly every 6 hours. Live data: [https://crazygeeky.com/nodes/](https://crazygeeky.com/nodes/).
