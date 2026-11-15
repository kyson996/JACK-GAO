# Jack Q. Gao 个人网站

完整静态网站：HTML、CSS、JavaScript 和图片均已包含。无需 npm、构建命令、API Key 或后端。

## 本地查看
解压后双击 index.html 即可。请保持 assets 文件夹与 index.html 在同一级。

## 上传到 GitHub
1. 打开目标仓库。若仓库已有其他项目，建议使用一个新的空仓库，避免覆盖首页。
2. 点击 Add file → Upload files。
3. 上传解压后的 index.html、assets 文件夹、README.md 等内容，不要仅上传 ZIP。
4. 确保 index.html 在仓库根目录，不要多套一层文件夹。
5. 点击 Commit changes，保存至 main 分支（若使用其他分支，以下设置选择对应分支）。

## 使用 GitHub Pages 上线
1. 打开仓库 Settings → Pages。
2. 在 Build and deployment 下，将 Source 设为 Deploy from a branch。
3. Branch 选择 main，文件夹选择 /(root)，点击 Save。
4. 等待部署完成，从 Pages 页面打开网站链接；如失败，在 Actions 查看错误信息。

上传仓库只是保存代码，启用 Pages 才会生成网站。GitHub Free 可使用公开仓库的 Pages；私有仓库支持取决于套餐。
本代码包不包含原托管平台的 ChatGPT 登录保护。普通 GitHub Pages 发布后是公开网站，即使源仓库私有也不代表网站私有。如果只想存代码，可使用私有仓库并暂不启用 Pages。

## 文件与修改
- index.html：页面结构、全部 CSS 样式和中英文切换脚本。
- assets/profile.png：所提供的资料截图，页面使用 CSS 显示其中头像区域；原始截图仍可被访问。
- .nojekyll：静态发布标记。
- .gitignore：忽略常见本机临时文件。

中英文文案位于 index.html 的 data-zh、data-en 属性。修改后重新提交，即可触发 Pages 更新。
联系区域目前是 Whale TV 官网链接，不包含个人邮箱或留言后端。

GitHub 官方说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
