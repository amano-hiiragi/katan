# カタンを身内でオンライン処理

## 参考

- 環境構築<https://qiita.com/saki-engineering/items/57eb970e49d31d779f60>

- 作ろうとするゲームのタイプ<https://www.4gamer.net/games/105/G010549/20100905002/>
- https://learning.unity3d.jp/3341/

## 利用

- AWS
- Docker

- Node.js
  - [Express](https://expressjs.com/ja/)
    - MVCで言うところのルーティング?
  - [Socket.IO]
    - <https://qiita.com/riku-shiru/items/ffba3448f3aff152b6c1>

AWS環境下でのDockerについて
<https://docs.aws.amazon.com/ja_jp/AmazonECS/latest/developerguide/docker-basics.html>

## note

### 間に調べたことまとめ

- ssh 使用時、接続情報書く手間を無くす<https://qiita.com/passol78/items/2ad123e39efeb1a5286b>

Socket.IOについてはもうちょい理解しとくべき？

npm install express --save