# K-ZONE
- klab(ポートフォリオ)
- kazugramming(ブログ)
- k-step（配信システム）
上記のアプリを新しくまとめてリニューアル。

## klab(ポートフォリオ)
ポートフォリオをまとめたアプリです。
個人で作成したアプリやブログをまとめています。

## kazugramming(ブログ)
プログラミング特化型のブログです。

## k-step(配信システム)
配信システムです。
LINEBOTで好きな配信を選択して、配信を受けることができます。

## Requirement
### klab・kazugramming
- FW: Laravel 5.8/Next.js
- DB: MySQL 5.7
- DEV: Docker/Docker-compose/VSCode
- CI/CD: Git hub Actions

### k-step(LINE BOT)
- FW: Ruby on Rails 6.0 || Flask
- DB: MySQL 5.7
- DEV: Docker/Docker-compose/VSCode
- CI/CD: Git hub Actions
- バッチ: AWS Lambda(python3.8)

## その他
- ドメイン: AWS Route53
- 画像: AWS S3
- サーバー:
  - EC2 ✖︎ 3(nginx + php-fpm, Next.js) 
  - ECS(LINE用 APIサーバー) ✖︎ １ 
- データベース: AWS RDS
- キャッシュ: AWS ElastiCache
- メール: AWS SES
- ログ: AWS CloudWatch
- cron: AWS CloudWatch Events
- バッチ（配信）： AWS Lambda




