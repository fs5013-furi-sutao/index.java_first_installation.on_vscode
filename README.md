# VSCode で Java 開発環境を爆速で作り上げる
Java 開発環境を VSCode で構築する Tips 一覧です。何度もやって、環境構築上手になってね。:shipit:

この Tips では、以下の環境を想定しています。
- Windows 10

VSCode で Java 開発環境を整えるには、大きく以下の 3 つの手順が必要になる。
- Java のインストール
- VSCode の導入
- VSCode に Java プロジェクト設定をする

以下、それぞれの詳細な手順を、順を追って説明していく。

## Java のインストール
Java は Scoop というパッケージ管理ツールを使ってインストールを行う。

Scoop とは（メリットと使い方）:  
[https://github.com/fs5013-furi-sutao/explain.scoop](https://github.com/fs5013-furi-sutao/explain.scoop)  

Java をインストールする（Scoop を使って）:  
https://github.com/fs5013-furi-sutao/explain.how_to_install_java.with_scoop  

## VSCode の導入
Java のプログラムを書いていくツール、エディタは Microsoft 社の Visual Studio Code を使う。略称 VSCode。

プログラミング向けの機能を備えたツールのことを一般的に、統合開発環境（IDE）と呼んでいる。

今回は、一般的な VSCode ではなく、開発者に適した形態である「ポータブル版」を利用する。

開発者に適した VSCode ポータブル版の導入方法:  
[https://github.com/fs5013-furi-sutao/explain.how_to_install_vscode.portable](https://github.com/fs5013-furi-sutao/explain.how_to_install_vscode.portable)

## VSCode に Java プロジェクト設定をする
VSCode はそのままでは Java プログラムを動かせない。Java など特定の言語を動かせるように初期設定されていない。理由は、様々なプログラミング言語に対応できるように、あえてそのように VSCode を設計しているためだ。

Java プログラミングをできるように、最後に VSCode のセッティングを整える。

VSCode で Java プロジェクトを使えるようにする:  
[https://github.com/fs5013-furi-sutao/explain.how_to_enable_java.on_vscode](https://github.com/fs5013-furi-sutao/explain.how_to_enable_java.on_vscode)  

補完機能でコーディングをスピードアップしよう:  
[https://github.com/fs5013-furi-sutao/explain.use_complementary_features.on_vscode/blob/master/README.md](https://github.com/fs5013-furi-sutao/explain.use_complementary_features.on_vscode/blob/master/README.md)   
