# GitHub 文件分享系统

这是一个基于 GitHub Pages 和 GitHub Issues 的简单文件分享系统。它允许用户上传文件并生成可分享的链接，所有文件都存储在 GitHub Issues 中。

## 特性

- 拖放文件上传
- 文件列表显示
- 文件下载功能
- 完全静态部署
- 无需服务器
- 基于 GitHub Issues 存储

## 部署步骤

1. Fork 这个仓库到你的 GitHub 账号

2. 创建 GitHub Personal Access Token:
   - 访问 https://github.com/settings/tokens
   - 点击 "Generate new token"
   - 选择 "repo" 权限
   - 复制生成的 token

3. 修改 `index.html` 文件:
   - 将 `YOUR_USERNAME/YOUR_REPO` 替换为你的 GitHub 用户名和仓库名
   - 将 `YOUR_TOKEN` 替换为你的 Personal Access Token

4. 启用 GitHub Pages:
   - 进入仓库设置
   - 找到 "Pages" 选项
   - 选择 main 分支作为源
   - 保存设置

5. 访问你的文件分享系统:
   - 网址格式为: `https://[你的用户名].github.io/[仓库名]`

## 使用说明

1. 上传文件:
   - 点击"选择文件"按钮或将文件拖放到上传区域
   - 等待上传完成

2. 下载文件:
   - 在文件列表中找到需要的文件
   - 点击"下载"按钮

## 注意事项

- GitHub Issues 有文件大小限制，建议不要上传超过 25MB 的文件
- Personal Access Token 请妥善保管，不要泄露
- 建议定期清理不需要的文件（关闭对应的 Issues）

## 技术栈

- HTML5
- CSS3
- JavaScript (ES6+)
- GitHub API
- GitHub Pages

## 许可证

MIT License 