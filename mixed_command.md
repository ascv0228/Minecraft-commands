# 告示牌召喚村民
#### **產生器:https://minecraft.tools/en/sign.php** 
`/give @p minecraft:oak_sign{BlockEntityTag:{Text1:'{"text":"Minecraft Tools","clickEvent":{"action":"run_command","value":"summon villager"}}'},display:{Name:'{"text":"Custom Sign"}'}}`


# 簡單小島+物資
#### **物品:鐵裝+肉+種子之類的** 

`summon falling_block ~ ~1 ~ {BlockState:{Name:activator_rail},Time:1,Passengers:[{id:falling_block,BlockState:{Name:redstone_block},Time:1,Passengers:[{id:falling_block,BlockState:{Name:activator_rail},Time:1,Passengers:[{id:falling_block,BlockState:{Name:activator_rail},Time:1,Passengers:[{id:command_block_minecart,Command:"setblock ~1 ~-2 ~-4 minecraft:dirt replace"},{id:command_block_minecart,Command:"fill ~1 ~ ~-2 ~6 ~ ~-4 minecraft:grass_block"},{id:command_block_minecart,Command:"fill ~4 ~ ~-5 ~6 ~ ~-7 minecraft:grass_block"},{id:command_block_minecart,Command:"fill ~1 ~-2 ~-2 ~6 ~-1 ~-4 minecraft:stone"},{id:command_block_minecart,Command:"fill ~4 ~-2 ~-5 ~6 ~-1 ~-7 minecraft:stone"},{id:command_block_minecart,Command:"setblock ~2 ~1 ~-3 minecraft:chest[facing=east]{CustomName:\"\\\"Command by NitroGamingYtR6\\\"\",Items:[{id:lava_bucket,Count:1,Slot:0},{id:ice,Count:1,Slot:1},{id:oak_sapling,Count:3,Slot:2},{id:cooked_beef,Count:32,Slot:8},{id:iron_helmet,Count:1,Slot:9},{id:iron_chestplate,Count:1,Slot:10},{id:iron_leggings,Count:1,Slot:11},{id:iron_boots,Count:1,Slot:12},{id:iron_sword,Count:1,Slot:13},{id:iron_axe,Count:1,Slot:14},{id:iron_pickaxe,Count:1,Slot:15},{id:iron_shovel,Count:1,Slot:16},{id:iron_hoe,Count:1,Slot:17},{id:spawner,Count:1,Slot:18},{id:chicken_spawn_egg,Count:1,Slot:19},{id:totem_of_undying,Count:1,Slot:20},{id:melon_seeds,Count:1,Slot:21},{id:pumpkin_seeds,Count:1,Slot:22},{id:wheat_seeds,Count:16,Slot:23},{id:ender_pearl,Count:8,Slot:25},{id:red_bed,Count:1,Slot:26}]} replace"},{id:command_block_minecart,Command:"setblock ~4 ~4 ~-9 minecraft:oak_leaves replace"},{id:command_block_minecart,Command:"setblock ~5 ~4 ~-9 minecraft:oak_leaves replace"},{id:command_block_minecart,Command:"fill ~5 ~4 ~-8 ~5 ~4 ~-5 minecraft:oak_leaves"},{id:command_block_minecart,Command:"fill ~6 ~4 ~-9 ~6 ~4 ~-8 minecraft:oak_leaves"},{id:command_block_minecart,Command:"fill ~6 ~4 ~-6 ~6 ~4 ~-5 minecraft:oak_leaves"},{id:command_block_minecart,Command:"setblock ~7 ~4 ~-9 minecraft:oak_leaves replace"},{id:command_block_minecart,Command:"fill ~7 ~4 ~-8 ~7 ~4 ~-5 minecraft:oak_leaves"},{id:command_block_minecart,Command:"fill ~8 ~4 ~-8 ~8 ~4 ~-6 minecraft:oak_leaves"},{id:command_block_minecart,Command:"setblock ~4 ~5 ~-8 minecraft:oak_leaves replace"},{id:command_block_minecart,Command:"fill ~4 ~5 ~-7 ~4 ~5 ~-5 minecraft:oak_leaves"},{id:command_block_minecart,Command:"fill ~5 ~5 ~-9 ~5 ~5 ~-5 minecraft:oak_leaves"},{id:command_block_minecart,Command:"setblock ~6 ~5 ~-9 minecraft:oak_leaves replace"},{id:command_block_minecart,Command:"setblock ~6 ~5 ~-8 minecraft:oak_leaves replace"},{id:command_block_minecart,Command:"fill ~6 ~5 ~-6 ~6 ~5 ~-5 minecraft:oak_leaves"},{id:command_block_minecart,Command:"fill ~7 ~5 ~-9 ~7 ~5 ~-5 minecraft:oak_leaves"},{id:command_block_minecart,Command:"setblock ~8 ~5 ~-8 minecraft:oak_leaves replace"},{id:command_block_minecart,Command:"fill ~5 ~4 ~-8 ~4 ~4 ~-5 minecraft:oak_leaves"},{id:command_block_minecart,Command:"fill ~8 ~5 ~-7 ~8 ~5 ~-6 minecraft:oak_leaves"},{id:command_block_minecart,Command:"setblock ~5 ~6 ~-7 minecraft:oak_leaves replace"},{id:command_block_minecart,Command:"setblock ~5 ~6 ~-6 minecraft:oak_leaves replace"},{id:command_block_minecart,Command:"setblock ~6 ~6 ~-8 minecraft:oak_leaves replace"},{id:command_block_minecart,Command:"setblock ~6 ~6 ~-6 minecraft:oak_leaves replace"},{id:command_block_minecart,Command:"setblock ~7 ~6 ~-7 minecraft:oak_leaves replace"},{id:command_block_minecart,Command:"setblock ~5 ~7 ~-7 minecraft:oak_leaves replace"},{id:command_block_minecart,Command:"fill ~6 ~7 ~-8 ~6 ~7 ~-6 minecraft:oak_leaves"},{id:command_block_minecart,Command:"setblock ~7 ~7 ~-7 minecraft:oak_leaves replace"},{id:command_block_minecart,Command:"fill ~6 ~1 ~-7 ~6 ~6 ~-7 minecraft:oak_log"},{id:command_block_minecart,Command:"setblock ~ ~-1 ~ air replace"}]}]}]}]}`

# 烽火台
`summon falling_block ~ ~1 ~ {Time:1,BlockState:{Name:redstone_block},Passengers:[
{id:armor_stand,Health:0,Passengers:[
{id:falling_block,Time:1,BlockState:{Name:activator_rail},Passengers:[
{id:command_block_minecart,Command:'gamerule commandBlockOutput false'},
{id:command_block_minecart,Command:'data merge block ~ ~-2 ~ {auto:0}'},
{id:command_block_minecart,Command:'setblock ~ ~5 ~ minecraft:beacon replace'},
{id:command_block_minecart,Command:'fill ~4 ~1 ~4 ~-4 ~1 ~-4 minecraft:netherite_block'},
{id:command_block_minecart,Command:'fill ~3 ~2 ~3 ~-3 ~2 ~-3 minecraft:netherite_block'},
{id:command_block_minecart,Command:'fill ~2 ~3 ~2 ~-2 ~3 ~-2 minecraft:netherite_block'},
{id:command_block_minecart,Command:'fill ~1 ~4 ~1 ~-1 ~4 ~-1 minecraft:netherite_block'},
{id:command_block_minecart,Command:'setblock ~ ~1 ~ command_block{auto:1,Command:"fill ~ ~ ~ ~ ~-2 ~ air"}'},
{id:command_block_minecart,Command:'kill @e[type=command_block_minecart,distance=..1]'}]}]}]}`

# 浮空文字
`summon area_effect_cloud ~ ~ ~ {CustomName:'"文字"',CustomNameVisible:1,Duration:2147483647}`
`summon armor_stand ~ ~ ~ {Invulnerable:1,Marker:1,Invisible:1,NoGravity:1,DisabledSlots:4144959,CustomName:'"懸浮文字"',CustomNameVisible:1}`
`summon area_effect_cloud ~ ~ ~ {Invulnerable:1,Duration:2147483647,Particle:"block air",CustomName:'"懸浮文字"',CustomNameVisible:1}`
`summon area_effect_cloud ~ ~ ~ {Tags:[""],CustomName:'"懸浮文字"',CustomNameVisible:1,Invulnerable:1,Duration:2147483647,Particle:"block air"}`
