# 清清静听技术支持网站

这是一个纯静态的 GitHub Pages 网站，提供：

- 使用帮助和常见问题
- 本地数据与内购说明
- 隐私政策
- GitHub Issues 技术支持入口

预计公开地址：

- 技术支持：`https://ktn4sgrtgc-gif.github.io/qingqingjingting-support/`
- 隐私政策：`https://ktn4sgrtgc-gif.github.io/qingqingjingting-support/privacy.html`

## 发布

仓库名使用 `qingqingjingting-support`，可见性设置为 Public。

推送代码后，在仓库的以下位置启用 Pages：

1. Settings
2. Pages
3. Build and deployment
4. Source 选择 `GitHub Actions`

`.github/workflows/pages.yml` 会在推送到 `main` 后自动部署。

## 本地预览

在项目目录运行：

```bash
python3 -m http.server 8080
```

然后访问 `http://127.0.0.1:8080/`。
