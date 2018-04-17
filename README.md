# Markdown
[Markdown](https://ja.wikipedia.org/wiki/Markdown)は、HTMLを簡略化して記載する軽量マークアップ言語です。GitHubでは、リポジトリにあげると自動でビジュアライズされます。以下では、Markdownの基本的な記載法についてhtmlと比較しながら紹介します。

```
//見出し(Heading)
<h1>見出し</h1>　→ # 見出し
<h2>見出し</h2> → ## 見出し

// 一文、段落(Paragraph)
<p>Markdown</p> → * Markdown
<p>HTML</p> → - HTML

//改行(brank)
Markdown<br>の記載法 → Markdown  の記載法
（※ 改行は、  半角スペースを2回)

//引用(blockquote)
<blockquote>Markdown記載法.html</blockquote> → > Markdown記載法.html

// テーブル(table)
<table>
<tr>
<th>用語</th>
<th>意味</th>
</tr>
<tr>
<td>Markdown</td>
<td>軽量マークアップ言語</td>
</tr>
</table>

|用語|意味|
|---|---|
|Markdown|軽量マークアップ言語|

//テキストリンク（2パターンの記載法）
詳しくは[Google](https://www.google.co.jp/)で検索

詳しくは[Yahoo]で検索

[Yahoo]:https://www.yahoo.co.jp/

//画像の埋め込み(<img src= "">)
![img](url)

//リスト
1. 自然地理学とは
  1. 地形学とは
  2. 水文学とは
  3. 気候学とは
2. 人文地理学とは
  1. 都市地理学とは

```
