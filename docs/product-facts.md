# 句刻网站产品事实

## 发布状态

- App Store 中文名称：`句刻 - 每日名言`
- App Store 英文名称：`Daily Quote: 句刻`
- 主屏幕显示名称：`句刻`
- App Store ID：`6801580173`
- Bundle ID：`team.MicroSpotlight.DailyQuote`
- 本文发布基线：iOS 1.0
- V1.0 发布状态：已在 App Store 公开上架（用户确认；发布核验时 Apple 美区公开查询返回版本 `1.0`）
- 正式下载：[App Store 美区](https://apps.apple.com/us/app/daily-quote-%E5%8F%A5%E5%88%BB/id6801580173?uo=4)
- 系统要求：iOS 17.0 或更高版本
- V1.0 地区核验：美区公开查询返回该 App；中国区公开查询未返回结果。地区可用性以商店实时结果为准，不能据此宣称所有地区可下载。
- 正式网站：<https://dailyquote.microspotlight.team>

中英文首页、支持页与分享回退页均提供 Apple 公开查询返回的下载链接；下载可用性以用户 Apple 账户所在地区为准。此处记录已发布的 1.0，不将主仓后续开发功能自动视为已发布能力。

V1.1（Build 51）已提交 App Store 审核，提交后核对状态为 `WAITING_FOR_REVIEW`，审核通过后自动发布；尚未视为公开上架。中英文首页和隐私政策已更新 RevenueCat 必需订阅服务、默认关闭的 Firebase 分析与崩溃诊断披露，ASC 隐私标签已同步发布。

V1.0 核验依据：Apple Lookup `https://itunes.apple.com/lookup?id=6801580173&country=us` 返回 `resultCount = 1`、`version = 1.0`、`minimumOsVersion = 17.0` 和上述 `trackViewUrl`；中国区查询返回 `resultCount = 0`。下载链接采用公开查询返回值，未将网页重定向的 HTTP 200 单独当作详情页验证通过。

## V1.0 产品能力

- 中英双语每日语录、出处、项目译文与策展元数据。
- 按兴趣、主题、心情和形式浏览与筛选。
- 收藏、手记、阅读历史、提醒、个人印记与分享卡片。
- Plus 包含高级分享样式、专题阅读、AI 深度解读、小组件、年度回顾、离线朗读与可选的 iCloud 私有同步。
- 默认无需账号；兴趣、收藏、手记、阅读历史和个人偏好默认保存在本机。
- AI 深度解读、内容更新、订阅核验和用户主动提交的内容反馈会按隐私政策描述使用网络。

## 权威来源

- App Store Connect：<https://appstoreconnect.apple.com/apps/6801580173>
- App Store 元数据：App Store Connect 中对应版本的中英文元数据
- App 行为与本地化：主仓 `ios/`
- Plus 当前实现：主仓 `docs/product/Plus订阅实现说明.md`
- 隐私实践：本仓 `privacy.html` 与主仓 `ios/DailyQuote/Supporting Files/PrivacyInfo.xcprivacy`、`docs/app-store/privacy-labels.md`

这些来源发生冲突时，以 App Store Connect 和公开商店的发布状态、已发布构建的数据行为及对应审核材料为准。
