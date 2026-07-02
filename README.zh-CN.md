# Shopify 退货应用低星评论审计公开页说明

日期：2026-06-04  
用途：第 5-6 天发布测试的静态公开入口。  
公开页：`index.html`
公开样例报告页：`sample-report.html`
小型软件交付服务作品页：`services/index.html`
平台安全作品页：`services/marketplace-safe.html`
中文伴随版本：`index.zh-CN.md`
样例报告中文伴随版本：`sample-report.zh-CN.md`
服务作品页中文说明：`services/README.zh-CN.md`
平台安全作品页中文说明：`services/marketplace-safe.zh-CN.md`
发布清单：`github-pages-publish-checklist.zh-CN.md`

## 当前状态

这个目录是“可公开链接包”，用于把免费样例和公开反馈入口放到一个静态页面里。页面默认英文，因为第一轮外部渠道优先测试独立开发者、SaaS 创始人和 Shopify App 开发者。

页面已明确：

- 验证期先收公开反馈，不自动收款。
- 只使用公开信息。
- 不登录客户账号，不处理订单、退款、隐私、支付、KYC 或争议。
- 当前不展示价格包，不放 Ko-fi 付款入口。

## 服务作品页

`services/index.html` 用于展示可接单的小型交付服务：

- TypeScript / Node.js 小 bug 修复；
- Playwright 回归测试；
- 公开竞品评论审计。

该页面只描述具体交付、公开证明链接和边界，不处理私有账号、支付数据、KYC、生产 cookie 或客户数据。

公开服务请求入口：

- `https://github.com/imgold2023-dot/competitor-low-star-review-audit/issues/new?template=service-request.yml`

该入口只适合提交公开或非敏感需求描述，不应包含密码、私钥、生产 cookie、支付数据、KYC 信息、银行信息、客户记录或私有后台访问。

首页和样例报告页也已加入该请求入口，避免访问者只看到样例但不知道如何提交一个小范围需求。

## 平台安全作品页

`services/marketplace-safe.html` 用于自由职业平台资料或 proposal。

该页面只作为 portfolio proof，不包含站外联系方式、站外下单、站外付款或服务请求表单。若客户来自 Upwork、Fiverr、Freelancer、Guru、PeoplePerHour、Contra 等平台，沟通、范围确认、订单、交付和付款都应留在对应平台内。

收入冲刺中：

- 平台投递默认使用 `services/marketplace-safe.html`。
- 独立公开渠道才使用 `services/index.html` 和 GitHub issue 服务请求表单。

## 发布前必须确认

创始人发布前需要确认：

- GitHub 链接是否仍适合作为公开作品证明。
- 是否已经接受“先收公开反馈，不自动收款”的发布边界。
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

48-72 小时内满足任意一条即可继续：

- 3 个来自目标用户的公开评论。
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
