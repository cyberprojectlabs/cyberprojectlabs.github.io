# Cyber Project Labs Pages

GitHub Organization `cyberprojectlabs` の公開サイト用。Google Play開発者名は Crazy Markun Project です。

## 公開ページ

- CPL: `/`
- CPS: `/cyber-project-studio/`
- Arrow Out 日本語プライバシーポリシー: `/cyber-project-studio/arrow-out/privacy/`

次の作品は `/cyber-project-studio/<game-slug>/privacy/index.html` を追加し、`cyber-project-studio/index.html` の作品一覧にリンクを追加します。英語版は例えば `/cyber-project-studio/arrow-out/privacy/en/` に追加できます。既存の日本語URLは固定します。

Arrow Outの本文は2026-09-25版から引き継ぎました。現在のAndroid版1.0.2は広告・課金SDKが未接続という前提です。実際にAdMobやGoogle Play Billingを接続する際は、取得・送信データ、送信先、目的、同意・広告設定、購入トークン、保存・削除、子ども向け設定、最終更新日を見直し、Google Playのデータセーフティ申告と整合させてください。

公開URLが確定したら、Arrow Out本体の `release.config.json` の `legal.privacy` とアプリ内リンクを更新し、提出するAABで動作確認してください。このサイトだけを更新してもアプリ内リンクは変わりません。
