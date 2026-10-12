# 部署说明

本仓库是 [AEtherside/skland-daily-attendance](https://github.com/AEtherside/skland-daily-attendance) 的 fork，用于通过 GitHub Actions 执行森空岛每日自动签到。

## 配置

- Secret `SKLAND_TOKENS`：森空岛凭据（在仓库 Settings → Secrets and variables → Actions 中配置）
- 定时执行：每天 21:00 (UTC)，即北京时间 05:00
- 手动触发：Actions → attendance → Run workflow

## 同步上游

在 fork 页面点击 Sync fork 即可获取上游更新；本地未修改工作流文件，同步不会冲突。
