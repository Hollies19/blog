# Blog Starter (GitHub Pages / Jekyll / Minima)

## 部署为项目站点（路径 /blog）
1. 新建一个仓库（建议名称：`blog`）。
2. 将本文件夹所有内容上传到仓库根目录。
3. 进入仓库 **Settings → Pages**：
   - Source: `Deploy from a branch`
   - Branch: `main`，Directory: `/ (root)`
4. 稍等片刻，访问：`https://你的用户名.github.io/blog/`

> 如果你希望博客作为根站点（不在 /blog/ 下），将 `_config.yml` 中的 `baseurl` 置空，并部署到你的用户名仓库 `你的用户名.github.io`。
