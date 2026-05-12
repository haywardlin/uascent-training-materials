# 集贤科技端侧语音售前培训文档

这是 GitHub Pages 部署目录。

## 文件说明

- `index.html`：培训文档首页，已内嵌图片，可直接作为单页网页发布。
- `.nojekyll`：避免 GitHub Pages 使用 Jekyll 处理静态文件。

## GitHub Pages 发布方式

1. 在 GitHub 新建一个仓库，例如：`uascent-voice-training`
2. 将本目录下所有文件推送到仓库根目录。
3. 进入仓库 `Settings > Pages`
4. Source 选择 `Deploy from a branch`
5. Branch 选择 `main`，目录选择 `/root`
6. 保存后等待 1-2 分钟。

发布后访问地址通常为：

```text
https://你的GitHub用户名.github.io/uascent-voice-training/
```

## 后续更新

每次更新培训文档后，将新的 HTML 覆盖为 `index.html`，然后提交并推送即可。
