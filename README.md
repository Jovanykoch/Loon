<div align="center">

# 🚀 Loon Rules

Optimized rule sets for **Loon**.

Lightweight • Fast • Continuously Updated

[![Stars](https://img.shields.io/github/stars/Jovanykoch/Loon?style=flat-square)](https://github.com/Jovanykoch/Loon/stargazers)
[![License](https://img.shields.io/github/license/Jovanykoch/Loon?style=flat-square)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/Jovanykoch/Loon?style=flat-square)](https://github.com/Jovanykoch/Loon/commits/main)

</div>

---

## 📖 Overview

This repository provides curated rule sets for **Loon**, helping you manage traffic routing, service-specific policies, and ad blocking with minimal configuration.

---

## 📦 Rule Sets

| Rule | Description |
|--------|-------------|
| Reject | Ads, trackers, analytics, and unwanted requests |
| OpenAI | OpenAI, ChatGPT, and related services |
| Microsoft | Microsoft services and infrastructure |
| Google | Google products and services |
| Edu | Educational networks and platforms |
| CN | Mainland China direct routing |
| Lan | Local network traffic |
| ByteDance | ByteDance services |
| Proxy | Final proxy fallback rules |

---

## 📡 Subscription

### Base URL

```text
https://raw.githubusercontent.com/Jovanykoch/Loon/main/rules/
```

### Available Rules

| Rule | Subscription Path |
|--------|------------------|
| Reject | `Reject.list` |
| OpenAI | `OpenAI.list` |
| Microsoft | `Microsoft.list` |
| Google | `Google.list` |
| Edu | `Edu.list` |
| CN | `CN.list` |
| Lan | `LAN.list` |
| ByteDance | `ByteDance.list` |
| Proxy | `Proxy.list` |

### Example

```text
https://raw.githubusercontent.com/Jovanykoch/Loon/main/rules/OpenAI.list
```

---

## 🚀 Usage

In Loon:

```text
Configuration
 └─ Remote Rules
     └─ Add Rule
```

Paste the desired subscription URL and save.

---

## 🔄 Updates

All rule sets are maintained directly in this repository.

Subscription URLs remain unchanged, allowing clients to receive updates automatically without reconfiguration.

---

## 📁 Structure

```text
rules/
├── Reject.list
├── OpenAI.list
├── Microsoft.list
├── Google.list
├── Edu.list
├── CN.list
├── Lan.list
├── ByteDance.list
└── Proxy.list
```

---

## 🤝 Contributing

Issues and pull requests are welcome.

If this project helps you, consider giving it a ⭐.

---

## 📄 License

MIT License