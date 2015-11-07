custom-css - Chrome Extension
====

Chrome拡張機能で閲覧サイトのCSSを追加する最小構成のテンプレート

## Usage
* `extension/manifest.json`を開き、変更したい箇所を適当に変える。
    + 例えばTwitterだけのカスタムCSSを作成する場合は、`matches`の値を`https://twitter.com/*`などにする。
* `extension/custom.css`の中身を適当なCSSで書く。
* `extension`ディレクトリを拡張機能として読み込ませる。

## Install
[chrome://extensions/](chrome://extensions/)より

* `パッケージ化されていない拡張機能を読み込む...`
* `extension`ディレクトリを指定
* 完了

## Licence
[WTFPL](http://www.wtfpl.net/)