MOB MASTER MANAGER v0.3.0

MOB STORY / MOB PIECE BATTLE / MOB MONSTERS の独立マスターデータ管理アプリです。

起動方法
1. ZIPを展開
2. index.html を Chrome / Edge で開く

重要
- ゲーム本体へ直接書き込みません。SAFE MODE固定です。
- v0.1.0 のブラウザ保存データは同じブラウザ/同じ場所で開いた場合、v0.3.0へ自動引継ぎします。
- 内部 masterId と表示順を分離しています。
- MOB STORY と MOB MONSTERS のモンスター能力は完全別管理です。COMPAREは表示のみです。
- GitHub画像は Settings の Raw Base URL + フォルダ/番号.png で参照します。画像データはZIPに含めません。

v0.3.0 主な追加
- FIGURE ORDER専用ドラッグ並び替え
- フィギュア一括編集 / 複製 / 新規作成ウィザード
- TAG DESIGN（カテゴリ順整理・新番号再採番）
- DIFF（初期スナップショット / 別BACKUPとの比較）
- SAFETY CHECK（重複ID・参照切れ・入力漏れ検査）
- ERROR時のゲーム別EXPORTブロック
- HISTORY / セッション内UNDO
- STORY vs MONSTERS比較ビュー
- SOUL RECORD専用フォーム / マイルストーン編集
- GitHub画像存在確認

反映は REFLECT からJSONを書き出し、Gitで退避したゲームへレビュー後に反映してください。


v0.3: SYNC CENTER / ZIP SCAN / SIMULATOR / IMAGE AUDIT / SKILL MASTER / REFLECT PREVIEW / RESTORE POINT を追加。
