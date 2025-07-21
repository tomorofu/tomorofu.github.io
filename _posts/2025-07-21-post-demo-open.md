---
title: "デモページ完成"

header:
  image: /assets/images/demo-open/demokansei.png
  # caption: "東大の赤門"

share: false

categories:
  - Blog
tags:

toc: true
toc_sticky: true
---

制作物を試すことができるページを作りました．


## 構造

ディレクトリ名は"_demos"

パーマリンクは”/demos/”

となっていて，その下にプロジェクトがあります．

---

## 難しかった

Jekyllの仕様の中でやりたい事をするのにつまずきました．

結局フロントマターに適切なメタデータをつけることが大事だったみたいです．

- ヘッダーとかをそのまま使いたい時は`layout: single`

```
---
title: 2Dゲームプレイ
layout: single
author_profile: true
permalink: /demos/2Dgame/
---
```

- htmlで自由にレイアウトしたい時は`layout: none`

```
---
title: ARカメラ起動
layout: none
permalink: /demos/ar/
---
```

---

## まとめ

何とか出来上がってよかった！