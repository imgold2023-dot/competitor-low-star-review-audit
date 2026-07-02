# 小型软件交付服务作品页

创建时间：2026-07-03 01:10 Asia/Shanghai

用途：作为 Upwork / Fiverr / PeoplePerHour / Guru 等平台资料里的公开作品入口。当前是本地静态页面，后续可发布到 GitHub Pages、Ko-fi 页面、个人站或任意静态托管。

## 文件

- `index.html`：英文公开作品页，可直接浏览或发布。
- `marketplace-safe.html`：平台安全作品页，用于 Upwork / Fiverr / Freelancer / Guru / PeoplePerHour / Contra 等平台，不包含站外联系、下单、付款或请求表单入口。
- `marketplace-safe.zh-CN.md`：平台安全作品页简体中文说明。
- `.github/ISSUE_TEMPLATE/service-request.yml`：公开服务请求表单，用于收集小范围任务线索。

## 当前定位

服务只承诺具体交付，不承诺“自动赚钱”或“无限制 AI 自动化”：

- TypeScript / Node.js 小 bug 修复；
- Playwright 自动化测试用例；
- 公开竞品评论审计。

## 使用方式

1. 本地打开 `index.html` 检查展示。
2. 收款和平台审核通过后，将页面发布到 GitHub Pages 或类似静态托管。
3. 在自由职业平台资料中优先使用 `marketplace-safe.html`，避免把平台客户引到站外沟通或下单。
4. 在独立公开渠道中可使用普通服务页 `index.html`。
5. 若对方来自独立公开渠道且愿意公开描述需求，可让对方通过 GitHub issue 表单提交小范围请求。

## 边界

页面不收集表单、不处理支付、不嵌入追踪脚本、不需要登录。

公开 issue 请求表单也不应收集敏感信息。表单已明确禁止提交密码、私钥、生产 cookie、支付数据、KYC 信息、银行信息、客户记录或私有后台访问。

自由职业平台客户应在对应平台内沟通、确认范围、创建订单、交付文件和付款；不要引导到 GitHub issue、邮箱、社交账号或其他站外渠道。
