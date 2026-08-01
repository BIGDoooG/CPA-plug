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

当前正式版本：`0.3.0`，平台：`linux/amd64`。

旧版 `codex-quota-scheduler` 与正式版使用不同的插件 ID。安装正式版前，
请先停用旧版，避免两个调度器同时运行。
