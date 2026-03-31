# A股评分看板

基于技术指标的A股评分系统，支持趋势图、历史快照、富途分组视图。

## 在线访问

打开: **https://[username].github.io/[repo]/dashboard.html**

（替换 `[username]` 和 `[repo]` 为你的 GitHub 用户名和仓库名）

## 本地运行

```bash
python3 run_scan.py    # 更新数据
```

## 数据说明

- 评分基于 RSI、MACD、均线、成交量等多维度技术指标
- 趋势图展示近30个交易日评分变化
- 数据每日收盘后自动更新
