# ArKUI-X社区治理制度

ArkUI-X社区由ArkUI-X项目管理委员会（Project Management Committee，PMC）负责管理及运作，社区主要参与者是PMC、Committer及Contributor。

## 社区行为准则

请参考[ArkUI-X社区行为准则]()。

## 社区组织架构

ArkUI-X社区设独立的项目管理委员会（PMC）负责项目及社区治理工作。社区主要由PMC、Committer和Contributor参与。

### PMC

PMC负责社区管理工作，包括版本规划、架构看护、特性代码开发维护、版本及补丁规划、发布和处理社区需求、社区安全工作、PMC及Committer成员的选举和退出等。 

PMC由一名主席和若干成员组成，所有PMC成员均有投票权。 

现有PMC成员见下表，后续成员由现有PMC成员提名并投票选出。

  |姓名|账号|角色|
  |---|----|----|
  |余枝强|[@yuzhiqiang101](https://gitee.com/yuzhiqiang101)|主席|
  |梁治峰|[@xuanchuan](https://gitee.com/xuanchuan)|成员|
  |杨海银|[@yanghy22](https://gitee.com/yanghy22)|成员|
  |孙斐|[@sunfei2021](https://gitee.com/sunfei2021)|成员|
  |兰守忍|[@lanshouren](https://gitee.com/lanshouren)|成员|
  |陈功平|[@gongpingde](https://gitee.com/gongpingde)|成员|
  |王树栋|[@wsd_card_admin](https://gitee.com/wsd_card_admin)|成员|
  |常佳|[@chang-jia](https://gitee.com/chang-jia)|成员|

#### PMC主席

PMC设主席一名，负责PMC总体事务并行使如下职权：

- 召集和主持PMC会议；
- 兼任IT系统代码仓管理员，并任命IT系统代码仓操作员；
- 检查PMC会议决议的落实情况；

### Committer

Committer负责子领域软件模块架构设计、评审和决策、代码开发、审核、合入等工作。

初始Committer由PMC提名并任命（见下表），后续Committer新成员由现任PMC、Committer提名后经PMC投票选出。

  |  姓名 |  账号  | 角色 |
  |-----| ----- | ---- |
  |余枝强|[@yuzhiqiang101](https://gitee.com/yuzhiqiang101)|community、docs、samples仓owner；manifest、build_plugins、plugins、cli、arkxtest、xts、productdefine、app_framework、arkui_for_android、arkui_for_ios、interface_sdk仓备份owner|
  |梁治峰 |[@xuanchuan](https://gitee.com/xuanchuan)|docs、plugins、build_plugins、samples、cli、arkui_for_android、arkui_for_ios仓备份owner|
  |杨海银 |[@yanghy22](https://gitee.com/yanghy22)|docs、plugins、build_plugins、samples、cli、arkui_for_android、arkui_for_ios仓备份owner|
  |孙斐 |[@sunfei2021](https://gitee.com/sunfei2021)|app_framework、arkui_for_android、arkui_for_ios仓owner；community、docs、samples、manifest、build_plugins、plugins、cli、arkxtest、xts、productdefine、interface_sdk仓备份owner|
  |兰守忍 |[@lanshouren](https://gitee.com/lanshouren)|manifest、build_plugins、cli、plugins、interface_sdk、productdefine仓owner；community、docs、samples、app_framework、arkui_for_android、arkui_for_ios、xts、arkxtest仓备份owner|
  |张绕 |[@tomatodevboy](https://gitee.com/tomatodevboy)|xts仓备份owner|
  |刘果 |[@guoguoliu](https://gitee.com/guoguoliu)|community仓备份owner|
  |李俊杰 |[@lijj01](https://gitee.com/lijj01)|app_framework仓备份owner|
  |曹春雷 |[@ccllee](https://gitee.com/ccllee)|app_framework仓备份owner|
  |任熠 |[@inter515](https://gitee.com/inter515)|arkxtest仓owner；xts仓备份owner|
  |纪永 |[@jiyong_sd](https://gitee.com/jiyong_sd)|xts仓owner|
  |陈牡丹 |[@chenmudan](https://gitee.com/chenmudan)|productdefine、build_plugins、interface_sdk仓备份owner|
  |夏登平 |[@xiadengping](https://gitee.com/xiadengping)|interface_sdk仓备份owner|
  |杨妮 |[@neeen](https://gitee.com/neeen)|docs仓备份owner|
  |时睿 |[@RayShih](https://gitee.com/RayShih)|docs仓备份owner|

### Contributor

Contributor参与ArkUI-X社区代码贡献、文档贡献、技术方案讨论及设计、解答用户问题。 
如何贡献，请参考[ArkUI-X社区贡献指南](https://gitee.com/arkui-x/doc/blob/master/zh-cn/contribute/how-to-contribute.md)。 

Contributor参与社区、保持活跃的途径主要有：
- 创建或审阅 PR；
- 提交或评论Issue；
- 完成社区任务，提交贡献，包括代码、文档等；
- 参与社区讨论，如例行会议、电子邮件论坛等；
- 推广ArkUI-X社区，吸引其他Contributor。


## 晋升机制

优秀的社区Contributor可以晋升为Committer，优秀的社区Committer可以晋升为PMC成员。

### 晋升Committer的流程及要求：
- 当Contributor在社区活跃度较高且有一定程度的代码贡献，并具备Committer能力要求，由现任PMC、Committer提名成为Committer候选人；
- PMC定期基于已提名的候选人在社区内发起投票，所有PMC成员有权通过“+1”或“-1”的形式表示支持或反对。其投票形式为以“+1 binding”或者“-1 binding”为表决内容，回复PMC邮件列表中的投票表决邮件,以表示对此表决项的支持或者反对；
- 认定投票通过的标准是获得3票及以上赞成票且无反对票，投反对票的PMC成员必须说明反对的具体问题（无问题描述的反对票无效），投票发起人可针对具体问题进行澄清或修复；
- 投票通过后，PMC在社区邮件列表公告新Committer。

### 晋升PMC成员的流程及要求：
- Committer的贡献达到一定程度，并具备PMC的能力要求，由现任PMC提名作为候选PMC成员；
- PMC定期基于已提名的候选人在社区内发起投票，所有PMC成员有权通过“+1”或“-1”形式表示支持或反对；其投票形式为以“+1 binding”或者“-1 binding”为表决内容，回复PMC邮件列表中的投票表决邮件,以表示对此表决项的支持或者反对；
- 认定投票通过的标准是获得3票及以上赞成票且无反对票，投反对票的PMC成员必须说明反对的具体问题（无问题描述的反对票无效），投票发起人可针对具体问题进行澄清或修复；
- 投票通过后，PMC主席在社区邮件列表公告新PMC成员。

## 决策机制

ArkUI-X社区治理过程中主要通过会议讨论、投票达成共识，进行技术决策。PMC基于某个主题发起讨论及投票，所有PMC成员通过“+1”或“-1”形式表示支持或反对。其投票形式为以“+1 binding”或者“-1 binding”为表决内容，回复PMC邮件列表中的投票表决邮件,以表示对此表决项的支持或者反对；

- 涉及架构设计、版本发布等技术决策事项，采用“懒惰共识”原则：
    - 在规定时间内没有反对意见则默认决议通过；
    - 如出现反对意见，PMC成员则需发起投票，赞成票“+1”多于反对票“-1”，即表明决议通过。

- PMC/Committer成员晋升等投票，参考如上晋升规则中规则： 


## 沟通机制

PMC通过例行会议及邮件进行交流。

### PMC会议
- 会议时间: 每双周周X xx:00-xx:00
- 议题申报: ArkUI-X PMC Meeting Proposal(链接XXX）。
- 会议通知: 通过邮件通知

## 代码仓管理制度

[ArkUI-X社区代码仓管理制度](./repository_management_regulations.md)



