# AviutlScript

## 目次
* 破砕Aシリーズ
    * 含まれている機能
    * 各パラメータの説明
        * 移動距離
        * 分割数
        * 余剰部分
        * 進行度
        * 間隔

## 破砕Aシリーズ
　このスクリプトはオブジェクトを分割し、砕けたような演出を行うスクリプトです。

### 含まれている機能
* **ランダムに砕ける演出（ランダム、または領域内ランダム拡散）**
    * リリースはv1からv2まであります。継続開発中です。
* **特定位置を軸に砕ける演出（クリップ座標指定）**
    * リリースはv1まであります。継続開発は検討中です。
* **任意の時間でオブジェクトがひび割れながら揺れる演出（揺れ文字）**
    * リリースはv1からv2まであります。継続開発中です。

### 各パラメータの説明
#### 共通
##### 移動距離
* **砕けて飛び散る距離を調整します。**
    * 単位は **ピクセル** です。
##### 分割数
* **分割する回数を指定します。**
    * v2時点では、8回程度が安全かと思われます。
    今後のアップデートで速度改善をした際に条件の緩和を検討しています。
##### 余剰部分
* **分割時にそれぞれのパーツが重複して重なるエリアの大きさを指定します。**
    * 単位は **ピクセル** です。

#### ランダムに砕ける演出（ランダムまたは領域内ランダム拡散）
##### 進行度
* **指定した移動距離をさらにパーセントで指定します。**
    * より細かく動かしたい際にご利用ください。

#### 任意の時間でオブジェクトがひび割れながら揺れる演出（揺れ文字）
##### 間隔
* **破砕エフェクトの切り替え時間を指定します。**

#### 