# OAGeneSnowstormOrphan-HSK-Patch
HSK patch for [OA]Ratkin Scenario: Snowstorm Orphan | [OA]鼠族剧本扩展：风雪的遗孤HSK补丁

**注意：开局的时候需要在右上角手动选择年龄段为儿童，否则不能正常生成14岁鼠鼠**

**IMPORTANT NOTE: At the start of the scenario you must manually set your colonist’s age range to “Child” in the top-right corner, otherwise a 14-year-old Ratkin won’t generate correctly.**


能力有限，目前只做了一点点东西，基本能开局玩了，归乡事件的袭击会有少量问题，不过结局能正常触发。永久心情buff好像没有生效。本来是自己弄着玩的，想了下说不定有其他人也想在HSK玩这个就传上来了（）别的我还没弄，能做到现在这个水平已经谢天谢地了

难度平衡也基本没做（）想着开局有野生作物和野生图腾可以拆了做原始零部件，以及早期食物保存有晾干架和罐子，屋顶底下石头还能自己长蘑菇，所以就没改太多，只给了一套工具，加了一点点起始资源，给了隔壁鼠鼠开局有的几个科技。推荐初始角色建筑等级至少roll到3级，否则连锯木台都做不了。

My modding skills are limited, and I’ve only made a few fixes so far. Basically “The orphan of the snowstorm” is playable now, the ending still triggers correctly, but homecoming event raid has some minor issues. Permanent mood buff from Snowstorm Orphan doesn’t seem to work.

I didn’t spend much time on difficulty balance -- I figured that starting with wild crops and totems can be dismantle for primitive parts, early food preservation with drying racks and pots, and mushrooms growing on stone ground under roof would be enough. So I only added a set of tools, a small amount of starting resources, and the few technologies that the neighboring Ratkin start with. Starting colonist recommends at least Lv3 Construction, or you won’t be able to build even a sawmill.

+ 主要修改：

+ 风雪遗孤剧本报错修复（将剧本适配为修改过的研究项目ID、添加了几个基础科技和工具）

+ 鼠鼠异种的生成添加

+ 替换鼠鼠耳朵和尾巴的基因为OA版本

+ 耳朵贴图修复

+ 风雪篝火使用HSK燃料机制的适配。

Main changes:

+ Fixed startup errors in the Snowstorm Orphan scenario (corrected modified research project IDs; added several basic technologies and tools).

+ Added new Ratkin xenotype to the generation lists.

+ Swapped the HSK Ratkin ear and tail genes for the OA versions.

+ Restored correct ear graphics so they display properly.

+ Adapted the Snowstorm Campfire to use the HSK fuel system.

已知问题：

+ roll人的时候会显示尝试300次无法生成符合要求的小人，并且需要手动选择年龄段才能正常生成14岁鼠鼠。（不过我看基本上没太大问题就没管了，HSK好像改了鼠鼠pawnkind的年龄段，但是我看着def好像也没有冲突，不知道是怎么回事）

+ 终局任务时围攻可能会出现寻路问题不进攻、循环红字报错,SkyAI在生成海盗袭击武器时出现空指针错误

+ 终局任务时“隐隐约约的人影”可能会变为空投袭击，同时隐身效果失效

+ 结局给的永久心情buff似乎不会正常触发

[OA]鼠族基因扩展  [![Steam Downloads](https://img.shields.io/steam/downloads/3300291918?style=flat&logo=steam&label=Steam%20Workshop)](https://steamcommunity.com/sharedfiles/filedetails/?id=3300291918)

[OA]鼠族剧本扩展：风雪的遗孤  [![Steam Downloads](https://img.shields.io/steam/downloads/3381392312?style=flat&logo=steam&label=Steam%20Workshop&color=blue)

License: CC BY-NC-SA 4.0 (https://creativecommons.org/licenses/by-nc-sa/4.0/)
