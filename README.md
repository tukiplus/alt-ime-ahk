# alt-ime-zenhan

## 概要

左右 Alt キーの空打ちで IME を OFF/ON する AutoHotKey スクリプトです。

IME の操作は AutoHotKey スクリプトで直接行わず [zenhan](https://github.com/iuchim/zenhan) の呼び出しで実現しています。  
[オリジナルのalt-ime-ahk](https://github.com/karakaram/alt-ime-ahk) で動作が不安定な環境があったため zenhan を使うバージョンを作成しました。  
安定性が向上しているかは不明です。

* 左 Alt キーの空打ちで IME を「英数」に切り替え
* 右 Alt キーの空打ちで IME を「かな」に切り替え
* Alt キーを押している間に他のキーを打つと通常の Alt キーとして動作

## 動作環境

* Windows10
* zenhan がインストールされており、動作すること

## 使い方

別途 zenhan をインストールする。

[alt-ime-zenhan v0.0.1](https://github.com/tukiplus/alt-ime-ahk/releases/download/v0.0.1/alt-ime-zenhan.zip) から alt-ime-zenhan.zip をダウンロードして解凍し、alt-ime-zenhan.exe を好きな場所に置き、起動してください。  
タスクトレイに常駐します。

終了する場合はタスクトレイのアイコンを右クリックし、「終了」をクリックしてください。

アンインストールは alt-ime-zenhan.exe を削除するだけで OK です。

## JetBrains 製の IDE で使う場合は Tool Buttons をオンに

オリジナル由来の注意事項です。  
alt-ime-zenhan では未確認ですが同様と思われます。

IntelliJ IDEA など JetBrains 製の IDE をお使いの方は「上部メニューバー　＞　View　＞　Tool Buttons」をオンにしてください。

オフのまま使うと Alt キーを離した際に alt-ime-zenhan.exe がエラー終了します。

## オリジナルの紹介ページ

[Altの空打ちで日本語入力(IME)を切り替えるツールを作った](http://www.karakaram.com/alt-ime-on-off/)
