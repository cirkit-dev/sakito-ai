# sakito-ai

# 環境構築方法
1. ビルド
    ```
    docker compose build
    ```
2. up
    ```
    docker compose up
    ```
# CI/CDの実行方法
基本は自動実行されます。しかしコードフォーマットに引っかかる場合があります。その際はコンテナ内で修正コマンドを打ってあげてください。
1. コンテナ内に入る
    ```
    docker compose exec web bash
    ```
2. 修正コマンドを打つ
    ```
    black .
    ```

