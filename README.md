# overseas-creators-marketplace

共享市场仓库：包含「海外全网络自媒体运营团」(`overseas-creators`) 专家团。

## 仓库结构
```
.codebuddy-plugin/marketplace.json   # 市场清单
plugins/overseas-creators/           # 专家目录（plugin.json + agents/ + avatars/ + references/）
```

## 如何安装 / 添加本市场
在 WorkBuddy 对话中输入斜杠命令（将 `<repo-url>` 替换为实际仓库地址）：

```
/plugin marketplace add <repo-url>
```

添加后，`overseas-creators` 会出现在「专家中心」中，可直接使用。

## 如何更新
1. 修改 `plugins/overseas-creators/` 下内容；
2. 提交并推送到本仓库；
3. 使用方在 WorkBuddy 中刷新 / 重新添加市场即可拉取最新版。

> 提示：`.tar.gz` 导出包（路径一·文件分发）与本市场仓库（路径二·共享市场）是两种独立分发方式，发布到市场时只需提交本仓库源码，**不需要**提交 `.tar.gz`。
