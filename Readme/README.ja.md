# R-Type Final 2 のBGMを差し替える

これは `PAK Mod` シリーズで、各Modはゲーム内の特定のBGMを差し替えます。以下の表から必要なModを [Releases](https://github.com/BLACKujira/RTypeFinal2MusicMod/releases/tag/250130) からダウンロードし、[PAK Mod インストールガイド](https://github.com/BLACKujira/RTF2ModdingGuide/blob/master/Chapter1_TheBasics/ja/PAKModのインストール.md) を参考にインストールしてください。

- *同じBGMを差し替えるMod* を複数インストールした場合、有効になるのは1つだけです。  
- ループセグメントに入るときに音楽が一時停止することがあります。原因は現在不明です。

| ファイル名 | 差し替えBGM | 元の出典 |
| ----- | ----- | ----- |
| StageClearBGM_Final_P.pak | ステージクリアBGM | R-Type Final ステージクリアBGM |
| StageClearBGM_Delta_P.pak | ステージクリアBGM | R-Type Delta ステージクリアBGM |
| TitleBGM_Final_P.pak | タイトルBGM | R-Type Final タイトル / Stage F-A BGM |
| BossBGM_Gradius5_P.pak | メインボスBGM（最終ボス含む） | Gradius V ボス & 最終ボスBGM |
| DLCBossBGM_Gradius5_P.pak | DLCボスBGM | Gradius V ボス & MKII & MKIII & 最終ボスBGM |
| RMuseum_Final.pak | RミュージアムBGM | R-Type Final RミュージアムBGM |
| Stage7_1_BGM_Final.pak | Stage Z7.1 BGM | R-Type Final タイトル / Stage F-A BGM |

## 開発者情報
プロジェクト内では、差し替えられる音楽によってリソースファイルが異なるPAKにパッケージされています。以下はChuckIdと差し替え音楽の対応表です。

| ChuckId | 差し替えBGM |
| ----- | ----- |
| 25 | ステージクリアBGM |
| 26 | タイトルBGM |
| 27 | メインボスBGM（最終ボス含む） |
| 28 | DLCボスBGM |
| 29 | Stage Z7.1 BGM |
| 30 | RミュージアムBGM |
