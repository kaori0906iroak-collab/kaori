# 2026-09-16 Codex制作プロジェクトのGitHub保存

- 日付: 2026-09-16
- 目的: これまでCodexで作成し、GitHubに保存していなかったプロジェクトを保存する。
- 実施内容: ユーザーフォルダー内の制作物、Documents/Codex、OneDriveのDesktop・Documentsの直下、既存GitHubリポジトリを確認。既存GitHubには作業記録のみだったため、非公開の [codex-projects](https://github.com/kaori0906iroak-collab/codex-projects) を新規作成して保存した。
- 保存対象: cafe-homepage、miyajima-latte、2026-07-29のWeb制作物、CodexPractice内のリール制作物・素材・編集スクリプト・確認画像、2026-09-05のInstagram投稿画像・文章、自作スキル4件（弁当献立、コーヒーカフェ案内、旅行カフェ案内、Instagramリール制作）。
- ファイル数: 元ファイル255件。249件はGitへ保存。大容量ファイル6パスは内容の重複をまとめた4ファイルとして [Releases](https://github.com/kaori0906iroak-collab/codex-projects/releases/tag/backup-2026-09-16) に保存。
- 変更したファイル: 元プロジェクトは変更していない。ローカルに github-backup-20260916/ 配下の保存用コピー、準備スクリプト、添付動画のコピー、作業記録を追加。保存リポジトリには README.md、backup-manifest.json、excluded-paths.json、restore-large-files.ps1、.gitignore を追加。
- 確認結果: コピーしたファイルのSHA-256一致、Git保存対象249件のファイル内容とGitオブジェクトの一致、ローカルとGitHubのコミットID一致、大容量動画4件のGitHub側サイズ・SHA-256・アップロード完了状態、非公開設定を確認した。代表的な認証情報のパターン検査では該当なし。アプリや動画の機能・表示の再検証は今回の対象外。
- 保存対象外: .vercelのローカル設定・ビルドキャッシュと.analysis_tmpの一時画像、計21件。認証情報、Codex会話履歴、他者配布のプラグイン・スキルは収集していない。
- 復元方法: Gitのファイルを取得後、必要に応じてrestore-large-files.ps1で大容量ファイルを取得する。元の相対パスと全ファイルのSHA-256はbackup-manifest.jsonに記載。
- 未完了事項: 今回発見した保存対象の未同期なし。上記確認範囲外の場所や外部サービスだけに存在する制作物については、網羅を保証していない。今後の編集内容は自動同期されない。
