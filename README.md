## Shadowrocket 脚本收集

本仓库收集 Shadowrocket（iOS 端代理工具）相关的模块（.sgmodule）、配置文件与脚本，方便集中管理与复用。

### 目录结构

| 目录 | 说明 |
|---|---|
| `modules/` | Shadowrocket 模块（.sgmodule） |

### 模块索引

| 模块 | 说明 | 出处 | 上游更新 | 添加日期 |
|---|---|---|---|---|
| `modules/Advertising.sgmodule` | 去广告复写规则（规则自动生成，源仓库 MASTER 分支每日更新） | [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script/tree/master/rewrite/Shadowrocket/Advertising) | 2025-12-22 | 2026-10-08 |
| `modules/GetCookie.sgmodule` | Cookie 获取辅助模块 | [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script/tree/master/rewrite/Shadowrocket/GetCookie) | 2025-07-12 | 2026-10-08 |

> 转载说明：以上模块均转载自原作者仓库，已注明出处；模块内容以原仓库最新版为准，本仓库仅做收集整理。2026-10-17 已与上游核对：两个模块与上游 master 分支字节一致，均为上游最新版本。

### 使用说明

1. 在上方「模块索引」中找到需要的模块，点击进入文件后点右上角「Raw」，复制原始链接（格式：`https://raw.githubusercontent.com/xwOzzz/Shadowrocket-Script/main/modules/模块名.sgmodule`）；
2. 打开 Shadowrocket，依次进入「配置」→「模块」，点击右上角「+」粘贴链接下载；
3. 按提示开启模块；需要抓包的模块请先确认已安装并信任证书。

### 特别感谢

* [@NobyDa](https://github.com/NobyDa)
* [@chavyleung](https://github.com/chavyleung)
* [@lxk0301](https://github.com/lxk0301)
