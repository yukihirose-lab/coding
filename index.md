---
layout: mermaid
---

## ページの構成

このウェブサイトでは
広瀬ゼミで扱われた勉強会の資料や外部で公開されている資料を
心理言語学の学生向けに体系化して公開していきます。
扱うトピックは (i) 統計 (ii) 実験 (iii) コーディング の3つです。
例として、統計ではANOVAレベルから一般化線形混合モデル、
実験ではVWPやWeb実験の実施方法、
コーディングでは一般知識や時代にあった管理方法を公開します。

ウェブサイトの入り口であるこのページでは、
全体を俯瞰した学習の手順と、
このサイトへ貢献する方法を記述します。
基本的にはオープンサイエンスやオープンソースと同じ
「自由なアクセス[^free]」をモットーにしており、
資料作成や共有といったコミットをいただけると助かります。

[^free]: お金がかからない、いつでもどこでもアクセスできる、
    著作権的に頒布できる、という意味での自由です。

## 学習の手順

### 統計

内容は重複していますが、複数の資料を読むと理解が深まる部分もあるので掲載しています。
`Prerequisites`列には資料を読む前に知っておいたほうがよい事前知識`Topic`を記載しており、
部分的に外部の資料を含みます。特にStep1と2はそれぞれ
[RStudio Education][rstudio-intro]で紹介されていた資料と、
統計の入門でよく使われている資料です。
また `Open`列はアクセス権限が不要なら True, 必要なら False の値になっています。

| Step | Title/URL                                        | Topic           | Prerequisites   | Open | 
|------|--------------------------------------------------|-----------------|-----------------|------|
|    1 | [Getting Started with Data in R][r-rstudio]      | R               | N/A             | True |
|    2 | [ハンバーガー統計学にようこそ！][hamburger]      | t検定, ANOVA    | N/A             | True |
|    3 | [(G)LMMの入門・実践的 ワークショップ][glmm-ws-m] | R, lm, glm      | R, t検定, ANOVA | True |
|    4 | [Rと統計の入門, 線形モデル][intro-k]             | R, lm, 言語学   | R               | True |
|    5 | [線形モデル -> 一般化線形モデル][lm2glm-k]       | R, glm          |                 | True |
|    6 | [一般化線形混合モデル][glm2lme-k]                | R, glm, lme     |                 | True |
|    7 | [Power Analysis][power-analysis]                 | power analysis  | LME             | True |
|    8 | ggplotを用いた可視化(TBA)                        | paper           | stats           | True |
|    9 | 論文へのまとめ方(TBA)                            | paper           | stats           | True |

[glmm-ws-m]: https://phiz.c.u-tokyo.ac.jp/~hiroselab/stats/0907.html
[power-analysis]: https://phiz.c.u-tokyo.ac.jp/~hiroselab/stats/220128_powerAnalysis_isono.html
[intro-k]: https://kishiyamat.github.io/tutorial-lme-vwp/1.html
[lm2glm-k]: https://kishiyamat.github.io/tutorial-lme-vwp/2.html
[glm2lme-k]: https://kishiyamat.github.io/tutorial-lme-vwp/3.html
[hamburger]: http://kogolab.chillout.jp/elearn/hamburger/
[rstudio-intro]: https://education.rstudio.com/
[r-rstudio]: https://moderndive.netlify.app/1-getting-started.html

* TODO
    * 資料の追加
        * 統計(優先度+++)
            * ggplotや論文周りはすでにあるので外部リンクを利用
        * 実験(優先度++)
        * コーディング(優先度+)

具体的な学習の手順は以下の通りになります。

* TODO
    * フローチャートの作成
    * 各ステップでの補足
        * 資料の種類
        * 進め方
        * より細かい資料

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

<!--[統計](./stats).-->

### 実験(TBA)

<!--[実験](./experiments)-->
| Step | Title/URL | Topic           | Prerequisites   | 
|------|-----------|-----------------|-----------------|
|    0 | na        | na              | na             |

### コーディング(TBA)

<!--[コーディング](./coding)-->
| Step | Title/URL | Topic           | Prerequisites   | 
|------|-----------|-----------------|-----------------|
|    0 | na        | na              | na             |

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

### なぜ GitHub Pages?

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

