【開発環境サンプル】

■proj_b

--------------------------------------------------------------------------------
▼内容

・プロジェクトB開発用リポジトリ。

--------------------------------------------------------------------------------
▼ブランチ

・本流のみ
※必要に応じてパッチ版や海外版などのブランチを作成。

--------------------------------------------------------------------------------
▼依存リポジトリ

・common_lib_individual   ... 共通ライブラリの動作設定（ヘッダーファイル）：ブランチ=proj_b。
・common_lib              ... 共通ライブラリ（ヘッダーファイル）：ブランチ=proj_b。
・common_lib_confidential ... 機密性共通ライブラリ（ヘッダーファイル）：ブランチ=proj_b。
・proj_a_lib              ... プロジェクトA開発用ライブラリ（ヘッダー＆ソースファイル）：ブランチ=master。

--------------------------------------------------------------------------------
▼サブモジュール適用フォルダ

・/lib/individual/          ← common_lib_individual
・/lib/common/              ← common_lib
・/lib/common_confidential/ ← common_lib
・/lib/proj/                ← proj_a_lib

--------------------------------------------------------------------------------
以上
