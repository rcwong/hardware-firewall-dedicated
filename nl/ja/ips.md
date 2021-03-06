---

copyright:
  years: 2017, 2018
lastupdated: "2018-11-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}

# IBM Cloud の IP 範囲

よくあるご質問の 1 つは、**どの IP 範囲を、ファイアウォール通過の許可対象にしますか?** というものです。 以下のリストに、IBM ファイアウォールおよびアプライアンスで使用する IP の全範囲を示します。

* IBM Cloud Juniper vSRX Standard
* IBM Virtual Router Appliance
* Fortigate Security Appliance 10Gbps
* Fortigate Security Appliance 1Gbps
* IBM Security Groups
* ハードウェア・ファイアウォール (専用)
* ハードウェア・ファイアウォール (共有)

## フロントエンド (パブリック) ネットワーク

|データ・センター|市|州|国|IP 範囲|
|---|---|---|---|---|
|ams01|アムステルダム|-|NLD|159.253.158.0/23|
|ams03|アムステルダム|-|NLD|159.8.198.0/23|
|che01|チェンナイ|-|IND|169.38.118.0/23|
|dal01|ダラス|テキサス|USA|66.228.118.0/23|
|dal05|ダラス|テキサス|USA|173.192.118.0/23|
|dal06|ダラス|テキサス|USA|184.172.118.0/23|
|dal07|ダラス|テキサス|USA|50.22.118.0/23|
|dal08|ダラス|テキサス|USA|192.255.18.0/24|
|dal09|ダラス|テキサス|USA|198.23.118.0/23|
|dal10|ダラス|テキサス|USA|169.46.118.0/23|
|dal12|ダラス|テキサス|USA|169.47.118.0/23|
|dal13|ダラス|テキサス|USA|169.48.118.0/24|
|fra02|フランクフルト|-|DEU|159.122.118.0/23|
|fra04|フランクフルト|-|DEU|161.156.118.0/24|
|fra05|フランクフルト|-|DEU|149.81.118.0/23|
|hkg02|香港|-|CHN|119.81.138.0/23|
|hou02|ヒューストン|テキサス|USA|173.193.118.0/23|
|lon02|ロンドン|-|ENG|5.10.118.0/23|
|lon04|ロンドン|-|ENG|169.62.118.0/24|
|lon05|ロンドン|-|ENG|141.125.118.0/23|
|lon06|ロンドン|-|ENG|158.176.118.0/23|
|mel01|メルボルン|-|AUS|168.1.118.0/23|
|mex01|メキシコ・シティー|-|MEX|169.57.118.0/23|
|mil01|ミラノ|-|ITA|159.122.138.0/23|
|mon01|モントリオール|-|CAN|169.54.118.0/23|
|par01|パリ|-|FRA|159.8.118.0/23|
|osl01|オスロ|-|NOR|169.51.118.0/24|
|sao01|サンパウロ|-|BRA|169.57.138.0/23|
|sea01|シアトル|ワシントン|USA|67.228.118.0/23|
|seo01|ソウル|-|KOR|169.56.118.0/24|
|sjc01|サンノゼ|カリフォルニア|USA|50.23.118.0/23|
|sjc03|サンノゼ|カリフォルニア|USA|169.45.118.0/23|
|sjc04|サンノゼ|カリフォルニア|USA|169.62.118.0/24|
|sng01|ジュロン・イースト|-|SGP|174.133.118.0/23|
|syd01|シドニー|-|AUS|168.1.18.0/23|
|syd04|シドニー|-|AUS|130.198.118.0/23|
|syd05|シドニー|-|AUS|135.90.118.0/23|
|tok02|東京|-|JPN|161.202.118.0/23|
|tok04|東京|-|JPN|128.168.118.0/23|
|tok05|東京|-|JPN|165.192.118.0/23|
|tor01|トロント|-|CAN|158.85.118.0/23|
|wdc01|ワシントン D.C.|-|USA|208.43.118.0/23|
|wdc03|ワシントン D.C.|-|USA|192.255.38.0/24|
|wdc04|ワシントン D.C.|-|USA|169.55.118.0/23|
|wdc06|ワシントン D.C.|-|USA|169.60.118.0/23|
|wdc07|ワシントン D.C.|-|USA|169.61.118.0/23|

許可するポート:<br>
すべての TCP/UDP ポート<br>
ICMP – ping (トラブルシューティングおよびモニタリングをサポートするため)

## ロード・バランサー IP

|データ・センター|市|州|国|IP 範囲|
|---|---|---|---|---|
|ams01|アムステルダム|-|NLD|159.253.157.0/24|
|ams03|アムステルダム|-|NLD|159.8.197.0./24|
|che01|チェンナイ|-|IND|169.38.117.0/24|
|dal01|ダラス|テキサス|USA|67.228.66.0/24、75.126.76.0/24、174.35.17.0/24、208.43.15.0/24|
|dal05|ダラス|テキサス|USA|50.23.203.0/24、108.168.157.0/24、173.192.117.0/24、192.155.205.0/24|
|dal06|ダラス|テキサス|USA|184.172.117.0/24|
|dal07|ダラス|テキサス|USA|50.22.117.0/24|
|dal09|ダラス|テキサス|USA|169.46.187.0/24、198.23.117.0/24|
|dal10|ダラス|テキサス|USA|169.46.117.0/24|
|dal12|ダラス|テキサス|USA|169.47.117.0/24|
|dal13|ダラス|テキサス|USA|169.48.117.0/24|
|fra02|フランクフルト|-|DEU|159.122.117.0/24|
|fra04|フランクフルト|-|DEU|161.156.117.0/24|
|fra05|フランクフルト|-|DEU|149.81.117.0/24|
|hkg02|香港|-|CHN|119.81.137.0/24|
|hou02|ヒューストン|テキサス|USA|173.193.118.0/23|
|lon02|ロンドン|-|ENG|5.10.117.0/24|
|lon04|ロンドン|-|ENG|158.175.117.0/24|
|lon05|ロンドン|-|ENG|141.125.117.0/24|
|lon06|ロンドン|-|ENG|158.176.117.0/24|
|mel01|メルボルン|-|AUS|168.1.117.0/24|
|mex01|メキシコ・シティー|-|MEX|169.57.117.0/24|
|mil01|ミラノ|-|ITA|159.122.137.0/24|
|mon01|モントリオール|-|CAN|169.54.117.0/24|
|par01|パリ|-|FRA|159.8.117.0/24|
|osl01|オスロ|-|NOR|169.51.117.0/24|
|sao01|サンパウロ|-|BRA|169.57.137.0/24|
|sea01|シアトル|ワシントン|USA|67.228.117.0/24|
|seo01|ソウル|-|KOR|169.56.117.0/24|
|sjc01|サンノゼ|カリフォルニア|USA|50.23.117.0/24|
|sjc03|サンノゼ|カリフォルニア|USA|169.45.117.0/24|
|sng01|ジュロン・イースト|-|SGP|174.133.117.0/24|
|syd01|シドニー|-|AUS|168.1.17.0/24|
|syd04|シドニー|-|AUS|130.198.117.0/24|
|syd05|シドニー|-|AUS|135.90.117.0/24|
|tok02|東京|-|JPN|161.202.117.0/24|
|tok04|東京|-|JPN|128.168.117.0/24|
|tok05|東京|-|JPN|165.192.117.0/24|
|tor01|トロント|-|CAN|158.85.117.0/24|
|wdc01|ワシントン D.C.|-|USA|50.22.248.0/25、169.54.27.0/24、198.11.250.0/24、208.43.117.0/24|
|wdc04|ワシントン D.C.|-|USA|169.55.117.0/24|
|wdc06|ワシントン D.C.|-|USA|169.60.117.0/24|
|wdc07|ワシントン D.C.|-|USA|169.61.117.0/24|

## DOS 緩和システム

|データ・センター|市|州|国|IP 範囲|
|---|---|---|---|---|
|AMS|アムステルダム|-|NLD|159.253.156.0/24、159.8.196.0/24|
|CHE|チェンナイ|-|IND|169.38.116.0/24|
|DAL|ダラス|テキサス|USA|75.126.61.0/24|
|FRA|フランクフルト|-|DEU|159.122.116.0/24|
|HKG|香港|-|CHN|119.81.136.0/24|
|HOU|ヒューストン|テキサス|USA|173.193.116.0/24|
|KOR|ソウル|-|韓国|169.56.116.0/24|
|LON|ロンドン|-|ENG|5.10.116.0/24|
|MEL|メルボルン|-|AUS|168.1.116.0/24|
|MEX|メキシコ・シティー|-|MEX|169.57.116.0/24|
|MIL|ミラノ|-|ITA|159.122.136.0/24|
|MON|モントリオール|-|CAN|169.54.116.0/24|
|NOR|オスロ|-|ノルウェー|169.56.116.0/24|
|PAR|パリ|-|FRA|159.8.116.0/24|
|SAO|サンパウロ|-|BRA|169.57.136.0/24|
|SEA|シアトル|ワシントン|USA|50.23.167.0/24|
|SJC|サンノゼ|カリフォルニア|USA|50.23.116.0/24|
|SNG|ジュロン・イースト|-|SGP|174.133.116.0/24|
|SYD|シドニー|-|AUS|168.1.16.0/24|
|TOK|東京|-|JPN|161.202.116.0/24|
|TOR|トロント|-|CAN|158.85.116.0/24|
|WDC|ワシントン D.C.|-|USA|50.22.255.0/24|

許可するポート: <br>
すべての TCP/UDP ポート

## 脆弱点スキャン
脆弱点スキャンが正常に完了するようにするため、IP アドレス **173.192.255.232** および **172.17.19.38** についてはアクセスを許可してください。

## バックエンド (プライベート) ネットワーク

IP ブロック: お客様のサーバー間通信用プライベート IP ブロック (10.X.X.X/X)<br>
許可するポート:<br>
ICMP – ping (トラブルシューティングをサポートするため)<br>
すべての TCP/UDP ポート<br>
EVault のポート固有情報については、[ここをクリック](/docs/infrastructure/Backup/evault-port-information.html#evault-port-information)してください。

## サービス・ネットワーク (バックエンド/プライベート・ネットワーク上)
DAL01、WDC04、およびサーバー・ロケーションのルールを必ず追加してください。 サーバーが EU 内にある場合は、DAL01、WDC04、および AMS01 からのトラフィックを許可するルールを追加する必要があります。

|データ・センター|市|州|国|IP 範囲|
|---|---|---|---|---|
|すべて|-|-|-|161.26.0.0/16
|ams01|アムステルダム|-|NLD|10.2.64.0/20|
|ams03|アムステルダム|-|NLD|10.3.128.0/20|
|che01|チェンナイ|-|IND|10.200.16.0/20|
|dal01|ダラス|テキサス|USA|10.0.64.0/19|
|dal05|ダラス|テキサス|USA|10.1.128.0/19|
|dal06|ダラス|テキサス|USA|10.2.128.0/20|
|dal07|ダラス|テキサス|USA|10.1.176.0/20|
|dal08|ダラス|テキサス|USA|100.100.0.0/20|
|dal09|ダラス|テキサス|USA|10.2.112.0/20 および 10.3.192.0/24|
|dal10|ダラス|テキサス|USA|10.200.80.0/20|
|dal12|ダラス|テキサス|USA|10.200.112.0/20|
|dal13|ダラス|テキサス|USA|10.200.128.0/20|
|fra02|フランクフルト|-|DEU|10.3.80.0/20|
|fra04|フランクフルト|-|DEU|10.201.112.0/20|
|fra05|フランクフルト|-|DEU|10.201.128.0/20|
|hkg02|香港|-|CHN|10.2.160.0/20|
|hou02|ヒューストン|テキサス|USA|10.1.160.0/20|
|lon02|ロンドン|-|ENG|10.1.208.0/20|
|lon04|ロンドン|-|ENG|10.201.32.0/20|
|lon05|ロンドン|-|ENG|10.201.48.0/20|
|lon06|ロンドン|-|ENG|10.201.64.0/20|
|mel01|メルボルン|-|AUS|10.2.80.0/20|
|mex01|メキシコ・シティー|-|MEX|10.2.176.0/20|
|mil01|ミラノ|-|ITA|10.3.144.0/20|
|mon01|モントリオール|-|CAN|10.3.112.0/20|
|par01|パリ|-|FRA|10.2.144.0/20|
|osl01|オスロ|-|NOR|10.200.96.0/20|
|sao01|サンパウロ|-|BRA|10.200.0.0/20|
|sea01|シアトル|ワシントン|USA|10.1.64.0/19|
|seo01|ソウル|-|KOR|10.200.64.0/20|
|sjc01|サンノゼ|カリフォルニア|USA|10.1.192.0/20|
|sjc03|サンノゼ|カリフォルニア|USA|10.3.176.0/20|
|sjc04|サンノゼ|カリフォルニア|USA|10.201.80.0/20|
|sng01|ジュロン・イースト|-|SGP|10.2.32.0/20|
|syd01|シドニー|-|AUS|10.3.96.0/20|
|syd04|シドニー|-|AUS|10.201.16.0/20|
|syd05|シドニー|-|AUS|10.202.16.0/20|
|tok02|東京|-|JPN|10.3.64.0/20|
|tok04|東京|-|JPN|10.201.176.0/20|
|tok05|東京|-|JPN|10.201.192.0/20|
|tor01|トロント|-|CAN|10.2.48.0/20|
|wdc01|ワシントン D.C.|-|USA|10.1.96.0/19|
|wdc03|ワシントン D.C.|-|USA|100.100.32.0/20|
|wdc04|ワシントン D.C.|-|USA|10.3.160.0/20 および 10.201.0.0/20|
|wdc06|ワシントン D.C.|-|USA|10.200.160.0/20|
|wdc07|ワシントン D.C.|-|USA|10.200.176.0/20|

## SSL VPN ネットワーク (バックエンド/プライベート・ネットワーク上)
ICMP – ping (トラブルシューティングをサポートするため) <br>
すべての TCP/UDP ポート (ご使用のローカル・ワークステーションからのアクセスのため)

## SSL VPN データ・センター

|データ・センター|市|州|国|IP 範囲|
|---|---|---|---|---|
|ams01|アムステルダム|-|NLD|10.2.200.0/23|
|ams03|アムステルダム|-|NLD|10.3.220.0/24|
|che01|チェンナイ|-|IND|10.200.232.0/24|
|dal01|ダラス|テキサス|USA|10.1.0.0/23|
|dal05|ダラス|テキサス|USA|10.1.24.0/23|
|dal06|ダラス|テキサス|USA|10.2.208.0/23|
|dal07|ダラス|テキサス|USA|10.1.236.0/24|
|dal09|ダラス|テキサス|USA|10.2.232.0/24|
|dal10|ダラス|テキサス|USA|10.200.228.0/24|
|dal12|ダラス|テキサス|USA|10.200.216.0/22|
|dal13|ダラス|テキサス|USA|10.200.212.0/22|
|fra02|フランクフルト|-|DEU|10.2.236.0/24|
|hkg02|香港|-|CHN|10.2.216.0/24|
|hou02|ヒューストン|テキサス|USA|10.1.56.0/23|
|lon02|ロンドン|-|ENG|10.2.220.0/24|
|lon04|ロンドン|-|ENG|10.200.196.0/24|
|lon05|ロンドン|-|ENG|10.201.208.0/24|
|lon06|ロンドン|-|ENG|10.3.200.0/24|
|mel01|メルボルン|-|AUS|10.2.228.0/24|
|mex01|メキシコ・シティー|-|MEX|10.3.232.0/24|
|mil01|ミラノ|-|ITA|10.3.216.0/24|
|mon01|モントリオール|-|CAN|10.3.224.0/24|
|par01|パリ|-|FRA|10.3.236.0/24|
|osl01|オスロ|-|NOR|10.200.220.0/22|
|sao01|サンパウロ|-|BRA|10.200.236.0/24|
|sea01|シアトル|ワシントン|USA|10.1.8.0/23|
|seo01|ソウル|-|KOR|10.200.224.0/22|
|sjc01|サンノゼ|カリフォルニア|USA|10.1.224.0/23|
|sjc03|サンノゼ|カリフォルニア|USA|10.3.204.0/24|
|sjc04|サンノゼ|カリフォルニア|USA|10.200.192.0/24|
|sng01|ジュロン・イースト|-|SGP|10.2.192.0/23|
|syd01|シドニー|-|AUS|10.3.228.0/24|
|syd04|シドニー|-|AUS|10.200.200.0/24|
|syd05|シドニー|-|AUS|10.201.212.0/24|
|tok02|東京|-|JPN|10.2.224.0/24|
|tok04|東京|-|JPN|10.201.228.0/24|
|tok05|東京|-|JPN|10.201.224.0/24|
|tor01|トロント|-|CAN|10.1.232.0/24|
|wdc01|ワシントン D.C.|-|USA|10.1.16.0/23|
|wdc04|ワシントン D.C.|-|USA|10.3.212.0/24|
|wdc06|ワシントン D.C.|-|USA|10.200.208.0/24|
|wdc07|ワシントン D.C.|-|USA|10.200.204.0/24|

## SSL VPN POP

|POP|市|州|国|IP 範囲|
|---|---|---|---|---|
|atl01|アトランタ|ジョージア|USA|10.1.41.0/24|
|chi01|シカゴ|イリノイ|USA|10.1.49.0/24|
|den01|デンバー|コロラド|USA|10.1.53.0/24|
|lax01|ロサンゼルス|カリフォルニア|USA|10.1.33.0/24|
|mia01|マイアミ|フロリダ|USA|10.1.37.0/24|
|nyc01|ニューヨーク|ニューヨーク|USA|10.1.45.0/24|

## PPTP VPN データ・センター

|データ・センター|市|州|国|IP 範囲|
|---|---|---|---|---|
|ams01|アムステルダム|-|NLD|10.2.203.0/24|
|ams03|アムステルダム|-|NLD|10.3.221.0/24|
|che01|チェンナイ|-|IND|10.200.233.0/24|
|dal01|ダラス|テキサス|USA|10.1.3.0/24|
|dal05|ダラス|テキサス|USA|10.1.27.0/24|
|dal06|ダラス|テキサス|USA|10.2.211.0/24|
|dal07|ダラス|テキサス|USA|10.1.238.0/24|
|dal09|ダラス|テキサス|USA|10.2.233.0/24|
|dal10|ダラス|テキサス|USA|10.200.229.0/24|
|dal12|ダラス|テキサス|USA|10.200.217.0/24|
|dal13|ダラス|テキサス|USA|10.200.213.0/24|
|fra02|フランクフルト|-|DEU|10.2.237.0/24|
|fra04|フランクフルト|-|DEU|10.3.197.0/24|
|hkg02|香港|-|CHN|10.2.217.0/24|
|hou02|ヒューストン|テキサス|USA|10.1.59.0/24|
|lon02|ロンドン|-|ENG|10.2.221.0/24|
|lon04|ロンドン|-|ENG|10.200.197.0/24|
|lon06|ロンドン|-|ENG|10.3.201.0/24|
|mel01|メルボルン|-|AUS|10.2.229.0/24|
|mil01|ミラノ|-|ITA|10.3.217.0/24|
|mon01|モントリオール|-|CAN|10.3.255.0/24|
|mex01|メキシコ・シティー|-|MEX|10.3.233.0/24|
|par01|パリ|-|FRA|10.3.237.0/24|
|sao01|サンパウロ|-|BRA|10.200.237.0/24|
|sea01|シアトル|ワシントン|USA|10.1.11.0/24|
|seo01|-|韓国|KOR|10.200.225.0/24|
|sjc01|サンノゼ|カリフォルニア|USA|10.1.227.0/24|
|sjc03|サンノゼ|カリフォルニア|USA|10.3.205.0/24|
|sjc04|サンノゼ|カリフォルニア|USA|10.200.193.0/24|
|sng01|ジュロン・イースト|-|SGP|10.2.195.0/24|
|syd01|シドニー|-|AUS|10.3.229.0/24|
|syd04|シドニー|-|AUS|10.200.201.0/24|
|tok02|東京|-|JPN|10.2.225.0/24|
|tor01|トロント|-|CAN|10.1.233.0/24|
|wdc01|ワシントン D.C.|-|USA|10.1.19.0/24|
|wdc04|ワシントン D.C.|-|USA|10.3.213.0/24|
|wdc06|ワシントン D.C.|-|USA|10.200.209.0/24|
|wdc07|ワシントン D.C.|-|USA|10.200.205.0/24|

## PPTP VPN POP

|POP|市|州|国|IP 範囲|
|---|---|---|---|---|
|atl01|アトランタ|ジョージア|USA|10.1.42.0/24|
|chi01|シカゴ|イリノイ|USA|10.1.40.0/24|
|den01|デンバー|コロラド|USA|10.1.54.0/24|
|lax01|ロサンゼルス|カリフォルニア|USA|10.1.34.0/24|
|mia01|マイアミ|フロリダ|USA|10.1.38.0/24|
|nyc01|ニューヨーク|ニューヨーク|USA|10.1.46.0/24|

## レガシー・ネットワーク

|IP 範囲|
|---|
|12.96.160.0/24|
|66.98.240.192/26|
|67.18.139.0/24|
|67.19.0.0/24|
|70.84.160.0/24|
|70.85.125.0/24|
|75.125.126.8|
|209.85.4.0/26|
|216.12.193.9|
|216.40.193.0/24|
|216.234.234.0/24|

ご使用のサーバーで SoftLayer によって提供された **Red Hat Enterprise Linux (RHEL)** ライセンスを利用している場合は、追加で以下のとおり、サービス・ネットワークへのアクセスを許可する必要があります。これを行わないと、更新とライセンス交付が正しく機能しません。

|サーバー・ロケーション|サービス・ネットワークの許可対象データ・センター|
|---|---|
|アムステルダム (AMS01、AMS03)|LON02|
|チェンナイ (CHE01)|TOK02 および SYD01|
|ダラス (DAL01、DAL05、DAL07、DAL09)|DAL09|
|ダラス (DAL06、DAL10)|DAL06|
|ヒューストン (HOU02)|DAL09|
|フランクフルト (FRA02)|LON02|
|香港 (HKG02)|TOK02 および SYD01|
|ロンドン (LON02)|LON02|
|メルボルン (MEL01)|SYD01|
|メキシコ (MEX01)|DAL06|
|ミラノ (MIL01)|LON02|
|モントリオール (MON01)|MON01|
|パリ (PAR01)|LON02|
|サンノゼ (SJC01、SJC03)|SJC03 および DAL06|
|サンパウロ (SAO01)|SAO01 および DAL09|
|シンガポール (SNG01)|TOK02 および SYD01|
|シアトル (SEA01)|SJC03 および DAL06|
|シドニー (SYD01、SYD04)|SYD01|
|トロント (TOR01)|TOR01|
|ワシントン DC (WDC01、WDC04、WDC06、WDC07)|MON01|
|上記以外のすべてのデータ・センター|DAL09|
