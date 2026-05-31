# MyAiDevelopment - 警備業界ニュース 公開データリポジトリ

このリポジトリは [shiroukaieda/MyAiDevelopment](https://github.com/shiroukaieda/MyAiDevelopment) の
security-news アプリが自動生成するニュース JSON を **公開配信** するための
専用 public リポジトリ。本体側ワークフローが毎時 force-push で上書きする
（履歴は保持しない）。

フロントエンドは以下から fetch する:
https://raw.githubusercontent.com/shiroukaieda/MyAiDevelopment-data/main/news.json
