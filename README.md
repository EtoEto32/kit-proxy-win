# kit-proxy-win
## プロキシグローバル設定（有効）
```
git config --global http.proxy http://[proxy]:[port]
```
## プロキシグローバル設定（無効）
```
git config --global --unset http.proxy
git config --global --unset https.proxy
```
## 特定の接続先のみをプロキシ設定を有効にする
```
git config --global http.[URL].proxy  http://[proxy]:[port]
```
## 設定内容を確認する
```
git config --global -l
```

