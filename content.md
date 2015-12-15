# GitHubを使おう

<!-- -->  
BS企業  
LT201512  
佐藤誠  


# GitHubを使わざればプログラマーに非ず！



# GitHubとは

<img src="https://octodex.github.com/images/original.png" width="300px" alt="マスコットoctcat">


# こんなサービス

Gitホスティングサービス  
<!-- -->  
特徴的なのは・・・  



## PullRequest  
<!--
    ご存知 'プルリク', 'プルリ', 'PR'  
    GitにはPullRequest機能なし。  
    サードパーティーが"clone->開発->オリジナル開発者に取り込み依頼"することを機能として表現したもの。  
    オープンソース開発のスタンダードになった偉大な機能。  
    このスクリーンショットではサードパーティーではなく自分自身だけど。
-->
![PullRequest作成](pullrequest01.jpg)  

これを  


![PullRequest作成](pullrequest02.jpg)  

こうして  


![PullRequestをマージ](pullrequest03.jpg)  

マージすると  


![PullRequestをマージ](pullrequest04.jpg)  

取り込まれる      


## Fork  
![Fork](fork.jpg)  
<!--
    Git本体には、リポジトリーをどこから持ってきたのかを管理する機能なし。  
    GitHubでは独自にオリジナルリポジトリーを管理している。  
    ちなみに貢献する気がなければFork機能は使わないのがふつう。  
    サードパーティがPullRequestするときに必要。  
    人気のバロメーターの一つ。  
-->



## markdown  
<!--
    ドキュメント類は全部markdownで。  
    GitHub上ではHTMLにレンダリングして表示される。  
    テキストなのでgitでなくてもvcsと相性よし。  
    リアルタイムレンダリングできるエディター多数(例:atom)  
-->

![レンダリング後](markdown01.jpg)  

これは実は・・・


![raw](markdown02.jpg)

こう書かれている。  


![VS Code](markdown03.jpg)

Visual Studio Codeでレンダリングしつつ書く。
  


## お値段無料  
![pricing](price.jpg)
<!--
    ・・・オープンソース(Public repository)なら。  
    Private repositoryは有料なり。  
-->


# こんなに便利


## issue管理  
![issue管理](issue.jpg)
<!--
    開発項目、バグを管理できる。  
    規模にもよるが多人数での開発でなければチケット/イシュー/バグトラッキングシステムは不要。  
-->


## Github pages  
<!--
    プロジェクトを他者に説明するページ。  
    Gitリポジトリーの1ブランチ。ブランチ名を"gh-pages"にするだけ。  
    Webサーバーが稼働していて、htmlをレンダリングして表示できる。
    アプリケーションサーバー的な使い方はできないが、Javascriptも動くので動きのあるページは作れる。  
    デモページが王道らしい。  
-->
![ブランチ](gh-pages_01.jpg)

gh-pagesブランチの  


![index.html](gh-pages_02.jpg)

index.htmlを表示しているだけ。  


![内容は外出し](gh-pages_03.jpg)

内容はcontent.mdに外出している。  


## gist  
<!--
    コードスニペットを管理できる。  
    これ自身もGitリポジトリー。  
    ブログ埋め込みできる。  
    対応している言語の拡張子であれば、それっぽくシンタックスハイライティングしてくれる。  
    スニペットなので一部だけでOK.
-->
![埋め込み用タグ](gist01.jpg)

ブログ埋め込みに使うタグ  


![シンタックスハイライト](gist02.jpg)

コードは適当です  


# 広大なエコシステム


## OAuth
<!--
    Githubアカウントでログインできるサービス多数  
-->
![OAuth](oauth01.jpg)    
![OAuth](oauth02.jpg)    


## reveal.js  
<!--
    Github pagesをパワポ代わりに！  
    これもmarkdownなので手元のエディターでOK。  
-->
![原稿](revealjs01.jpg)   

これが原稿で・・・  


![プレゼン風](revealjs02.jpg)

こう見せてくれる。  
今見てますね。  
   

## zenhub
<!--
    issueをカンバン風に表示してくれるChromeアプリ。  
-->

![issue](issue.jpg)  

これを・・・  


![zenhub](zenhub.jpg)  

こう整理できる。  


## travis ci  
<!--
    Githubでは定番のCIツール。  
    みんなREADME.mdにバッジを貼ってる。  
-->
![travis ci passing](travisci01.jpg)  

このバッジは  


![travis ci](travisci02.jpg)  

Travis CIのビルド通過のバッジ。  



## slack  
<!--
    チャットアプリ。  
    SlackはGithubの周辺サービスというわけではなく、それ自身がハブになっている。  
    ここではgithubにcommitをpushすると自動的にSlackにコミットログが流れるようにしている。  
    自分でリポジトリを持ち、PullRequestを活用するようになるとありがたくなるかと。  
-->
![slack](slack01.jpg)

commitをpushすると  


  
![slack](slack02.jpg)

チャットにログが流れる



これらはほんの一例です。



# だからみんなGitHubを使おう

こんなに便利で楽しいGitHub。
さあ、 Let's social coding!  
<img src="https://octodex.github.com/images/original.png" width="300px" alt="マスコットoctcat">


<!--
こんなに便利なサービスを使わないんですか？  
プログラマーなら楽をしましょう。  
便利な道具を無視してわざわざ苦労を背負い込むなんてプログラマーじゃないですよ！  
-->

<!-- -->  
<!-- -->  
## といいつつ、実は・・・



残酷なことに、   
**GitHubのアカウントはプログラマーの履歴書になってしまう**  
のです・・・。  
<!-- -->  
GitHubにアカウントを持っていないプログラマーなんて、そんなプログラマーはいないんです・・・。  
これからいっぱい使って立派なプログラマーになるんだ・・・ (´・ω・`)  


# 俺たちの戦いはこれからだ！  


