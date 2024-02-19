## 网站使用到的工具

### 域名管理
Cloudflare 海外域名管理网站，服务很多：DNS、SSL、CDN、缓存、防火墙、统计、Workers……最近还发布了 Workers AI。Cloudflare 后台每个子菜单都值得花时间去了解一下具体应用场景，比如还有蛮多人不知道 Worker 是可以运行 Puppeteer 的。

### 部署平台
Vercel 是一个部署平台，也有数据存储、Edge Functions。官方支持的框架语言以 JavaScript 为主，但实际上也可以运行 PHP、Python 等等。开发者社区非常活跃，官方模板是一个找现成轮子的好地方。类似服务：<https://render.com、https://railway.app、https://fly.io>

### 数据库
Supabase 主打 PostgreSQL 数据库服务，并且集成了用户登录验证，换句话说，前端登录界面都不用自己写了。Supabase 同样也有数据存储、Edge Functions，近期还上线了向量数据库。类似服务：<https://clerk.com、https://planetscale.com、https://neon.tech、https://mongodb.com、https://upstash.com>

### 支付
Stripe 是海外收款的首选，几乎能想到与收款相关的服务，他们都有相应产品。接入也不难，Vercel 还有一个 Stripe 订阅模板，第一次见如此详尽的开发文档。类似服务：<https://paddle.com、https://lemonsqueezy.com>
缺点：Stripe 的注册成本比较高，需要海外的公司账户。
曲线救国：网站上线，就可以先开通 ko-fi.com 捐赠按钮，等网站有流量了，再开通Adsense，再等后面流量继续增长，才考虑接入支付。支付可以用 <https://lemonsqueezy.com/> ，护照就可以开通，要求用已经做好的网站去申请，会审核网站。再等后面订单多了，为了降低通道费，可以注册美国公司，再注册 Stripe

###  分销联盟
Affiliate 分销联盟是一个不可忽略的推广方式。<https://rewardful.com> 用的人比较多，它能跟 Stripe 关联，用户注册的体验也很流畅。类似服务：<https://tapfiliate.com、https://tolt.io>

### 邮件服务
邮件服务就非常多了，免费的可以用 Amazon SES，邮件营销还是建议选择成熟的付费服务。我的项目在用 <http://Mailjet.com，体验下来足够简单，也便宜。类似服务：https://mailgun.com、https://resend.com、https://postmarkapp.com、https://brevo.com>

### 域名邮箱
可以使用 <https://zoho.com，最便宜> $1/月，还要什么自行车。类似服务：<https://mymangomail.com>

### 数据统计
已经受够了 Google Analytics，于是换成了 <https://plausible.io，也有开源版本。类似服务：https://beamanalytics.io>
还有微软的 clarity，非常形象化的一款分析工具。 <https://clarity.microsoft.com/>

### 错误跟踪
可以使用 <https://sentry.io>，只要代码写得不太烂，免费额度应该是够用的，同样也有开源版本。类似服务：<https://rollbar.com、https://newrelic.com>
