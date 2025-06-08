## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能

エンドポイント：https://zipcloud.ibsnet.co.jp/api/search

機能: 指定された郵便番号に基づいて住所情報を検索し、その結果を返すAPI。
* リクエストとレスポンスのフォーマット

パラメータ: zipcode

URL例：GET https://zipcloud.ibsnet.co.jp/api/search?zipcode=1000002

レスポンス：JSON形式

{ "message": null, "results": [ { "address1": "東京都", "address2": "千代田区", "address3": "皇居外苑", "kana1": "ﾄｳｷｮｳﾄ", "kana2": "ﾁﾖﾀﾞｸ", "kana3": "ｺｳｷｮｶﾞｲｴﾝ", "prefcode": "13", "zipcode": "1000002" } ], "status": 200 }
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL

APIの名称：Cat Facts API

参照URL：https://catfact.ninja/fact
* エンドポイントと機能

エンドポイント：https://catfact.ninja/fact

機能：取得ボタンを押すと、猫の豆知識を一つ表示するAPI。
* リクエストとレスポンスのフォーマット

レスポンス：JSON方式

表示例：There is a species of cat smaller than the average housecat. It is native to Africa and it is the Black-footed cat (Felis nigripes). Its top weight is 5.5 pounds.
### Q3-3. 感想
* 今回の課題で苦労したこと
* 
　WedAPIの結果を表示することで、コードが少し違えばテキストに反映されなかったりと大変だった。
* 演習を通して理解できたこと
* 
　WebAPIの基本的な使い方を理解した。
* Web APIの利便性や課題など
  
 利便性：開発する際にコストがかからなくて済む、既存の機能やデータを再利用できるので、開発が楽になる。
 
 課題：APIの仕様変更や提供終了のリスク、利用制限など、問題点が多い。
