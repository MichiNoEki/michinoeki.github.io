# ヘルプの作り方

GitHub上で新しくページを作ったり編集したりできます

## 作り方

直接HTMLをつくってもいいけど、タグとか書くのが大変なのでマークダウンで書く方法にします

1. このツールにMarkdown書くと、HTMLに変換してくれる
   * https://yosiakatsuki.github.io/markdown-blog-editor/
   * 見出しは `#` か `##` のどちらかを使うの推奨
   
2. 変換して吐かれたHTMLの先頭に以下のCSSを貼る

```html
<head>
<link rel="stylesheet" type="text/css" href="../style.css">
</head>
```

3. ヘルプページ以下のディレクトリに、`好きな名前.html`（これがページ名になる）で作って、HTMLを貼って保存
   * ヘルプページ以下のディレクトリ→ https://github.com/MichiNoEki/michinoeki.github.io/tree/master/helps
   
これでOK。`https://michinoeki.github.io/helps/好きな名前.html`に即時反映される

## その他

* このリポジトリは公開されてるのでパスワードとかセンシティブなことは書かない
* JavaScriptも動かせる
