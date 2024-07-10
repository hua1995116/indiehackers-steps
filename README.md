
> 本教程将记录我的独立开发者出海之路，包含从最基本的如何注册美国公司到银行，使用stripe收款，出海的工作流选择以及如何营销。有疑问可以关注我的 [twitter](https://twitter.com/qiufenghyf) ,私信交流

## 目录

1.出海淘金基础
- [美国公司注册](https://github.com/hua1995116/indiehackers-steps/tree/main?tab=readme-ov-file#step1-%E7%94%B3%E8%AF%B7%E7%BE%8E%E5%9B%BD%E5%85%AC%E5%8F%B8)
- [EIN](https://github.com/hua1995116/indiehackers-steps/tree/main?tab=readme-ov-file#step2-ein)
- [stripe开通](https://github.com/hua1995116/indiehackers-steps/tree/main?tab=readme-ov-file#step4-stripe)
- [美国银行申请](https://github.com/hua1995116/indiehackers-steps/tree/main?tab=readme-ov-file#step3-%E6%B0%B4%E6%98%9F%E9%93%B6%E8%A1%8C)
- [BOI](https://github.com/hua1995116/indiehackers-steps/tree/main?tab=readme-ov-file#step5-beneficial-ownership-informationboi)
- [Wise账户](https://github.com/hua1995116/indiehackers-steps/tree/main?tab=readme-ov-file#step5-%E7%94%B3%E8%AF%B7-wise-%E8%B4%A6%E6%88%B7)
- [税务](https://github.com/hua1995116/indiehackers-steps/tree/main?tab=readme-ov-file#step6-%E7%A8%8E%E5%8A%A1)
- 港卡开通

2.免费的启动资金
- GitHub Enterprise X 12个月(价值 $5040)
- Azure ($15w creit)
- AWS ($15k)
- Google (2k)
- Nvidia
- 阿里云
- 华为云

3.技术篇
- 技术栈
  - 全栈框架全家桶
  - 免费数据库
  - 免费云Redis
  - 负载均衡
  - 免费的CDN
  - 免费对象存储
  - 注册登录
  - 支付
- 企业客服邮箱
- 如何抵御攻击
- 基础性能优化
- 如何找到AI API

4.增长篇
- 如何寻找influencer
- ProductHunt如何养号
- 如何做好SEO


你的支持是我更新的动力!

<a href="https://www.buymeacoffee.com/qiufeng" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

### 1.出海淘金基础

**193 刀注册美国公司 + EIN + stripe + 水星银行**

<img width="919" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/911d5ed7-acca-4607-8d6e-0b021f9ffa52">


#### Step1: 申请美国公司

这里我选择的是  wyoming 州注册, 因为 wyoming 免公司税和个人税，并且任何国籍也可以注册

1.打开 https://www.wyomingagents.com/ 

<img width="705" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/5242b5c6-a90d-4e8e-8926-919046358598">

按照要求填写基本资料

<img width="759" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/5c1ff0b3-6ecc-4a32-809a-31d7c94f285e">

<img width="696" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/f6f55555-cdb8-4047-9461-64069eec55f7">

公司类型，个人或者小型组织可以选择 LLC, 如果有公司有融资需求可以选择 CORP，但是本教程面向的还是大多数独立开发者，因此选择 LLC, 里面的地址信息就填写你实际的地址，不需要做啥修饰

<img width="714" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/bcf62ebb-55bb-4f5e-8a57-68ac0d711559">

关于增值付费部分，按照默认就好，增值部分在注册完毕后，都是可以额外购买的，需要担心选错了，导致注册失败，默认的选项就可以完成公司注册。

<img width="690" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/449f187f-cd29-4aa5-83cd-44e23682ac2e">

大约等待1周，就可以完成公司注册，你会得到 公司章程以及一些公司的信息材料。

> tip: 注册完后，会给你一个美国地址，可以收发邮件，但是需要收费，有需要的也可以购买它的扫描信件服务

花费 150 刀，耗时 1周

#### Step2: EIN 

有了公司章程后，我们就可以去申请 EIN 了。 你可以自己去申请到官网，也是有中文的 https://www.irs.gov/zh-hant/businesses/small-businesses-self-employed/how-to-apply-for-an-ein

当然也可以找代办，**我这里 EIN 办理去 fiverr 上找人帮我代办了**，你发给他公司章程，他就直接可以帮你申请。

平台上说一半是10点才能交付，但是我等了大概3天就拿到了 EIN + IRS 的回执信，但是代办的人说同步 EIN 需要时间，让我隔1周再去注册 Stripe

花费 35 刀 + 8.17刀(fiverr平台手续费) + 耗时 3天

#### Step3: 水星银行

https://mercury.com

其实有了美国公司主体 + EIN, 申请真的超级简单，直接按照你的真实情况填写好了，大约经过3个工作日的审核，会要求你提供一个地址证明，证明材料需要是 水电费账单 + 有你的名字 + 你的地址，或者是银行账单 + 你的名字 + 你的地址。

所以在申请账号的时候，地址需要填写的谨慎一些，我当时为了方便，填写了家庭地址。然后证明材料使用了 水电账单 + 户口本(因为水电户名是我爸的名字) 。如果你提供的水电账单没有你的名字，应该加上租房合同或者房产证明也是可以的。

花费 0 刀 + 耗时 3天初审核 + 2天地址审核

#### Step4: Stripe

有了以上材料，我们直接申请 [Stripe](https://stripe.com/) 就可以，因为 Stripe 难点就是 EIN 

花费 0 刀 + 1天

最后，就可以开始你的宏图大业了!!!

#### Step5: Beneficial Ownership Information(BOI) 

官方地址: https://www.fincen.gov/boi-faqs#A_1

<img width="523" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/6ca613bf-b56e-4563-81d7-be707543d521">

目前 wyomingagents.com 上提供了代理申请，价格是 9刀, 如果是刚注册的公司，注册的时候会帮你默认勾上。

case1: 24年后注册的公司

<img width="523" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/c55a26c1-4005-4883-8681-a32ca9b655ba">

case2: 24年前的注册的公司

登录网站后，点击 Hire Us

<img width="523" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/f8d182bc-2c5a-4eaf-9272-74198462fdd8">

拉到最底下

<img width="523" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/46a45d0f-1e4c-40e8-aebf-8f6069ad7a03">

花9刀购买，然后填写信息（需要准备好护照）

#### Step6: 申请 wise 账户

https://wise.com/

好处是可以接受所有地区的汇款和收款(准备在Affiliate分销付款使用)， 企业账户需要有 $31 的开户费

<img width="1169" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/a92aca64-1bd0-4c27-a371-e853b7156913">

准备材料

1.美国公司 + EIN

2.国内地址

3.国内护照

4.关联的美国银行(可以使用上述的水星银行)，好处是转到账户内不需要手续费

<img width="585" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/b5761ab2-6002-4e9d-9745-d46b4c774558">

相关开通账户官方教程： https://wise.com/zh-cn/blog/open-wise-account

费率: https://wise.com/zh-cn/blog/paypal-business-account

支付完成 + 认证完成后的账户界面

<img width="1466" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/2da2a66a-3145-492c-862a-28a31e6a54e3">


#### Step7: 税务 

目前已经通过 fiverr 把税务相关的表格 1120 和 5472 申报好了，流程非常简单，卖家会给你一个表格，你按照要求填好就可以了，他会帮你处理好正式的表格并传真给IRS。

表格如下: 

<img width="441" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/253a9123-3afa-4274-ade1-a7b92036826a">


税务申报:  $50

申报完成会给你两张表的信息回执和传真的回执。

相关信息：https://twitter.com/qiufenghyf/status/1757604024734687232


*(注册的常见问题**

1 目前有小伙伴注册的时候遇到这样的问题，如果是开发人员注册时候记得打开控制台查看正确的抛错，目前有一个 case 是账号的密码，没有大小写导致校验出错。

![WechatIMG36](https://github.com/hua1995116/indiehackers-steps/assets/12070073/760c0bfa-75c3-464d-8f3a-7d1040dcc494)

![WechatIMG41](https://github.com/hua1995116/indiehackers-steps/assets/12070073/0f0aad34-a78d-4cab-933b-9a8ef81f275a)


### 2.免费的启动资金

为什么要申请？ 

因为在企业初期，如果没有投资的话，初期比较困难，特别是对于独立开发者。

如何申请？ 

（后面写）

为什么云厂商要给这么大的额度？

因为云厂商看中的是你后期的付费力，如果看到你前期不行的话，不会给 Creits 。如果你前期不错的话，给了 Creits 你大概率就会一直续费了，因为云技术设施迁移成本非常高，特别是对于你已经发展起来了产品，万一一个迁移导致业务全面崩了，为了节省一点点费用，简直是得不偿失的。

后面准备在各个云上折腾一番，最后也会总结一下，哪些云的性价比最高。当然我后面应该也会选择1-2家长期合作，目前只体验了 AWS，感觉还是是不错的，使用竞价实例价格也很合适。


#### 1.GitHub Enterprise X 12个月(价值 $5040) 

(已获得)

![image](https://github.com/hua1995116/indiehackers-steps/assets/12070073/c79f2a2d-64b5-44a5-bf34-eee63cb29230)


#### Azure ($15w creit) 

（已获得）

<img width="523" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/ec8ad25f-605b-421c-916f-c1a0b7f2bfb5">


也是分阶段，但是可以逐步提升额度

- 阶段1: 1k
- 阶段2: 5K
- 阶段3  2.5w
- 阶段4: 15w

#### AWS ($15k) 

（已获得）

<img width="523" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/ec8ad25f-605b-421c-916f-c1a0b7f2bfb5">

AWS 一共给 15k, 但是分阶段，前面5k是无门槛，后面是每花 5k送 5k, AWS还是非常好用的！价格也比较便宜。
  
#### Google 

（已获得）

<img width="523" alt="image" src="https://github.com/hua1995116/indiehackers-steps/assets/12070073/ffad057a-b6ef-41a5-ac0d-b127a053d775">

- Nvidia
- 阿里云
- 华为云


