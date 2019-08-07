# shellProgramming
learning linux programming based on a book

## 1


## Command Line Basics
-----------------------------------
- `cd -`: 前のディレクトリに戻る
- `ctrl + a`: 行頭移動
- `ctrl + e`: 行末移動
- `ctrl + w`: 後方に1単語削除
- `ctrl + k`: 行末までカット
- `ctrl + u`: 行頭までカット
- `ctrl + y`: 最後に削除した内容を挿入
- `ctrl + l`: 画面削除
- `ctrl + r`: インクリメント検索
-----------------------------------

# 02┃Linuxのディレクトリ構造
Windowsとの違いディレクトリについてはWindowsも同様の階層構造を持ちますが、Linuxと多少の違いがあります。たとえばシステム全体で2台の物理ディスクがある場合、Windowsでは2つのディレクトリツリーができます。一方、Linuxでは何台のディスクがあろうが、システム全体で1つのディレクトリツリーしか持たないのが大きな違いです。このため複数ディスクがある場合、Linuxではルートディレクトリ配下のどこかに、ディスクをディレクトリとしてくっつける手法を取っています。この操作を「マウント」と呼びます。

(三宅 英明,大角 祐介. 新しいLinuxの教科書 (Japanese Edition) (Kindle Locations 1341-1347). Kindle Edition. )