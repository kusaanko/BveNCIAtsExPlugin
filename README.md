# BveNCIAtsExPlugin
![C#](https://img.shields.io/badge/-C%23-512BD4?logo=csharp&style=for-the-badge)
![.NET Framework](https://img.shields.io/badge/-.NET%20Framework-512BD4?logo=.NET&style=for-the-badge)
![Supports BVE5](https://img.shields.io/badge/supports-Bve5-green?style=for-the-badge)
![Supports BVE6](https://img.shields.io/badge/supports-Bve6-orange?style=for-the-badge)
![Made for AtsEX](https://img.shields.io/badge/Made%20for-AtsEX-68EDD1?style=for-the-badge)
![Release](https://img.shields.io/github/v/release/kusaanko/bvenciatsexplugin?style=for-the-badge)
![Downloads](https://img.shields.io/github/downloads/kusaanko/bvenciatsexplugin/total?style=for-the-badge)

BVE5、6用のコントローラー入力プラグイン NumerousContollerInterfaceにAtsEXと連携する機能を追加するためのAtsEXプラグイン

Supported language is only Japanese now.

> [!WARNING]
> AtsEXとの連携機能はまだまだ不安定であり、手動でのインストールが必要です。詳しくは下の項目をご覧ください。

# ダウンロード
[Releases](https://github.com/kusaanko/BveNCIAtsExPlugin/releases)からダウンロード

`NumerousControllerInterfaceAtsEXPlugin.zip`がプラグインの本体です。

# インストール
まだこの機能は不安定のためインストーラーから自動でインストールできません。

`NumerousControllerInterfaceAtsEXPlugin.zip`をダウンロードし、中にある`NumerousControllerInterfaceAtsEXPlugin.dll`のプロパティを開き、セキュリティを許可して下さい。

![許可](https://github.com/kusaanko/BveNCIAtsExPlugin/blob/main/pic/1.jpg?raw=true)  

そして、このファイルを`C:\User\Public\Documents\AtsEX\1.0\Extensions`もしくは`Input Devices\AtsEX\1.0\Extensions`に入れてください。

NumerousControllerInterfaceの設定画面のタブから`AtsEX`より、正常に読み込めたかどうかが確認できます。また、正常に読み込めていた場合にはコントローラー設定のAtsEXが選択可能になっています。
