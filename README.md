
# 小账本 Pro

A modern personal finance tracker for iPhone and iPad.

小账本 Pro 是一款简洁、现代化的个人财务管理应用，旨在帮助用户轻松记录日常收支、管理预算，并通过可视化图表了解个人财务状况。

本项目基于 Progressive Web App（PWA）技术开发，无需通过 App Store 安装，可直接添加到 iPhone 和 iPad 主屏幕。

## Features

- **Income & Expenses** — 记录日常收入与支出
- **Financial Analytics** — 收支统计与分类分析
- **Budget Management** — 设置并追踪每月预算
- **Monthly Trends** — 查看最近六个月的收支趋势
- **Transaction History** — 搜索、编辑和管理历史账单
- **Local Storage** — 在设备本地保存数据
- **Data Export** — 支持 JSON 数据备份和 CSV 导出
- **Responsive Design** — 适配 iPhone、iPad 和桌面设备
- **Dark Mode** — 现代化深色界面
- **Offline Support** — 支持离线访问和记账

## Getting Started

### Online Access

访问以下地址：

https://orange0414.github.io/xiaozhangben-pro/

网站需要先完成 GitHub Pages 部署。

### Installation

在 iPhone 或 iPad 上：

1. 使用 Safari 打开应用网址。
2. 点击分享按钮。
3. 选择「添加到主屏幕」。
4. 选择「作为网页 App 打开」（如有此选项）。
5. 点击「添加」。

安装完成后，即可通过主屏幕图标启动应用。

## Technology Stack

- HTML5
- CSS3
- JavaScript
- Progressive Web App (PWA)
- Service Worker
- Local Storage
- GitHub Pages

## Project Structure

```text
xiaozhangben-pro/
├── index.html
├── manifest.json
├── sw.js
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

## Privacy & Security

小账本 Pro 采用本地优先的数据存储方式。

- 无需注册用户账户
- 无需绑定银行账户
- 财务记录默认保存在当前设备
- 不需要服务器存储个人账单
- 支持导出数据进行备份

请注意，清除网站数据可能导致本地记录丢失。

目前不同设备之间的数据不会自动同步，建议定期导出备份。

## Deployment

本项目支持通过 GitHub Pages 免费部署。

1. Fork 或下载本仓库。
2. 将项目文件上传至 GitHub。
3. 进入仓库 Settings → Pages。
4. 在 Build and deployment 中选择 Deploy from a branch。
5. 选择 `main` 分支和 `/ (root)` 目录。
6. 保存设置并等待部署完成。

## Future Improvements

- [ ] iCloud / Cross-device Sync
- [ ] Face ID / Touch ID Authentication
- [ ] Multiple Accounts
- [ ] Custom Transaction Categories
- [ ] Recurring Transactions
- [ ] Advanced Financial Analytics
- [ ] Multi-currency Support
- [ ] Home Screen Widgets

## License

This project is intended for personal use.

All rights reserved.

## Author

Developed by orange0414.

---

小账本 Pro — Simple, private and efficient personal finance management.
