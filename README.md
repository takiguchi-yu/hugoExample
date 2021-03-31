# こちらのQiita記事の続きです。

カスタマイズの続きになります。できあがりはこんな感じとなります。
git clone して `hugo server -D` して動作確認してみてください。

```bash
git clone git@github.com:takiguchi-yu/hugoExample.git
git submodule update -i
hugo server -D
```

![トップページ](./_images/sc1.png)
# ページ作成

Hugo はすべてのページを Markdown で記述することができます。<br>
まずは次のコマンドでページを作成してみましょう。ページは作成したら中身をいじってみよう。

```bash
# 日本語ページの作成
hugo new ja/_index.md
hugo new ja/contact.md
hugo new ja/about/_index.md
hugo new ja/posts/_index.md
# 英語ページの作成
hugo new en/_index.md
hugo new en/contact.md
hugo new en/about/_index.md
hugo new en/posts/_index.md
```

# サイト全体設定

config.toml をいじる

https://github.com/takiguchi-yu/hugoExample/blob/master/config.toml

# ブログを投稿してみる

```Bash
# デフォルト言語を日本語にしているので、パスに"ja"の指定は不要
hugo new posts/chapter-1.md
hugo new posts/chapter-2.md
hugo new posts/chapter-3.md
hugo new posts/chapter-4.md
```