# 敦煌瑞羊 · 金沙与原画彩色

沉浸式三维粒子交互网站。拖动拨沙、松手重聚，支持金沙与原画彩色切换、模型旋转、触屏操作与本地运动数据录制。

- [金沙版](https://zxl9456-hub.github.io/dunhuang-golden-ram/)
- [原画彩色版](https://zxl9456-hub.github.io/dunhuang-golden-ram/?style=color)

## 源码与发布

`site-source.zip` 包含完整静态网站与依赖许可。解压后网站位于 `dunhuang-golden-ram/dist/`。

GitHub Actions 校验源码包 SHA-256，解压静态文件并发布到 GitHub Pages。无需安装 npm 依赖。更新源码包时同步更新 `.github/workflows/pages.yml` 中的 SHA-256。

本地预览：`python3 -m http.server 4317 --directory dunhuang-golden-ram/dist`。

摄像头手势需要 HTTPS、浏览器摄像头授权与兼容的设备；部分应用内置浏览器可能限制摄像头。运动录制在本地生成数据包，不上传摄像头视频。
