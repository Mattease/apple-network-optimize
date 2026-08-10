# 🍎 Apple Network Optimize

优化 Apple 系列服务的网络连接体验，改善部分区域用户在使用 iCloud、Siri、App Store 等服务时遇到的连通性问题。

## ✨ 功能

- 针对 Apple 核心服务域名进行网络路径优化
- 提升 iCloud Private Relay、Gateway 等服务的连接质量
- 改善 Siri、定位服务及 App Store 的响应速度
- 支持自定义策略与规则类型配置

## 🎈 Loon 插件

### 一键安装

👉 **[点击此处一键安装 Loon 插件](https://raw.githubusercontent.com/Mattease/apple-network-optimize/master/apple_geofence_unlock.plugin)**

或复制以下链接在 Loon 中添加：

```text
https://raw.githubusercontent.com/Mattease/apple-network-optimize/master/apple_geofence_unlock.plugin
```

安装时，Loon 会自动提示你为 `PROXY` 选择一个对应的策略组或节点。

## 📦 Surge / Shadowrocket 模块

### 一键安装

👉 **[点击此处一键导入模块](https://raw.githubusercontent.com/Mattease/apple-network-optimize/master/Apple-Geofence-Unlock.sgmodule)**

或复制以下链接在 Surge 或 Shadowrocket 中手动添加：

```text
https://raw.githubusercontent.com/Mattease/apple-network-optimize/master/Apple-Geofence-Unlock.sgmodule
```

安装后，请在 App 内调整参数：

| 参数 | 默认值 | 说明 |
|------|--------|------|
| `代理策略` | `PROXY` | 指定流量出口，填写你的策略组名称 |

> **提示**：`代理策略` 需与你配置中的策略组名称完全一致方可生效。常用值如 `PROXY`、`🇺🇸 美国节点` 等。

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
