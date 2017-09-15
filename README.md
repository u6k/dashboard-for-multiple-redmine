# dashboard-for-multiple-redmine

複数のRedmineインスタンスのためのダッシュボード

## Description

企業におけるRedmine運用は、企業としての最低限共通ルールを定義した上で、チームごとにRedmineインスタンスを構築したほうが良いと考えています。しかし、全チームを横断して状況を俯瞰したいという想いもあります。そのため、複数のRedmineインスタンスを横断して状況を俯瞰するためのダッシュボードが欲しい。

## Features

- それぞれのプロジェクトの進捗状況を確認
- バージョン(ロードマップ、スプリント)ごとの状況をバーンダウンチャートで確認
    - スプリントに対応するRedmine運用がばらけると考えられるので、プロジェクト・バージョン・カテゴリーなどを個別に指定できるように
- 組織統廃合によるチケット・Wiki・担当者などの、Redmineインスタンス間の移行
    - Redmineインスタンスをまたいでチケットを単純移行すると、コメント中のチケット番号参照が崩れる
    - トラッカー、カテゴリー、独自項目など存在しない項目があるかも
- 統計情報を確認
    - 具体的に？

## Links

- [Redmineインスタンスとプロセスの関係～Redmineは組織に従うのか、Redmineに合ったチームを作るべきか: プログラマの思索](http://forza.cocolog-nifty.com/blog/2017/09/redmineredminer.html)

## Author

- [u6k - GitHub](https://github.com/u6k/)

## License

[![license](https://img.shields.io/github/license/u6k/dashboard-for-multiple-redmine.svg)](https://github.com/u6k/dashboard-for-multiple-redmine/blob/master/LICENSE)
