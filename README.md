## 記事の投稿
/content/posts以下に.mdファイルを追加する

## ローカルで実行する
Hugoをインストール
```powershell
winget install Hugo.Hugo.Extended
hugo version
```
githubのリポジトリをクローン
```powershell
git clone https://github.com/ki1989/hugo-blog.git
git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)
```
Hugoを開発モードで起動
```powershell
hugo server
```
ブラウザで開く

http://localhost:1313/

## リソース
- Hugo
https://gohugo.io/getting-started/quick-start/

- Paper Mod(Hugo Theme)
https://adityatelange.github.io/hugo-PaperMod/

- netlify
https://docs.netlify.com/get-started/