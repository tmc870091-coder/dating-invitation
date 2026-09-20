# 浪漫約會邀請網站

這是一個粉嫩浪漫的四步驟單頁約會邀請網站：

1. 接受約會邀請
2. 選擇約會日期
3. 複選想一起進行的行程
4. 產生專屬情書並將計畫保存到瀏覽器的 `localStorage`

## GitHub Pages

網站透過 `.github/workflows/deploy-pages.yml` 自動部署。將變更推送到 `main` 分支後，GitHub Actions 會使用官方的 Pages actions 建置並發布根目錄的靜態檔案；也可以在 Actions 頁面手動執行 `workflow_dispatch`。

首次使用時，請到 repository 的 **Settings → Pages**，將 **Source** 設為 **GitHub Actions**。公開網址：

<https://tmc870091-coder.github.io/dating-invitation/>
