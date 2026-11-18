# Shakei release 1.0 — 第三者コンポーネントと出典

この配布物はMOD本体と説明資料です。スマートフォン用アプリ、PC用USB接続ソフト、Android Platform-Tools、CPython、PyInstaller、OpenSSLのランタイムは含めません。

## Recipe Lab v1.7.0

Based on Recipe Lab by André Domingues, © 2026. MIT版v1.7.0の固定コミット `6d70495e62d4a9ec15a9c5cfcf835e775ff9c8cc` を使用しています。後発のGPL版は取り込んでいません。

出典：https://github.com/voxivoid/recipe-lab-sony-pmca/tree/v1.7.0

元のMIT許諾文全文を `licenses/recipe-lab-v1.7.0-MIT.txt` とJAR内 `assets/shakei/licenses/recipe-lab-v1.7.0-MIT.txt` に保持しています。レシピの数値を独自の色処理へ適用した近似であり、メーカー公式の画像処理を再現するものではありません。

## Spectral Film LUT

Copyright (c) 2026 Jan Lohse. MIT版の固定コミット `a15043f6fe2d365d0c359d22e0868076800916d9` から生成したLUTを使用しています。

出典：https://github.com/JanLohse/spectral_film_lut

元のMIT許諾文全文を `licenses/spectral-film-lut-MIT.txt` とJAR内 `assets/shakei/licenses/spectral-film-lut-MIT.txt` に保持しています。ゲームの描画済みRGBから実際の光のスペクトルを復元するものではありません。生成用のPython等はゲーム依存関係として同梱していません。

## ホワイトバランス

Mitchell Charityの色データを基にTanner Hellandが公開した、黒体色の近似係数を使用しています。

出典：https://tannerhelland.com/2012/09/18/convert-temperature-rgb-algorithm-code.html

## 動画処理

Shakei独自コードとWindows Media Foundation APIを使用します。Windowsのコーデック、FFmpeg、第三者コーデックのバイナリは配布しません。

参照：https://learn.microsoft.com/en-us/windows/win32/medfound/tutorial--using-the-sink-writer-to-encode-video

## 同梱しないもの

Minecraft、Forge、OptiFine、SEUS、BSL、RealTrainMod、NGTLib、KaizPatchX、JourneyMap、検証用の車両モデルパックの本体・ソース・JAR・ZIPは同梱していません。

カメラ・レンズ・三脚はShakei独自のゲーム用モデルです。メーカー公式のモデル素材やロゴは使用していません。フィルム等の名称は近似する外観・対応形式の説明であり、提携や推奨を示すものではありません。

本体の利用・配布条件は `LICENSE.ja.txt` を参照してください。MIT等が第三者コンポーネントに与える権利を、本体の規約で制限することはありません。
