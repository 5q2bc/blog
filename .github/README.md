Zolaを利用した静的サイト

構造は以下の通り

.
├── config.toml -> Zolaのメイン設定ファイル  
├── content -> Markdown形式のコンテンツ  
│   ├── _index.en.md -> 英語のトップページ  
│   ├── _index.md -> 日本語のトップページ  
│   ├── about.md -> 自己紹介ページ  
│   └── blog -> ブログ記事  
│       ├── ... (omitted) ...  
│       └── _index.md -> ブログのトップページ  
├── scripts -> 自動化用のスクリプト  
│   └── format_md.sh -> Markdownをフォーマットするスクリプト  
├── static -> CSS, JS, 画像などの静的ファイル  
│   ├── click.ogg -> クリック音  
│   ├── css -> スタイルシート  
│   │   └── style.css -> メインのスタイルシート  
│   ├── icons.svg -> アイコン  
│   ├── js -> JavaScript  
│   │   ├── anchor-link.js -> アンカーリンク用のスクリプト  
│   │   └── script.js -> 汎用スクリプト  
│   ├── logo.png -> サイトのロゴ  
│   └── syntax_themes -> シンタックスハイライトのテーマ  
│       └── Dimmed_Monokai.tmTheme -> Dimmed Monokaiテーマ  
└── templates -> コンテンツをレンダリングするためのHTMLテンプレート  
    ├── 404.html -> 404エラーページ  
    ├── atom.xml -> Atomフィード  
    ├── base.html -> ベースとなるHTML  
    ├── blog -> ブログ用のテンプレート  
    │   ├── page.html -> ブログの個別記事ページ  
    │   └── section.html -> ブログのセクションページ  
    ├── footer.html -> フッター  
    ├── index.html -> トップページ  
    ├── page.html -> 固定ページ  
    ├── partials -> 再利用可能なテンプレート部品  
    │   ├── content-listing-item.html -> コンテンツ一覧のアイテム  
    │   ├── pagination.html -> ページネーション  
    │   ├── schema-article.html -> 構造化データ (Article)  
    │   └── share-links.html -> SNSシェアリンク  
    ├── section.html -> セクションページ  
    ├── shortcodes -> Markdown中で使えるショートコード  
    │   ├── img.html -> 画像表示  
    │   ├── mark.html -> マーカー表示  
    │   ├── webring.html -> Webring  
    │   └── youtube.html -> YouTube埋め込み  
    ├── sitemap.xml -> サイトマップ  
    └── tags -> タグ用のテンプレート  
        ├── list.html -> タグ一覧ページ  
        └── single.html -> 個別のタグページ  