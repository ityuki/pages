# fontfamily_list

* フォントファミリーで使用出来るものの一覧を`fontfamily_list`配列に入れて返します。
* `fontfamily_list`の1要素は、次のプロパティで構成されています。
    * `"name"` : フォントファミリー名
    * `"lang"` : 使用出来る言語一覧
        * `"ja"` : 日本語使用可能フォントならtrue

* `window`の`'fontfamily-loaded'`イベント発生以降で有効な値が入っています。

## sample

* 基本的には、sample.htmlが全てです。


### 読み込み

```html
<head>
 <script src="fontfamily_list.js" type="text/javascript" charset="UTF-8" ></script>
</head>
```


## ライセンス
* 本プログラムは、MIT Licenseです
* 内部で使用しているフォントは、OFL-1.1 License（Adobe Blank）です


