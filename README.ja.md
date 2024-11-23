# Marshallect

Marshal + Collect | 素材ダウンロードコマンド

### 必要コマンド

- `curl`
- `wget`
- `zip`

### 使い方

1. このリポジトリ内で、あなたがダウンロードしたい素材のリンクを開く  
(例: `https://github.com/lemon73-computing/marshallect/blob/main/docs/copyright-text_japan-gov-bunka.sh`)
1. 生のリンクを入手する  
(例: `https://raw.githubusercontent.com/lemon73-computing/marshallect/main/docs/copyright-text_japan-gov-bunka.sh`)
1. あなたのターミナル上で動かす
    ```bash
    sh  <(curl "Raw URL")

    # 例:
    # sh <(curl https://raw.githubusercontent.com/lemon73-computing/marshallect/main/docs/copyright-text_japan-gov-bunka.sh)
    ```
