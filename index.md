---
layout: mermaid
---

## ページの構成

このウェブサイトでは広瀬ゼミで扱われた勉強会の資料のうち、
許可が得られたものを体系化して公開していきます。
扱うトピックは (i) 統計 (ii) 実験 (iii) コーディング の3つです。
例として、統計ではANOVAレベルから一般化線形モデル、
実験ではVWPやWeb実験、
コーディングでは一般知識や管理方法を公開します。

このページでは全体を俯瞰した学習の手順と、
このウェブサイトへ貢献する方法を記述します。
基本的にはオープンサイエンスやオープンソースと同じ
自由なアクセスをモットーにしているので、
積極的なコミットをいただけると助かります。

## 学習の手順

### 統計

内容は重複していますが、複数の資料を読むと理解が深まる部分もあるので掲載しています。
`Prerequisites` には資料を読む前に知っておいたほうがよい事前知識を記載しており、
部分的に外部の資料を含みます。特にStep1と2はそれぞれ
[RStudio Education][rstudio-intro]で紹介されていた資料と、
統計の入門でよく使われている資料です。

| Step | Title/URL                                        | Topic           | Prerequisites   | 
|------|--------------------------------------------------|-----------------|-----------------|
|    1 | [Getting Started with Data in R][r-rstudio]      | t検定, ANOVA    | N/A             |
|    2 | [ハンバーガー統計学にようこそ！][hamburger]      | t検定, ANOVA    | N/A             |
|    3 | [(G)LMMの入門・実践的 ワークショップ][glmm-ws-m] | R, lm, glm      | R, t検定, ANOVA |
|    4 | [Rと統計の入門, 線形モデル][intro-k]             | R, lm, 言語学   | R               |
|    5 | [線形モデル -> 一般化線形モデル][lm2glm-k]       | R, glm          |                 |
|    6 | [一般化線形混合モデル][glm2lme-k]                | R, glm, lme     |                 |
|    7 | [Power Analysis][power-analysis]                 | power analysis  | LME             |

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

<!--[実験](./experiments)-->

### コーディング(TBA)

<!--[コーディング](./coding)-->

## 貢献する方法

### 資料作成

よしなに

### 資料追加(ウェブサイト)

- markdown
- htmlはhiroselabのサーバーに配置

### 手順の更新(ウェブサイト)

https://mermaid.live

## 補足

### なぜ GitHub Pagesか

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

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

itemize

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

num

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

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

