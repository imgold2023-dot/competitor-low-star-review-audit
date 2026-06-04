# GitHub Pages 推送说明

日期：2026-06-04  
目录：`D:\个人\solo-company-research\promotion\github-repo\competitor-low-star-review-audit`

## CEO 判断

先用 GitHub Pages 发布公开样例，不急着开收款。

理由：当前验证目标是“是否有人询价或要求看自己的类目”，不是先证明付款链条。公开页和完整样例报告先上线，才有可引用链接。

## 推荐远程 repo

| 字段 | 建议 |
| --- | --- |
| Repo name | `competitor-low-star-review-audit` |
| Visibility | Public |
| Description | `A public sample of a competitor low-star review audit for indie builders.` |
| Topics | `competitor-analysis`, `shopify`, `saas`, `indie-hackers`, `market-research` |

## 首次推送命令

在 GitHub 创建空 repo 后，在 PowerShell 里执行：

```powershell
cd "D:\个人\solo-company-research\promotion\github-repo\competitor-low-star-review-audit"
git remote add origin https://github.com/imgold2023-dot/competitor-low-star-review-audit.git
git branch -M main
git push -u origin main
```

如果提示 `remote origin already exists`：

```powershell
git remote set-url origin https://github.com/imgold2023-dot/competitor-low-star-review-audit.git
git push -u origin main
```

如果仍然出现 GitHub 443 连接失败，先不要反复重试。记录错误时间，再稍后换网络或代理后重试。

## 开启 GitHub Pages

推送成功后：

1. 打开 GitHub repo。
2. 进入 `Settings > Pages`。
3. Source 选择 `Deploy from a branch`。
4. Branch 选择 `main`。
5. Folder 选择 `/root`。
6. 保存并等待 Pages URL 生成。
7. 打开首页和 `sample-report.html` 检查。

## 发布后回填

拿到公开 URL 后，回填：

- `D:\个人\solo-company-research\promotion\public-shopify-returns-radar\feedback-log.zh-CN.md`
- `D:\个人\solo-company-research\promotion\tracking\promotion-tracker.csv`
- `D:\个人\solo-company-research\promotion\shopify-returns-radar-publish-packet.zh-CN.md`

## 不要做

- 不要开启自动收款。
- 不要承诺退款、KYC、税务或外汇处理。
- 不要要求客户提供账号、cookie、订单、付款、退款或隐私数据。
- 不要批量复制同一段内容到多个社区。
