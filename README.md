# ByeSweetCarole-JP

Bye Sweet Carole の非公式日本語化パッチです。
XUnity.AutoTranslator を使用し、機械翻訳をもとに手作業で自然な日本語に修正しています。

## 導入方法

1. ダウンロードは Releasesをクリックした先のAssets の「ByeSweetCarole_JapaneseTranslation_v1.0.0.zip」を選んでください。
   「Source code」は導入には使用しません。
2. zip を展開し、中身をすべてゲームフォルダ（`Bye Sweet Carole.exe` がある場所）にコピーします。
3. ゲームを起動します。

※ 初回起動時は BepInEx の準備処理が行われるため、起動まで数分かかります。2回目以降は通常どおり起動します。

ゲームフォルダは、Steam のライブラリでゲームを右クリック →「管理」→「ローカルファイルを閲覧」で開けます。

## アンインストール方法

ゲームフォルダの `winhttp.dll` を削除すると、日本語化が無効になります。
完全に削除する場合は、導入時にコピーした以下のファイル・フォルダ、

- BepInEx
- dotnet
- doorstop_config.ini
- notosansjp_sdf
- BepInEx_LICENSE.txt
- XUnity.AutoTranslator_LICENSE.txt
- OFL.txt

を削除してください。

## 動作環境

- 対応ゲームバージョン：Steam版
- BepInEx：BepInEx-Unity.IL2CPP-win-x64-6.0.0-be.790+4e98359
- XUnity.AutoTranslator：XUnity.AutoTranslator-BepInEx-IL2CPP-5.6.3.1

ゲームのアップデートで動作しなくなる場合があります。

## 使用ツール・ライセンス

| 名称 | ライセンス |
|---|---|
| [BepInEx](https://github.com/BepInEx/BepInEx) | LGPL-2.1 |
| [XUnity.AutoTranslator](https://github.com/bbepis/XUnity.AutoTranslator) | MIT |
| [Noto Sans JP](https://fonts.google.com/noto/specimen/Noto+Sans+JP) | SIL Open Font License 1.1 |

各ライセンス文は `licenses` フォルダに同梱しています。

## 翻訳ファイルの扱い

   個人での利用は自由です。改変・再配布する場合は、このリポジトリへのリンクを記載してください。

## 免責事項

- 本パッチは非公式のファン翻訳であり、開発元・販売元とは一切関係ありません。
- 本パッチの使用によって生じたいかなる問題についても、作者は責任を負いません。
- 権利者から要請があった場合は、速やかに公開を停止します。
- 不具合や誤訳の報告は [Issues](../../issues) へお願いします。
