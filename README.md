# CPA Codex Plugin Store

CPA `codex-scheduler`（Codex 调度器）插件的公共安装源。

## 插件源地址

```text
https://raw.githubusercontent.com/BIGDoooG/CPA-plug/main/registry.json
```

CPA 配置示例：

```yaml
plugins:
  enabled: true
  store-sources:
    - "https://raw.githubusercontent.com/BIGDoooG/CPA-plug/main/registry.json"
```

当前正式版本：`0.4.0`，平台：`linux/amd64`。

`0.4.0` 增加新的 CPA 风格管理工作台、账号并发与冷却完整控制、
详情抽屉、轻量分析、未保存保护以及新数据目录持久化诊断。

旧版 `codex-quota-scheduler` 与正式版使用不同的插件 ID。安装正式版前，
请先停用旧版，避免两个调度器同时运行。
