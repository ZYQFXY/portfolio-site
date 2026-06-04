# 赵永旗 - 个人简历网站 / 作品集

> AI 原生开发者 · 作品集官网

## 📁 项目结构

```
portfolio-site/
├── index.html      # 作品集网站（单页 HTML，可直接在浏览器打开）
├── README.md        # 本文件
```

## 🌐 在线访问

**网站地址：https://models.aiznt.com**

## 📄 相关文件

- **优化版 PDF 简历** → `../赵永旗-个人简历-优化版.pdf`
- **原始简历 PDF** → `../赵永旗-个人简历.pdf`

## 🚀 本地开发

### 方式一：直接打开（无需任何工具）

直接双击 `index.html` 在浏览器中打开即可预览。

### 方式二：简单 HTTP 服务器

```bash
# Python（进入 portfolio-site 目录）
python -m http.server 8080

# Node.js（需要 http-server）
npx http-server . -p 8080
```

然后访问 http://localhost:8080

### 方式三：部署到 GitHub Pages

1. 将 `portfolio-site` 文件夹推送到 GitHub 仓库
2. 在仓库 Settings → Pages → Source 选择 `main` 分支
3. 访问 `https://yourusername.github.io/repo-name/`

### 方式四：部署到 Vercel / Netlify

1. 上传整个文件夹到 GitHub
2. 连接 GitHub 到 Vercel 或 Netlify，自动部署

## 📝 网站内容模块

| 模块 | 说明 |
|------|------|
| Hero | 个人信息 + 标签徽章 |
| 关于我 | AI 原生实践者定位 + 数据亮点 |
| 实习经历 | 杭州易有料科技有限公司 |
| 项目作品 | 6 个项目，含链接和技术栈 |
| 核心技能 | 4 大类技能标签 |
| Footer | 联系方式 + PDF 下载链接 |

## ✏️ 更新内容

编辑 `index.html` 中各 section 的内容即可。所有样式已内联，无需额外 CSS 文件。

如需替换 PDF 简历，重新生成后放在上级目录并确保文件名一致即可。## 🎯 设计理念

- **单文件部署**：纯 HTML + 内联 CSS，无需构建工具
- **二维码友好**：手机扫描可直接访问作品集
- **作品集+简历联动**：Footer 内置 PDF 简历下载链接，面试官可直接下载优化版简历
- **SEO 优化**：Meta 标签完整，可被搜索引擎收录