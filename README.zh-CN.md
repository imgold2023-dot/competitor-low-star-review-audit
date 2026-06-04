# Shopify 退货应用低星评论审计公开页说明

日期：2026-06-04  
用途：第 5-6 天发布测试的静态公开入口。  
公开页：`index.html`
公开样例报告页：`sample-report.html`
中文伴随版本：`index.zh-CN.md`
样例报告中文伴随版本：`sample-report.zh-CN.md`
发布清单：`github-pages-publish-checklist.zh-CN.md`

## 当前状态

这个目录是“可公开链接包”，用于把免费样例和销售说明放到一个静态页面里。页面默认英文，因为第一轮外部渠道优先测试独立开发者、SaaS 创始人和 Shopify App 开发者。

页面已明确：

- 验证期只收询价，不自动收款。
- 只使用公开信息。
- 不登录客户账号，不处理订单、退款、隐私、支付、KYC 或争议。
- 价格只是测试区间，最终收款由创始人确认平台规则后再开放。

## 发布前必须确认

创始人发布前需要确认：

- Ko-fi 个人主页是否可以作为留言或询价入口。
- GitHub 链接是否仍适合作为公开作品证明。
- 是否已经接受“先收询价，不自动收款”的发布边界。
- 是否需要把页面托管到 GitHub Pages、Cloudflare Pages、Netlify 或其他静态站。
- `sample-report.html` 是否能从首页打开。

如果没有公开 URL，不要发布需要链接的英文长帖；可以先发不带链接的讨论帖，测试评论。

## 推荐托管方式

第一选择：GitHub Pages。

理由：

- 零成本。
- 和目标用户信任链一致。
- 页面是纯静态 HTML，不需要服务器、数据库或第三方脚本。

创始人需要处理：

- 创建或选择公开 repo。
- 上传本目录中的全部文件。
- 在 repo 设置里开启 Pages。
- 拿到公开 URL 后再补到发布帖里。

## 公开页文案原则

对外文案不要写：

- 大而全市场研究。
- 自动赚钱。
- 保证增长。
- 代运营、代退款、代处理争议。
- 空泛的“AI 自动分析一切”。

对外只说：

- 看公开价格。
- 看低星评论。
- 看社区讨论。
- 看免费替代方案。
- 输出 Proceed / Narrow / Hold / Reject。

## 本轮成功信号

48 小时内满足任意一条即可继续：

- 1 个明确询价。
- 3 个目标用户问“能不能看我的类目/竞品”。
- 5 个高质量反馈指出报告哪里有用或没用。

## 本轮收窄信号

- 只有点赞、收藏，没有问题。
- 大家觉得有用，但说自己会做。
- 反馈都要求“直接帮我搭建/优化”，不买报告。

如果出现收窄信号，下一版标题改成：

`[具体类目] Competitor Low-Star Review Audit`

例如：

- `Shopify Returns App Competitor Low-Star Review Audit`
- `Chrome Extension Competitor Low-Star Review Audit`
- `n8n Template Competitor Low-Star Review Audit`
