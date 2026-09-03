# 互动祝福贺卡

一张单文件、可直接部署的互动 HTML 贺卡。点击蜡封即可展开信笺并播放祝福动画。

## 本地预览

直接用浏览器打开 `index.html`，或在本目录运行：

```powershell
python -m http.server 8080
```

然后访问 `http://localhost:8080`。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个空仓库，例如 `birthday-greeting-card`。
2. 将本地仓库关联并推送：

```powershell
git remote add origin https://github.com/<你的用户名>/birthday-greeting-card.git
git branch -M main
git push -u origin main
```

3. 在 GitHub 仓库中进入 **Settings → Pages**，将部署来源设为 **Deploy from a branch**，选择 `main` 分支和 `/(root)` 目录。
4. 保存后，GitHub 会生成一个可在 iPhone Safari 打开的公开网址。

## 自定义内容

直接编辑 `index.html` 中的称呼、标题和祝福文字即可。
