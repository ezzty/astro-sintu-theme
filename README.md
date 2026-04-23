# Astro Sintu Theme

A simple blog theme, optimized single-column layout for mobile/tablet，originally designed by the author.

一个简洁的单栏 Astro 博客自适应主题，作者jin原创设计。

## Features 特性

🚀 Powered by Astro 6.x – High performance guaranteed.

🌙 Dark Mode Support – Seamless switching between light and dark themes.

📱 Responsive Design – Fully optimized for mobile and diverse screen sizes.

🎨 Clean & Elegant – Minimalist design focused on readability.

📝 Markdown Blogging – Built-in support for Markdown-based content.

- 🚀 基于 Astro 6.x，性能优异
- 🌙 暗黑模式支持
- 📱 响应式设计，移动端优化
- 🎨 简洁优雅的设计风格
- 📝 支持 Markdown 博客文章

## Quick Start 快速开始 

```bash
# Install dependencies 安装依赖
npm install

# Start development server 开发模式
npm run dev

# Build for production 构建生产版本
npm run build

# Preview production build 预览构建结果
npm run preview
```

## Configuration 配置

### Image Processing 图片处理

- Image Optimization: Automatically scale homepage thumbnails using Alibaba Cloud OSS image processing parameters.
- 图片用阿里云oss自动添加参数能实现首页缩略图自动缩放；


### Theme Colors 主题颜色

- Edit  `src/styles/variables.css`  to customize the theme colors.
- 编辑 `src/styles/variables.css` 修改主题颜色。

## Deployment 部署

### Static Hosting 静态托管

- The built dist/ directory can be deployed to any static hosting service: 
- 构建后的 `dist/` 目录可以部署到任何静态托管服务：

- Vercel
- Netlify
- Cloudflare Pages
- GitHub Pages
- AWS AMPLIFY

### Docker

```bash
docker build -t astro-sintu-theme .
docker run -p 8080:80 astro-sintu-theme
```

## Tech Stack 技术栈

- [Astro](https://astro.build/) - 静态站点生成器
- TypeScript - 类型安全
- CSS Variables - 主题定制

## License 许可证

MIT

## 作者

Jin (@ezzty)
