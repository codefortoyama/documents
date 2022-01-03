# 富山市公衆浴場マップ 
## 使用するデータ
- 富山市のオープンデータサイトから取得する。<BR>
https://opdt.city.toyama.lg.jp/dataset/seikatsu-eisei04

データは、dataフォルダに格納しています。
  
| № | 項目名 | 内容 |
|:---|:---:|---:|
|1 |施設名 | (オープンデータと同じ値)|
|2 |許可年月日| (オープンデータと同じ値)|
|3 |許可番号| (オープンデータと同じ値)|
|4 |URL|URLを独自に入力する|

オープンデータとURLのリレーションシップには、「許可番号」を利用しています。「施設名」、「許可番号」は目視確認用に残しています。

- 公衆浴場の種別データ(独自作成)<BR>
https://evolinq-my.sharepoint.com/:x:/g/personal/tominari_evolinq_link/EfNa8kTL471Eok0PYEhf3ygB7_xGkVvAW10hCUq17ReyiQ?e=MJhvqc

| № | 項目名 | 内容 |
|:---|:---:|---:|
|1 |施設名 | (オープンデータと同じ値)|
|2 |許可年月日| (オープンデータと同じ値)|
|3 |許可番号| (オープンデータと同じ値)|
|4 |種別|下に記す種別を設定する|
| ||エステサロン|
| ||介護施設|
| ||ゴルフ場|
| ||宿泊施設(宿泊可能な銭湯・温泉)|
| ||スーパー銭湯(飲食を供する銭湯)|
| ||銭湯|
| ||スポーツジム|
| ||マンション|
| ||福祉施設|
| ||その他|
| ||不明|

## 実装方法
- PowerBI Desktopで作成したものをWEB上に公開する。
## 公開URL
- https://app.powerbi.com/view?r=eyJrIjoiY2M3MDdkNTAtOWFhNi00ZmU5LWE2NGEtM2MyNDNlOWM1ZjM2IiwidCI6IjhmMDk1ODJlLWYxYTMtNGU3Mi04NjA1LWVlMjc0MjFkMGVjMyJ9&pageName=ReportSection
