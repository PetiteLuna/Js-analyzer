# JS Analyzer

一个用于扫描和分析 JavaScript 文件中可能包含的敏感信息的小工具。  
支持关键字匹配、敏感函数检测等功能，帮助安全研究人员快速发现潜在风险点。  

---

## ✨ 功能特性
- 扫描本地或远程 JS 文件  
- 自动识别常见敏感信息（如 `key`、`token`、`password` 等）  
- 支持自定义敏感关键字  
- 终端彩色输出，结果清晰直观  

---

## 📦 安装依赖
确保已安装 Python 3.6+，然后执行：

```bash
pip install -r requirements.txt

🚀 使用方法

命令行参数说明：

python3 js_sensitive_scanner_plus.py -u <url>    # 扫描目标 URL
python3 js_sensitive_scanner_plus.py -f <file>   # 扫描本地 JS 文件

示例：

python3 js_sensitive_scanner_plus.py -u https://example.com/main.js

运行后会显示工具 LOGO 和扫描结果。

📂 项目结构
<img width="1920" height="946" alt="图片" src="https://github.com/user-attachments/assets/b9bf91a6-515d-43a9-96ff-3b06785b9e0d" />

├── js_sensitive_scanner_plus.py   # 工具主程序
├── requirements.txt               # 依赖库
└── README.md                      # 项目说明

🧑‍💻 作者

Zh0uI<e

🛡️ 免责声明
本工具仅用于 合法授权的渗透测试与安全研究。使用者需自行承担因滥用导致的一切法律责任。
.🤝 贡献 & 反馈
欢迎提交 Issue 与 PR！

