# test
テストリポジトリ

# Wikipedia関連キーワードツリーの作成

### ソースファイルのダウンロード
GitLabからsrcをclonし、任意のディレクトリに配置してください

### インストールおよび起動
キーワードツリー作成実行に必要なdocker環境の起動

* 前提条件  
Docker Desktop for Windows もしくは Docker Desktop for Mac がインストールされている環境で実施してください  
【ダウンロードサイト】  
Docker Desktop for Windows：https://hub.docker.com/editions/community/docker-ce-desktop-windows/  
Docker Desktop for Mac：https://hub.docker.com/editions/community/docker-ce-desktop-mac

* コンテナのビルド・起動
```
$ cd {任意のディレクトリ}
$ docker-compose up -d --build
```

### 実行
Wikipedia関連キーワードツリー作成の実行
* コンテナに入る
```
$ docker-compose exec kurokawa_code_test bash
```

* 引数を指定して実行  
※第一引数がない場合や引数が複数設定されている場合はエラーとなります。

```
$ python3 ./src/wikipedia_relation_tree.py {引数}
```
【例】
$ python3 ./src/wikipedia_relation_tree.py 物流
