# PhD Research Hub · 博士研究文献管理与分析系统

一个可直接部署到 GitHub Pages 的静态网页 MVP，支持文献录入、检索、编辑、状态分类、研究缺口记录，以及 JSON 导入/导出和 CSV 导出。

## 部署步骤

1. 在 GitHub 创建公开仓库 `phd-research-hub`。
2. 将本文件与 `index.html` 上传至仓库 **根目录** 并提交。
3. 打开 Settings → Pages → Build and deployment。
4. Source 选择 **Deploy from a branch**；Branch 选择 **main**，目录选择 **/(root)**，点击 Save。
5. 打开 `https://你的用户名.github.io/phd-research-hub/`。

## 注意事项

- 数据只保存在**当前浏览器的 localStorage**；无账号、后端、云端同步或自动备份。
- 定期点击 **导出 JSON**，把文件另存到安全位置；CSV 可在 Excel/WPS 中打开。
- 浏览器清缓存、更换浏览器或设备，可能导致看不到先前的记录。
- GitHub Pages 网站**公开可访问**，请不要把未发表研究资料、隐私信息、API 密钥写入公开仓库或前端源代码。
- 网站程序代码与个人文献数据是分开的；导出的私人 JSON 不应上传到公开仓库。

## 技术

原生 HTML + CSS + JavaScript，无需 Node.js、数据库、编译命令或外部依赖。
