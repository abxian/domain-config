# 业务地址清单

这是域名分发的 GitHub 公共镜像。客户端可通过 Raw HTTPS 读取清单。

- 神仙云使用 `manifests/shenxianyun.json`。
- Shell 管理平台使用 `manifests/shell.json`。
- 神仙面板使用 `manifests/shenxian-panel.json`，上线入口确认后发布。

每个项目有独立的修订号。正式更新由域名分发管理端发布，两个入口提供同一份 JSON。仓库内容仅包含公开的服务入口。
