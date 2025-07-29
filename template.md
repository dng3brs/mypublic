---
marp: true
theme: gaia
style: |
  @import url('https://fonts.googleapis.com/css2?family=Lato:wght@400;700&family=Open+Sans:wght@400;600&display=swap');

  /* 全体設定 */
  section {
    background-color: #f8f9fa;
    font-family: 'Open Sans', sans-serif;
    color: #343a40;
    padding: 60px;
  }

  /* 見出し */
  h1, h2, h3, h4, h5, h6 {
    font-family: 'Lato', sans-serif;
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
  _footer: '© 2025 あなたの名前 / 会社名'
-->

# **プレゼンテーションタイトル**
## サブタイトル

---

<!-- _footer: '' -->

## アジェンダ

1.  はじめに
2.  主な内容
    -   トピックA
    -   トピックB
    -   トピックC
3.  まとめ

---

## 1. はじめに

ここに導入部分のテキストを記述します。
プレゼンテーションの目的や概要を説明します。

---

<!-- 
  _class: invert 
  _footer: ''
-->

## 2. 主な内容

---

### トピックA: 基本的なリスト

- 箇条書きリストのアイテム1
- 箇条書きリストのアイテム2
  - ネストされたアイテム
- 箇条書きリストのアイテム3

1. 番号付きリストのアイテム1
2. 番号付きリストのアイテム2
3. 番号付きリストのアイテム3

---

### トピックB: 画像との組み合わせ

![bg left:40% 80%](https://images.unsplash.com/photo-1488190211105-8b0e65b80b4e?q=80&w=2940&auto=format&fit=crop)

- 画像とテキストを並べて表示できます。
- `![bg left:40% 80%](URL)` のように記述します。
- `left` の部分を `right` に変えれば画像を右側に配置できます。
- `40%` は画像の幅、 `80%` は画像の高さを調整します。

---

### トピックC: コードの表示

```python
# コードブロックのサンプル
import marp

def hello(name):
  # コードのハイライトも自動で行われます
  print(f"Hello, {name}!")

hello("Marp")
```
---

<!-- 
  _class: lead 
  _footer: '© 2025 あなたの名前 / 会社名'
-->

# ご清聴ありがとうございました
