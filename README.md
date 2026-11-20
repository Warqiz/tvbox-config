# Marco Movie 自维护片源配置

自动维护的 TVBox / 影视仓配置，每周更新：源池扩源 → 全量体检 → 剔除死源 → 按「点开即播」优先级排序。

- 当前片源：**40** 个点播源 + **8** 个直播源
- 最近更新：2026-11-20
- 维护方式：本机脚本每周自动体检 + 扩源，结果自动提交到本仓库

## 怎么用

在 Marco Movie / 影视仓 / TVBox / 映匣 的「设置 → 配置地址」里填下面任意一条即可，填一次长期有效：

| 类型 | 地址 | 说明 |
| --- | --- | --- |
| 主地址 | `https://raw.githubusercontent.com/Warqiz/tvbox-config/main/marco_config.json` | GitHub 官方 raw，最新 |
| 备用 1 | `https://cdn.jsdelivr.net/gh/Warqiz/tvbox-config@main/marco_config.json` | jsDelivr CDN，国内一般更快 |
| 备用 2 | `https://ghproxy.net/https://raw.githubusercontent.com/Warqiz/tvbox-config/main/marco_config.json` | 前两个不通时用 |

一条不通就换下一条，三条内容完全一样。

## 说明

- 所有接口均来自互联网公开分享，本仓库仅做聚合与整理，版权归原作者所有，仅供学习交流，请勿商用。
- 配置为 JSON 格式（`type=1`），适配 Marco Movie 等只吃 JSON 的播放器。
