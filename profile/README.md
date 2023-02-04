# 日本の城API プロジェクト
![banner](/profile/banner.png)

### 日本の城をAPI化することを目標としています!

## 城郭データストア
[城郭データストア(城郭まとめサイト)](https://castle-datastore.vercel.app/)

## 日本の城 API
日本の城をJSON形式でまとめてます。目標は1000城!!  
助っ人求む `情報提供` `プルリク` `Issues` 是非お願いします  

- [JP-CastleAPI app](https://github.com/castle-api-project/castle-api-app/releases)
- [JP-CastleAPI app(ブラウザ版)](https://castle-api-app.vercel.app/)
- [GitHub](https://github.com/castle-api-project/jp-castle-api)

### サンプルデータ
```json
{
  "name": "名古屋城",
  "alias": ["金鯱城", "金城", "柳城", "亀屋城", "蓬左城"],
  "build": 1619,
  "castle_tower": {
    "structure": [5, 5],
    "condition": "復元",
  },
  "scale": 5,
  "type": "平城",
  "latlng": [35.18551, 136.89923],
  "place": {
    "prefecture": "愛知県",
    "area": "尾張",
    "city": "名古屋市中区",
    "address": "愛知県名古屋市中区本丸1-1",
  },
  "remains": ["堀", "土塁", "石垣", "曲輪", "虎口", "井戸", "櫓", "庭園"],
  "restorations": ["天守閣", "門", "塀"],
  "categories": ["重要文化財", "特別史跡", "百名城", "三大名城"],
  "site": "https://www.nagoyajo.city.nagoya.jp",
},
```
