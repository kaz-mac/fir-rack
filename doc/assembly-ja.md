# FIR RACK 組み立て手順

組み立て手順: [English](./assembly-en.md) | **日本語**

フィラメントは PETG でプリントすることをおすすめします。PLA は高温により変形する恐れがあります。

## 4つのプロファイル

作成するラックの構成によって、プリントするパーツの種類や個数が変わります。Bambu Studioで3MFファイルを開くと、プレート上部にプリント数などの情報が記載されているので参考にしてください。

### (1) BASICプロファイル

基本のパーツはBASIC Profileに全て納められています。

| ファイル名 | 部位 | 数量 | 備考 |
|---|---|---:|---|
| X Edge Top | 支柱 (水平方向) 上 | 2 |  |
| X Edge Bottom | 支柱 (水平方向) 下 | 2 |  |
| Y Edge | 支柱 (奥方向) | 4 |  |
| Z Edge 5U | 支柱 (垂直方向) | 4 |  |
| Handle | 取っ手 | 2 |  |
| Foot | 足 | 4 |  |

<a href="image/names_basic.webp" target="_blank" rel="noopener noreferrer"><img src="image/names_basic.webp" width="640"></a>

### (2) PANELプロファイル (optional)

パネルは別プロファイルになっています。PANEL Profileから必要なものをプリントしてください。

| ファイル名 | 部位 |
|---|---|
| TB Panel 12cm-fan | 上下パネル (12cm FAN用) |
| TB Panel 14cm-fan | 上下パネル (14cm FAN用) |
| TB Panel mesh | 上下パネル (メッシュ) |
| TB Panel plane | 上下パネル (プレーン) |
| LR Panel mesh 5U | 左右パネル (メッシュ) |
| LR Panel plane 5U | 左右パネル (プレーン) |

<a href="image/names_panel.webp" target="_blank" rel="noopener noreferrer"><img src="image/names_panel.webp" width="640"></a>

### (3) 延長プロファイル (optional)

3Uまたは5Uの延長をしたい場合はExtend Profileから必要なものをプリントしてください。"3U"と書かれたパーツは3Uの延長用です。5Uの延長をする場合はBASICやPANEL内のパーツを使ってください。

| ファイル名 | 部位 | 3U | 5U |
|---|---|---:|---:|
| Extend Unit | 延長ユニット | 2 | 2 |
| Extend Unit-cover | 延長ユニットねじ蓋 | 6 | 6 |
| Z Edge 3U | 支柱 (垂直) 3U | 4 |  |
| Rail Holder-L 3U | サポートレール固定 左 3U | (2) *1 |  |
| Rail Holder-R 3U | サポートレール固定 右 3U | (2) *1 |  |
| LR Panel mesh 3U | 左右パネル (メッシュ) 3U | (2) |  |
| LR Panel plane 3U | 左右パネル (プレーン) 3U | (2) |  |

注: *1 ... サポートレールを使用する場合のみプリント

延長について詳しくは、本ドキュメントの「延長オプションの組み立て方法」をご覧ください。

### (4) レールプロファイル (optional)

サポートレールのプリントは任意です。サポートレールを使用すると重いシェルフを支えることができますが、使用できるシェルフに制限があります。詳しくはこのドキュメントの「サポートレールの使い方」をご覧ください。

| ファイル名 | 場所 | 数量 | 備考 |
|---|---|---:|---|
| Rail Holder-L 5U | サポートレール固定 左 | (2) | *1 |
| Rail Holder-R 5U | サポートレール固定 右 | (2) | *1 |
| Rail-1U | サポートレール (1U) | (2xUnit) | *1 |
| Rail-1.5U | サポートレール (1.5U) | (2xUnit) | *1 |

注: *1 ... サポートレールを使用する場合のみプリント

サポートレールについて詳しくは、本ドキュメントの「サポートレールの使い方」をご覧ください。


## STEP 1 ナット埋め込み

必要なパーツのプリントが終わったら、"X Edge Top/Bottom" と "Y Edge" と "Z Edge 5U" を用意します。
これらにパネル取り付け用のM3ナットを埋め込みます。

<a href="image/m3nut-1.webp" target="_blank" rel="noopener noreferrer"><img src="image/m3nut-1.webp" width="480"></a>

マイナスドライバーや細い棒で奥まで押し込みます。

<a href="image/m3nut-2.webp" target="_blank" rel="noopener noreferrer"><img src="image/m3nut-2.webp" width="480"></a>


## STEP 2 底面の組み立て

底面部分を組み立てます。"X Edge Bottom" と "Y Edge" を組み合わせ、中に選択した "TB Panel xxxx" を入れます。パネル用の溝の向きに注意してください。位置の確認ができたら、M6ナットとM6ねじで固定します。ナットがきつい場合はペンチを使用してください。緩い場合は少量の接着剤を付けておくと便利です。

<a href="image/bottom-1.webp" target="_blank" rel="noopener noreferrer"><img src="image/bottom-1.webp" width="480"></a>

裏返して "Foot" を取り付けます。内側の穴は使用しません。

<a href="image/bottom-2.webp" target="_blank" rel="noopener noreferrer"><img src="image/bottom-2.webp" width="480"></a>


## STEP 3 屋根の組み立て

屋根部分を組み立てます。"X Edge Top" と "Y Edge" を組み合わせ、中に "TB Panel xxxx" を入れます。

<a href="image/top-1.webp" target="_blank" rel="noopener noreferrer"><img src="image/top-1.webp" width="480"></a>

組み立てたら "Handle" を取り付けます。


## STEP 4 サポートレール (optional)

サポートレールを使用しない場合は STEP 5 に進んでください。サポートレールを使用すると重いシェルフを支えることができます。サポートレールを使用する場合は、マウントレールを取り付ける前に加工が必要です。

### インサートナットの取り付け

"Z Edge 5U" と "Rail Holder-L 5U" と "Rail Holder-R 5U" にインサートナットを取り付けます。インサートナットを付けるのは小さいほうの穴です。

<a href="image/inut-1.webp" target="_blank" rel="noopener noreferrer"><img src="image/inut-1.webp" width="480"></a>

インサートナットのサイズ: ID 3mm, OD 5mm, Length 4mm

### 結合

"Z Edge 5U" に "Rail Holder-* 5U" を取り付けます。5mmのM3ねじで固定します。向きに注意してください。写真のように配置して、"▼"マークが書かれた部分を下にしてください。

<a href="image/inut-2.webp" target="_blank" rel="noopener noreferrer"><img src="image/inut-2.webp" width="480"></a>

完成写真。

<a href="image/inut-3.webp" target="_blank" rel="noopener noreferrer"><img src="image/inut-3.webp" width="480"></a>

M6ねじ穴が塞がれている場合は位置が逆ですので、写真のように配置して確認してください。


## STEP 5 組み立て

底面部分とマウントレール "Z Edge 5U" を、M6ねじ(12mm)で接続します。先にナットを入れて、マウントレールの位置を決めたらネジで固定します。

<a href="image/asm-1.webp" target="_blank" rel="noopener noreferrer"><img src="image/asm-1.webp" width="480"></a>

サポートレールを使用する場合は、"▼"マークが書かれた部分を下にしてください。サポートレールを使用しない場合は、上下の向きはどちらでもかまいません。

同様に屋根部分を取り付けます。

<a href="image/asm-2.webp" target="_blank" rel="noopener noreferrer"><img src="image/asm-2.webp" width="480"></a>


## STEP 6 サイドパネル (optional)

サイドパネルを使用する場合は、本体にM3ねじ(12mm)で固定します。

<a href="image/side-1.webp" target="_blank" rel="noopener noreferrer"><img src="image/side-1.webp" width="480"></a>

## 完成!

おめでとうございます！あなただけのサーバーラックが完成しました。

<a href="image/side-2.webp" target="_blank" rel="noopener noreferrer"><img src="image/side-2.webp" width="480"></a>

素敵な自宅鯖ライフをお楽しみください！


## ケージナットの固定方法

マウントレールにM6ナットを取り付けます。ナットは横方向から入れて指で押すと、カチッと穴に固定されます。

<a href="image/movie-1.webp" target="_blank" rel="noopener noreferrer"><img src="image/movie-1.webp" width="480"></a>

機器をM6ねじで固定するときは、ねじを強く押さないように注意してください。力を入れるとナットが外れます。


## 延長オプションの組み立て方法

ここでは例として、3Uを延長する手順を説明します。延長用プロファイルのパーツのプリントをします。"Extend Unit" にM3ナットを埋め込み、蓋をします。M6ナットも取り付けます。

<a href="image/ext-1.webp" target="_blank" rel="noopener noreferrer"><img src="image/ext-1.webp" width="480"></a>

屋根を外し、"Extend Unit" をマウントレールに取り付けます。向きを写真のようにしてください。

<a href="image/ext-2.webp" target="_blank" rel="noopener noreferrer"><img src="image/ext-2.webp" width="480"></a>

延長用のマウントレールを取り付けます。オプションのサポートレールを使用する場合は、先に取り付けておく必要があります。

<a href="image/ext-3.webp" target="_blank" rel="noopener noreferrer"><img src="image/ext-3.webp" width="480"></a>

最後に屋根を載せて完成です。

<a href="image/ext-4.webp" target="_blank" rel="noopener noreferrer"><img src="image/ext-4.webp" width="480"></a>

サイドパネルを使用する場合は、一番最後に取り付けます。

<a href="image/ext-5.webp" target="_blank" rel="noopener noreferrer"><img src="image/ext-5.webp" width="480"></a>


## サポートレールの使い方 (optional)

サポートレールのプリントは任意です。サポートレールを使用すると重いシェルフを支えることができますが、使用できるシェルフに制限があります。

### 使用可能なシェルフの条件

* 横幅: 215mm 以上
* 奥行: 90mm 以上

### シェルフの3Dモデル

以下の3Dモデルを配布しています。

* [各種テンプレート](../shelf/template/)
    （フロントパネルの部分が空です。ご自身で加工してご使用ください。）
* [5インチドライブ用](../shelf/5-inch_drive_1U/)

### サポートレールの固定方法

"Rail-1U" をM3ねじ(5mm)で固定します。1.5Uのシェルフを設置する場合は "Rail-1.5U" を使用します。

<a href="image/rail-1.webp" target="_blank" rel="noopener noreferrer"><img src="image/rail-1.webp" width="480"></a>

シェルフがサポートレールの上に乗るので、重い荷物が乗ってもマウントレールに負担がかかりません。

<a href="image/rail-2.webp" target="_blank" rel="noopener noreferrer"><img src="image/rail-2.webp" width="480"></a>

