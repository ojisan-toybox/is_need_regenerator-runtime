core-js, regenerator-runtime なしで async-await やろうとしたらどうなるのか確かめてみた系レポジトリ

結果は commit log 参照.

```sh
❯ node -v
v12.14.1

❯ yarn -v
1.21.1
```

```sh
yarn babel ./main.js --out-file bundle.js
```

実行

```
node bundle.js
```
