# 四级备考打卡

给最可爱的 +0 做的 2026 年 12 月 12 日大学英语四级（CET-4）每日备考打卡网页。

## 功能

- 按当天日期自动显示当天任务（47 天计划：周一到周五背单词，周末做真题）
- 逐词背单词（含音标、释义、进度条，每 10 个词弹出卡通鼓励）
- 第 2 段复习昨日单词（乱序、无释义自测）
- 周末真题（阅读/写译专项，真题全文内嵌）
- 完成打卡有礼炮+烟花庆祝动画，统计"已完成 X 天打卡"
- 可跳转到任意一天查看
- 全部打卡完成后显示鼓励语

## 使用

网页是单文件自包含（CSS/JS 全部内联），无需安装任何东西：

- 本地使用：直接用浏览器打开 `index.html` 即可
- 打卡数据保存在浏览器本地（localStorage），按设备和浏览器独立

## 部署到 GitHub Pages

1. 在 GitHub 新建仓库（Public 即可，Pages 免费）
2. 把本目录文件推上去（见下方命令）
3. 仓库 `Settings → Pages → Build and deployment → Source 选 "Deploy from a branch" → 分支 main / 根目录 → Save`
4. 等 1-2 分钟，访问 `https://<你的用户名>.github.io/<仓库名>/` 即可打开

## 推送命令

```bash
git init
git add .
git commit -m "CET4 备考打卡网页"
git branch -M main
git remote add origin https://github.com/<你的用户名>/<仓库名>.git
git push -u origin main
```
