# 函館家賃調べ
函館の家賃を可視化します

# 環境構築
パッケージ管理はRyeを用いて行っています。
[installation documentation](https://rye-up.com/guide/installation/)に従ってインストールしてください。
その後は
```
rye sync
```
を叩けばvenv環境が構築されます。
構築されたvenv環境のパスは
```
rye shell
which python
```
で確認できます。

# 実行方法
上記で作成した環境でdvz.ipynbを開いてください。
その後はすべてのセルを実行すれば家賃の可視化を行えます。