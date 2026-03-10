# TinaRen 的 AI 作品集

个人 AI 作品展示网站，包含 AI 游戏、AI 应用和 AI 视频作品。

## 特性

- 🎨 霓虹渐变效果和动态背景
- ✨ 交互式卡片设计，悬停发光效果
- 📱 完全响应式布局，适配手机和电脑
- 🎬 嵌入式 YouTube 视频播放
- 🚀 纯静态网站，易于部署

## 部署到 Vercel

### 方法一：通过 Vercel CLI（推荐）

1. 安装 Vercel CLI：
```bash
npm install -g vercel
```

2. 在项目目录下运行：
```bash
cd /home/omnisky/Documents/claude/ai-portfolio
vercel
```

3. 按照提示完成部署

### 方法二：通过 GitHub + Vercel

1. 将项目推送到 GitHub：
```bash
cd /home/omnisky/Documents/claude/ai-portfolio
git init
git add .
git commit -m "Initial commit: AI Portfolio"
git remote add origin <你的GitHub仓库地址>
git push -u origin main
```

2. 访问 [Vercel](https://vercel.com)
3. 点击 "Import Project"
4. 选择你的 GitHub 仓库
5. 点击 "Deploy"

### 方法三：拖拽部署

1. 访问 [Vercel](https://vercel.com)
2. 直接将 `ai-portfolio` 文件夹拖拽到 Vercel 网页上
3. 等待部署完成

## 本地预览

```bash
cd /home/omnisky/Documents/claude/ai-portfolio
python3 -m http.server 8000
```

然后访问 http://localhost:8000

## 自定义

- 替换头像：将你的头像图片命名为 `avatar.jpg` 放在项目根目录
- 修改内容：编辑 `index.html` 文件
- 调整样式：修改 `<style>` 标签内的 CSS

## 技术栈

- HTML5
- CSS3（动画、渐变、响应式）
- JavaScript（YouTube API）
- Vercel（部署平台）

## 联系方式

Email: renhong6@gmail.com
小红书: @Tina读书时间