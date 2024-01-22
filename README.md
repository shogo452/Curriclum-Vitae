# Curriclum-Vitae

最終更新日 2024/01/22

## 基本情報

| Name | 田中 章悟(Shogo Tanaka)|
|  ----  |  ----  |
| Qiita |https://qiita.com/shogo452 |
|  Zenn  |  https://zenn.dev/shogo452  |
|  Speaker Deck  |  https://speakerdeck.com/shogo452 |

## 概要

* SRE
* インフラ、バックエンド開発がメイン
* 現職は株式会社スタメン

## スキル

* 言語
  * Ruby
  * HTML/CSS/JavaScript
  * 日本語
    * ネイティブ
  * 英語
    * 日常会話レベル 
* フレームワーク
  * Rails
* インフラ
  * AWS
    * EC2, ECS, RDS, CloudWatch, S3, Route53, CloudFormation, Athena, Lambda, QuickSight, EventBridge, CostExplorer, IAM, ACM, CodeDeploy, CodeBuild, OpenSeach Service, ElastiCache, WAF, CloudTrail, Glue, Elemental MediaConvert, Systems Manager, SNS, SES
  * Docker
  * Terraform
* ツール、その他
  * Slack
  * Backlog
  * Docbase
  * Bugsnag
  * Sendgrid
  * Datadog
  * Github
  * CI/CD(CircleCI)
  * Figma 

## 職歴

### 株式会社東雲火山：2024/1 ~ 現在(業務委託)

API Gateway + Lambda(serverless-express)のAPI用のインフラをTerraformを用いて構築

### 株式会社スタメン：2021/2 ~ 現在(正社員)

バックエンドエンジニアとして入社し、エンゲージメント経営プラットフォームサービス「[TUNAG](https://biz.tunag.jp/)」の機能改善、新機能開発に従事。

| 期間 |内容| 役割/開発チーム規模 |
| ---- | ---- | ---- |
| 2021/2〜2021/5  | ・細かい不具合の修正、機能改善<br />・Cypressを用いた認証機能のE2Eテスト<br />・SRE業務(監視) | サーバーサイドエンジニア/4名程度 |
| 2021/6〜2021/8| ・[deep_cloneable](https://github.com/moiristo/deep_cloneable)を使用した複製機能のプロジェクト<br />・SRE業務(運用・監視・コスト管理) |サーバーサイドエンジニア/4名程度|
| 2021/8〜2021/10| ・[タイムラインへのメール投稿機能](https://prtimes.jp/main/html/rd/p/000000027.000023589.html)の開発<br />・SRE業務(運用・監視・コスト管理) |サーバーサイドエンジニア/4名程度|
| 2021/10〜2021/11| ・[タイムトラベル投稿機能](https://prtimes.jp/main/html/rd/p/000000040.000023589.html)の開発<br />・SRE業務(運用・監視・コスト管理) |サーバーサイドエンジニア/4名程度|
| 2021/11〜2022/1| ・[タスク依頼機能PC版](https://prtimes.jp/main/html/rd/p/000000065.000023589.html)の開発<br />・SRE業務(運用・監視・コスト管理) |サーバーサイドエンジニア/4名程度|
| 2022/1〜2022/7| ・[カスタムダッシュボード機能](https://prtimes.jp/main/html/rd/p/000000062.000023589.html)のインフラ構築、<br />サーバーサイド、フロントエンドの開発<br />・SRE業務(運用・監視・コスト管理) |フルスタックエンジニア/4名程度|
|  2022/8〜2022/12  |  ・カスタムダッシュボード機能の拡張<br />・チャットタスク機能の開発<br />・IPアドレス制限機能の開発<br />・SRE業務(運用・監視・コスト管理)  | フルスタックエンジニア/4名程度 |
|  2023/1〜2023/6  |  ・カスタムプラン機能の開発<br />・マルチアカウント機能の開発<br />・SRE業務(運用・監視・コスト管理・障害対応責任者)<br />・セキュリティチェックシートの回答  | フルスタックエンジニア/3名程度 |
|  2023/7〜現在  |  ・インフラ運用・監視・コスト管理<br />・アラート対応・障害対応<br />・細かい不具合の修正、機能改善<br />・パフォーマンス・チューニング<br />・セキュリティチェック対応  | SRE/2名程度 |

#### 概要

* 入社後は主にRuby on Railsを用いたバックエンドの機能実装をメインに担当。 
* バックエンド開発と並行してSRE業務にも従事。2023年7月からSREとしてインフラメインで業務に従事。
  * 監視・障害対応
    * CloudWatchやBugsnagのアラート対応
    * CloudWatchのメトリクス監視
    * Athenaによるアクセスログの集計及びRDSのパフォーマンスインサイト・DataDogを用いたパフォーマンス監視
    * 障害対応
    * CI/CD周りのトラブルシュート
  * インフラコスト管理
    * AWS及びSaaSの費用の集計・傾向分析
    * RI/Savings Plansの管理
    * コスト削減の提案
     * EC2からSavings Plansへの移行、CloudFront Saving Bundleの導入を主導し、コスト削減に貢献。
    * SaaSの契約更新に伴う社外調整
  * 脆弱性診断の推進
    * 診断業者との社外調整
  * 基盤整備
    * Aurora MySQLのバージョンアップ
    * 監視アラートの見直し
    * Sentryの導入

#### その他

* 会社の技術ブログへの投稿
  * [RailsのActiveRecord::AttributeMethods::Dirtyを使ってみた](https://tech.stmn.co.jp/entry/2021/04/22/100133)
  * [名前空間を用いたQuickSight上でのマルチテナントの実現](https://tech.stmn.co.jp/entry/2022/04/18/135545)
  * [QuickSightを利用してカスタマイズしたダッシュボードを埋め込む](https://tech.stmn.co.jp/entry/2022/08/03/122204)
  * [QuickSight SPICEデータのLambda関数を用いた自動更新処理](https://tech.stmn.co.jp/entry/2022/08/05/091212)
  * [QuickSightのSPICEデータ使用量をLambdaで監視している話](https://tech.stmn.co.jp/entry/2022/08/08/090850)
  * [Rubyを用いたAWS LambdaからSlackに通知する仕組みを作った話](https://zenn.dev/stmn_inc/articles/6869d707b3af70)
  * [TUNAGのDBをAurora MySQL v3にアップグレードしました](https://tech.stmn.co.jp/entry/2023/11/30/115509)

### 三菱重工業株式会社：2013/4 ~ 2021/1:正社員

|期間|職務要約|
| ---- | ---- |
|2013年4月〜2014年12月 | 三菱重工業株式会社 航空宇宙部品の品質管理担当|
|2015年1月〜2015年3月　| Mitsubishi Heavy Industries America, Inc.　海外調達品の品質管理担当(加勢派遣)|
|2016年4月〜2021年1月　| 三菱重工業株式会社 航空宇宙部品の品質管理担当 |


* 主な担当業務
  * 民間航空機・防衛航空機・宇宙機器に使用される炭素繊維部品及び
  * 金属接着部品の品質分析及び測定・外観検査プラン策定業務
  * 工程監査プログラムの運営業務
  * 超音波検査の初期計画、マニュアル整備及び検査用基準試験片の設計業務
  * 超音波検査、レントゲン検査装置の維持管理、新規設備・技術の導入検討業務
  * RPAロボットの開発

* 成果
  * 新材料・新構造の部品に対する検査手順の確立・検査用基準試験片を設計し、
　新規プロジェクトの完遂に貢献
    * [技報「複合材の最新非破壊検査技術」](https://www.wantedly.com/id/tiphp452/items/565b5b05-e124-4ef2-b4e5-1f99ca5ac711)
  * 工程監査のマニュアル整備・監査不適合傾向の分析業務の標準化
  * 国内外の検査設備メーカーの新規開拓、社内設備の近代化計画の推進
  * 開発したRPAロボットによる定型業務の工数削減

## 学歴

* 2013年3月 豊田工業高等専門学校 電気・電子システム工学科卒
* 研究内容：Bi系超伝導体の結晶構造の解析

## 資格

| 資格名  |  取得時期  |
| ---- | ---- |
|  AWS Certified Solutions Architect - Associate  | 2021年8月 |
|  MOS Office Excel 2016 Expert  | 2019年05月 | 
|  TOEIC スコア810  | 2018年12月 | 
| STEP BULATS SPEAKING B2, WRITING B2  | 2013年4月 | 

## 業務外活動

|  Date  |  Event/Comunity  | Details |
| ---- | ---- |---- |
| 2022/12〜 | JAWS-UG 名古屋支部 | 運営スタッフ |

## 登壇歴(社外)

|  Date  |  Event  | Slide |
| ---- | ---- |---- |
|  2022/9/26  | [BigData-JAWS 勉強会#21](https://jawsug-bigdata.connpass.com/event/257903/) |  [マルチテナントSaaSにおけるAmazon QuickSightの活用例](https://speakerdeck.com/shogo452/marutitenantosaasniokeruamazon-quicksightnohuo-yong-li)  |
|  2022/12/23  | [JAWS-UG 名古屋 2022年 "re:Invent"の復習 -忘年会-](https://jawsug-nagoya.doorkeeper.jp/events/146962) |  [Amazon QuickSightのアップデート -re:Invent 2022の復習&2022年ハイライト-](https://speakerdeck.com/shogo452/amazon-quicksightnoatupudeto-re-invent-2022nofu-xi-and-2022nian-hairaito)  |
|  2023/1/21  | [NGK2023S](https://ngk2022s.connpass.com/event/265837/) |  [5分で分かるドラッカー風エクササイズ](https://speakerdeck.com/shogo452/5fen-defen-karudoratukafeng-ekusasaizu)  |
|  2023/3/24  | [【LT会】この技術書がすごい in 名古屋](https://nagoya-it.connpass.com/event/274872/) |  [モブプログラミングの理解を深めた話](https://speakerdeck.com/shogo452/mobupuroguramingunoli-jie-woshen-metahua)  |
|  2023/5/23  | [JAWS-UG朝会 #45](https://jawsug-asa.connpass.com/event/274687/) |  [Amazon EventBridge Schedulerを用いて Amazon QuickSightの運用を改善した話](https://speakerdeck.com/shogo452/amazon-eventbridge-schedulerwoyong-ite-amazon-quicksightnoyun-yong-wogai-shan-sitahua)  |
|  2023/11/22  | [【ハイブリッド開催】BtoB SaaSのSRE奮闘事例秋まつり](https://stmn.connpass.com/event/298576/) |  [SREチーム立ち上げまでの変遷と取り組み事例](https://speakerdeck.com/shogo452/sretimuli-tishang-gemadenobian-qian-toqu-rizu-mishi-li) |
|  2023/12/18  | [JAWS-UG 名古屋 2023年 AWS re:Inventの復習](https://jawsug-nagoya.doorkeeper.jp/events/165969) |  [Amazon QuickSightのアップデート - re:Invent 2023 & 2023年ハイライト -](https://speakerdeck.com/shogo452/amazon-quicksightnoatupudeto-re-invent-2023-and-2023nian-hairaito) |
