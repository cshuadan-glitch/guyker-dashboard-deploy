# Guyker 运营看板 · 部署仓库

这个仓库**只放看板的静态产物**(`index.html`),由 launchd 每天北京 15:00 自动从源工作目录(`~/Desktop/ecom-dashboard/`)重建并推送上来。

- **源代码**:在 `~/Desktop/ecom-dashboard/`(含数据、凭证、脚本,**不入 Git**)
- **本仓库**:只对外公开看板 HTML(给 Zeabur 拉取部署)
- **部署**:Zeabur 静态站,自动从此仓库 main 分支拉
- **访问**:`https://guyker-dashboard.zeabur.app`(具体域以 Zeabur 配置为准)

⚠️ 看板 HTML 内嵌真实财务数据(Guyker 销售/利润/客户)。仓库设 **Private**,Zeabur 站建议加访问口令。
