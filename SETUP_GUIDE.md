# 网站设置和运行指南

## 🚀 快速开始

这是您的个人学术网站，基于Jekyll和Academic Pages模板构建。

## 📝 需要完善的内容

### 1. 个人信息更新
请编辑以下文件来完善您的个人信息：

#### `_pages/about.md`
- 填写具体的研究领域
- 添加研究兴趣
- 更新教育背景

#### `_pages/cv.md`
- 更新教育经历
- 添加研究经验
- 完善技能列表
- 添加奖项和荣誉

#### `_config.yml`
- 取消注释并填写学术社交媒体链接：
  ```yaml
  googlescholar: "https://scholar.google.com/citations?user=YOUR_ID"
  orcid: "https://orcid.org/YOUR-ORCID-ID"
  researchgate: "https://www.researchgate.net/profile/YOUR_PROFILE"
  ```

### 2. 发表论文
在 `_publications/` 目录下：
- 删除示例文件
- 添加您的真实论文，参考现有格式

### 3. 博客文章
在 `_posts/` 目录下：
- 删除示例文章
- 添加您的博客文章

## 🛠️ 本地运行

### 方法1：使用Docker（推荐）
```bash
# 拉取Jekyll Docker镜像
docker pull jekyll/jekyll:latest

# 在项目目录运行
cd /path/to/your/site
docker run --rm -it -p 4000:4000 -v $(pwd):/srv/jekyll jekyll/jekyll:latest jekyll serve --host 0.0.0.0
```

### 方法2：使用Ruby（如果遇到依赖问题）
```bash
# 安装依赖
bundle install --path vendor/bundle

# 运行网站
bundle exec jekyll serve --host localhost --port 4000
```

### 方法3：使用GitHub Codespaces
1. 在GitHub仓库页面点击"Code" > "Codespaces"
2. 创建新的Codespace
3. 在终端运行：`bundle exec jekyll serve`

## 🌐 部署到GitHub Pages

1. 确保仓库名为 `HENGRUIZZZZ.github.io`
2. 推送代码到GitHub
3. 在仓库设置中启用GitHub Pages
4. 选择源为 `Deploy from a branch` 和 `main` 分支
5. 网站将在 `https://HENGRUIZZZZ.github.io` 可访问

## 📁 重要文件说明

- `_config.yml` - 网站主配置文件
- `_pages/` - 主要页面（About, CV, Publications等）
- `_posts/` - 博客文章
- `_publications/` - 发表论文
- `_data/navigation.yml` - 导航菜单配置
- `images/` - 图片资源（包括头像 profile2.png）

## 🔧 常见问题

### Q: 如何更换头像？
A: 替换 `images/profile2.png` 文件，或在 `_config.yml` 中修改 `avatar` 设置。

### Q: 如何添加新页面？
A: 在 `_pages/` 目录下创建新的 `.md` 文件，并在 `_data/navigation.yml` 中添加导航链接。

### Q: 网站更新后多久生效？
A: GitHub Pages通常在推送后几分钟内更新，最多可能需要10分钟。

## 📞 获取帮助

- [Jekyll官方文档](https://jekyllrb.com/docs/)
- [Academic Pages文档](https://github.com/academicpages/academicpages.github.io)
- [GitHub Pages文档](https://docs.github.com/en/pages)
