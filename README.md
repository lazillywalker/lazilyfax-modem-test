# LazilyFAX Modem Test

**Free USB FAX Modem Diagnostic Tool for Linux**

LazilyFAX Modem Test is a free utility developed by **LazilySoft** to help Linux users detect and test USB FAX modems before installing a FAX application.

It provides a simple graphical interface and supports **English, Japanese, and Korean**.

## Features

- Detect USB serial modem devices
- Test modem responses using AT commands
- Display diagnostic results
- Help identify modem connection and permission problems
- Graphical user interface
- English / Japanese / Korean support
- Free to use

## Supported Environment

- Developed and tested on Linux Mint 22
- Debian-based Linux distributions may be compatible
- USB FAX modem with a supported serial interface
- Python 3

Compatibility depends on the modem hardware, drivers, and Linux environment.

**Important:** A successful modem response does not guarantee that the device supports FAX transmission or reception.

## Download

Download the latest `.deb` installer from the GitHub **Releases** section.

[Download Latest Release](https://github.com/lazillywalker/lazilyfax-modem-test/releases)

## Installation

1. Download the `.deb` package.
2. Open the downloaded file using your package installer.
3. Select **Install**.
4. Launch LazilyFAX Modem Test from the application menu.
5. Follow the instructions if additional modem access permissions are required.

Alternatively, install using the terminal:

```bash
sudo apt install ./lazilyfax-modem-test_0.1.0-1_all.deb
```

After changing user permissions, logging out and logging back in may be required.

## Uninstallation

Remove the application using your package manager, or run:

```bash
sudo apt remove lazilyfax-modem-test
```

Removing the application does not automatically reverse all system-level permission changes made during setup.

## Safety and Limitations

- The diagnostic test does not place telephone calls.
- Modem response testing is performed using AT and ATI commands.
- A detected USB serial device is not necessarily a compatible FAX modem.
- Actual FAX transmission and reception require additional software and compatible hardware.
- Use the software at your own discretion.

## About LazilyFAX

LazilyFAX is a separate Linux FAX application developed by LazilySoft.

It provides PDF FAX transmission, document preview, contact management, transmission history, and multilingual support.

**LazilyFAX Modem Test is a free diagnostic utility and does not include the full LazilyFAX application.**

Learn more:

[LazilyFAX GitHub](https://github.com/lazillywalker/lazilyfax)

## Support

For bug reports and suggestions, please use GitHub Issues.

Email: **lazilysoft@gmail.com**

Developed by **LazilySoft**

---

# LazilyFAX Modem Test 日本語説明

**Linux向け無料USB FAXモデム診断ツール**

LazilyFAX Modem Testは、Linux環境でUSB FAXモデムの接続状態や基本的な応答を確認するために開発された無料ツールです。

FAXソフトウェアを導入する前に、モデムが認識されているかを確認できます。

## 主な機能

- USBシリアルモデムの検出
- ATコマンドによるモデム応答テスト
- 診断結果の表示
- 接続やアクセス権限の問題を確認するための補助機能
- GUIによる簡単操作
- 日本語・英語・韓国語対応
- 無料で利用可能

## 対応環境

- Linux Mint 22で開発・動作確認
- Debian系Linuxでも動作する可能性があります
- Linuxに対応したUSB FAXモデム
- Python 3

モデムの種類やドライバー、Linux環境によって動作状況は異なります。

**注意：ATコマンドに正常応答しても、FAX送受信が可能であることを保証するものではありません。**

## ダウンロード

GitHubの **Releases** から最新版の `.deb` ファイルをダウンロードしてください。

[最新版をダウンロード](https://github.com/lazillywalker/lazilyfax-modem-test/releases)

## インストール方法

1. `.deb` ファイルをダウンロードします。
2. ファイルをダブルクリックしてパッケージインストーラーを起動します。
3. インストールを実行します。
4. アプリケーションメニューからLazilyFAX Modem Testを起動します。
5. 必要に応じて、画面の案内に従ってモデムのアクセス権限を設定します。

端末からインストールする場合：

```bash
sudo apt install ./lazilyfax-modem-test_0.1.0-1_all.deb
```

アクセス権限の変更後は、ログアウトと再ログインが必要になる場合があります。

## アンインストール方法

パッケージ管理ソフトから削除するか、次のコマンドを実行してください。

```bash
sudo apt remove lazilyfax-modem-test
```

初期設定によって追加されたユーザーのグループ権限などは、アンインストール後も残る場合があります。

## 注意事項

- 本ツールは電話を発信しません。
- 診断にはAT・ATIコマンドを使用します。
- USBシリアル機器が検出されてもFAX対応モデムとは限りません。
- FAXの送受信には別途対応するソフトウェアが必要です。
- ご利用は自己責任でお願いいたします。

## LazilyFAXについて

LazilyFAXはLazilySoftが開発するLinux向けFAXソフトウェアです。

PDFから
