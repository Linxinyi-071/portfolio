# 个人作品集网站 (Portfolio)

## 简介

面向外部用户的个人作品集网站，展示自主开发的桌面效率工具。支持中英双语切换，采用卡片式视觉设计。

## 工具列表

| 工具 | 说明 |
|------|------|
| HTML 批量对比工具 | 批量对比 HTML 文件差异，智能过滤标签属性 |
| 界面词校验工具 | 从 PDF 提取界面词并对照术语表 |
| 界面词定位工具 | OCR 识别定位术语在文档中的位置 |

## 技术栈

- 纯 HTML/CSS/JavaScript（零依赖）
- 响应式布局，适配桌面与移动端
- 中英双语切换（localStorage 持久化）

## 配置

编辑 `js/main.js` 中的以下配置：

```javascript
const GITHUB_USER = "Linxinyi-071";  // GitHub 用户名
```

## 部署

### GitHub Pages

1. 将本文件夹推送到 GitHub 仓库
2. 仓库 Settings → Pages → Source 选择 `main` 分支 `/root` 目录
3. 访问 `https://YOUR_USERNAME.github.io/REPO_NAME/`

### 本地预览

直接用浏览器打开 `index.html` 即可。
