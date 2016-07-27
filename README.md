# Slack Emoji Pokémon (Japanized)

This repository is a fork of [Templarian/slack-emoji-pokemon
](https://github.com/Templarian/slack-emoji-pokemon) that japanizes Pokémon names (rōmaji).

<img src="https://cloud.githubusercontent.com/assets/1413408/17162445/2e3eda68-53f1-11e6-99a6-10fecb041919.gif" width="600" />

## Usage

1. Install [lambtron/emojipacks](https://github.com/lambtron/emojipacks)

  ```shell
$ npm install -g emojipacks
```

2. Clone this repo

  ```shell
$ git clone git@github.com:morishin/slack-emoji-pokemon.git
$ cd slack-emoji-pokemon
```

3. Run `emojipacks` command

  ```shell
$ emojipacks
Slack subdomain: <YOUR SLACK SUBDOMAIN>
Email address login: <YOUR EMAIL>
Password: <YOUR PASSWORD>
Path or URL of Emoji yaml file: pokemon.yaml
Starting import
Got tokens
Logged in
Upload crumb is s-1469586832-cbd70267a6-☃
Getting emoji page
Uploading fushigidane with http://i.imgur.com/J9ynKU9.png
Uploading fushigisou with http://i.imgur.com/2BmEJY1.png
Uploading fushigibana with http://i.imgur.com/HyvH3iG.png
⋮
Uploading kairyu- with http://i.imgur.com/tRAf2ht.png
Uploading myuutsu- with http://i.imgur.com/EbSLVKQ.png
Uploading myuu with http://i.imgur.com/5n3F79K.png
Uploaded emojis
```

## Special Thanks
- [wiki.ポケモン.com/wiki/ポケモンの外国語名一覧](http://wiki.xn--rckteqa2e.com/wiki/%E3%83%9D%E3%82%B1%E3%83%A2%E3%83%B3%E3%81%AE%E5%A4%96%E5%9B%BD%E8%AA%9E%E5%90%8D%E4%B8%80%E8%A6%A7)
- [makimoto/romaji](https://github.com/makimoto/romaji)