README.md

Loon Rules

适用于 Loon 的远程规则集仓库。

订阅地址

Reject

广告拦截、隐私追踪及无用请求拦截规则

https://github.com/Jovanykoch/Loon/releases/latest/download/Reject.list

OpenAI

OpenAI / ChatGPT 服务规则

https://github.com/Jovanykoch/Loon/releases/latest/download/OpenAi.list

Microsoft

Microsoft 服务规则

https://github.com/Jovanykoch/Loon/releases/latest/download/Microsoft.list

Google

Google 服务规则

https://github.com/Jovanykoch/Loon/releases/latest/download/Google.list

Edu

教育网络相关规则

https://github.com/Jovanykoch/Loon/releases/latest/download/Edu.list

CN

中国大陆直连规则

https://github.com/Jovanykoch/Loon/releases/latest/download/CN.list

Lan

局域网规则

https://github.com/Jovanykoch/Loon/releases/latest/download/Lan.list

ByteDance

字节跳动相关服务规则

https://github.com/Jovanykoch/Loon/releases/latest/download/ByteDance.list

Proxy

代理兜底规则

https://github.com/Jovanykoch/Loon/releases/latest/download/Proxy.list

⸻

Loon 导入

进入：

配置 → 远程规则 → 添加

填入对应规则地址即可。

⸻

目录结构

rules
├── Reject.list
├── OpenAi.list
├── Microsoft.list
├── Google.list
├── Edu.list
├── CN.list
├── Lan.list
├── ByteDance.list
└── Proxy.list

⸻

自动更新

仓库使用 GitHub Actions 自动发布 Release。

每次更新规则后：

git add .
git commit -m "update rules"
git push

即可自动生成新的 Release。

⸻

License

MIT
