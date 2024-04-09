# kit-proxy-win
Windows環境かつ学内環境の人がgit開発が出来るシェルスクリプト
```
#ひな形
git config --global http.[URL].proxy  http://[proxy]:[port]
```
```
#win版　プロキシ設定方法
git config --global http.https://github.com/EtoEto32/1-run-per-day.git.proxy http://wwwproxy.kanazawa-it.ac.jp:8080
```
```
git config --global -l　#実行結果を確認する
[http "https://github.com/"]
    proxy = http://sample.com:8080

#~/.gitconfigファイルに記述されています。
```
```
#補足　全てのファイルで設定を適応する方法
git config --global http.proxy http://[proxy]:[port]
```
```
#補足2 プロキシ無効化
git config --global http.<url>.proxy ""
```
