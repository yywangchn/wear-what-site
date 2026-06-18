# 明天穿啥 GitHub Pages 站点

这个文件夹是一套纯静态页面，可以直接放到新的 public GitHub 仓库根目录，用于 GitHub Pages 发布。

## 文件说明

- `index.html`：App 展示页
- `privacy.html`：Google Play 可填写的隐私政策页
- `styles.css`：页面样式
- `assets/app-icon.png`：App 图标

## 发布步骤

1. 确认仓库是 public，或你的 GitHub 账号支持 private 仓库发布 Pages。
2. 提交并推送当前文件到 GitHub。
3. 进入仓库 `Settings` -> `Pages`。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择当前发布分支，目录选择 `/root`，保存。
6. 等待 GitHub Pages 部署完成。

发布后，隐私政策地址通常是：

```text
https://你的用户名.github.io/仓库名/privacy.html
```

把这个地址填到 Google Play Console 的“隐私权政策网址”输入框。

## 需要替换的内容

发布前请确认 `privacy.html` 里的联系邮箱是你的真实可用邮箱：

```text
yuywangchn@gmail.com
```

如果 Google Play 地址已经生成，也可以打开 `index.html`，把“获取应用”的链接改成你的 Google Play 应用地址。
