---
title: Mixin123
sidebar_position: 1
---

# 1.背景

我在顶呱呱（Prsdigg.com）写的文章所涉及的内容有一个原则就是，内容都是我用得到的，我需要研究的东西，或者我自己需要持续成文的内容，所以，无论有没有人看我也会写，既然写了，索性也就分享出去，万一对别人也有帮助呢？

有一天，无意的看到了一位Mixin群友的机器人截图，我发现有好多机器人我都没有用过，我意识到Mixin Network中应该也有多个小世界，本着类似写文章的原则，我想做一个东西，不管有没有人用，我也用的到的东西，万一对别人也有帮助呢？这就是Mixin123，一个Mixin生态的导航和wiki网站，一个方便人们探索Mixin Network的地方。

其实，我只是个使用Mixin的新人，也就刚刚一年，虽然不知道以前的Mixin发生过哪些翻天覆地的变化，可是仅仅我经历的这一年，Mixin从主网性能的提升，MTG推出，抵押率超400%的稳定币pUSD发行，各类金融产品HODL！，DEX，OptionDance等初具规模，NFT支持上线，再到即将出世的MVM，我切身的感受到了Mixin正在飞速的进化，即将迎来1.0版本，即将破圈而出，虽然主网快到红包再也抢不到了，但我想我们对于Mixin的出圈也必然是喜闻乐见的。

随着各种各样的应用出现，无论对于圈内人使用Mixin时，能够寻找自己需要的应用，发现自己未用过的应用，帮助应用推广引流让更多的人知道，还是对于圈外人了解Mixin的生态有哪些好玩有趣的产品，Mixin123或许都可以发挥一定的作用，起到一定的效果。

为此，我会以自己已有的知识先搭凑一版简单的，因为实在是水平有限，也仅能算是练习一下对于前端开发的学习和工程能力的学习，其实是边学边做，做中学，当然，对于Mixin123，最好的迭代方式应该是共创共建，假如Mixin123能够产生收益，就可以回报参与共创共建的贡献者，倘若没有收益，不能更好的迭代，至少于我自己而言，我想也应该算是为Mixin生态尽了绵薄之力，希望有同样希望尽一份力的朋友们参与进来。

> 因为本文章是边想边写边补充的，所以有些部分内容涉及的词语，会在后面有具体的说明，即会有部分前置引用，但应该不影响对整体内容的理解。

# 2.Slogan

探索这个有趣的Mixin Network

# 3.Mixin123的页面内容及布局

初步考虑参考qkl123.com的结构：

![image-20211110225225945.png](https://prsdigg.oss-accelerate.aliyuncs.com/8arxyusyn9ib6owcf5nr1fcezz2f)

本着先完成再完美的指导原则，前期，我考虑了两个阶段性目标，以及目标中希望Mixin123能够实现的具体功能如下：

## 3.1.第一阶段

先把当前Mixin生态中的产品的信息收集起来并完善

### 3.1.1.网址导航的汇总页（Index）

#### 3.1.1.1顶部栏

* Logo
* Slogan

#### 3.1.1.2.侧边栏

* 分类列表

#### 3.1.1.3.主内容区

分类列出Mixin生态中的应用，应用图标，应用ID，并用限制字数的描述，简明扼要的介绍产品。

类别分为两个级别，其中第一级别为大类别，大类别参考Mixin Network开发者后台对应用的分类，第二级别为细分类别，参考其他网站对同类应用的细分分类以及个人理解进行分类

类别及部分产品举例（暂定）：

* 钱包

  网页钱包：Fennec

  机器人钱包：Mixin Wallet，小钱包，ExinOne

* 金融

  OTC：ExinLocal，TIGA

  DEX：4swap，ExinSwap，MixSwap，Pando Lake，Mixcoin

  CEX：BigONE

  借贷：Pando Rings

  期权：Option Dance

  稳定币：Pando Leaf

  其他：HODL大牢宝，IFTTB，水龙头，B.Watch，Coin Exchange

* 商业

  资讯：Mixin产品动态，ExinNews，Fox.ONE NEWS，Mixin直播频道，IMEOS快讯

  社群：Mixin 中文群，Mixin English，RUM 中文群，Avalanche 中文社群，Solana 中文群，MobileCoin 中文群，TopDAO 中文群，Polygon 中文群，Horizen 中文群，RUM 中文群，Human Protocol 中文群，TRON 中文群，Bitcoin 中文群，Ethereum 中文群，EOS 中文群，Exin 核心用户群， 李笑来.定投公开课， Exin 中文群，Fox.ONE 中文群，BigONE中文群，安桥小宝盒

* 社交

  小迷圈：冯晓东的小迷圈，歌词经理和他的朋友们，李安的朋友圈，Thorb的小迷圈，发条的小迷圈，Robin的小迷圈，韩如初，MiFi大本营

* 购物

* 教育

  社群：定投人生课堂，定投健身课堂，定投课堂读书会

* 新闻：链闻ChainNews，小道消息，币世界 Bot，Readhub要闻，ChainONE Channel，

* 工具：猫头鹰递信，Mixin 数据，BitHub，Mixin区块浏览器助手，红包，群助手，我信（小密圈），持仓助手，Mixin直播小助手，Mixin文章小助手，Mixin监控，Mixin收款，Shitcoin垃圾桶，自助发币工具

* 游戏

* 书籍

* 音乐

* 图片

* 视频：Div

* 其他: PRSDigg



每一个大分类成为Container，每一个Container内的一个个产品位称为Block

在各种分类Container的最前面，会有一个Container的内容为热门应用，其内的Block为推荐位1个，广告位1个，各分类目名下的Top3产品或根据总得分罗列，具体数量后期根据页面布局确定。

每个分类Container内的Block排序为：推广应用1个——上新应用1个——按评分排序的应用

新上应用和推广应用应在角部显著标明。

#### 3.1.1.4.底部区域

* 社区
* 荣誉墙
* 版权声明
* 友情链接

### 3.1.2.产品详情页

初步考虑借鉴苹果应用商店对于应用的介绍，产品详情页包含该产品的：

* 主要版本历史记录
* 产品预览信息
* 产品介绍
* 开发者或开发团队信息
* 用户对该产品的评分和评价 //采用1-5颗星表示得分，原始分3颗星，最小颗粒度半颗星
* 相同开发者或团队开发的其他产品

其中评分评价由用户给出，其他信息由开发者或开发团队提供，前期的信息，我会从应用本身的信息收集。

## 3.2.第二阶段

考虑可以产生收益的方式，比如：

* 推广栏  //即推广Block
* 广告
* 赞助
* P2P CDN

前期，推广栏显示竞拍推广和上新推广两种推广信息。

# 4.Mixin123自动工作流

Mixin123上面的功能实现后，Mixin123将基于下面的工作流自动运行。

关于产品信息：

1. 产品开发者或产品团队提交产品数据
2. 限时免费推广曝光
3. 用户根据使用感受进行打分
4. 分类排名依据得分定期排序

关于推广栏：

1. 产品开发者或产品团队在推广位竞拍页面参与竞拍
2. 在一定期限内价高者竞得推广权
3. 竞拍到期后，竞拍获胜者的应用将会在合同期内出现在推广位

整体机制的设计对与推广形成的正向循环为：通过推广位提升曝光，本身品质优秀，排名靠前，提高曝光，进而进入置顶Container提高曝光，最终，还是好的应用获得更大的曝光，让用户更多的看得到。



总体上，工作流以站点信息自动更新作为设计流程的原则。



# 5.Mixin123以什么样的形式呈现

受限于本人的能力水平，以及考虑到导航网站的内容可能会比较多，因此页面先考虑对于PC做适配，对于手机，以及直接在Mixin内访问，留到以后。
又因为，导航页往往用于寻找应用，以及了解应用的用途，之后就可以在Mixin中添加应用来使用，所以用PC访问，然后在Mixin Messenger中添加应用再去使用，应该也还算是可以接受的使用方式。
所以，就先做Mixin123的PC页面，具体应该就是用HTML+CSS的静态页面来呈现网址导航汇总页，用Docusaurus搭建一个产品详情的文档库，然后通过导航页跳转的方式跳转到产品详情页，整体应该都可以通过Docusaurus来实现。

# 6.协作共建

基于上面的构想，基于协作共建的Mixin123的进一步迭代应该会需要：

* 设计人员  //帮忙完整个Mixin123的设计工作

* 开发人员  //帮忙根据设计稿完成站点的开发，并实现规划功能的开发

* 献计献策 //为此站点建设，运营，推广，创收出谋献策

* 前期建设补充产品的人  //因为目前没有统一的Mixin生态的应用列表，所以可能需要大家一起补充，包括详细信息

  

站点会设置贡献墙页面，展示协作共建的贡献，并根据个人意愿选择是否公开个人信息
对于方案的采用，前期可能会由我拍脑袋确定方案，后续可以考虑设立评审组，投票确定对献计献策的采用

# 7.协作方式

* Trello  //用来做项目管理
* Github  //用来做协作/版本控制/Issues Track
* Mixin Messenger  //聊天群组用来即时通信

# 8.奖励方式

初步考虑，对于早期参与贡献者，即帮助实现前面规划内容的功能的贡献者，将奖励由Xin铸造的贡献者NFT纪念章，如果资金池中资金不足以完成纪念章铸造，则根据贡献分配比例分得资金池中资金，之后，资金如果足够铸造NFT纪念章，将为贡献者补发。铸造NFT纪念章的剩余资金，全部按比例奖励给早起贡献者。

* 对于设计和开发贡献者后面会根据具体明确后的工作项后确定总分配比例和细分分配比例；
* 对于献计献策着，设定一定的限制总采纳条数，跟据该类贡献占比确定每条的奖励比例；
* 对于前期帮忙补充产品的朋友，根据提交条数分配该项总奖励，补充产品占30%，后期补充产品信息占70%（为避免一两句描述，补充信息的具体标准确定下来会公示，但也不会要求过多描述）。

本文章自发表至NFT商店上线，本文章的所有本人收益，将作为资金池中的资金，用于对贡献者奖励。所以，我想应该不至于发不起NFT。

如果后期持续有盈利，将设定一定比例的资金，用于长期激励贡献者，其余资金将储备，看能否以此为一个火种，开启征程。

## 9.具体工作项

根据上面的规划，具体角色工作项如下：

### 设计人员

- [ ] 站点页面UI设计
- [ ] 工作流相关页面设计，如：荣誉墙页面/推广栏竞标页面/推广信息提交页面/收录申请页面等
- [ ] 相关图标，NFT纪念章等设计工作

### 开发人员

- [ ] 根据规划及设计人员设计实现页面及功能

### 献计献策

主要设计已经列出，除此之外的好的建议，请直接与我联系，我的Mixin ID：37351541。

### 应用补充

因为我不占分配奖金的名额，所以，排除前面我已经列出的我常用的应用，应该会提高该项贡献者的奖金比例。
但是，因为该项奖励分陪到了提交应用和补充应用信息（应用详情页内容）两个具体工作，因此，可以选择为我已经列出的应用补充应用信息（应用详情页内容）获得奖励。

可以选择本帖留言，以及文末社区中发消息的方式，将需要提交的应用发出来进行占位。

比如：
PRSDigg 7000101549，表示补充此应用
PRSDigg 7000101549 + ，表示补充应用，补充详情页信息都将是您
PRSDigg 7000101549 ++，表示您仅对某个应用补充详情页信息。

都以更早的时间戳，作为占位标准。

# 10.奖励比例

需要与设计和开发人员讨论详细的任务，待详细任务明确后确定。

初步考虑整体比例为：

开发：50%

设计：25%

前期产品信息补充：15%

献计献策：10%，以采纳建议为准，前期最多采纳5条建议。 

# 11.域名

mixin123.one

# 12.社区

Twitter:

Discord:https://discord.gg/BBTx2F5R

Mixin Group:https://mixin.one/codes/a513962d-052f-4db3-86ee-2a4c070675bc

RUM群组：

```
{
  "genesis_block": {
    "BlockId": "e7ce6309-6348-4ea9-9704-badae6ebd423",
    "GroupId": "17c725aa-10f5-477e-9acd-c822be47fa77",
    "ProducerPubKey": "CAISIQKQ3D+tx/EatERCRngG8Odsj3sKHwuYxOPQ2DeCdVxmKQ==",
    "Hash": "k8TnEX1BNjsdkjse3b1F6eTvfiHTxKQ618Mk+IgdQGI=",
    "Signature": "MEQCIE9F88w9VGBOuStdM4PcT48lp16dtfSop4jD5GwNYZOXAiAyRRfMR20VSCzbcrAa/r1CVwvgbId1bUxkJoBKIfzmvw==",
    "TimeStamp": "1636615042624483000"
  },
  "group_id": "17c725aa-10f5-477e-9acd-c822be47fa77",
  "group_name": "Mixin123群组",
  "owner_pubkey": "CAISIQKQ3D+tx/EatERCRngG8Odsj3sKHwuYxOPQ2DeCdVxmKQ==",
  "owner_encryptpubkey": "age1hq5tfnnpmqz93v3tus26g9z5vuruamk598wtszcks8nenqp8svyqm7el2e",
  "consensus_type": "poa",
  "encryption_type": "public",
  "cipher_key": "663f00dc0a42664f47949c66b610f8471b9360fc7521cf576d6dd431529f365b",
  "app_key": "group_timeline",
  "signature": "3045022100f8f7c53c0bfe78b565ec9addc86ea4a807b2e886c4cd84e10e2019215cab351f02203104d1104c232b402569ca9d1161993a0a0a293f1ed56c4cba10923db61b2dc1"
}
```

# 13.贡献墙

* 我所使用和本文中列出的应用，大量的参考了用户：他们都叫我唐长老 的机器人Mixin机器人精选（Mixin ID:7000101700）的内容;

* 增加收益项 P2P CDN，来自另一位大佬，目前仅仅是提出来，待确定采用后，将奖励给建议提出者



最后，如果未能有协作共建，我想对我也还是有益的，因为我有了一个明确的需求，让我可以做中学，持续成长。

感谢所有人的支持，希望我们的Mixin越来越好。

Mumu Wu

2021.11.11