
# 定期テスト集計プログラム

1学年分の定期テストの結果を集計するプログラムを開発します。

このプログラムの要件は下記です。上から順番に優先度が高いです。標準出力で結果を表示してください。3はできていなくても構いません。

1. 全生徒の平均を表示する
2. 全生徒の順位表を表示する(順位,氏名,合計点数で生徒数分の行数表示)
3. 与えられた生徒名の明細(氏名,合計点数,順位,偏差値など)を表示する

生徒数は分かりません。どんな生徒数でも動作するように心がけてください。

## ステップ1

1生徒のテスト結果を表現する`TestResult`インターフェイスを定義してください。

- `getName`
  - 受験者の名前を返す(returnする)メソッド
- `getTotalScore`
  - 全科目の合計点数を計算して返すメソッド

## ステップ2

`TestResult`インターフェイスを実装した中間テストを表現する`MidTermResult`クラスを定義してください。

受験科目は国数英の3科目とします。

## ステップ3

中間テストの結果を集計するプログラムを実装してください。`MidTermResult`インスタンスの配列作成はべた書きで構いません。

## ステップ4

`TestResult`インターフェイスを実装した期末テストを表現する`EndTermResult`クラスを定義してください。

受験科目は国社数理英の5科目とします。

## ステップ5

期末テストの結果を集計するプログラムを実装してください。`EndTermResult`インスタンスの配列作成はべた書きで構いません。
