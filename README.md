# 业务地址清单

NAS 发布每个项目的最新清单，并把相同内容同步到本仓库。客户端可访问 NAS HTTPS 或 GitHub Raw。

| 项目 | NAS 路径 | GitHub 文件 |
| --- | --- | --- |
| 神仙云 | [/v1/shenxianyun.json](https://domains.52nm.de:5443/v1/shenxianyun.json) | [shenxianyun.json](manifests/shenxianyun.json) |
| 神仙面板 Agent | [/v1/shenxian-panel.json](https://domains.52nm.de:5443/v1/shenxian-panel.json) | [shenxian-panel.json](manifests/shenxian-panel.json) |
| 神仙面板网页 | [/go/shenxian-panel-web/web](https://domains.52nm.de:5443/go/shenxian-panel-web/web) | [shenxian-panel-web.json](manifests/shenxian-panel-web.json) |
| Shell 管理平台 | [/go/shell/workbench](https://domains.52nm.de:5443/go/shell/workbench) | [shell.json](manifests/shell.json) |
| 吾爱云 | [/v1/wuaiyun.json](https://domains.52nm.de:5443/v1/wuaiyun.json) | [wuaiyun.json](manifests/wuaiyun.json) |

Shell 脚本目录另有[固定入口](https://domains.52nm.de:5443/go/shell/web)。已部署的神仙云和吾爱云客户端继续使用各自现有的发现入口。启用神仙面板 Agent 双源时，需配置本表 NAS gRPC 清单以及本仓库对应的 Raw URL。
