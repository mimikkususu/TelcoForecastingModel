<div align = "center" >

  ![header](https://capsule-render.vercel.app/api?type=rounded&height=300&color=gradient&text=TelcoForecastingModel)

</div>

### 通信会社のデータを使った予測モデル
アメリカのとある通信会社のデータを使い、通信会社と契約した人が解約するかどうかを予測する学習モデルを作りました。

#### 使用したモデル
- サポートベクターマシン
- ニューラルネットワークモデル(MLPC)
- k-means法
- lightBGM

#### やったこと
- 主成分分析
- エルボー法
- クロスバリデーション
- アウトライヤー削除
- ターゲットエンコーディング
- ラベルエンコーディング
- ワンホットエンコーディング
- KNNimputer

#### 精度
| `モデル`                | `accuracy` | `recall` | `precision` |
|:--------------------:|:--------:|:------:|:---------:|
| サポートベクターマシン |   0.595  |  0.62  |    0.59   |
| ニューラルネットワークモデル |   0.61   |  0.61  |    0.61   |
| lightBGM            |   0.69   |  0.7   |    0.69   |
