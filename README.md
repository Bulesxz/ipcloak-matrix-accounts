# ipcloak.ai Accounts · 广告账户供应子站

> accounts.ipcloak.ai — 明码标价卖户子产品（FB 户 / TK 户 / BM / 粉丝页）

## 定位

矩阵内**第二个**广告账户相关入口，与 `ads.ipcloak.ai` 形成两条业务线：

| 子站 | 定位 | 客单 | 客户类型 |
|---|---|---|---|
| **accounts.ipcloak.ai**（本站） | 明码标价**卖户**（零售） | 低中 | 自己跑广告的投手 |
| **ads.ipcloak.ai** | 开户 + **代投托管** | 高 | 不会自己跑广告的甲方 |

## SKU 参考价

| SKU | 描述 | 价格 |
|---|---|---|
| V.1 | FB 广告账户 | 4%（3+1） |
| V.2 | TK 广告账户 | 5.5%（4.5+1） |
| V.3 | Facebook BM | $15 / 个 |
| V.4 | FB 粉丝页 | $20 / 个 |
| V.5 | 封户免费换户 | 免费 |

下单方式：Telegram `@webpage1688`

## 部署

```bash
# 本地预览
cd accounts-www
wrangler pages dev .

# 部署
wrangler pages deploy . --project-name=ipcloak-accounts-www
```

## 域名

CF Pages 项目名：`ipcloak-accounts-www`
绑定自定义域名：`accounts.ipcloak.ai`

## 多语言

- 中文（默认）: `/`
- English: `/en/`

## 集成

- 品牌资源: `cdn.ipcloak.ai/brand/cyber-shield.css`
- Logo: `cdn.ipcloak.ai/logos/ipcloak-accounts.svg`（需上传到 cdn）
- 矩阵 SSOT: `shared/data/matrix.json`（已加 accounts 产品节点）
- 聚合 sitemap: `cdn.ipcloak.ai/sitemap-index.xml`（已加 accounts/sitemap.xml）
