# Otera-line-richmenuの進め方
1. app/　以下にサブモジュールとして，line-richmenu-editorを取り入れる.
    ```
    git submodule add https://github.com/e-chan1007/line-richmenu-editor.git app/line-richmenu-editor
    ```

1. docker-compose-react.ymlを使って，コンテナを立ち上げる.
    ```
    docker compose -f docker-compose-react.yml build
    docker compose -f docker-compose-react.yml up -d
    ```

1. docker-compose-react.ymlを使って，コンテナに入る.
    ```
    docker compose -f docker-compose-react.yml exec bash app
    ```

1. 指定ディレクトリに移動して，npm installで関連パッケージをインストール．
    ```
    npm install
    npm build
    ```

1. 