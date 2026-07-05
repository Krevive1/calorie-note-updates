# calorie-note-updates

## 用途
CalorieNote / 筋トレ飯セットメーカーのアプリ内アップデート通知用。
- gh-pages ブランチの version/latest-version.json を、アプリ起動時にfetchしてバージョン比較している(想定)
- App Storeの審査を待たずに、このJSONを更新するだけでアプリ側に「最新版があります」と表示できる
- このリポジトリ/ファイルを削除するとアプリの更新通知機能が壊れる可能性があるため、削除・改名しないこと