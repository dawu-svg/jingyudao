# 鲸鱼岛 — 高中教师伴侣

一款面向高中教师的移动端 PWA 工具，辅助日常教学与班级管理。

## 技术栈

- 纯 HTML/CSS/JavaScript，零外部依赖
- PWA (可添加到手机主屏幕，离线可用)
- localStorage 数据存储

## 部署

将以下三个文件上传到任意静态服务器：

- `index.html`
- `manifest.json`
- `sw.js`

### 推荐部署方式：

**Vercel (免费)：**
```bash
npx vercel jingyudao/ --prod
```

**GitHub Pages：**
将 `jingyudao/` 目录推送到 GitHub 仓库，在 Settings → Pages 中启用。

**任意静态服务器：**
将三个文件放在同一目录下，确保通过 HTTPS 访问（PWA 要求）。

## 使用

1. 用手机浏览器打开部署后的 URL
2. 首次访问会进入新手引导
3. 按提示添加到手机主屏幕
4. 开始使用

## 纸条投放（开发者用）

1. 打开「我们」标签页
2. 滚动到底部空白区域
3. 长按 3 秒触发隐藏入口
4. 输入纸条内容、选择日期、投递
