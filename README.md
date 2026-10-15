# 链接·梦角 · 专属占卜

一个纯前端 HTML 小工具，可直接部署到 GitHub Pages。

## 文件说明
- `index.html`：网页主文件
- `.nojekyll`：避免 GitHub Pages 对文件进行 Jekyll 处理

## 部署到 GitHub Pages
1. 登录 GitHub，创建一个新的仓库（Repository）。
2. 将本压缩包中的文件解压。
3. 进入仓库，点击 **Add file → Upload files**，上传 `index.html`、`.nojekyll` 和 `README.md`。
4. 点击 **Commit changes** 保存。
5. 打开仓库的 **Settings → Pages**。
6. 在 **Build and deployment** 中选择 **Deploy from a branch**。
7. Branch 选择 `main`，目录选择 `/(root)`，点击 **Save**。
8. 等待部署完成，Pages 页面会显示网页地址，格式通常为：
   `https://你的GitHub用户名.github.io/仓库名/`

## 备注
- 本项目是单文件网页，无需安装依赖、无需构建。
- 上传背景图仅在当前打开的页面中生效；刷新页面后通常需要重新选择背景图。
