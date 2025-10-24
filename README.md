Environment
===

# Docker composeによる起動

```
cd docker
docker compose up -d
```

起動したら、http://localhost:8080 にブラウザでアクセス可能です。

# 停止

```
cd docker
docker compose down
```

# PDF出力に必要なパッケージ

```
sudo apt-get install pandoc texlive-xetex texlive-fonts-recommended texlive-plain-generic texlive-lang-japanese -y
```

* [PandocでMarkdownをPDFに変換](https://zenn.dev/karaage0703/articles/976863b4f95486)

# SDKMAN!

```
curl -s "https://get.sdkman.io" | bash
source "/home/vscode/.sdkman/bin/sdkman-init.sh"
```
