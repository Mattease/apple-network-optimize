# 🍎 Apple Network Optimize

优化 Apple 系列服务的网络连接体验，改善部分区域用户在使用 iCloud、Siri、App Store 等服务时遇到的连通性问题。

## ✨ 功能

- 针对 Apple 核心服务域名进行网络路径优化
- 提升 iCloud Private Relay、Gateway 等服务的连接质量
- 改善 Siri、定位服务及 App Store 的响应速度
- 支持自定义策略与规则类型配置

## 📦 Shadowrocket 模块

### 一键安装

点击下方链接直接导入模块：

```
https://raw.githubusercontent.com/Mattease/apple-network-optimize/main/Apple-Geofence-Unlock.sgmodule
```

或在 Shadowrocket 中操作：**配置 → 模块 → + → 粘贴上方链接 → 下载**

### 参数说明

安装后**长按模块**即可编辑以下参数：

| 参数 | 默认值 | 说明 |
|------|--------|------|
| `POLICY` | `🍎 苹果解锁` | 指定流量出口，填写你的策略组名称 |
| `RULE_TYPE` | `DOMAIN-SUFFIX` | 匹配模式，可选 `DOMAIN` 或 `DOMAIN-SUFFIX` |

> **提示**：`POLICY` 需与你配置中的策略组名称完全一致方可生效。常用值如 `PROXY`、`🇺🇸 美国节点` 等。

## 📋 覆盖服务

- iCloud Private Relay & Mask
- Apple Relay (Apple / Cloudflare / Fastly)
- iCloud Gateway
- Siri & Siri Suggestions
- Location Services
- App Store Resources

## ⚠️ 注意事项

- 本模块仅做网络路径优化，不包含节点信息
- 需配合具有对应策略组的完整配置使用
- 建议选择延迟较低的出口以获得最佳体验

## 📄 License

MIT
