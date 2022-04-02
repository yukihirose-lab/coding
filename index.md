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
プログラミングでは一般知識や時代にあった管理方法を公開します。

ウェブサイトの入り口であるこのページでは、
全体を俯瞰した学習の手順と、
このサイトへ貢献する方法を記述します。
基本的にはオープンサイエンスやオープンソースと同じ
「自由なアクセス[^free]」をモットーにしており、
資料作成や共有といったコミットをいただけると助かります。
GitHubを利用したページの公開が特色で、
WordPressやサーバー、データベースなどの知識は
編集に不要です。


[^free]: お金がかからない、いつでもどこでもアクセスできる、
    著作権的に頒布できる、という意味での自由です。

### 学習の手順

#### 統計

内容は重複していますが、複数の資料を読むと理解が深まる部分もあるので掲載しています。
`Prerequisites`列には資料を読む前に知っておいたほうがよい`Topic`を記載しており、
部分的に外部の資料を含みます。特にStep1と2はそれぞれ
[RStudio Education][rstudio-intro]で紹介されていた資料と、
統計の入門でよく使われている資料です。
また `Open`列はアクセス権限が不要なら True, 必要なら False の値になっています。
以下は基礎編になります。


| Step | Title/URL                                        | Topic             | Prerequisites   | Open | 
|------|--------------------------------------------------|-----------------  |-----------------|------|
|    1 | [Getting Started with Data in R][r-rstudio]      | R                 | N/A             | True |
|    2 | [ハンバーガー統計学にようこそ！][hamburger]      | t検定, ANOVA      | N/A             | True |
|    3 | [(G)LMMの入門・実践的 ワークショップ][glmm-ws-m] | `glm`, Coding     | R, t検定, ANOVA | True |
|    4 | [Rと統計の入門, 線形モデル][intro-k]             | `lm`, `dataframe` | R               | True |
|    5 | [線形モデル -> 一般化線形モデル][lm2glm-k]       | `glm`             |                 | True |
|    6 | [一般化線形混合モデル][glm2lme-k]                | `lme`             |                 | True |
|    7 | [ベイズ統計(アヒル本)][ahiru]                    | TBA             | TBA             | True |

続いて発展編になります。

| Step | Title/URL                          | Topic           | Prerequisites   | Open | 
|------|------------------------------------|-----------------|-----------------|------|
|    0 | [コーディング概要][contrastcoding] | TBA             | TBA             | True |
|    0 | [Factor Coding 詳細][factor-coding]| Coding          | Coding          | True |
|    0 | [Power Analysis][power-analysis]   | TBA             | TBA             | True |
|    0 | [VWPデータ分析][arai]              | TBA             | TBA             | True |
|    0 | 脳波データデータ分析(TBA)          | TBA             | TBA             | True |
|    0 | Permutation Analysis(TBA)          | TBA             | TBA             | True |
|    0 | [ggplotを用いた可視化][ggplot]     | TBA             | TBA             | True |
|    0 | 論文での報告手順(TBA)              | TBA             | TBA             | True |
|    0 | オンラインWeb実験(TBA)             | TBA             | TBA             | True |
|    0 | Gitを用いたスクリプト管理(TBA)     | TBA             | TBA             | True |

今後全てをカバーできるとは限りませんが、
新学期が始まる頃をメドにアンケートなどを通じて優先順位をつけ、
特に統計の部分はチュートリアルを実施する予定です。
基礎編に関しては最低限のパッケージで実施できるようにします。

<!--
FIXME: 
- [ ] 脳波は陳さんの脳波祭
- [ ] Permutation Analysis
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

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

<!--[統計](./stats).-->

### 実験(TBA)

| Step | Title/URL | Topic           | Prerequisites   | 
|------|-----------|-----------------|-----------------|
|    0 | VWP       | na              | na              |
|    0 | 脳波      | na              | na              |

<!--[実験](./experiments)-->

### プログラミング(TBA)

| Step | Title/URL  | Topic           | Prerequisites   | 
|------|------------|-----------------|-----------------|
|    0 | Git/GitHub | na              | na              |
|    0 | linter     | na              | na              |
|    0 | renv       | na              | na              |
|    0 | test       | na              | na              |
|    0 | AWS        | na              | na              |
|    0 | Python     | na              | na              |

<!--[プログラミング](./programming)-->

## 貢献する方法

### 資料作成

よしなに

### 資料追加(ウェブサイト)

- markdown
- htmlはhiroselabのサーバーに配置

### 手順の更新(ウェブサイト)

https://mermaid.live

## 謝辞

- 提供者
- 東大

## 補足

### 協力の仕方

なぜ GitHub Pages?

- Google Docs -> 資料に制限がある(動画や音源が使いづらい)
- WordPress -> 管理面倒&使いづらい
- GitHub Pages
    - Gitが必要になるがオープンサイエンスの時代では
      誰もが使えるようになるはずなので、
      実質学習コストはゼロ
    - 色々な記法が使える
    - 各所の学会やブログで採用実績あり

Mermaid

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

code

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

table

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

nested list

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

images

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

