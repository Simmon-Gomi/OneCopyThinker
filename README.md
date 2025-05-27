README.md：日本語版
OneCopyThinker (日本語版)

ワンコピペで導入できる多角思考プロンプトです。
ChatGPTやClaudeなどで、下記「prompts/multi-role-ja.md」を
Systemメッセージに丸ごと貼り付けるだけで、
(L)(C)(H)(I)の4ロールが段階的(フェーズ0～3)に回答します。

ディレクトリ構成

OneCopyThinker/
README.md // 日本語版の説明
README.en.md // 英語版の説明
LICENSE
prompts/
multi-role-ja.md // 日本語プロンプト本体 (Systemに貼る用)
multi-role-en.md // 英語プロンプト本体 (Systemに貼る用)

使い方 (日本語版)

prompts/multi-role-ja.md を開く

中身を全コピーして、ChatGPTなどの「System」欄に貼り付ける

質問をすると、(L)(C)(H)(I) がフェーズ(0)～(3)に沿って回答

必要なら「(A)(B)(R)(D)」や「S(医師):…」などを1行追加することで
ファクトチェックや専門家視点を補強

回答は1～2画面に収める想定

出力例 (簡易)
Phase 1:
L: 論理的な観点...
C: 新しいアイデア...
H: 倫理・感情の考慮...
I: 主な論点を整理

ライセンス
本リポジトリは MIT License の下で公開しています (LICENSE参照)

英語版 (English)
英語での使い方は README.en.md をご覧ください
（英語プロンプトは prompts/multi-role-en.md にあります）
