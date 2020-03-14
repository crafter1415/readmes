# TUSB オフライン経験値パッチ v2  

TUSB v12で遠くのプレイヤー/オフラインのプレイヤーにも経験値が入るようにするパッチです

### 使用方法

以下のページにあるコマンドをコピーし、  
コマンドブロックから実行してください。  

https://pastebin.com/hqfdV4KG

### カスタム倍率

本パッチでは、以下のプレイヤーのExpMultiスコアを調整することで経験値の倍率を指定できます:  
 - #NormalPlayer
 - #FarPlayer
 - #OfflinePlayer
 - #Default
倍率は#Defaultを1としたときのそれぞれの倍率で計算されます。
デフォルト設定だと半径50m以内にいれば100%、  
遠い場合50%、オフラインの場合25%の経験値が入ります。  

### スペシャルサンクス

デバッグ協力: tomosan142

### 問題があった場合

DiscordかTwitterのDMまでお願いします。  
Discord: mkm75#1764
Twitter: @crafter1415