

# ファイル

### assets/scss

```sh
.
├── breakpoints.scss
├── custom.scss
├── external
│   └── normalize.scss
├── general.scss
├── grid.scss
├── partials
│   ├── article.scss
│   ├── base.scss
│   ├── comments
│   │   └── disqusjs.scss
│   ├── footer.scss
│   ├── highlight
│   │   ├── common.scss
│   │   ├── dark.scss
│   │   └── light.scss
│   ├── layout
│   │   ├── 404.scss
│   │   ├── article.scss
│   │   ├── list.scss
│   │   └── search.scss
│   ├── menu.scss
│   ├── pagination.scss
│   ├── sidebar.scss
│   └── widgets.scss
├── style.scss
└── variables.scss        # 変数
```

### assets/ts

```sh
.
├── color.ts
├── colorScheme.ts
├── createElement.ts
├── gallery.ts
├── main.ts
├── menu.ts
├── scrollspy.ts       # スクロールスパイの実装 (スクロール部分に応じてTOCを太文字にする)
├── search.tsx
└── smoothAnchors.ts
```


### assets/scss/variables.scss

```
--tag-border-radius: 100px;
--section-separation: 50px;
```


### mixin

## ブレークポイント

画面幅に合わせてCSSを切り替えることで各デバイスに適したwebサイトを作るのが通例で、ここでは

```
breakpoints.css
```

でブレークポイントと mixin が定義されている。この mixin を使用することで画面幅に応じて設定値（ex.フォントサイズ）を変更することができる。