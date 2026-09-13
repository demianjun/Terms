---
layout: default
title: 外部送信について
permalink: /ja/external-transmission/
lang: ja
---

# 外部送信について

**最終改定日:** 2026年9月13日

Just 3 Days（3日だけ）は、サービス提供、認証、同期、広告、同意管理およびセキュリティのため、以下の外部サービスおよびSDKを利用します。これらの機能により、利用者の端末に関する情報が外部の事業者へ送信される場合があります。

## 外部送信先と利用目的

| サービス・SDK | 送信される情報 | 送信先 | 運営者の利用目的 | 送信先の利用目的 |
|---|---|---|---|---|
| Google Mobile Ads SDK | IPアドレス、端末・OS・アプリ情報、広告関連識別子（利用可能な場合）、広告の表示・操作・診断情報 | Google LLC | 広告配信、効果測定、不正防止、障害対応 | 広告の提供・測定・最適化、不正行為の防止、サービス改善 |
| User Messaging Platform | 同意状態、地域および端末・アプリ情報 | Google LLC | 広告に関する同意およびプライバシー選択肢の管理 | 同意状態の保存・適用および広告処理の制御 |
| Google Sign-In | Googleアカウント識別子、メールアドレス、氏名、プロフィール画像URL、認証トークン | Google LLC | ログイン、本人確認およびアカウント連携 | 認証処理、セキュリティおよびサービス提供 |
| Firebase Authentication | Firebase UID、認証プロバイダ、認証トークン、端末・アプリ情報 | Google LLC | 認証およびアカウント管理 | 認証、セキュリティ、不正防止およびサービス提供 |
| Cloud Firestore | 同期対象の目標・記録・再開情報、広告削除状態および購入日、更新・削除情報 | Google LLC | 複数端末間の同期およびデータ復元 | クラウドデータベースの提供、保守、セキュリティおよび障害対応 |
| Firebase App Check | アプリ・端末の正当性を検証するトークン、アプリ・端末の技術情報 | Google LLC | 不正なサーバーアクセスの防止 | アプリ検証、不正防止、セキュリティおよびサービス提供 |
| Appleでサインイン | Appleユーザー識別子、メールアドレス、認証情報 | Apple Inc. | ログイン、本人確認およびアカウント連携 | 認証、セキュリティおよびAppleサービスの提供 |
| StoreKit・App Store | 商品識別子、取引識別子、購入日、利用権限および端末・アプリ情報 | Apple Inc. | 広告削除購入の検証、提供および復元 | 決済、取引管理、不正防止およびAppleサービスの提供 |

## 確認・停止方法

- Google AdMobのプライバシー選択肢は、利用可能な場合にアプリ内の「広告プライバシー設定」から変更できます。
- iOSのプライバシーおよび広告関連設定は、端末の「設定」から変更できます。
- Apple・GoogleログインおよびCloud Firestoreへの同期を希望しない場合は、アカウントに接続せず端末内だけで本サービスを利用できます。
- 接続済みアカウントはアプリ内でログアウトまたは削除できます。ログアウトは同期を停止しますが、サーバーデータを削除しません。サーバーデータを削除する場合は、アカウント削除を行ってください。
- Firebase App Check等、セキュリティや機能提供に不可欠な送信を停止した場合、関連機能を利用できないことがあります。

詳細は、各提供者の説明をご確認ください。

- [Googleプライバシーポリシー](https://policies.google.com/privacy?hl=ja)
- [Googleサービスを使用するサイトやアプリから収集した情報の利用](https://policies.google.com/technologies/partner-sites?hl=ja)
- [Googleの広告・データ利用に関する説明](https://business.safety.google/intl/ja/privacy/)
- [Appleプライバシーポリシー](https://www.apple.com/jp/legal/privacy/)

## お問い合わせ

- **運営者:** DreamAppLab
- **Email:** [demianjun1@gmail.com](mailto:demianjun1@gmail.com)
