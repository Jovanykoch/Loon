Loon Rules



A collection of rule sets for Loon.

Rule Sets

Rule

Description

Reject

Ad blocking, trackers and unwanted requests

OpenAi

OpenAI and ChatGPT services

Microsoft

Microsoft services

Google

Google services

Edu

Educational networks and services

CN

Mainland China direct connection

Lan

Local Area Network (LAN)

ByteDance

ByteDance services

Proxy

Final proxy fallback rules

Subscription URLs

Reject

https://github.com/Jovanykoch/Loon/releases/latest/download/Reject.list

OpenAi

https://github.com/Jovanykoch/Loon/releases/latest/download/OpenAi.list

Microsoft

https://github.com/Jovanykoch/Loon/releases/latest/download/Microsoft.list

Google

https://github.com/Jovanykoch/Loon/releases/latest/download/Google.list

Edu

https://github.com/Jovanykoch/Loon/releases/latest/download/Edu.list

CN

https://github.com/Jovanykoch/Loon/releases/latest/download/CN.list

Lan

https://github.com/Jovanykoch/Loon/releases/latest/download/Lan.list

ByteDance

https://github.com/Jovanykoch/Loon/releases/latest/download/ByteDance.list

Proxy

https://github.com/Jovanykoch/Loon/releases/latest/download/Proxy.list

Usage

Add the rule set in Loon:

Configuration
└── Remote Rules
    └── Add Rule

Paste the corresponding subscription URL.

Repository Structure

Loon
└── rules
    ├── Reject.list
    ├── OpenAi.list
    ├── Microsoft.list
    ├── Google.list
    ├── Edu.list
    ├── CN.list
    ├── Lan.list
    ├── ByteDance.list
    └── Proxy.list

Auto Release

This repository uses GitHub Actions to automatically publish a new Release whenever any rule file is updated.

After modifying rule files:

git add .
git commit -m "update rules"
git push

GitHub Actions will automatically:

Create a new Release

Upload all .list files

Update the latest Release assets

License

MIT License
