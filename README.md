# 🚀 CF-vpn 订阅转换

> ✨ 本项目托管于 GitHub，利用 GitHub Actions 每小时自动更新订阅配置文件，提供多种主流代理工具的订阅链接。

## 📦 订阅链接列表

以下是自动生成的订阅文件，可直接复制链接导入对应的软件中。

> 💡 **推荐使用 CDN 链接**：访问速度更快、更稳定，国内用户建议优先选择。

| 客户端类型                                                                                                                      | 文件名               | Raw 原始链接 | CDN 加速链接 |
| :------------------------------------------------------------------------------------------------------------------------- | :---------------- | :------- | :------- |
| **Base64 (通用)**                                                                                                            | `cf-b64.txt`      |          |          |
| <button onclick="copyText('https://raw.githubusercontent.com/xxsa520/CF-vpn/refs/heads/main/cf-b64.txt')">复制</button>      |                   |          |          |
| <button onclick="copyText('https://cdn.jsdelivr.net/gh/xxsa520/CF-vpn@main/cf-b64.txt')">复制</button>                       |                   |          |          |
| **Clash / Stash**                                                                                                          | `clash-stash.txt` |          |          |
| <button onclick="copyText('https://raw.githubusercontent.com/xxsa520/CF-vpn/refs/heads/main/clash-stash.txt')">复制</button> |                   |          |          |
| <button onclick="copyText('https://cdn.jsdelivr.net/gh/xxsa520/CF-vpn@main/clash-stash.txt')">复制</button>                  |                   |          |          |
| **Surge**                                                                                                                  | `surge.txt`       |          |          |
| <button onclick="copyText('https://raw.githubusercontent.com/xxsa520/CF-vpn/refs/heads/main/surge.txt')">复制</button>       |                   |          |          |
| <button onclick="copyText('https://cdn.jsdelivr.net/gh/xxsa520/CF-vpn@main/surge.txt')">复制</button>                        |                   |          |          |
| **Sing-box**                                                                                                               | `singbox.txt`     |          |          |
| <button onclick="copyText('https://raw.githubusercontent.com/xxsa520/CF-vpn/refs/heads/main/singbox.txt')">复制</button>     |                   |          |          |
| <button onclick="copyText('https://cdn.jsdelivr.net/gh/xxsa520/CF-vpn@main/singbox.txt')">复制</button>                      |                   |          |          |
| **Loon**                                                                                                                   | `loon.txt`        |          |          |
| <button onclick="copyText('https://raw.githubusercontent.com/xxsa520/CF-vpn/refs/heads/main/loon.txt')">复制</button>        |                   |          |          |
| <button onclick="copyText('https://cdn.jsdelivr.net/gh/xxsa520/CF-vpn@main/loon.txt')">复制</button>                         |                   |          |          |

---

## 📝 使用说明

1. 点击 **复制按钮**，复制对应订阅链接。
2. 打开你的代理客户端（如 Clash、Surge、Loon、Sing-box 等）。
3. 进入订阅管理页面，粘贴链接并更新配置即可。

> ⚠️ 如果 CDN 链接无法访问，请尝试 Raw 原始链接。

---

## ⚙️ 自动更新

本仓库通过 GitHub Actions 设置定时任务：

* ⏰ 每小时自动拉取最新配置
* 🔄 自动生成订阅文件
* 🚀 无需手动维护

---

## 📋 复制按钮代码

将以下代码放在页面底部即可启用复制功能：

```html
<script>
function copyText(text) {
    navigator.clipboard.writeText(text).then(() => {
        alert("复制成功！");
    }).catch(() => {
        alert("复制失败，请手动复制！");
    });
}
</script>
```

---

## 📄 许可证

MIT License

---

<div align="center">

**如果觉得有用，请给个 ⭐️ Star 支持一下！**

Made with ❤️ by xxsa520

</div>
