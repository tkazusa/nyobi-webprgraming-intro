## Requirments
yarn のインストール
```
$ npm install -g yarn
$ yarn init
```

ライブラリのインストール
- yo
- generator-hubot
- coffeescript

```
yarn global add yo@3.0.0
yarn global add generator-hubot
yarn global add coffeescript@1.12.7
```

## hutob の作成
```
yo hubot
```

## Slack App で Hubot の設定


env HUBOT_SLACK_TOKEN=xoxb-629296318723-1004836879266-lHDHHZ9R5oXsZ8AeaEQKz0YR -bin/hubot --adapter slack