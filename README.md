# 職務経歴書

**2026年9月21日時点**

[PDF版をダウンロード](https://yutodanno.github.io/profile/profile.pdf)

---

## 職務要約

インフラエンジニアとして約8年。大学卒業後、SIer 2社で計3年4ヶ月、オンプレミス更改からクラウド分析基盤の構築までを経験した。2022年5月に独立し、以降4年5ヶ月はフリーランスとして、AWS / Google Cloud / Azure の3クラウド案件に並行参画している。

提案・要件定義から設計・構築・運用まで一貫して担当でき、IaC（Terraform / Bicep / CloudFormation）とCI/CDによる自動化、属人化した環境の整理・標準化を得意とする。近年はインフラに加え、生成AIを活用したPoCアプリの開発から本番公開・運用までを一人で完結させる案件も担当。

AWS Solutions Architect Professional / AWS DevOps Engineer Professional / Google Cloud Professional Cloud Architect 保有。

---

## 職歴サマリ

| 期間 | 所属 |
|:--|:--|
| 2022年5月〜現在（4年5ヶ月） | フリーランス |
| 2020年10月〜2022年4月（1年7ヶ月） | SIer（独立系・SES） |
| 2018年4月〜2019年12月（1年9ヶ月） | SIer（独立系・SES） |

---

## 技術スキル

| 分類 | 内容 |
|:--|:--|
| クラウド | AWS（6年） / Google Cloud（5年） / Azure（4年） ― 設計から運用まで |
| IaC・CI/CD | Terraform（Enterprise / Sentinel / tfmigrate） / Bicep / CloudFormation / GitHub Actions / Azure DevOps / Cloud Build |
| コンテナ・DB | ECS / Cloud Run / Container Apps / GKE / Docker / Aurora / PostgreSQL / Cloud SQL / Cosmos DB |
| 監視・セキュリティ | CloudWatch / Azure Monitor / Datadog / IAM設計 / WAF / OWASP ZAP / GuardDuty |
| 生成AI | Amazon Bedrock / Azure OpenAI / Dify / Claude Code / Codex |
| 言語 | Python / Shell / TypeScript / PowerShell |

---

## 職務経歴

### フリーランス｜ 2022年5月〜現在（4年5ヶ月）

マルチクラウド案件を中心に、常時2〜4案件に並行参画。IaC推進・コスト最適化・生成AI導入支援・アプリ開発まで、インフラを軸に領域を広げている。

#### サーバレス基盤の設計・構築・運用

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2026年7月〜2026年9月（3ヶ月） | インフラ担当 | 設計・構築・運用保守 |

- **業務内容** — サーバレス基盤の設計・構築・運用、IaCテンプレート管理、CI/CDパイプライン運用、マルチテナント展開を担当。

技術: `AWS Lambda(SnapStart)` `API Gateway` `Aurora MySQL` `RDS Proxy` `CloudFront` `S3` `Cognito` `DynamoDB` `WAF` `SES` `CodePipeline` `CodeBuild` `CloudFormation` `GuardDuty` `Inspector` `Parameter Store` `Java(Spring Boot)`

#### Webサービスの運用改善・コスト削減

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2026年2月〜2026年9月（8ヶ月） | インフラ担当 | 運用 |

- **業務内容** — ログ・メトリクス設計とコスト削減対応を担当。負荷の発生源を可視化したうえで構成を見直し、監視体制も整備した。

技術: `AWS ECS` `Aurora(Serverless v2)` `CloudWatch` `Cognito` `Performance Insights` `Terraform` `Metabase` `Slack` `Java(Spring Boot)`

#### マルチクラウド基盤構築・生成AI導入支援

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2025年3月〜2026年9月（1年7ヶ月） | インフラ担当 | 要件定義〜運用保守 |

- **業務内容** — 3クラウド横断の構築・運用、コスト最適化とガバナンス整備、コーポレートサイト開発、mTLSインフラ構築、閉域環境へのアプリ導入、生成AIを活用したアプリ開発を担当。

技術: `AWS ECS` `RDS` `App Runner` `Amplify` `CloudFront` `S3` `Bedrock` `IAM Identity Center` `Azure App Service` `Container Apps` `Azure OpenAI` `Load Balancer` `Google Cloud Run` `Cloud SQL` `Claude Code` `Codex` `Strapi`

#### AWS基盤の最適化・移行支援

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2025年3月〜2026年5月（1年3ヶ月） | インフラ担当 | 運用〜設計〜移行 |

- **業務内容** — パフォーマンス改善調査、VPCサブネット設計・構築、IAM整備、CI/CD導入、IaC設計・導入支援、移行計画の策定を担当。

技術: `AWS RDS` `ECS` `ELB` `VPC` `SG` `WAF` `VPN` `PrivateLink` `Terraform` `GitHub Actions`

#### データ移行支援・運用設計

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2024年12月〜2026年9月（1年10ヶ月） | メンバー（インフラ担当） | 開発・運用 |

- **業務内容** — 移行元ごとに異なるデータを自社システムへ取り込む移行ツールの作成、データ処理スクリプトによる業務効率化、カスタマーサポート部門と連携した運用改善・運用設計を担当。

技術: `AWS Aurora` `PostgreSQL` `Python` `TypeScript`

#### AIアプリ基盤・API環境構築

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2024年8月〜2025年2月（7ヶ月） | インフラ担当 | 設計・構築 |

- **業務内容** — AIアプリ基盤の構築とAPI環境の構築を担当。アプリケーション開発には関与せず、インフラ構築に専念した。

技術: `AWS CloudFormation` `Certificate Manager` `API Gateway` `WAF` `Google Cloud IAP` `GCE` `GCS` `Cloud SQL` `VPC` `IAM` `Terraform` `Dify`

#### 情報システム支援・自社サービスのインフラ／アプリ開発

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2024年4月〜2026年9月（2年6ヶ月） | メンバー（インフラ担当） | 要件定義〜運用 |

- **業務内容** — 情報システム部門の役割を担い、セキュリティ対策支援、Google Workspace移行支援、データベース移行支援、ECサイト・LPの運用、社内AI基盤の整備を担当。手作業をコード化し、変更履歴を追える状態へ移行させた。

技術: `AWS RDS` `Lightsail` `Route 53` `WorkSpaces` `Google Cloud SQL` `IAM` `Supabase` `Shopify` `WordPress` `Zoho Analytics` `Google Workspace` `GitHub Actions` `Claude Code` `MCP` `Slack` `Dart(Flutter)`

#### 新規Webサービス開発

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2024年4月〜2024年10月（7ヶ月） | アプリケーションエンジニア（全5名） | 開発 |

- **業務内容** — toC向け新規Webサービスの開発に、アプリケーションエンジニアとして参画。フロントエンド・バックエンドの双方を担当した。

技術: `TypeScript（Next.js` `React Hook Form` `Chakra UI` `Express` `Prisma` `Zod）`

#### Webサービス基盤へのIaC導入・CI/CD改善（Azure）

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2023年11月〜2025年3月（1年5ヶ月） | メンバー（インフラ担当） | 要件定義〜運用保守 |

- **業務内容** — IaC導入の推進、CI/CD改善、インフラ構成の最適化を担当。スコープを絞って段階的にコード化を進め、アプリケーションエンジニアだけでリリースを完結できる状態にした。

技術: `Azure API Management` `Cosmos DB` `Blob Storage` `Key Vault` `Functions` `DNS` `Monitor` `Front Door` `Logic Apps` `App Service` `Terraform`

#### ホスティング環境移行・リアルタイム通信基盤の技術検証

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2023年9月〜2023年12月（4ヶ月） | メンバー（インフラ担当） | 要件定義〜運用保守 |

- **業務内容** — ホスティング環境の移行支援と、リアルタイム通信基盤の機能調査を担当。

技術: `AWS Amplify` `LiveKit Cloud` `Vercel` `Datadog`

#### インフラ技術検証（Google Cloud）

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2022年11月〜2023年5月（7ヶ月） | メンバー（全2名） | 技術検証 |

- **業務内容** — 新基盤の技術選定に向け、各種ミドルウェア・マネージドサービスの技術検証を担当。検証結果を整理し、判断材料として提供した。

技術: `Google Cloud IAM` `GCS` `GKE` `Cloud Scheduler` `Cloud Build` `Anthos Service Mesh` `Datastream` `BigQuery` `Cloud SQL` `Cloud Deploy` `Artifact Registry` `Cloud Workstations` `Config Connector` `Backstage` `Apache Kafka` `Apache Pulsar` `OWASP Juice Shop` `Terraform` `Docker` `Strapi`

#### Azure基盤のPaaS移行・Bicepによる IaC 化

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2022年7月〜2026年9月（4年3ヶ月） | インフラ担当（全6名） | 要件定義〜運用保守 |

- **業務内容** — VMベースの既存インフラをPaaS中心の構成へリプレース。IaCはAzureネイティブのBicepを選定し、ネットワーク設計、各種サービス設計、DB移行、セキュリティ検証、CI/CD構築までを担当した。

技術: `Azure VM` `VNet` `NSG` `VPN` `SignalR` `Blob Storage` `Key Vault` `Cosmos DB` `Database for MySQL` `DNS` `Database Migration Service` `Functions` `Monitor` `Front Door` `Logic Apps` `App Service` `DevOps` `AWS Cognito` `IAM Identity Center` `Lambda` `S3` `CloudTrail` `Bicep` `Metabase` `OWASP ZAP`

#### アプリ開発基盤のTerraform運用・Policy as Code

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2022年5月〜2024年9月（2年5ヶ月） | メンバー（全4名） | 要件定義〜運用保守 |

- **業務内容** — Terraformのmodule化・リファクタリング、tfmigrateによるstate移行、HashiCorp SentinelによるPolicy as Code、CI/CDパイプライン改修を担当。社内規定への準拠を機械的に判定するガードレールを構築した。

技術: `AWS EC2` `IAM` `VPC` `SG` `ELB` `PrivateLink` `Route53` `S3` `WorkMail` `Transit Gateway` `SES` `Terraform` `Terraform Enterprise` `HashiCorp Vault` `HashiCorp Sentinel` `tfmigrate` `Shell` `Rust`

---

### SIer（独立系・SES）｜ 2020年10月〜2022年4月（1年7ヶ月）

クラウド領域に軸足を移し、Google Cloud / AWS でのデータ分析基盤の設計・構築、IaC・CI/CD整備を担当。

#### IoTデータ分析基盤の設計・構築

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2021年12月〜2022年4月（5ヶ月） | メンバー（全25名） | 設計・構築 |

- **業務内容** — インフラ管理、CI/CD構築、API基盤・テスト自動化基盤の構築を担当。IoTデバイスからのデータ送信機能について検証・設計・構築を行い、あわせて利用料の試算も実施した。

技術: `Google Cloud GCE` `GCS` `Cloud SQL` `VPC` `IAP` `IAM` `Cloud Functions` `Pub/Sub` `Cloud Build` `Bigtable` `GAE` `API Gateway` `IoT Core` `Dataflow` `BigQuery` `Firebase` `Secret Manager` `Stackdriver` `Terraform` `Goss` `Docker` `Shell` `Python`

#### データ分析基盤の設計・構築

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2021年8月〜2022年4月（9ヶ月） | メンバー（全8名） | 設計・構築 |

- **業務内容** — インフラ管理、CI/CD構築を担当。IoTデバイスからのHTTP通信を受信するスクリプトの作成、データパイプラインの構築、データカタログの検証を行った。

技術: `Google Cloud IAM` `Pub/Sub` `Cloud Functions` `Cloud Shell` `Cloud Build` `Dataflow` `GCS` `BigQuery` `Terraform` `Docker` `Shell` `Python`

#### 社内ポータルサイトの保守運用・自動化

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2021年3月〜2022年4月（1年2ヶ月） | メンバー（全3名） | 構築・保守運用 |

- **業務内容** — インフラ管理、CI/CD構築、サーバーの自動開始・停止スクリプト作成を担当。アラート監視・ログ監視の設定と、発生した事象への対応も行った。

技術: `Google Cloud GCE` `GCS` `Cloud SQL` `GCR` `VPC` `IAP` `CLB` `Cloud Armor` `Cloud DNS` `IAM` `Pub/Sub` `Cloud Functions` `Secret Manager` `Stackdriver` `Cloud Build` `Ansible` `Docker` `Terraform` `CentOS 7` `Shell` `Python`

#### データ分析基盤の機能追加（AWS）

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2020年10月〜2020年12月（3ヶ月） | メンバー（全8名） | 設計・構築 |

- **業務内容** — 内部設計書の改修、各種定義の確認とテスト実施、リリース手順書・試験項目表の作成、運用手順書の作成を担当した。

技術: `AWS EC2` `S3` `IAM` `VPC` `SG` `EBS` `CloudFormation` `CloudWatch` `CloudTrail` `WorkSpaces` `RDS` `Windows Server 2012/2012R2` `Amazon Linux` `JP1` `Squid` `PowerShell` `Python`

---

### SIer（独立系・SES）｜ 2018年4月〜2019年12月（1年9ヶ月）

新卒入社。オンプレミス環境のサーバ・ストレージ・バックアップ更改案件に、提案から移行・運用引継ぎまで一貫して参画。

#### バックアップシステムの更改・移行

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2019年7月〜2019年12月（6ヶ月） | メンバー（全4名） | 提案〜要件定義〜設計〜構築〜移行 |

- **業務内容** — サーバ調査とドキュメント作成、ネットワーク図の改修と設定仕様書の作成、OS設定とバックアップソフトの導入を担当。テスト・移行から運用引継ぎまで一貫して対応した。

技術: `NetBackup 7.x/8.x` `VMware vSphere 6.5` `JP1` `DataDomain(SAN)` `StoreOnce(NAS)` `3PAR(SAN)` `Windows Server 2008〜2016` `Red Hat 6・7` `Shell` `Batch`

#### ストレージ更改・データ移行

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2019年4月〜2019年7月（4ヶ月） | メンバー（全3名） | 提案・移行 |

- **業務内容** — ネットワーク図・ラック図の改修、設定仕様書と移行手順書の作成および移行作業の実施、既存スクリプトの改修、運用手順書の作成を担当した。

技術: `DataDomain(SAN)` `StoreOnce(NAS)` `3PAR(SAN)` `JP1` `NetBackup 7.x/8.x` `VMware vSphere 6.5` `Windows Server 2008〜2016` `Red Hat 6・7` `Shell` `Batch`

#### 受注管理システムの更改・移行

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2018年9月〜2019年3月（7ヶ月） | メンバー（全4名） | 提案〜要件定義〜設計〜構築〜移行 |

- **業務内容** — サーバ調査とドキュメント作成、ネットワーク図の改修とパラメータシートの作成、仮想基盤およびOSの構築、単体・結合テストの実施を担当した。

技術: `Oracle 13.1.0.x` `JP1` `NetBackup 7.x/8.x` `VMware vSphere 5.5・6.0` `DataDomain(SAN)` `Unity(SAN)` `Hydra(NAS)` `Windows Server 2008R2〜2016` `Red Hat 5・6` `Shell` `Batch` `PowerShell`

#### 受注管理システム更改の提案・要件定義

| 期間 | 役割 | フェーズ |
|:--|:--|:--|
| 2018年5月〜2018年8月（4ヶ月） | メンバー（全6名） | 提案・要件定義 |

- **業務内容** — サーバ調査（情報取得スクリプトの作成を含む）と、取得情報の集計・整形にもとづく移行計画の作成を担当した。

技術: `Windows Server 2000〜2012R2` `Red Hat 5・6` `Shell` `Batch` `PowerShell`

---

## 資格

| 取得年月 | 資格名 |
|:--|:--|
| 2022年9月 | Microsoft Certified: Azure Fundamentals ／ Azure AI Fundamentals ／ Security, Compliance, and Identity Fundamentals |
| 2022年5月 | AWS Certified Developer – Associate |
| 2022年1月 | ORACLE MASTER Silver DBA 2019 |
| 2021年8月 | AWS Certified Solutions Architect – Professional ／ AWS Certified DevOps Engineer – Professional ／ Google Cloud Certified Professional Cloud Architect |
| 2021年5月 | Python 3 エンジニア認定基礎試験 ／ Python 3 エンジニア認定データ分析試験 |
| 2021年4月 | LinuC Level-3 303 Security ／ LinuC Level-3 300 Mixed Environment |
| 2020年12月 | AWS Certified Cloud Practitioner |
| 2020年11月 | JDLA Deep Learning for GENERAL |
| 2020年10月 | LinuC Level-3 304 Virtualization & High Availability |
| 2019年6月 | LinuC Level-2 |
| 2019年2月 | AWS Certified Solutions Architect – Associate |
| 2018年12月 | ORACLE MASTER Bronze Oracle Database 12c |
| 2018年9月 | CompTIA Server+ |
| 2018年7月 | LinuC Level-1 |
