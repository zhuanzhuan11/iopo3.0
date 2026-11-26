# iopo3.0

OPO 商城独立原型仓库。当前版本以已确认并公开的 `opo1-preview` 单页原型为基线，保留原有页面与交互，便于后续逐步拆分和升级。

## 在线预览

GitHub Pages：<https://zhuanzhuan11.github.io/iopo3.0/>

## 目录

- `apps/storefront/index.html`：静态商城交互原型，包含当前页面与演示逻辑。
- `docs/`：项目范围、维护和发布说明。
- `.github/workflows/pages.yml`：推送到 `main` 后自动发布 GitHub Pages。

## 本地查看

直接用浏览器打开 `apps/storefront/index.html`。本地打开时浏览器权限可能限制部分功能；通过 Pages 链接体验更完整。

## 当前范围

本仓库只包含静态界面原型。商品、会员、OPoc 积分、推荐关系、订单、快捷支付和分润均为浏览器内的模拟展示，不连接支付机构，不创建真实订单，也不接收真实资金或积分。它不具备生产商城所需的服务端、数据库、身份权限、安全、对账、审计、备份、监控或运营能力。生产上线需另行建设后端并完成相应经营与合规评估。

## 维护

提交界面修改到 `apps/storefront/index.html`；保持纯静态资源和相对路径，避免提交凭据、生产配置、真实用户/交易数据或截图。发布流程见 [`docs/发布与维护.md`](docs/发布与维护.md)，范围说明见 [`docs/产品范围与边界.md`](docs/产品范围与边界.md)。
