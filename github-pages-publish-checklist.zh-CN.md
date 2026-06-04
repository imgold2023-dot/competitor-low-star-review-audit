# GitHub Pages 发布清单

日期：2026-06-04  
用途：把 `public-shopify-returns-radar` 目录发布成公开 URL。  
边界：创始人亲自操作 GitHub 账号和发布设置；AI 员工只准备文件和步骤。

## 发布前文件

需要发布的文件：

- `index.html`
- `sample-report.html`
- `README.zh-CN.md`
- `index.zh-CN.md`
- `sample-report.zh-CN.md`
- `feedback-log.zh-CN.md`
- `reply-templates.zh-CN.md`
- `.nojekyll`

## 推荐 repo 设置

| 字段 | 建议 |
| --- | --- |
| Repo 名 | `competitor-low-star-review-audit` |
| 可见性 | Public |
| Description | `A public sample of a competitor low-star review audit for indie builders.` |
| Topics | `competitor-analysis`, `shopify`, `saas`, `indie-hackers`, `market-research` |
| Pages source | Deploy from branch |
| Branch | `main` |
| Folder | `/root` |

## 手动发布步骤

1. 在 GitHub 创建公开 repo。
2. 把本目录里的文件放到 repo 根目录。
3. 提交到 `main`。
4. 打开 repo 的 `Settings > Pages`。
5. Source 选择 `Deploy from branch`。
6. Branch 选择 `main` 和 `/root`。
7. 等 GitHub 生成 Pages URL。
8. 打开 URL，检查首页和 `sample-report.html` 都能访问。
9. 把公开 URL 填回发布帖和反馈日志。

## 发布后检查

| 检查项 | 结果 |
| --- | --- |
| 首页可打开 | 待填写 |
| 样例报告页可打开 | 待填写 |
| Ko-fi profile 链接可打开 | 待填写 |
| GitHub 作品链接可打开 | 待填写 |
| 移动端阅读不拥挤 | 待填写 |
| 没有自动收款承诺 | 待填写 |
| 没有登录客户账号、付款、退款或隐私承诺 | 待填写 |

## 发布后要更新的文件

拿到公开 URL 后，更新：

- `feedback-log.zh-CN.md` 的发布记录。
- `promotion-tracker.csv` 的 Static HTML 行 URL。
- `shopify-returns-radar-publish-packet.zh-CN.md` 的帖子链接。

## 不要做

- 不要打开自动付款入口，除非平台规则、退款规则和交付承诺已经由创始人确认。
- 不要承诺登录客户后台。
- 不要承诺自动处理退款、争议、KYC、税务或外汇。
- 不要在多个社区批量复制同一段推广文。
