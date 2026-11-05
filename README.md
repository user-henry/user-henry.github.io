**简体中文** | [English](README.en.md)

# huangzhiyuan · 个人作品集

> 网站与软件开发者黄志远（GitHub：user-henry）的个人作品集：精选作品、简介、技能与联系方式。

在线访问：**<https://user-henry.github.io/>**

## 内容

- **精选作品**：NFLSHC Chat、HZYAI、ScreenTool、Clipboard Queue、化石信息管理、Web macOS、Web Linux、OrbitLive，共 8 个项目
- **简介 / 技能 / 联系方式**
- 响应式布局、滚动动画、作品分类筛选
- 联系表单**只把内容保存在本机浏览器**，不会发送到任何服务器

## 技术说明

- 由 TanStack Start（React 19 + Vite + Tailwind CSS 4）构建，导出为静态站点后托管在 GitHub Pages
- 资源路径与部署路径一致，当前部署在 `https://user-henry.github.io/`
- 使用 `.nojekyll` 关闭 Jekyll，确保 `__grok` 等以下划线开头的目录被正常发布

## 本地预览

```bash
python -m http.server 8080
# 打开 http://127.0.0.1:8080/
```

## 目录结构

```text
index.html              首页（已预渲染的 HTML）
404.html                未找到页面（与首页一致）
assets/                 JS 与 CSS
images/                 作品截图与头像
__grok/                 PWA 图标
manifest.webmanifest    PWA 清单
.nojekyll               跳过 Jekyll 处理
```

## 版权

页面内容与作品图片归 huangzhiyuan 所有；字体由 Google Fonts（Noto Sans SC / Noto Serif SC，OFL）提供。
