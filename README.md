# app-privacy-policies

各 App 的隱私權政策，透過 GitHub Pages 對外服務。每個 App 一個子路徑，
`main` 分支的 repo 根目錄就是 Pages 的內容來源。

```
/                     根目錄索引（各 App 連結）
/<package短名>/index.html   該 App 的隱私權政策（多語，同一頁用 #zh/#en/#ja 錨點切換）
```

新增一個 App 的隱私權政策：

1. 在這裡新增一個子資料夾（例如 `picopdf/`），放一份自成一體的 `index.html`
   （不依賴這個 repo 的其他檔案，方便之後單獨搬走也不會壞）
2. 把連結加進根目錄 `index.html`
3. push 到 `main`，Pages 會自動重新部署

`happy_candle` **不在這裡**——它有自己獨立的 `happy-candle-privacy` repo，
已經是正式上架、Play Console 登記過那個網址的狀態，沒有理由搬過來冒風險。
這個共用 repo 是給 `happy_candle` 之後的新 App 用的。

政策內容的來源在各自 App 的 repo（例如 PicoPdfViewer 的
`docs/privacy.html`），改完之後要手動複製過來這裡再推——兩邊不會自動同步。
