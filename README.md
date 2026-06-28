# drupal on codesandbox
環境構築用のデモレポジトリ

## Claude Code 用の API Key を設定する

1. 以下のコマンドで `.env` を作成する

  ```sh
  cp .env.sample .env
  ```

2. `.env` で環境変数 `ANTHROPIC_API_KEY` に Claude Console から払い出した API Key を貼り付ける

3. `.env` の環境変数を source する

```sh
source .env
```

## Claude Code CLI のセットアップ

以下コマンドを実行することで Claude による開発が進められるようになります

```sh
./setup.sh
```
