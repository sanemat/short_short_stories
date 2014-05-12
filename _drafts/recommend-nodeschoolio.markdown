---
layout: post
title: "Recommend Nodeschoolio"
---
nodebeginner.orgの次。

[nodeschool.io](http://nodeschool.io/#)

このシリーズいいのは、問題とヒントが出て、それを満たす答えのスクリプトを書い
て、
```bash
checker verify your_script.js
```
verifyすると, passかfailか実行して教えてくれるところ。しかも、正答はその場で教
えてくれないので、ちょっとだけ自制心を働かせると(プロジェクトのリポジトリclone
すれば回答もそれを呼ぶ側のスクリプトもOSSなので全部おいてある)、ぐぐりつついい
感じにストレッチ出来るのがよい。

learnyounode
nodejsのライブラリの使い方基本とsync, async, I/O, tcp, httpとかそのへん

[mozillaのreference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/)
[nodeのdocument](http://nodejs.org/api/)

stream-adventure

streamの扱い方 pipeとかthroughとか
なおjson入力を変形するところでわからなくなった けどほっといて進んでる 

functional-javascript
nodoscool.ioのコマンドをグローバルに入れるの嫌だったので

```bash
npm init
npm install functional-javascript-workshop@latest --save
ne functional-javascript
```

ちなみに
```bash
alias npm-exec='PATH=$(npm bin):$PATH'
alias ne='npm-exec'
```
see also:
http://stackoverflow.com/questions/9679932/how-to-use-package-installed-locally-in-node-modules
http://bokukoko.hatenablog.com/entry/2014/02/08/npm_%E3%81%A7%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB%E3%81%97%E3%81%9F%E3%83%A2%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB%E3%81%AEbin%E3%81%ABPATH%E3%82%92%E9%80%9A%E3%81%99_(bundle_exec)

npm exec, ne便利。
