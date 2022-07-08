# mongodb

# 学習用プラグイン
MongoDB for VS Code

# データベースの作成
use データベース名

【補足】
useを実行した時点では、データベースは作成されない。
コレクションの作成など、何らかの操作を実行するとデータベースが作成される。

# データベースの一覧
show dbs

# データベースの統計情報の確認
db.stats()

# データベースの削除
db.dropDatabase()
【例】testデータベースの削除
use test
db.dropDatabase()

# コレクションの作成
db.createCollection("コレクション名)

# コレクションの一覧
show collections

# コレクションの削除
db.コレクション名.drop()

