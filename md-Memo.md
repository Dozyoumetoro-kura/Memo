# **MDファイルの書き方**
# 目次の目次
1.[見出し](#anchor0001)</p>
2.[文字列の装飾](#anchor0002)</p>
3.[リスト](#anchor0003)</p>
4.[画面の装飾](#anchor0004)</p>
5.[コメントアウト](#anchor0005)</p>
6.[リンク](#anchor0006)</p>


0.[メンテ用](#anchor0000)</p>

<br>
<br>
<br>

<a id="anchor0001"></a>
# 目次


## 見出し
1.[見出し](#anchor0100)</p>

<a id="anchor0002"></a>
## 文字列の装飾
1.[改行](#anchor0206)</p>
2.[改行(複数)](#anchor0207)</p>
3.[引用](#anchor0200)</p>
4.[ソースコード(大)](#anchor0201)</p>
5.[ソースコード(小)](#anchor0205)</p>
6.[強調](#anchor0202)</p>
7.[打ち消し](#anchor0203)</p>
8.[注釈](#anchor0204)</p>
8.[文字色の変更](#anchor0208)</p>

<a id="anchor0003"></a>
## リスト
1.[リスト(Disc)](#anchor0300)</p>
2.[リスト(Decimal)](#anchor0301)</p>
3.[リスト(Definition)](#anchor0302)</p>
4.[リスト(Checkbox)](#anchor0303)</p>
5.[リスト(ドット)](#anchor0305)</p>
6.[表](#anchor0304)</p>

<a id="anchor0004"></a>
## 画面の装飾
1.[水平線](#anchor0400)</p>
1.[画像](#anchor0401)</p>

<a id="anchor0005"></a>
## コメントアウト
1.[コメントアウト](#anchor0500)</p>

<a id="anchor0006"></a>
## リンク

1.[自動リンク](#anchor0600)</p>
2.[インラインリンク](#anchor0601)</p>
3.[ファイル内リンク](#anchor0602)</p>

<br>
<br>
<br>


<a id="anchor0100"></a>
# 見出し

```
## 文字列
```

#の数が多くなると大きさが小さくなる(1~6個)</p>

<br>
<br>
<br>

<a id="anchor0200"></a>
# 文字列の装飾
## 引用

```
> 文字列
>文字列
> 

```


> 文字列
>文字列
> 

引用欄に入れたい文字列の前に>を付ける。</p>
2行改行された場所までが引用範囲となる。</p>

```
>  文字列
>>文字列
>>
>文字列

```

>文字列
>>文字列
>>
>文字列

重ね掛けもできる



<a id="anchor0201"></a>
## ソースコード(大)
文字列の前と後に```を付ける</p>

```
    ```
    ソースコード
    ソースコード
    ```
```
```
    ソースコード
    ソースコード
```

tabキーを使うと中に入れ子構造にできる



<a id="anchor0205"></a>

## ソースコード(小)
```
`文字列`
```
`文字列`



<a id="anchor0202"></a>
## 強調
```
*文字列*</p>
**文字列**</p>
***文字列***</p>
```
*文字列*</p>
**文字列**</p>
***文字列***</p>

*の代わりに_でも行けるっぽい



<a id="anchor0203"></a>
## 打ち消し
```
~~ここに本音を書きましょう~~
```
~~ここに本音を書きましょう~~



<a id="anchor0204"></a>
## 注釈
```
文字列 [^1]

[^1]:文字列の型はchar
```

文字列 [^1]

[^1]:文字列の型はchar



<a id="anchor0206"></a>
## 改行
```
文字列</p>
文字列
```

文字列</p>
文字列



<a id="anchor0207"></a>
## 改行(複数)
```
文字列<br>
<br>
<br>
文字列
```

文字列<br>
<br>
<br>
文字列

<a id="anchor0208"></a>
## 文字色の変更
```
<font color="red">文字列</font></p>
<font color="blue">文字列</font></p>
<font color="green">文字列</font></p>
<font color="yellow">文字列</font></p>
```

<font color="red">文字列</font></p>
<font color="blue">文字列</font></p>
<font color="green">文字列</font></p>
<font color="yellow">文字列</font></p>

~~github非対応かよ！~~</p>
ここでも文字列の装飾は使える</p>

`<font color="red">**文字列**</font></p>`

<font color="red">**文字列**</font></p>

<br>
<br>
<br>

<a id="anchor0300"></a>
# リスト

## リスト(Disc)

```
* リスト１
* リスト２
    * リスト3
        * リスト４
```
* リスト１
* リスト２
    * リスト3
        * リスト４

tabキーで階層表示できる。(スペースキーでは不可)






<a id="anchor0301"></a>

## リスト(Decimal)

```
1. リスト１
2. リスト２
    3. リスト３
4. リスト４
```

1. リスト１
2. リスト２
    3. リスト３
4. リスト４

tabキーを入れると改行されない。



<a id="anchor0302"></a>

## リスト(Definition)
```
<dl>
    <dt>リスト１</dt>
    <dd>リスト２</dd>
</dl>
```
<dl>
    <dt>リスト１</dt>
    <dd>リスト２</dd>
</dl>

dtが見出しでddが本文っぽい



<a id="anchor0303"></a>

## リスト(Checkbox)
```
- [ ] リスト１
- [x] リスト２
```

- [ ] リスト１
- [x] リスト２

~~VSCodeのプレビュー対応してないの何?~~

<a id="anchor0305"></a>

## リスト(ドット)
```
- 文字列
* 文字列
```

- 文字列
* 文字列



<a id="anchor0304"></a>

## 表
```
|文字列1|文字列2|文字列3|
|:------|------:|:-----:|
|A      |B      |C      |
|a      |b      |c      |
|`int`  |*main* |~~void~~|
```

|文字列1|文字列2|文字列3|
|:------|------:|:-----:|
|A      |B      |C      |
|a      |b      |c      |
|`int`  |*main* |~~void~~|

表示されているように文字列の装飾もできる。</p>
|の位置がそろっていなくても大丈夫っぽい

<br>
<br>
<br>

<a id="anchor0400"></a>
# 画面の装飾

## 水平線
```
***
* * *
---
- - -
```

***
* * *
---
- - -

四通りの書き方がある。

<a id="anchor0401"></a>
## 画像の挿入
```
![画像](https://www.mext.go.jp/common/img/top_a_menu_ta_imgs_logo_mext.jpg)

![画像](https://www.mext.go.jp/common/img/top_a_menu_ta_imgs_logo_mext.jpg)"文科省画像"
```
![画像](https://www.mext.go.jp/common/img/top_a_menu_ta_imgs_logo_mext.jpg)

![画像](https://www.mext.go.jp/common/img/top_a_menu_ta_imgs_logo_mext.jpg)"文科省画像"


<br>
<br>
<br>

<a id="anchor0500"></a>

# コメントアウト


```
<!--コメント-->
```
<!--コメント-->

<br>
<br>
<br>

<a id="anchor0600"></a>
# リンク


## 自動リンク

```
<https://www.mext.go.jp/>
```
<https://www.mext.go.jp/>



<a id="anchor0601"></a>

## インラインリンク

```
[文科省](https://www.mext.go.jp/)
```
[文科省](https://www.mext.go.jp/)



<a id="anchor0602"></a>

## ファイル内リンク

```
[文字列](#anchor文字列)</p>
<a id="anchor文字列"></a>
```
1.[文字列](#anchor文字列)</p>
<a id="anchor文字列"></a>

同じID(文字列)の場所にジャンプする。

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>




<a id="anchor0000"></a>

# メンテ用
## 命名規則


上二桁：カテゴリNO.
0. 目次
1. 見出し
2. リスト

下二桁：項目NO.

