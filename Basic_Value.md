https://minecraft.fandom.com/zh/wiki/%E5%B1%9E%E6%80%A7  
https://home.gamer.com.tw/creationDetail.php?sn=3960292  
https://minecraft.fandom.com/zh/wiki/%E7%8A%B6%E6%80%81%E6%95%88%E6%9E%9C  
https://home.gamer.com.tw/creationDetail.php?sn=3948212  

# 生物屬性
#### **屬性** 
```Java
Attributes:
   [             
    {Name:"generic.max_health",Base:20},	             // 最大生命值    ( 0.0 < n < 1024.0 )
    {Name:"generic.armor",Base:0},                   	     // 盔甲          ( 0.0 < n < 30.0 )
    {Name:"generic.armor_toughness",Base:0},	             // 盔甲強度      ( 0.0 < n < 20.0 )
    {Name:"generic.attack_damage",Base:1},	             // 攻擊傷害      ( 0.0 < n < 2048.0 )
    {Name:"generic.attack_speed",Base:4},	             // 攻擊速度      ( 0.0 < n < 1024.0 )
    {Name:"generic.attack_knockback",Base:0},                // 擊退力度      ( 0.0 < n < 0.0 )
    {Name:"generic.flying_speed",Base:0.4},	             // 飛行速度      ( 0.0 < n < 1024.0 )
    {Name:"generic.follow_range",Base:32},	             // 生物追蹤範圍  ( 0.0 < n < 2048.0 )
    {Name:"generic.knockback_resistance",Base:0},	     // 抗擊退率      ( 0.0 < n < 1.0 )
    {Name:"generic.luck",Base:0},	                     // 幸運         ( -1024.0 < n < 1024.0 )
    {Name:"generic.movement_speed",Base:20},	             // 速度         ( 0.0 < n < 1024.0 )
    {Name:"horse.jump_strength",Base:0.7},	             // 馬跳躍力      ( 0.0 < n < 2.0 )
    {Name:"zombie.spawn_reinforcements",Base:0},	     // 殭屍增援      ( 0.0 < n < 1.0 )
   ]
   generic.attackReach（正式版本尚未使用）	玩家的攻擊距離	3.0	0.0	6.0
   generic.reachDistance（正式版本尚未使用）	玩家的觸及半徑	5.0	0.0	256.0
```

#### **狀態效果**

```Java
ActiveEffects:
   [
    {Id:14b,Amplifier:0b,Duration:2000000000,ShowParticles:0b}  //隱形
   ]
    
```
```
1   速度
2   緩速
3   挖掘加速
4   挖掘疲勞
5   力量
6   立即治療
7   立即傷害
8   跳躍提升
9   噁心
10  回復
11  抗性
12  抗火
13  水下呼吸
14  隱形
15  失明
16  夜視
17  飢餓
18  虛弱
19  劇毒
20  凋零
21  生命值提升
22  吸收
23  飽食
24  發光
25  懸浮
XX  劇毒(基岩版)
26  幸運
27  霉運
28  緩降
29  海靈祝福
30  海豚悠游
31  不祥之兆
32  村莊英雄
```

# 武器屬性
```java
mainhand，offhand，head，legs，chest，feet。

diamond_sword
   {
    AttributeModifiers:
     [
     {Slot:"mainhand",AttributeName:"generic.attack_damage",Name:"generic.attack_damage",Amount:20,Operation:0,UUID:[I;1,1,1,1]}
     ]
   }
```
