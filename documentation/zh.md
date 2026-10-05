<!-- ELUCENIA technical documentation · escore-de-alvarado · zh · no clinical/professional/rights approval -->

# Alvarado 评分

[条件、来源与许可](https://elucenia.org/zh/tools/escore-de-alvarado)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 疼痛迁移至右髂窝

`migra`

### 食欲减退（或尿中丙酮）

`anorex`

### 恶心或呕吐

`nausea`

### 右髂窝压痛

`dor`

### 反跳痛（Blumberg 征）

`desc`

### 体温 ≥ 37.3 °C

`febre`

### 白细胞增多 \> 10000/mm³

`leuco`

### 核左移（中性粒细胞 \> 75%）

`desvio`

## 方法版本

Alvarado 1986：MANTRELS 8项、0–10；含核左移版

## 已记录的公式

MANTRELS：M疼痛转移（1）、A食欲不振（1）、N恶心/呕吐（1）、T右髂窝压痛（2）、R反跳痛（1）、E体温升高（1）、L白细胞增多（2）、S核左移（1）。总分0至10。

## 限制与适用人群

Alvarado 1986基于305名因提示阑尾炎的腹痛住院的患者和八项临床或实验室因素制定。原始摘要并不自动验证不同年龄组、孕妇或出院及影像策略。决策阈值和所用版本的人群须分别核对；本工具实现的是包含白细胞核左移的变体。

## 参考文献

- [Alvarado A. A practical score for the early diagnosis of acute appendicitis. Ann Emerg Med, 1986.](https://doi.org/10.1016/S0196-0644(86)80993-3)

- [Di Saverio S et al. Diagnosis and treatment of acute appendicitis: 2020 update of the WSES Jerusalem guidelines. World J Emerg Surg, 2020.](https://doi.org/10.1186/s13017-020-00306-3)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
