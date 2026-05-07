# AI 毕业设计展示网站

一个现代化的毕业设计展示平台，展现多模态大语言模型推理加速与轻量化部署研究。

## 快速部署 (Vercel)

### 方法一：自动部署 (推荐)

1. **创建 GitHub 账号** (如果还没有) → https://github.com/signup

2. **创建新仓库**
   - 点击 New Repository
   - 名称填 `ai-graduation-showcase`
   - 选 "Public"
   - 勾选 "Add a README file"
   - 点 "Create repository"

3. **上传文件**
   - 打开新仓库，点 "Add file" → "Upload files"
   - 选择本目录下的所有文件 (index.html, vercel.json 等)
   - 提交

4. **部署到 Vercel**
   - 访问 https://vercel.com/signup (用 GitHub 账号登录)
   - 点 "New Project"
   - 选择你刚才创建的仓库
   - 点 "Deploy"
   - **完成！** 网址会自动生成

### 方法二：快速本地部署测试

```bash
# 如果你有 Python
python -m http.server 8000

# 然后访问 http://localhost:8000
```

## 文件结构

```
.
├── index.html       # 主网页 (所有内容都在这个文件里)
├── vercel.json      # Vercel 配置
└── README.md        # 本文件
```

## 网站特性

✨ **亮色优雅主题** - 浅灰白底色 + 温暖金色点缀  
🎨 **响应式设计** - 完美适配手机、平板、桌面  
⚡ **无依赖** - 完全自包含，无需服务器  
🎬 **交互动画** - 滚动显示、悬停效果  

## 自定义内容

在 `index.html` 中搜索以下内容可快速修改：

- `[方括号]` 内的文本都是占位符
- 所有图像占位符会显示渐变背景

## 技术栈

- HTML5
- CSS3 (Grid, Flexbox, Gradients)
- Vanilla JavaScript (Intersection Observer)
- Google Fonts (Cormorant Garamond, Outfit, JetBrains Mono)

## 许可证

MIT License - 自由使用与修改
