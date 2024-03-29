## 网站使用到的工具

### 域名管理
Cloudflare 海外域名管理网站，服务很多：DNS、SSL、CDN、缓存、防火墙、统计、Workers……最近还发布了 Workers AI。Cloudflare 后台每个子菜单都值得花时间去了解一下具体应用场景，比如还有蛮多人不知道 Worker 是可以运行 Puppeteer 的。

### 部署平台
Vercel 是一个部署平台，也有数据存储、Edge Functions。官方支持的框架语言以 JavaScript 为主，但实际上也可以运行 PHP、Python 等等。开发者社区非常活跃，官方模板是一个找现成轮子的好地方。类似服务：<https://render.com>、<https://railway.app>、<https://fly.io>

### 数据库
Supabase 主打 PostgreSQL 数据库服务，并且集成了用户登录验证，换句话说，前端登录界面都不用自己写了。Supabase 同样也有数据存储、Edge Functions，近期还上线了向量数据库。类似服务：<https://clerk.com>、<https://planetscale.com>、<https://neon.tech>、<https://mongodb.com>、<https://upstash.com>

### 支付
Stripe 是海外收款的首选，几乎能想到与收款相关的服务，他们都有相应产品。接入也不难，Vercel 还有一个 Stripe 订阅模板，第一次见如此详尽的开发文档。类似服务：<https://paddle.com>、<https://lemonsqueezy.com>

缺点：Stripe 的注册成本比较高，需要海外的公司账户。
曲线救国：网站上线，就可以先开通 ko-fi.com 捐赠按钮，等网站有流量了，再开通Adsense，再等后面流量继续增长，才考虑接入支付。支付可以用 <https://lemonsqueezy.com/> ，护照就可以开通，要求用已经做好的网站去申请，会审核网站。再等后面订单多了，为了降低通道费，可以注册美国公司，再注册 Stripe

###  分销联盟
Affiliate 分销联盟是一个不可忽略的推广方式。<https://rewardful.com> 用的人比较多，它能跟 Stripe 关联，用户注册的体验也很流畅。类似服务：<https://tapfiliate.com>、<https://tolt.io>

### 邮件服务
邮件服务就非常多了，免费的可以用 Amazon SES，邮件营销还是建议选择成熟的付费服务。我的项目在用 <http://Mailjet.com>，体验下来足够简单，也便宜。类似服务：<https://mailgun.com>、<https://resend.com>、<https://postmarkapp.com>、<https://brevo.com>

### 域名邮箱
可以使用 <https://zoho.com>，最便宜 $1/月，还要什么自行车。类似服务：<https://mymangomail.com>
[text](https://www.mailgun.com/)

### 数据统计
已经受够了 Google Analytics，于是换成了 <https://plausible.io>，也有开源版本。类似服务：<https://beamanalytics.io>
还有微软的 clarity，非常形象化的一款分析工具。 <https://clarity.microsoft.com/>

### 错误跟踪
可以使用 <https://sentry.io>，只要代码写得不太烂，免费额度应该是够用的，同样也有开源版本。类似服务：<https://rollbar.com>、<https://newrelic.com>


### 网页样式
<https://web3templates.com/>
<https://vercel.com/new/ibrothergangs-projects/templates>


### 一些 SVG 资源

SVG 教程
<https://svg-tutorial.com/>
一步一步教你如何画出 SVG 图形，如何做 SVG 动画

SVG 天气图标动画库
<https://bas.dev/work/meteocons>
都是一些简单的图形，可以用来学习看看别人怎么用 SVG 实现画出各种想要的图形，如何做动画。

开源 Web 动画编辑器
<https://github.com/theatre-js/theatre>
一个带图形界面的 Web 动画编辑器，支持 React 实现 HTML 或者 SVG 动画


### Paywall Screens集

链<https://www.paywallscreens.com>
付费墙是指软件将免费与付费内容分隔开，提示用户付费后才能查看内容的页面。这个网站收集了8千多个付费墙页面供参考。帮助产品经理和设计师设计出美观转化率又高的付费墙页面。

### 网站评论系统
<https://twikoo.js.org/>

### 海外公司注册
[通过1st Formations 28英镑注册正规英国公司教程——只需护照（身份证）、国内地址](https://jiamizixun.com/331)

https://www.xujiahua.com/9627.html

### Stripe
[国内如何注册香港Stripe个人账户（可全球收款，2024年最新教程）](https://mp.weixin.qq.com/s/br0anhSFN8qXlnbogk-sfg)


### 短信激活
https://5sim.net/zh
https://sms-activate.org/cn/buy

### 域名注册
2.1、域名购买渠道
海外站，尽量不要在国内的域名注册商注册域名，国外的推荐注册商:
[text](https://www.godaddy.com/)
[text](https://www.namecheap.com/)
[text](https://www.namesilo.com/)
[text](https://porkbun.com/)
[text](https://www.cloudflare.com/)
[text](https://www.hostinger.com/)
随便哪个都可以，你有哪个账号就在哪里注册，不用去纠结那几块钱的价格差

### 虚拟手机短信
[text](https://sms-man.com/cn)

### 登录
[text](https://next-auth.js.org/)
[text](https://supabase.com/)