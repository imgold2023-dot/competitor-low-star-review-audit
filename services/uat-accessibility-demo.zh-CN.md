# UAT 与 Accessibility First Pass 样例页说明

创建时间：2026-07-04 04:40 Asia/Shanghai

## 用途

`uat-accessibility-demo.html` 是一个公开作品页，用于 Upwork 等平台的 UAT、accessibility audit、pre-launch website QA、mobile/web first pass 类 proposal。

它展示的是一个 2-5 小时小范围 paid trial 的交付形态：

- UAT pass/fail 矩阵；
- accessibility issue table；
- pre-launch checklist；
- confirmed issue / unclear requirement 分离；
- scope boundary。

## 商业作用

这页用于降低新账号的信任成本。客户打开后能看到实际报告结构，而不是只看到泛泛的“可以帮你测试”。

适配候选：

- iOS accessibility audit；
- desktop SaaS UAT；
- website pre-launch QA；
- web/mobile QA first pass；
- Shopify / marketplace QA，但仅限 test mode、sandbox、dummy data。

## 平台边界

页面不包含：

- 站外下单入口；
- 站外付款链接；
- 联系表单；
- 邮箱；
- 追踪脚本；
- 登录或账号操作。

平台客户仍应在对应平台内沟通、确认 milestone、付款和交付。

## 数据边界

只接受：

- staging；
- sandbox；
- dummy data；
- test account；
- public URL；
- safe test build。

拒绝：

- 生产密码；
- 私钥；
- 生产 cookie；
- 真实支付数据；
- KYC / 身份证件；
- 银行 / 钱包信息；
- 真实客户记录；
- 私有后台无限制访问；
- PayPal 或站外付款。

目标未完成。
