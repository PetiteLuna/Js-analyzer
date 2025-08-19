# 🔍 JS-Sensitive-Scanner-Plus  
**轻量级 JavaScript 敏感信息 & 接口探测工具**

[![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Release](https://img.shields.io/github/v/release/你的用户名/js-sensitive-scanner-plus)](https://github.com/你的用户名/js-sensitive-scanner-plus/releases)

---

## 📌 功能特性
- 🔍 从单个 JS 文件或远程 URL 中提取所有 **相对/绝对路径**
- 🔐 内置正则匹配 **API Key、Token、云存储域名** 等敏感信息
- 🚀 多线程快速探测提取出的接口是否 **200 可访问**
- 📊 自动生成 **HTML 可视化报告**
- ✅ **-u / -f 二选一即可运行**，无需同时输入
- 🛡️ 支持本地文件与在线 JS 文件

---
② 安装依赖
pip install -r requirements.txt
③ 运行示例
python js_sensitive_scanner_plus.py -u https://example.com/static/js/app.js -o report.html
<img width="1808" height="943" alt="图片" src="https://github.com/user-attachments/assets/8b532873-0c75-4144-b4c4-80a621877df9" />
🛡️ 免责声明
本工具仅用于 合法授权的渗透测试与安全研究。使用者需自行承担因滥用导致的一切法律责任。
.🤝 贡献 & 反馈
欢迎提交 Issue 与 PR！

