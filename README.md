# 函館家賃調べ
函館の家賃を可視化します
![成果物](https://github.com/yama-yeah/hakodate_rent_dvz/blob/master/%E3%83%8D%E3%82%A4%E3%83%94%E3%82%A2%E6%95%B0%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%9F%E5%BC%B7%E8%AA%BF%E3%81%82%E3%82%8A.png?raw=true)

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
