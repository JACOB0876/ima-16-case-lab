# IMA 第 16 届案例赛训练站

Netlify 站点的 Git 部署源。仓库根目录就是站点根目录。

## 文件

- `index.html`：单页应用（学习路线、案例拆解、计算实验室、词典）
- `finance.js`：计算实验室的财务计算库
- `basics-data.js`：基础课程数据
- `netlify.toml`：Netlify 发布配置（publish = "."，无构建命令）

## Netlify 关联方式

Site configuration → Build & deploy → Continuous deployment → Link repository → 选择本仓库 → 分支 `main` → Publish directory 填 `.` → 保存。

关联后每次 push 到 `main` 会自动部署。

## 本地预览

直接用浏览器打开 `index.html` 即可（需要同目录下有上述两个 js 文件）。
