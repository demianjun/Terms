---
layout: default
title: 隐私政策
permalink: /zh-cn/privacy-policy/
lang: zh-CN
---

# Just 3 Days 隐私政策（v1.1）

**生效日期：**2026年7月31日
**最后更新：**2026年9月13日

## 1. 个人信息处理者

DreamAppLab（以下简称“运营者”）运营 Just 3 Days（以下简称“本服务”），并依据适用的个人信息保护法律处理用户信息。

- **处理者/运营者：**DreamAppLab
- **隐私联系邮箱：**[demianjun1@gmail.com](mailto:demianjun1@gmail.com)

## 2. 处理的信息与目的

| 类别 | 信息 | 目的 |
|---|---|---|
| 本机目标与记录 | 目标名称、难度、开始日期、周期、提醒时间、每日完成记录、重新开始记录 | 目标管理、进度、统计、提醒和重新开始功能 |
| 本机设置 | 语言、主题、通知和显示设置、四位PIN、去广告状态 | 用户设置、本机锁定和购买状态显示 |
| 通过Apple登录 | Apple用户标识符、公开邮箱或隐藏邮箱中继地址 | 登录、身份验证和账号连接 |
| Google登录 | Google账号标识符、邮箱、姓名和头像URL（如提供） | 登录、身份验证和账号连接 |
| Firebase Authentication | Firebase UID、认证提供方和认证状态 | 认证和账号管理 |
| Cloud Firestore | 同步的目标、每日记录、重新开始信息、去广告状态和购买日期、更新与删除信息 | 多设备同步和恢复 |
| 应用内购买 | 商品和交易标识符、购买日期、已验证权益 | 提供、验证和恢复去广告功能 |
| 广告与同意 | IP地址、设备、系统和应用信息、可用的广告相关标识符、广告展示、互动、诊断信息和同意状态 | 广告投放与衡量、反欺诈、同意管理和故障处理 |
| Firebase App Check | 应用验证令牌和应用、设备技术信息 | 防止未经授权的服务器访问 |

未连接账号时，目标和记录通常只保存在本机，不会同步到 Cloud Firestore。本服务不直接收集银行卡号等付款信息或 Face ID 面部数据。Face ID 由 iOS 验证，本服务只接收验证结果。

## 3. 处理方式与依据

用户创建目标、记录进度、更改设置、登录、购买或选择同意选项时会输入或生成信息；应用及所含SDK运行时可能自动传输技术信息。

本服务基于用户请求提供核心功能、账号同步和购买功能；在需要时基于同意处理可选广告；为保障安全、反欺诈和排障处理必要信息；并履行适用的法律义务。拒绝可选账号连接或通知会限制同步或提醒，但不影响本机目标管理。

## 4. 使用目的

- 提供目标、记录、进度、统计、日常提醒，以及连续七天未实践后的一次重新开始提醒
- 提供Apple/Google登录、账号管理和多设备同步
- 验证、提供和恢复去广告购买
- 投放和衡量Google AdMob广告并防止欺诈
- 管理广告同意和隐私选择
- 维护安全、稳定和质量并处理咨询

## 5. 广告与跟踪

本服务可使用 Google Mobile Ads SDK 展示广告，并通过 Google User Messaging Platform 在适用地区取得同意和提供隐私选项。当前版本不请求 App Tracking Transparency 权限，也不使用 IDFA 进行跨应用跟踪。根据同意、地区和设备设置，可能展示非个性化或受限广告。

## 6. 外部服务

| 提供方 | 服务 | 目的 |
|---|---|---|
| Google LLC | Google登录、Firebase Authentication | 登录、认证和账号管理 |
| Google LLC | Cloud Firestore | 云端存储和多设备同步 |
| Google LLC | Firebase App Check | 防止未经授权的访问 |
| Google LLC | Google AdMob、User Messaging Platform | 广告、衡量、反欺诈和同意管理 |
| Apple Inc. | 通过Apple登录、App Store、StoreKit | 登录、支付、权益验证和购买恢复 |

除法律允许的情况外，运营者不会出售个人信息或超出上述目的使用信息。运营者会审查服务提供方的合同及公开保护措施，要求其按照本政策和适用法律保护信息。

## 7. 存储与跨境处理

同步的 Cloud Firestore 数据存储在 Google Cloud 首尔区域（`asia-northeast3`）的命名数据库 `just3db`。Firebase Authentication、App Check、Google登录、AdMob、User Messaging Platform、通过Apple登录和 App Store 可能在 Google 或 Apple 运营服务的其他国家或地区处理信息。信息通过加密连接传输。

- [Google隐私权政策](https://policies.google.com/privacy?hl=zh-CN)
- [Google如何使用采用其服务的应用所提供的信息](https://policies.google.com/technologies/partner-sites?hl=zh-CN)
- [Apple隐私政策](https://www.apple.com.cn/legal/privacy/)

## 8. 保存与删除

| 存储位置/信息 | 保存与删除方式 |
|---|---|
| 本机目标和记录 | 直至用户删除相关数据或应用数据 |
| UserDefaults设置 | 直至用户删除设置或应用数据 |
| Keychain中的PIN和会话信息 | 直至关闭功能、明确删除或由iOS清除；部分信息可能在重新安装后保留 |
| Firebase Authentication和Cloud Firestore | 直至注销账号；此后除法律要求保留外及时删除 |
| App Store购买和交易记录 | 按Apple政策和适用法律保存 |
| 广告和诊断信息 | 按Google政策和适用法律保存 |

在应用内注销账号会删除 Firebase Authentication 账号及其 Cloud Firestore 数据。退出登录不会删除服务器数据。注销账号不会自动删除本机目标和记录，App Store购买记录由Apple管理。

## 9. 用户权利与选择

用户可依据适用法律请求查阅、复制、更正、补充、删除、限制或拒绝处理，撤回同意，并要求停止向第三方提供信息。

- 在“账号管理”中注销账号。
- 在应用内相应页面删除目标和记录。
- 在iOS“设置”中更改通知权限。
- 在可用时通过“广告隐私设置”更改广告选择。
- 其他请求请将注册邮箱和所需操作发送至 [demianjun1@gmail.com](mailto:demianjun1@gmail.com)。

运营者可在答复前进行必要的身份验证，并按照适用法律处理请求。

## 10. 安全、未成年人和变更

我们采用TLS、Firebase Authentication、按用户限制的 Firestore Security Rules、Firebase App Check、Keychain、最小权限和安全更新。本服务不会在缺少父母或监护人必要同意的情况下故意为未成年人创建连接账号。重大变更将在生效前通过应用、本页面或其他适当方式通知。

## 11. 联系方式

- **运营者：**DreamAppLab
- **邮箱：**[demianjun1@gmail.com](mailto:demianjun1@gmail.com)
