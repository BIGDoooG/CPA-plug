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

当前正式版本：`0.4.1`，平台：`linux/amd64`。

`0.4.1` 修复 CPA Manager Plus 延迟注入宿主样式后，顶部菜单变成圆角
按钮并发生布局跳变的问题。导航保持上下两层结构，其他工作台功能继承
`0.4.0`：账号并发、冷却控制、错误规则、数据分析和持久化诊断。

旧版 `codex-quota-scheduler` 与正式版使用不同的插件 ID。安装正式版前，
请先停用旧版，避免两个调度器同时运行。
