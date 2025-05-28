# OneCopyThinker (日本語版)

ワンコピペで導入できる多角思考プロンプトです。  
ChatGPTやClaudeなどで、下記の「[prompts/multi-role-ja.md](prompts/multi-role-ja.md)」をSystemメッセージに丸ごと貼り付けるだけで、(L)(C)(H)(I)の4ロールが段階的(フェーズ0～3)に回答します。

## ディレクトリ構成

OneCopyThinker/
├── [README.md](README.md)            // 日本語版の説明

├── [README.en.md](README.en.md)      // 英語版の説明

├── [LICENSE](LICENSE)                // ライセンスファイル

└── prompts/

├── [multi-role-ja.md](prompts/multi-role-ja.md)  // 日本語プロンプト本体

└── [multi-role-en.md](prompts/multi-role-en.md)  // 英語プロンプト本体

> **Note**: 上記リンクはGitHub上でクリックすると該当ファイルへ飛びます。

## 使い方 (日本語版)

1. **プロンプト本体を開く**  
   → 「[prompts/multi-role-ja.md](prompts/multi-role-ja.md)」をクリックして内容を確認。

2. **System欄にコピペ**  
   - ChatGPTやClaudeなどで、Systemメッセージに丸ごと貼り付ける。  
   - これで (L)(C)(H)(I) がフェーズ(0)～(3)の流れで回答するようになります。

3. **オプション機能**  
   - “`(A)(B)(R)(D)`”や “`S(医師): ...`”などを1行追加すると、  
     ファクトチェック・専門家ロール等を補強できます。

4. **想定出力**  
   - 回答は1～2画面に収める設計（過度な長文化を防止）。  

## 出力例 (簡易)

Phase 1:
L: 論理的観点から...
C: 新たなアイデアを...
H: 倫理・感情面の考慮...
I: 主な論点を整理

このように「フェーズ×ロール」の形式で回答が展開され、段階的思考が行われます。

## ライセンス

本リポジトリは [MIT License](LICENSE) の下で公開しています。  
詳細は「[LICENSE](LICENSE)」ファイルを参照してください。

## 英語版 (English)

- 英語での詳しい説明や使い方 → [README.en.md](README.en.md)  
- 英語プロンプト → [prompts/multi-role-en.md](prompts/multi-role-en.md)

> **ご意見や質問**： [Issues](../../issues) へどうぞ！
