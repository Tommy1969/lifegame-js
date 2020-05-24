# Lifegame

## 概要

**機能を追加したいが、実際にコードを書いた担当者はすでにいない。実際に使われているが、テストコードはない。**

そんなシチュエーションにどう取り組むか? 

元は [TDDBCでのレガシーコード改善を行うためのサンプルコード](https://github.com/tddbc/lifegame) の JavaScript 版で、ES2017 & jest を使えるようにカスタマイズしたものです。

## インスコ

```sh
% git clone https://github.com/Tommy1969/lifegame-js.git
% cd lifegame-js
% yarn install
```

## 使い方

実行
```sh
% yarn start
```

テスト
```sh
% yarn test
```

テスト:ウォッチモード
```sh
% yarn test:watch
```

## 出力
```
□□□□□
□□□□□
□■■■□
□□□□□
□□□□□
0==========
□□□□□
□□■□□
□□■□□
□□■□□
□□□□□
1==========
□□□□□
□□□□□
□■■■□
□□□□□
□□□□□
2==========
□□□□□
□□■□□
□□■□□
□□■□□
□□□□□
```

Enjoy hacking! :-)
