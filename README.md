# PenReso（ペンレゾ）ダウンロード

CLIP STUDIO PAINTでの描画に合わせて音を添える、Windows向け作画サポートアプリです。

## ダウンロード
[最新版の配布ページ](https://github.com/jin-plus-humor/penreso-downloads/releases/latest) の **Assets** から `PenReso-*-windows.zip` を取得してください。GitHubのアカウントやGitのインストールは不要です。`Source code` はアプリ本体ではありません。

ZIPをすべて展開し、`CintiqScribbleLauncher.exe` を開きます。機器を登録し、音色・描画キーを設定して音をONにします。細かな説明はZIP内の「はじめに.txt」をご覧ください。

## 対応環境と制限
Windows 10/11 x64、.NET Framework 4.8以降、Wacomドライバー、CLIP STUDIO PAINTが必要です。macOS/iPad版はありません。開発版で、録音素材は含みません。素材のないGペン音色は無音です。標準の合成音か、利用者が権利を持つWAV音源を使ってください。

## 更新する場合
アプリを完全に終了し、新しいZIPを別フォルダーに展開して、`bin/CintiqScribble.exe` を既存の同じ場所へ上書きします。既存の `bin/data` と `bin/assets` は保持してください。各Releaseに異なる手順がある場合はそちらを優先してください。

## このリポジトリについて
配布専用です。開発用ソースコードは公開していません。無料でダウンロードできますが、オープンソースとしての利用許諾を意味するものではありません。

[紹介・お問い合わせ：プラスユーモア](https://plus-humor.com/2026/10/02/penreso/)