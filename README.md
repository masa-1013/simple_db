# simple-db

[Database Design and Implementation](https://link.springer.com/book/10.1007/978-3-030-33836-7) を読みながら DB の実装をする

## 本のまとめ

### 第１章 Database System

データベースの 5 つの基本機能
・永続的でなければならない
・共有できること
・正確に保たれること
・非常に大きくなること
・使いやすいこと

データベースの機能まとめ
・ファイルシステムでただ保存するよりも効率的にアクセスできる形式を使用して、ファイルにレコードを保存する機能
・ファイル内のデータにインデックスを付けるためのアルゴリズムを使用することで、高速なアクセスを可能にする機能
・ネットワーク経由で複数のユーザーからの同時アクセスを処理し、必要に応じて排他制御を行う機能
・変更のコミットやロールバックを実施する機能
・データベースのレコードをインメモリにキャッシュしながらも、システムがクラッシュした際にデータを失わない機能
・テーブルに対するユーザークエリをファイル上の実行可能なコードに変換する機能
・非効率なクエリを効率的なクエリに変換するための最適化機能

参考文献
https://en.wikipedia.org/wiki/Database#History
