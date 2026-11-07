# OoBLE trial-v03 テロップのみ修正

- 日付：2026-11-07
- 目的：trial-v02の映像を保持し、テロップの書体・大きさ・色・表示時間と位置だけを更新。
- 実施：trial-v02の文字なしMP4を無変更コピー。HGP教科書体、60/69px相当、ダークグレー、0.22秒のフェード。指定の0.5〜2.8、3.2〜5.0、5.5〜9.8秒に表示し、最後の写真は文字なし。
- 新規ファイル：captions-v03.json、render_v03.py、README-v03.md、WORK_LOG-v03.md、save_v03.py、output/trial-v03/。
- 既存のtrial-v01・trial-v02、元動画・元写真・以前の設定は変更していない。
- 検査：文字なし映像SHA-256と映像設定JSONをtrial-v02と照合。書き出しの1080×1920・30fps・12秒・360フレームと全フレームデコードを確認。テロップ3場面と文字なしの最終写真を確認画像で目視検査。
- 未完了事項：ユーザーによる試作レビュー。


制作物保存確認：https://github.com/kaori0906iroak-collab/codex-projects/commit/bbd17a436e8a7dc045acfe668bfc87205d2c4a6a
