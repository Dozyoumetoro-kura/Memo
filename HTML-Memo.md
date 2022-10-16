# 目次の目次

[基本](#anchor0000)</p>
[ヘッダ](#anchor0001)</p>
[文字列の装飾](#anchor0002)</p>
[画像](#anchor0003)</p>
[リンク](#anchor0004)</p>
[箇条書き](#anchor0005)</p>
[コメントアウト](#anchor0006)</p>
[属性指定](#anchor0007)</p>
[逆引き](#anchor9900)</p>

<br>
<br>
<br>

<a id="anchor0000"></a>
# 基本
[`<!DOCTYPE html>`](#anchor0100)</p>
[`<html></html>`](#anchor0101)</p>
[`<head></head>`](#anchor0200)</p>
[`<body></body>`](#anchor0102)</p>


<a id="anchor0001"></a>
# ヘッダ
[`<head></head>`](#anchor0200)</p>
[`<title></title>`](#anchor0201)</p>
[`<meta charset="UTF-8">`](#anchor0202)</p>

<a id="anchor0002"></a>
# 文字列の装飾

[`見出し`](#anchor0301)</p>

<a id="anchor0003"></a>
# 画像
[`画像挿入`](#anchor0400)</p>

<a id="anchor0004"></a>
# リンク
[`リンク`](#anchor0500)</p>

<a id="anchor0005"></a>
# 箇条書き
[`段落`](#anchor0300)</p>
[`箇条書き(ドット)`](#anchor0600)</p>
[`箇条書き(番号)`](#anchor0601)</p>
[`強制改行`](#anchor0602)</p>

<a id="anchor0006"></a>
# コメントアウト
[`コメントアウト`](#anchor0700)</p>

<a id="anchor0007"></a>
# 属性指定
[`固有の管理名を指定`](#anchor0800)</p>



<br>
<br>
<br>

<a id="anchor0100"></a>
# `<!DOCTYPE html>`

```
<!DOCTYPE html>
```

初めに書く。意味？取り合えず書きゃいいんだよ書きゃ。

<br>

<a id="anchor0101"></a>
# `<html></html>`



```
<html>
コード
</html>
```

コード全体をこれで挟む。

<br>

<a id="anchor0102"></a>
# `<body></body>`

```
<body>
コード
</body>
```

これで挟んだ部分が表示される。原則一つのHTMLに一つ。

<br>

<a id="anchor0200"></a>
# `<head></head>`

```
<head>
コード
</head>
```

主に検索エンジンやブラウザ向けの情報を書く。

<br>

<a id="anchor0201"></a>
# `<title></title>`

```
<title>
コード
</title>
```

タイトルを書く。タブに表示されるらしい。

<br>

<a id="anchor0202"></a>
# `<meta charset="UTF-8">`

```
<meta charset="UTF-8">
```

文字コードを指定。文字化けの防止に。

<br>




段落を作る。</p>
改行したいときに`</p>`単独でも使えるっぽい

<br>

<a id="anchor0301"></a>
# 見出し

```
<h1>文字列</h1>
<h2>文字列</h2>
<h3>文字列</h3>
<h4>文字列</h4>
<h5>文字列</h5>
<h6>文字列</h6>
```
<h1>文字列</h1>
<h2>文字列</h2>
<h3>文字列</h3>
<h4>文字列</h4>
<h5>文字列</h5>
<h6>文字列</h6>

<br>

説明不要。

<br>

<a id="anchor0400"></a>
# 画像挿入

```
<img src="ファイルパス" alt="代替テキスト"/>
```
<img src="アイコン.png" alt="画像"/>

<br>


終了タグはない。

<br>

<a id="anchor0500"></a>
# リンク

```
<a href="https://www.tokyometro.jp/index.html">文字列</a>
```
<a href="https://www.tokyometro.jp/index.html">文字列</a></p>
はさまれているものがリンクに変化する。
<br>

<a id="anchor0300"></a>
# 段落

```
<p>文字列</p>
<p>文字列</p>
```
<p>文字列</p>
<p>文字列</p>

<br>
<a id="anchor0600"></a>

# 箇条書き(ドット)

```
<ul>
<li>文字列A</li>
<li>文字列B</li>
<li>文字列C</li>
</ul>
```
<ul>
<li>文字列A</li>
<li>文字列B</li>
<li>文字列C</li>
</ul>

<a id="anchor0601"></a>
# 箇条書き(番号)

```
<ul>
<li>文字列A</li>
<li>文字列B</li>
<li>文字列C</li>
</ul>
```
<ol>
<li>文字列A</li>
<li>文字列B</li>
<li>文字列C</li>
</ol>



<br>

<a id="anchor0602"></a>
# 強制改行

```
文字列<br>文字列
```
文字列<br>文字列</p>
某サイト曰くこれを多用する人はへたくそらしい

<br>

<a id="anchor0700"></a>
# コメントアウト

```
<!--コメントアウト-->
```
<!--コメントアウト-->
見ようと思えば見れるので間違っても極秘情報を書かないように

<br>

<a id="anchor0800"></a>
# 固有の管理名を指定

```
<タグ id="名前">
```



<br>

<br>
<br>
<br>


<a id="anchor9900"></a>

# 逆引き

[`<!DOCTYPE html>`](#anchor0100)</p>
[`<html></html>`](#anchor0101)</p>
[`<head></head>`](#anchor0200)</p>
[`<body></body>`](#anchor0102)</p>
[`<head></head>`](#anchor0200)</p>
[`<title></title>`](#anchor0201)</p>
[`<meta charset="UTF-8">`](#anchor0202)</p>
[`<p></p>`](#anchor0300)</p>
[`<h></h>`](#anchor0301)</p>
[`<img/>`](#anchor0400)</p>
[`<a></a>`](#anchor0500)</p>
[`<ul><li></li></ul>`](#anchor0600)</p>
[`<ul><li></li></ul>`](#anchor0601)</p>
[`<br>`](#anchor0602)</p>