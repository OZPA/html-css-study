# Sassを使ってcssを効率よく記述しよう

このlessonでは `Sass` というメタ言語を使って、cssを効率よく書く方法を学びます。  
Sass（さす）：https://sass-lang.com/

## なんでSassを使うの？

Sassにはcssを入れ子にできたり、変数を使用できたり、一言では書ききれないほどたくさん便利な機能があります。  
というか現在、大規模サイトでメタ言語（Sass -> css のように、他の言語を構築するための言語。）を使用せずに生のcssを書いていくことはまずありえません。マンガボックスでも当然使用されています。

## Sassを使うための手順

Sassはcssのように直接ブラウザが読み取ってくれません。そこで、コンパイル（Sassをcssに変換する作業）が必要となります。手順は下記に記しますのでコピペでできるはずです。

```
ターミナルを起動

$ cd Desktop/html-css-study/lesson_sass
$ npm i -D parcel
$ npm run watch
```

あとはindex.htmlファイルやstyle.scssファイルを変更、保存すると自動でcssに変換してくれます。