# OpenCHJ-Torahiro
OpenCHJ版「虎寛本狂言集」形態論情報データ

国立国語研究所・「[オープンCHJ](https://chunagon.ninjal.ac.jp/open-chj/)」で公開されている「虎寛本狂言集」の形態論情報のデータです。

大蔵流狂言台本「虎寛本」（通称「虎寛本狂言集」）は、大蔵弥右衛門虎寛［1758-1805］による寛政4［1792］写の狂言台本です。台本の整理を経た本文は現行曲のものに近く、一般に近世中期頃の言語を反映すると考えられます。
同じ大蔵流台本「虎明本」（1642写、CHJ『室町時代編Ⅰ狂言』で検索可）との比較によって、室町末期から近世にかけての言語変化を窺い知ることができる点においても有用性のある資料です。

本データの構築の詳細については、北﨑・渡辺・村山（2025）（[PDF](https://researchmap.jp/ufo/presentations/51540876)）をご参照ください。

## 底本

笹野堅（校訂）（1942-1945）『能狂言: 大蔵虎寛本 上・中・下』岩波書店.

国会図書館デジタルライブラリーでも原本画像の確認が可能です。

- 上: https://dl.ndl.go.jp/pid/1129307
- 中: https://dl.ndl.go.jp/pid/1129318
- 下: https://dl.ndl.go.jp/pid/1129331

## ファイル形式
- UTF-8 (BOMなし) LF改行, タブ区切り
- フィールド（左から）
  - ファイル名（作者 作品名）
  - サブコーパス名
  - 開始文字位置（ファイル頭からのオフセット値*10）
  - 終了文字位置（同上）
  - 文境界（B=文頭）
  - 書字形出現形（=キー, 表層形）
  - 語彙素
  - 語彙素読み
  - 品詞
  - 活用型
  - 活用形
  - 発音形
  - 語種

## 開発者（公開当時）

- 北﨑勇帆（大阪大学, [URL](https://researchmap.jp/ufo)）
- 渡辺由貴（常葉大学, [URL](https://researchmap.jp/ywatanabe)）
- 村山実和子（日本女子大学, [URL](https://researchmap.jp/mmurayama)）
- 小木曽智信（国立国語研究所, [URL](https://researchmap.jp/togiso)）

## ライセンス

- [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## データサンプル
〓〓

## Acknowledgement
- 本コーパスは以下のプロジェクトの成果の一部です。
  - JSPS科研費[JP23K12192](https://kaken.nii.ac.jp/grant/KAKENHI-PROJECT-23K12192), [JP23K00564](https://kaken.nii.ac.jp/grant/KAKENHI-PROJECT-23K00564/), [JP25K04134](https://kaken.nii.ac.jp/grant/KAKENHI-PROJECT-25K04134/)
  - [国立国語研究所共同研究プロジェクト「開かれた共同構築環境による通時コーパスの拡張」](https://www.ninjal.ac.jp/research/cr-project/project-4/diachronic-corpus/)
- 本コーパスの構築に関わる研究発表は以下の通りです。
  - 北﨑勇帆、渡辺由貴、村山実和子「OpenCHJ「虎寛本狂言集」の公開に向けて」「通時コーパス」シンポジウム2026（2026/3/7）
  - 北﨑勇帆、渡辺由貴、村山実和子「大蔵流狂言台本『虎寛本』コーパスの構築とOpenCHJでの公開」日本語学会2025年度秋季大会（ワークショップ 通時コーパスをひらく―『日本語歴史コーパス』と『OpenCHJ』―）（2025/10/26, [PDF](https://researchmap.jp/ufo/presentations/51540876)）
  - 北﨑勇帆、渡辺由貴、村山実和子「『虎寛本』狂言台本のコーパス化試論」「通時コーパスの構築と日本語史研究の新展開」研究発表会（2018/6/9）
