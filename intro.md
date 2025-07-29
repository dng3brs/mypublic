---
marp: true
theme: gaia
style: |
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@400;700&family=Noto+Sans+JP:wght@400;600&display=swap');

  /* 全体設定 */
  section {
    background-color: #f8f9fa;
    font-family: 'Noto Sans JP', sans-serif;
    color: #343a40;
    padding: 60px;
  }

  /* 本文 */
  p, li {
    font-size: 1.2em;
  }

  /* 見出し */
  h1, h2, h3, h4, h5, h6 {
    font-family: 'Noto Sans JP', sans-serif;
    color: #212529;
    border-bottom: 2px solid #007bff;
    padding-bottom: 10px;
    margin-bottom: 30px;
  }

  h1 { font-size: 2.8em; }
  h2 { font-size: 2.2em; }
  h3 { font-size: 1.8em; }

  /* リンク */
  a {
    color: #007bff;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  /* コードブロック */
  pre {
    border: 1px solid #dee2e6;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
  }
  
  /* フッター */
  .footer {
    position: absolute;
    bottom: 20px;
    left: 60px;
    font-size: 0.7em;
    color: #6c757d;
  }

  /* タイトルページ用クラス */
  .lead {
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  
  /* 反転カラー用クラス */
  .invert {
    background-color: #212529;
    color: #f8f9fa;
  }
  .invert h1, .invert h2, .invert h3, .invert h4, .invert h5, .invert h6 {
    color: #f8f9fa;
    border-bottom-color: #f8f9fa;
  }

paginate: true
---

<!-- 
  _class: lead 
  _footer: '© 2025 Gemini CLI User'
-->

# **Gemini CLIを使ってMCPを試してみた**
## Context7, GitHub, Playwrightの活用事例

---

<!-- _footer: '' -->

## アジェンダ

1.  Gemini CLIとは？
2.  MCPデモ: Context7
3.  MCPデモ: GitHub
4.  MCPデモ: Playwright
5.  まとめ

---

## 1. Gemini CLIとは？

Google製の大規模言語モデル「Gemini」を、コマンドラインから対話的に利用するためのツールです。

- **ローカル環境での実行**: ファイル操作やコマンド実行が可能
- **豊富なツール**: Web検索、ファイル書き込みなど、多彩な機能を搭載
- **MCP (Model Context Protocol)**: 外部サービスと連携し、機能を拡張

---

<!-- 
  _class: invert 
  _footer: ''
-->

## 2. MCPデモ: Context7
### 最新ドキュメントで、<br>常に正しくコーディング

---

### MCP: Context7 の概要

- **最新のライブラリドキュメントを提供**: Gemini CLIに最新のライブラリ情報をRAGソースとして提供します。
- **コード生成の陳腐化を防止**: 古い情報に基づくコード生成を防ぎ、バージョン互換性の問題を回避します。
- **成功例**: LangChainとStreamlitを使用し、最新のベストプラクティスに沿ったPythonチャットアプリを開発。

---

<!-- 
  _class: invert 
  _footer: ''
-->

## 3. MCPデモ: GitHub
### Issue駆動開発を、AIで完全自動化

---

### MCP: GitHub の概要

- **開発ワークフローの自動化**: Issueの作成からPull Requestのマージまで、開発フローをAIが自律的に実行します。
- **`GEMINI.md`によるプロセス定義**: `GEMINI.md`ファイルに開発プロセスを記述するだけで、一貫したタスク遂行が可能です。
- **開発生産性の向上**: 開発者はPull Requestのレビューに集中でき、開発の効率と一貫性が飛躍的に向上します。

---

<!-- 
  _class: invert 
  _footer: ''
-->

## 4. MCPデモ: Playwright
### ブラウザ操作を、自然言語で意のままに

---

### MCP: Playwright の概要

- **自然言語によるブラウザ制御**: PlaywrightのE2Eテストフレームワークを、自然言語の指示で操作できます。
- **ブラウザタスクの自動化**: ページの移動、スクリーンショット撮影、Webフォームへの入力などを自動化します。
- **成功例**: 複数ステップにわたるWebチャットアプリケーションとの対話を、完全に自動化。

---

## 5. まとめ

Gemini CLIとMCPの連携は、開発のあり方を大きく変える可能性を秘めています。

- **Context7**: **最新情報**で、コーディングを常に正確に
- **GitHub**: **開発フロー**を、Issue起票から自動化
- **Playwright**: **ブラウザ操作**を、自然言語で直感的に

これらのツールを組み合わせることで、開発者はより創造的な作業に集中できます。

---

<!-- 
  _class: lead 
  _footer: '© 2025 Gemini CLI User'
-->

# ご清聴ありがとうございました
