Zolaを利用した静的サイト

構造は以下の通り

.  
├── README.md  
├── config.toml  
├── content  
│   ├── _index.en.md  
│   ├── _index.md  
│   ├── about.md  
│   └── blog  
│       ├── Blog記事.md  
│       ├── _index.md  
├── static  
│   ├── click.ogg  
│   ├── css  
│   │   └── style.css  
│   ├── favicon.ico  
│   ├── icons.svg  
│   └── js  
│       └── script.js  
└── templates  
    ├── 404.html  
    ├── atom.xml  
    ├── base.html  
    ├── blog  
    │   ├── page.html  
    │   └── section.html  
    ├── footer.html  
    ├── index.html  
    ├── page.html  
    ├── partials  
    │   ├── content-listing-item.html  
    │   ├── pagination.html  
    │   └── schema-article.html  
    ├── section.html  
    ├── shortcodes  
    │   ├── img.html  
    │   ├── mark.html  
    │   ├── webring.html  
    │   └── youtube.html  
    ├── sitemap.xml  
    └── tags  
        ├── list.html  
        └── single.html  