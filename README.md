# 简单网页

纯 HTML/CSS/JavaScript 页面，无构建依赖，适配手机和电脑。

## 本地预览

在此目录执行 `python3 -m http.server 8080 --bind 127.0.0.1`，然后访问 http://127.0.0.1:8080。

## 发布到 GitHub Pages

1. 使用 `gh auth login -h github.com` 登录 GitHub。
2. 新建一个公开仓库，将 `index.html` 和 `.nojekyll` 推送到 `main` 分支。
3. 在仓库 Settings → Pages → Build and deployment 中选择 Deploy from a branch，选择 `main` 和 `/ (root)`，保存。
4. 等待部署完成，使用 Pages 设置页返回的网址访问。

GitHub Pages 托管静态页面。若需要运行 Python/Node.js 后端，则需要额外的服务器托管服务。
