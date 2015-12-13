# GitHubを使おう

<!-- -->  
BS企業  
LT201512  
佐藤誠  


# GitHubを使わざればプログラマーに非ず！



# GitHubとは



## こんなサービス

端的にはGitホスティングサービス。  
特徴的なのは・・・  



- PullRequest  
    ご存知 'プルリク', 'プルリ', 'PR'  
    GitにはPullRequest機能なし。  
    サードパーティーが"clone->開発->オリジナル開発者に取り込み依頼"することを機能として表現したもの。  



- Forkの概念  
    Git本体には、リポジトリーをどこから持ってきたのかを管理する機能なし。  
    GitHubでは独自にオリジナルリポジトリーを管理している。  



- markdown  
    ドキュメント類は全部markdownで。  
    GitHub上ではHTMLにレンダリングして表示される。  
    テキストなのでgitでなくてもvcsと相性よし。  
    リアルタイムレンダリングできるエディター多数(例:atom)  



## こんな便利なことができる

- issue管理  


- Github pages  
    プロジェクトを他者に説明するページ。  
    Gitリポジトリーの1ブランチ。ブランチ名を"gh-pages"にするだけ。  
    デモページ作れるし、そのままプレゼン風にもできる。(まさしく今見ているこのLTのことだ！)


- gist  
    コードスニペットを管理できる。  
    これ自身もGitリポジトリー。  


- wiki  
    ふつーにWiki。  
    これ自身もGitリポジトリー。  
    表現もMarkdownでおkなので、手元のエディターで書いてgit pushができる。  



- 自分の秘伝のタレを管理しておくと環境変わってもいけるよ  
    .vimとか.bash_profileとかdotenvを持っておくとgit cloneで自分のHomeを再現できる、かも。  
    (別にGithubじゃなくても可能だけど)  


## 広大なエコシステム

- jekyll, reveal.js  
    github pagesを便利に使える  
- issueをカンバン化  
  - trello  
  - zenhub  
- CIツール  
    ビルド通ったアイコン出る  
  - travis ci  
  - circle ci  
- provisioning  
  - ansible-galaxy  
- チャットツール  
  - slack  
  - hipchat  
- Online IDE  
  - cloud9  
  - koding  



# だからみんなGitHubを使おう

こんなに便利なサービスを使わないんですか？  
プログラマーなら楽をしましょう。  
便利な道具を無視してわざわざ苦労を背負い込むなんてプログラマーじゃないですよ！  


# そしてプログラマーになるんだ・・・

自分ではあんまり使ってないから、これから使うんだ・・・
