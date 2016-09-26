# Semantic UI

## [hub](https://hub.github.com)

- brew install hub
- alias git=hub

使用：

- git clone myproject 下載自己的倉儲只需輸入名稱
- git clone github/hub 下載別人的倉儲只需加入 `用戶名/倉儲名`
- git browse -- issues 會開啟瀏覽器觀看問題提報
- git browse mojombo/jekyll wiki 也可以開啟觀看其他東西

貢獻到開源專案，也很接近與其他人協作某專案的流程：

1. git clone github/hub 下載 github 的 hub 專案倉儲
2. cd hub
3. git checkout -b feature 開一個新功能的分支（本地）
4. git commit -m 'done with fearure' 做完後提交
5. git fork 在 GitHub 上 fork 專案；會自動加入遠端位置
6. git push YOUR_USER feature 將新開發（建議）的功能推到自己 fork 的倉儲
7. git pull-request 開啟文字編輯器撰寫訊息



