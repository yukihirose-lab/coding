---
layout: mermaid
---

## README

### ページの構成

このウェブサイトでは
広瀬ゼミや「オンキャンパスジョブを活用した修学支援事業」
で扱われた勉強会の資料や外部で公開されている資料を
心理言語学の学生向けに体系化して公開していきます。
扱うトピックは (i) 統計 (ii) 実験 (iii) プログラミング の3つです。
例として、統計ではANOVAレベルから一般化線形混合モデル、
実験ではVWPやWeb実験の実施方法、
プログラミングでは一般知識やスクリプトの管理方法を公開します。

ウェブサイトの入り口であるこのページでは、
全体を俯瞰した[学習の手順](.#学習の手順)と、
このサイトへ[貢献する方法](.#貢献の方法)を記述します。
このサイトはオープンサイエンスやオープンソースと同じ
「自由なアクセス[[^free]]」をモットーにしているので、
資料作成や知識共有といった形でコミット
[[^commit]]していただける非常に助かります。

[^free]: お金がかからない、いつでもどこでもアクセスできる、
    著作権的に頒布できる、という意味での自由です。

[^commit]: GitHubを利用したページの公開が特色で、
    WordPressやサーバー、データベースなどの知識は編集に不要です。

### 学習の手順

#### 統計

以下に示すコンテンツは重複していますが、
複数の資料を読むと理解が深まる部分もあるので掲載しています。
`Prerequisites`列には資料を読む前に知っておいたほうがよい`Topic`を記載しており、
部分的に外部の資料を含みます。特にStep1と2はそれぞれ
[RStudio Education][rstudio-intro]で紹介されていた資料と、
統計の入門でよく使われている資料です。
統計も*p*値も聞いたことのない場合は1 、
Rに触れたことのない場合は2から始めると良いかと思います。

| Step | Title/URL                                        | Topic             | Prerequisites   |
|------|--------------------------------------------------|-----------------  |-----------------|
|    1 | [Getting Started with Data in R][r-rstudio]      | R                 | N/A             |
|    2 | [ハンバーガー統計学にようこそ！][hamburger]      | t検定, ANOVA      | N/A             |
|    3 | [(G)LMMの入門・実践的 ワークショップ][glmm-ws-m] | `glm`, Coding     | R, t検定, ANOVA |
|    4 | [Rと統計の入門, 線形モデル][intro-k]             | `lm`, `dataframe` | R               |
|    5 | [線形モデル -> 一般化線形モデル][lm2glm-k]       | `glm`             |                 |
|    6 | [一般化線形混合モデル][glm2lme-k]                | `lme`             |                 |
|    7 | [ベイズ統計(アヒル本)][ahiru]                    | TBA             | TBA               |

続いて発展編になります。
基本的な統計の手順を抑えた後、
少し凝った要因の設計にしたい、
あるいは分析の対象を時系列データに広げたい
場合に役立つかと思います。

| Step | Title/URL                          | Topic           | Prerequisites   |
|------|------------------------------------|-----------------|-----------------|
|    0 | [コーディング概要][contrastcoding] | TBA             | TBA             |
|    0 | [Factor Coding 詳細][factor-coding]| Coding          | Coding          |
|    0 | [Power Analysis][power-analysis]   | TBA             | TBA             |
|    0 | [VWPデータ分析][arai]              | TBA             | TBA             |
|    0 | 脳波データデータ分析(TBA)          | TBA             | TBA             |
|    0 | Permutation Analysis(TBA)          | TBA             | TBA             |
|    0 | [ggplotを用いた可視化][ggplot]     | TBA             | TBA             |
|    0 | 論文での報告手順(TBA)              | TBA             | TBA             |

今後全てをカバーできるとは限りませんが、
新学期が始まる頃をメドにアンケートなどを通じて優先順位をつけ、
特に統計の部分はチュートリアルを実施する予定です。
基礎編に関しては最低限のパッケージで実施できるようにします。

<!--
FIXME: 
- [ ] 脳波は陳さんの脳波祭
- [ ] Permutation Analysis
- [ ] Mermaidを使ったフローチャートの作成
-->
[ggplot]: https://ggplot2.tidyverse.org/reference/ggplot.html
[ahiru]: https://www.kyoritsu-pub.co.jp/bookdetail/9784320112421
[arai]: https://www.ism.ac.jp/editsec/toukei/pdf/64-2-201.pdf
[contrastcoding]: https://marissabarlaz.github.io/portfolio/contrastcoding/
[factor-coding]: https://github.com/CLRafaelR/factor_coding
[glmm-ws-m]: https://phiz.c.u-tokyo.ac.jp/~hiroselab/stats/0907.html
[power-analysis]: https://phiz.c.u-tokyo.ac.jp/~hiroselab/stats/220128_powerAnalysis_isono.html
[intro-k]: https://kishiyamat.github.io/tutorial-lme-vwp/1.html
[lm2glm-k]: https://kishiyamat.github.io/tutorial-lme-vwp/2.html
[glm2lme-k]: https://kishiyamat.github.io/tutorial-lme-vwp/3.html
[hamburger]: http://kogolab.chillout.jp/elearn/hamburger/
[rstudio-intro]: https://education.rstudio.com/
[r-rstudio]: https://moderndive.netlify.app/1-getting-started.html

<!--[統計](./stats)-->

<!--
```mermaid
graph TD;
```
-->


### 実験(TBA)

| Step | Title/URL                     | Topic           | Prerequisites   | 
|------|-------------------------------|-----------------|-----------------|
|    0 | VWP                           | na              | na              |
|    0 | 脳波                          | na              | na              |
|    0 | 音声                          | na              | na              |
|    0 | オンラインWeb実験             | TBA             | TBA             |
|    0 | オンラインWeb実験の公開       | TBA             | TBA             |

<!--[実験](./experiments)-->

### プログラミング(TBA)

| Step | Title/URL                       | Topic           | Prerequisites   | 
|------|---------------------------------|-----------------|-----------------|
|    0 | Gitを用いたスクリプト管理       | TBA             |     TBA         |
|    0 | 開発基礎（仮想環境、テスト、CI）| na              |     TBA         |
|    0 | 外部計算資源活用（AWS）         | na              |     TBA         |

<!--[プログラミング](./programming)-->

## 貢献の方法

ここでいう「貢献」というのは、
「みんなでアプリケーションを作ろうよ」
というオープンソースの精神に基づいています。
ここではアプリケーションではなく、
研究に必要な資料をみんなで作ることを目的としています。
オープンにプロジェクトをすすめるのは
アプリだけでなく書籍（技術書や小説）や研究の文脈の
文脈でも活発になってきています。

しかしながら、みんなで編集して公開するというのは
言うほど簡単ではありません。
同時に、Google DocsやDriveに資料を配置してしまっては
変な変更が入ってしまうリスクがあります。
他方、そのリスクを減らそうとすると
編集できる権限を絞る必要がでてきて、
こんどは「みんなで」の部分が損なわれます[[^trade]]。

[^trade]: ここらへんは情報セキュリティの
    機密性--完全性--可用性トレードオフですね。

この問題に対してソフトウェア開発はかなり有効な手段を持っていて、
それがGitを用いた分散バージョン管理です。
Gitを使ってもらうのは学習コストが高い気もするのですが、
WordPressなどの学習コストに比べれば微々たるものだと思います。
もし協力していただける場合、
[こちらのサイト](https://github.com/firstcontributions/first-contributions)を参考にし、
`index.md` にあなたの名前を追加するところから
初めていただけると嬉しいです。

## Acknowledgement

- 東大オンキャンパスジョブ

## Contributors

- 岸山健
- YourName


### 脚注
---

