# 荣格八维测试静态网页

这是一个可直接部署到 GitHub Pages / 任意静态网页托管平台的单页 HTML。

## 文件结构

```txt
index.html
README.md
.nojekyll
```

## GitHub Pages 部署

1. 新建 GitHub 仓库，例如 `jung8-test`
2. 上传本文件夹内的 `index.html`、`README.md`、`.nojekyll`
3. 进入仓库 `Settings` → `Pages`
4. `Build and deployment` 选择 `Deploy from a branch`
5. Branch 选择 `main`，Folder 选择 `/root`
6. 保存后等待 GitHub Pages 发布

访问地址通常是：

```txt
https://你的用户名.github.io/jung8-test/
```

## 数据说明

- 答题记录默认保存在浏览器 localStorage
- 导出 JSON 会下载到本地
- 静态网页没有服务器数据库，换设备/换浏览器不会自动同步
