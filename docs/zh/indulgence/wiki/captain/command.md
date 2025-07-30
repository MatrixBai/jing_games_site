# 指令
!!! quote ""

    “”

＃＃ 通用的
＃＃＃ 讲话
与_entity_开始对话，默认[对话主题]将根据游戏情况发生变化。例如，在战斗中_player_可以，
 - 鼓励_crew_改善他们的[[士气]]。
 - 减少敌人的_ morale_或说服他们放弃战斗，甚至加入您。
 - 从中立_agent _获得支持，说服他们支持您。

__应用实体__：所有可话的_entity_;
###设置移动目的地
创建一个[[[杂货 - 索引]]，让_agent_步行至可及的协调。

__应用实体__：仅_agent_在_captain_的控制下，_crew_和Ally在战斗中，请有此_command_，
###开关机舱电源
_captain_可以直接打开/关闭_cabin_的功率。
__应用实体__：大多数_cabin_，除了``驾驶室''，`发动机机舱'，`dinning Cabin''和'bilge'。
###聚焦目标
移动`摄像机'专注于_entity_。
__应用实体__：所有_stage Entity_。
###给出项目
打开``ImeT fiving window''以将_item_提供给_agent_，这将立即提供_item_。
__在舞台上应用实体__：_agent_。
###使用项目
在友好_agent_的自我背包中使用_item_。
__应用实体__：友好_agent_。
＃＃＃ 救援
使用[[PERK列表＃现场救援能力（LVL.13）|战斗场救援]]将“无意识的Ally返回到“意识”。
__应用实体__：_agent_与相关的_perk_。
＃＃ 普通的
### ~~打开的失速窗口~~
###股票转移
打开“传输窗口”以在_ship stock_和_stage item_之间传输_item_，这将创建一个_chore_让_crew_做。
__ applied entity __：_ stage item_ with`itemownerCpt'。
＃＃＃ 买
打开“购物窗口”。
__应用实体__：_entity_在'itemownerCpt`'s ostable cantaper'中具有_item_。
###设置旅行目的地
将_anchor_设置为_Ship_的旅行目的地。
__ applied实体__：_anchor_在地图上。
##战斗
###开关武器
在_agent_背包中的所有武器中选择，如果武器没有“弹药”，则选择将被禁用。
__应用实体__：友好_agent_。
###设定攻击目标
任命友好_agent_的攻击目标。
__应用实体__：感知距离的友好_agent_。
###共享供应
订单_agent_与附近的_agent _共享`ammo`或`neverical'。
__应用实体__：在动作范围内友好_agent_。
＃切换
＃＃ 通用的
＃＃ 普通的
##战斗
###停止攻击
禁止_agent_自动攻击敌人。
__应用实体__：友好_agent_。
###启用通灵
允许_agent_使用其[[Psychic]]功率。
__应用实体__：友好_agent_是_psychic_。
###禁止使用项目
禁止_agent_自动使用_item_。
__应用实体__：友好_agent_。
＃切换组
＃＃ 通用的
＃＃ 普通的
##战斗
###射击策略
从所有拍摄策略中选择_agent_学习。
 -  __非正常射击__
 -  __ sharp shot__，使用[[PERK LIST＃COMBAT | SHARPHOOTER]] PERK，每次镜头都会击中，但花费更多的时间
__应用实体__：使用范围武器友好_agent_。
###近战战术
从所有近战战术中选择学习。
 -  __非正常罢工__
 -  __ berserk罢工__，带有“狂热的振兴，损坏更大，但命中率较低
 -  __ PRECISE Strike__，具有“精确的罢工”振兴，命中率更高，但花费更多的时间
###搜索策略
从所有移动中选择_agent _学习。
 -  __ Sole Space__，仅在当前[[战斗空间＃space | space]]中搜索敌人。
 -  _____________________
__应用实体__：友好_agent_。