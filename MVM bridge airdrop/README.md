# MVM bridge 空投活动策划

## 目标

- 增加MVM bridge使用用户
- 增加粉丝数(twitter/discord)
- 增加裂变曝光

## 流量闭环

```flow
o1=operation: mixin社群/mixinnetwork推特
o2=operation: 链上资质证明平台
o3=operation: discord
o4=operation: twitter
o5=operation: MVM bridge
o6=operation: mixin社群

o1-o2
o2-o3
o2-o4
o2-o5
o3-o1
o4-o1
o5-o1

```

## 流程相关

### 一、种子用户

- 以现有mixin社群、mixinnetwork推特用户作为流量入口，发射活动
- mixin活动公告文案（待完善）
- mixinnetwork推特文案（待完善）
- 活动海报（待定）

### 二、链上资质证明平台

- 参与用户由mixin社群、mixinnetwork推特导入，引向链上资质证明平台
- 用户需完成全部任务才能获得链上凭证（OAT）:
   1. 关注mixinnetwork推特账户
   2. 关注MVM bridge推特账户
   3. 加入MVM bridge discord社群
   4. 转发&点赞mixinnetwork推特的活动推文
   5. 使用MVM bridge完成一次任意金额的充值

### 三、discord社群

- 用户进入discord首先需要进行非机器人验证，验证后自动获得Mixiner身份组标签
- 设置资产验证（机器人Collab.Land#6372），凡持有OAT者自动获得early bird身份组标签
- 设置discord任务，完成条件者可开票获得OG身份组标签（暂定500上限）
  1. 社群等级达到3级
  2. 邀请三人
  3. 持有OAT

## 奖励设置

- 所有OAT持有者瓜分1000u奖励，需进入discord指定频道提交MixinID领取
- early bird身份可以享有后续福利的准入资格（如合作项目福利抽奖等）
- OG身份同时享有部分功能、福利的优先体验权

## 准备相关

- 目前尚不清楚OAT领取是否需要先支持mixin网络，如果是则需要提前联系平台合作
- 需设计OAT样式
- 需提前设置discord相关验证机器人、频道、身份组

## 扩大宣传（待选）

- 如果付费推广，需要提前联系相关KOL确定具体价格
- 主推国内or海外

## 一些说明

- 考虑到防止羊毛用户，所以采用绑定社交账号的方式，提高领取门槛，避免多号党
- 因为尚不能准确预测参与用户数量，所以采用固定的奖励总额度，以免成本过大
- 通过调研一些空投案例，用户普遍会对未发币且有空投预期的早期项目更为热情，所以不太好评估目前的奖励力度是否对用户有足够的吸引力

