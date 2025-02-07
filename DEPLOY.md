# 智能身高计算器部署指南

本指南将帮助您将智能身高计算器部署到GitHub Pages上。请按照以下步骤操作：

## 1. 准备工作

1. 确保您已经安装了Git
   - 在终端中运行 `git --version` 检查是否已安装
   - 如果未安装，请从 https://git-scm.com/downloads 下载并安装

2. 注册GitHub账号
   - 访问 https://github.com
   - 点击 "Sign up" 注册新账号（如果已有账号则跳过此步骤）

## 2. 创建GitHub仓库

1. 登录GitHub账号
2. 点击右上角 "+" 按钮，选择 "New repository"
3. 在 "Repository name" 中输入 "180CM"
4. 选择 "Public" 选项
5. 点击 "Create repository"

## 3. 配置本地仓库

在终端中执行以下命令：

```bash
# 进入项目目录
cd 项目所在路径/180CM

# 初始化Git仓库
git init

# 添加所有文件到暂存区
git add .

# 提交更改
git commit -m "Initial commit"

# 添加远程仓库（将 username 替换为您的GitHub用户名）
git remote add origin https://github.com/username/180CM.git

# 推送代码到GitHub
git push -u origin main
```

## 4. 配置GitHub Pages

1. 在GitHub仓库页面，点击 "Settings"
2. 在左侧菜单中找到并点击 "Pages"
3. 在 "Source" 部分，选择 "Deploy from a branch"
4. 在 "Branch" 下拉菜单中选择 "main"，点击 "Save"
5. 等待几分钟，您的网站将被部署到 `https://username.github.io/180CM`

## 5. 验证部署

1. 访问 `https://username.github.io/180CM`
2. 确认网站是否正常运行
3. 测试所有功能是否正常工作

## 注意事项

- 确保所有文件都已正确提交到仓库
- 部署可能需要几分钟时间
- 如果遇到问题，请检查GitHub Pages设置是否正确
- 记得将链接中的 "username" 替换为您的GitHub用户名