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

当前正式版本：`0.5.5`，平台：`linux/amd64`。

`0.5.5` 新增 Claude 独立运行账号池，支持候选扫描、并发租约、模型冷却和管理页状态展示，同时保留 Codex 额度刷新隔离；
Codex 与 Claude 均可使用独立的并发租约、错误分类和凭证+模型冷却。
Claude 不会被送入 Codex OAuth 额度刷新或 Codex 主动探测链路。

`0.4.4` 修复 CPA 宿主样式导致的品牌图标字色异常，移除页面顶部黄色提示条，
并统一调大工作台、菜单、表格和说明文字。`0.4.3` 为错误规则分类按钮增加独立语义样式，彻底隔离默认主按钮的
高优先级背景覆盖。`0.4.2` 修复错误规则分类按钮被统一染成蓝色，以及页面标题区被宿主
`panel/card` 样式强制显示白色背景的问题。`0.4.1` 修复 CPA Manager Plus
延迟注入宿主样式后，顶部菜单变成圆角
按钮并发生布局跳变的问题。导航保持上下两层结构，其他工作台功能继承
`0.4.0`：账号并发、冷却控制、错误规则、数据分析和持久化诊断。

旧版 `codex-quota-scheduler` 与正式版使用不同的插件 ID。安装正式版前，
请先停用旧版，避免两个调度器同时运行。
