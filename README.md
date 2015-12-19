# my-dev
node.jsの開発環境作ってみた

## 使い方

環境設定

```bash
vagrant up
```

モジュール追加

```bash
docker-compose run node npm install モジュール名 --save
```

実行

```bash
docker-compose run node node 実行ファイル
```
