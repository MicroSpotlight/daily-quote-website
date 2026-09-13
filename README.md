# 句刻 - 每日名言 Website

句刻（Daily Quote）的公开产品、隐私政策与支持网站。

首页内容与当前 App 保持一致，介绍个性化推荐、此刻心情、双语文集、收藏、分享卡片、阅读设置、每日提醒与本地隐私。

## 页面

- `index.html`：产品首页
- `en/index.html`：英文产品首页
- `privacy.html`：App Store 隐私政策 URL
- `en/privacy.html`：英文隐私政策
- `support.html`：App Store 支持 URL
- `en/support.html`：英文支持页面
- `404.html`：Universal Link 在未安装 App 时的分享/今日路由回退页
- `sitemap.xml`：中英文公开页面索引
- `.github/ISSUE_TEMPLATE/`：问题反馈、功能建议与内容勘误模板
- `.well-known/apple-app-site-association`：把 `/quote/*`、`/q/*` 和 `/today` Universal Link 路由到句刻 App

线上地址：<https://dailyquote.microspotlight.team>

iOS 1.0 已在 App Store 上架：[下载句刻](https://apps.apple.com/us/app/daily-quote-%E5%8F%A5%E5%88%BB/id6801580173?uo=4)。需要 iOS 17.0 或更高版本，下载可用性以 Apple 账户所在地区为准。

网站是无构建步骤的静态 HTML/CSS，可直接由 GitHub Pages 托管。

发布事实与品牌基线分别记录在 `docs/product-facts.md` 和 `docs/brand-spec.md`。Apple 审核状态变化后，应先更新产品事实，再调整首页状态或下载入口。
