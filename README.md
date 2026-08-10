# 🍎 Apple Network Optimize (苹果解除电子围栏)

通过将 Apple 核心服务（如 Siri、定位服务、iCloud 等）的请求代理到海外节点，让苹果服务器判定设备不在中国大陆地区，从而解锁并使用海外版 Siri（Apple Intelligence）及其他受地区限制的服务。

## ✨ 功能

- **解除区域限制**：代理 Siri (`guzzoni.apple.com`) 等域名，解锁海外版 Siri 及 Apple Intelligence 等功能。
- **解锁 iCloud 隐私代理**：代理相关域名，正常开启和使用 iCloud Private Relay。
- **修改定位判定**：代理定位服务（`ls.apple.com`），配合海外节点让设备伪装在非限制区域。
- **多平台支持**：支持 Loon、Surge、Shadowrocket 等主流代理软件的一键配置。

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
