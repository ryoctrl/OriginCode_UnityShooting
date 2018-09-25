# OriginCode UnityShooting

https://app.aniplex.co.jp/fatehf/game.html
OriginCodeの横スクロールゲー by Unity

[RUN RUN LANCER](https://app.aniplex.co.jp/fatehf/)を目標に

## 目標

10月末のbucchaさんの休み日に成果物確認ができること

## 要件定義

目標としては上記のRUN RUN LANCERと同等のもの。

- キャラクターが自動移動
    - 時間経過若しくはスコア依存で移動速度が向上する
- プレイヤーの入力
    - 十字キー
        - ↑　ジャンプ
        - →  攻撃（長押し: ブーメラン的な攻撃)
        - ←　スピードアップ
        - ↓  スライディング(画像なし)
    - ESC 終了
- ランダムな障害物若しくは落とし穴

- スコアシステム
- ゴール位置生成
- 制限時間システム

### その他要件
- 体力
- 攻撃力
- 移動速度

を後々にゲームシステムに組み込みたい。

## 設計

1. キャラクターオブジェクトを