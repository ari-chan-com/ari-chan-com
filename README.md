# Git hubの使い方

## HTML＆CSSファイルのアップロード
- 「Create new file」メニューを選択しファイルの追加画面を開く
- 入力欄にファイル名を入力する(ex.index.html / stylesheet.css)

## 画像のアップロード
- 「Upload files」というボタンをクリック
- 画像をドラッグアンドドロップor「choose your files」からアップロード

## ページの公開
- 「Settings」をクリック
- 「GitHub Pages」という項目の緑色の背景の箇所に「Your site is published at ...」と表示されている場合には、そこに表示されているURLで既にWebページが公開されている
  - もし表示されていない場合には、「Source」の項目が「None」となっているので、これをデフォルトブランチ（リポジトリが作成された時期に応じて、「master branch」または「main branch」）に変更して「Save」ボタンを押すことでURLが表示される

# HTMLの基本構文
`<!DOCTYPE html>`    
`<html>`  
`<head>`  
`</head>`  
`<body>`  
`</body>`  
`</html>`  

## head要素の中身
- <head>要素にはWebページの設定に関する情報を書く。
ex.文字コードの指定、ページのタイトルの設定、CSSの読み込みなど
- <head>要素内に記述した内容はWebページには表示されない。

## head要素の中身①文字コードの指定
`<meta charset="utf-8">`

## head要素の中身②ページのタイトル設定
`<title>ページのタイトル</title>`

## head要素の中身③CSSの読み込み
`<link rel="stylesheet" href="スタイルシートのファイル名(ex.stylesheet.css)">`
