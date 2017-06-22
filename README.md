#studyrails
Railsのお勉強をするリポジトリ
- ブログとTwitterの中間になるようなSNSを作ります 自分新聞的ななにか

## 環境
- Ruby 2.3.4
- Rails 5.1.1
- DB: MySQL

# 自分新聞 My News (仮)

## 作りたいもの コンセプト
### Twitterとブログの中間なSNS

Twitterのように気楽に投稿し、ブログのように記事をまとまった形で残す  
気楽に多くの事柄を投稿してもらい、簡単にまとめられる。

### シンプルに
とにかく手軽さを重要視。投稿について、思ったことをそのまま書けるように   
すべて自動で記事をまとめてくれる(手動で編集も可能)


## 投稿の仕様
一回に投稿できる最大文字数は200文字程度  
投稿できる文字/絵文字+写真  
写真は投稿の任意の位置におけるものとする(指定しなければ一番下)

### 会話・リプライ
Twitterのようにそれぞれの投稿に対する会話も可能(会話は基本まとめに入らない)

## まとめる機能
自動でまとめてくれる機能  
基本時系列順  
UIはただタイムラインをまとめただけにならないよう、グラフィカルにしたい(いろいろ未定)  
まとめたものに対してコメントも付ける事ができるし、タイムラインで会話もできる

## ホーム画面(閲覧側)
一番上に来るのは、あくまでまとまった日記(他人の)
脇にタイムラインを流す?(モード切替でタイムラインメイン表示に)
