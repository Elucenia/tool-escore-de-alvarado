<!-- ELUCENIA technical documentation · escore-de-alvarado · ja · no clinical/professional/rights approval -->

# Alvaradoスコア

[条件・出典・許諾](https://elucenia.org/ja/tools/escore-de-alvarado)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 右下腹部への疼痛移動

`migra`

### 食欲不振（または尿中アセトン）

`anorex`

### 悪心または嘔吐

`nausea`

### 右下腹部圧痛

`dor`

### 反跳痛（Blumberg徴候）

`desc`

### 体温 ≥ 37.3 °C

`febre`

### 白血球増多 \> 10000/mm³

`leuco`

### 左方移動（好中球 \> 75%）

`desvio`

## 方法の版

Alvarado 1986：MANTRELS 8項目、0–10、左方移動を含む

## 記載された計算式

MANTRELS：M痛み移動（1）、A食欲不振（1）、N悪心/嘔吐（1）、T右下腹圧痛（2）、R反跳痛（1）、E体温上昇（1）、L白血球増多（2）、S左方移動（1）。合計0～10。

## 限界・対象集団

Alvarado 1986は、虫垂炎を疑わせる腹痛で入院した305人の患者と、八つの臨床・検査因子から作成されました。原抄録は、異なる年齢層、妊婦、退院や画像検査の方針を自動的に妥当とするものではありません。判断の閾値と使用する版の対象集団は別途確認する必要があります。このツールは白血球の核左方移動を含む変法を実装しています。

## 参考文献

- [Alvarado A. A practical score for the early diagnosis of acute appendicitis. Ann Emerg Med, 1986.](https://doi.org/10.1016/S0196-0644(86)80993-3)

- [Di Saverio S et al. Diagnosis and treatment of acute appendicitis: 2020 update of the WSES Jerusalem guidelines. World J Emerg Surg, 2020.](https://doi.org/10.1186/s13017-020-00306-3)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

虫垂炎の可能性は低い（0から4）

他の原因を考慮する。症状が持続する場合は再評価する。


### 2

虫垂炎と一致（5から6）

経過観察と連続的再評価、または画像検査。


### 3

虫垂炎が疑われる（7から8）

外科的評価；患者のプロファイルに応じた画像検査。


### 4

虫垂炎の可能性が非常に高い（9～10）

外科的評価。

