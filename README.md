# こちらのQiita記事の続きです。

# ページ作成

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

# ブログを投稿する

```Bash
# デフォルト言語を日本語にしているので、パスに"ja"の指定は不要
hugo new posts/chapter-1.md
hugo new posts/chapter-2.md
hugo new posts/chapter-3.md
hugo new posts/chapter-4.md
```