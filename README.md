# test
テストリポジトリ

# python3系のWikipedia関連キーワードツリーの作成

### インストール

キーワードツリー作成に必要なpython3および関連ライブラリのインストール

* python3のインストール
```
$ brew install python3
```
* 関連モジュールのインストール
```
$ pip3 install requests beautifulsoup4 anytree 
```
 
### ファイルの配置
・任意のディレクトリに「wikipedia_relation_tree.py」を配置

### 実行

引数を指定して実行  
※引数がない場合や複数設定されている場合はエラーとなります。

```
$ python3 {任意のディレクトリ}/wikipedia_relation_tree.py {引数}
```
【例】
$ python3 ~/wikipedia_relation_tree.py 物流
