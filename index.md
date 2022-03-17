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

[統計](./stats).
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

### 実験

[実験](./experiments).
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

### コーディング

[コーディング](./coding).
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## 貢献する方法

### 資料作成

よしなに

### 資料追加(ウェブサイト)

markdown

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

