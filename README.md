# 🚀 JustRunMy 自动续期（GitHub Actions）
修改自 https://github.com/losy-mify/JustRunMy-Renew

这是一个基于 GitHub Actions 的自动化脚本，用于定时登录并自动续期 JustRunMy 应用。

━━━━━━━━━━━━━━━━━━━━━━

🔐 Secrets 配置说明

| Secret 名称         | 是否必填 | 说明                                              |
|---------------------|----------|---------------------------------------------------|
| JUSTRUNMY_EMAIL     | ✅ 必填  | JustRunMy 登录邮箱                                |
| JUSTRUNMY_PASSWORD  | ✅ 必填  | JustRunMy 登录密码                                |
| GOST_PROXY_TARGET   | ❌ 可选  | Gost 代理完整地址（需包含协议，如 socks5://）     |
| TG_BOT_TOKEN        | ❌ 可选  | Telegram Bot Token（用于发送通知）                |
| TG_CHAT_ID          | ❌ 可选  | Telegram Chat ID（接收通知的用户或群组 ID）        |

━━━━━━━━━━━━━━━━━━━━━━

📌 示例填写格式（复制下面内容，分开添加）：

JUSTRUNMY_EMAIL=abc@abc.com  
JUSTRUNMY_PASSWORD=abc123  
GOST_PROXY_TARGET=socks5://user:pass@123.456.789:1234  
TG_BOT_TOKEN=123456789:ABCdefGhIJKlmNoPQRstuVWXyz  
TG_CHAT_ID=123456789  

━━━━━━━━━━━━━━━━━━━━━━
