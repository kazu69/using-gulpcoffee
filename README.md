## gulpfile.coffeeを使う

[using-coffee-script-for-gulpfile](https://github.com/gulpjs/gulp/blob/master/docs/recipes/using-coffee-script-for-gulpfile.md)

---

### コマンドオプション

```
gulp --require coffee-script
```

gulpfile.coffee を設定して読み込んでタスクを実行する。

```.zshrc```などに```alias gulp=gulp --require coffee-script```を追加しておくと便利

---


### gulpfile.jsから実行する

```shell
gulp
```

で通常通り```gulpfile.js```実行して、gulpfile.coffeeを読込みタスクを実行させる
