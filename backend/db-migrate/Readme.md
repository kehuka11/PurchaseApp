# Flyway運用

## ファイル形式

形式：Vx.x.x.x__[ファイル概要].sql

## ファイル作成方針

新しくテーブル定義を追加、変更する場合は、新規ファイルを追加してFlywayで差分更新できるようにする。