# Last of kokaton

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
主人公が敵を倒すことでスコアを獲得しながら、一定のスコアで次のステージに移行。3面クリアすることでゲームクリア。ステージを移行するたびに南下していくように設定。

## ゲームの実装
### 共通基本機能
* 背景画像と主人公キャラクターの描画
* 主人公キャラの攻撃手段の描画
* 敵機と敵機の攻撃手段の描画
* 敵機と敵機の攻撃手段と主人公キャラの攻撃手段の衝突時の爆発の描画
* スコアの増加についての設定と描画
* 主人公キャラの指定キー押した場合に移動速度増加
* スコア消費によって特殊機能発生
* スコア200消費で画面全体に重力場設置
* スコア20消費で発動時に存在する鉄器と爆弾の無効化
* スコア100消費で無敵化

### 担当追加機能
* BGM・SE（担当：おがわ）：全体のBGMと効果音を付与する機能
* ゲームオーバー画面・ゲームクリア画面（担当：なかさわ）：ゲームオーバーとゲームクリア時の画面表示設定
* 制限時間設定（担当：やまぐち）：ゲームオーバーまでの制限時間の設定
* ステージ2作成（担当：こきた）： 
* ステージ3作成（担当：みぞぐち）：　

### ToDo
。
### メモ

