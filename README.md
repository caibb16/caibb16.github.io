# caibb16.github.io个人主页

此目录包含由 Hugo 自动生成的静态网站文件。

## ⚠️ 注意事项

- **请勿手动编辑此目录中的文件**
- 此目录的所有内容会在每次运行 `hugo` 命令时被重新生成
- 修改内容请编辑 `content/` 目录中的源文件

## 🔄 重新生成

```bash
# 清理并重新构建
hugo --gc --cleanDestinationDir

# 或简单构建
hugo
```

## 📁 目录结构

| 目录/文件 | 说明 |
|-----------|------|
| `index.html` | 网站首页 |
| `sitemap.xml` | 站点地图 |
| `index.xml` | RSS 订阅源 |
| `p/` | 博客文章页面 |
| `page/` | 分页页面 |
| `categories/` | 分类页面 |
| `tags/` | 标签页面 |
| `archives/` | 归档页面 |
| `search/` | 搜索页面 |
| `zh-cn/` | 中文内容 |
| `en/` | 英文内容 |
| `scss/` | 编译后的 CSS 样式 |
| `img/` | 图片资源 |

## 🚀 部署

此目录的内容可直接部署到任何静态网站托管服务：

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- 等等
