---
title: 导航
icon: mdi:compass-rose
permalink: /features/PathFinder/
createTime: 2025/10/02 17:24:58
---

## ::mdi:help-circle-outline:: 插件简介

**PathFinder** 是一款强大的寻路插件，它能为您在广阔的服务器世界中找到通往其他玩家的最佳路线。

它会通过一条仅您自己可见的实时粒子路径，清晰地引导您前往目的地，再也不用担心迷路了！

- ::mdi:flash:: **性能卓越**：所有复杂的路径计算都在后台异步进行，完全不会造成服务器卡顿。
- ::mdi:translate:: **多语言支持**：插件界面会自动适配您的客户端语言，支持简/繁中文、英语等 8 种语言。
- ::mdi:map-marker:: **精准导航**：基于强大的 A* 算法，为您规划出高效、智能的移动路线。

## ::mdi:play-box-outline:: 插件演示

导航时的粒子效果：
![1756470220397.png](https://free.picui.cn/free/2025/08/29/68b19dcf4573e.png)
![1756470179981.png](https://free.picui.cn/free/2025/08/29/68b19dd0beeb5.png)

导航菜单界面（使用 `/toc cd` 打开）：
![1756470687812.png](https://free.picui.cn/free/2025/08/29/68b19ddba00d2.png)

## ::mdi:console-line:: 玩家常用指令

### 打开主菜单
这是最核心的指令，所有功能都可以在菜单中完成。
- **`/toc cd`**: 打开玩家导航菜单。

### 路径点管理
您可以将当前位置保存为路径点，方便以后快速导航回来。

- **`/toc nav add <路径点名称>`**
  - ::mdi:plus-circle /#4CAF50:: 在您当前的位置创建一个新的路径点。
  - *示例: `/toc nav add home`*

- **`/toc nav go <路径点名称>`**
  - ::mdi:run /#2196F3:: 开始导航至您指定的路径点。
  - *示例: `/toc nav go home`*

- **`/toc nav list`**
  - ::mdi:format-list-bulleted:: 查看所有您已创建的路径点列表。

- **`/toc nav remove <路径点名称>`**
  - ::mdi:delete /#F44336:: 删除一个已创建的路径点。
  - *示例: `/toc nav remove old_base`*

- **`/toc nav rename <旧名称> <新名称>`**
  - ::mdi:pencil:: 重命名一个路径点。
  - *示例: `/toc nav rename home sweet_home`*

### 其他指令

- **`/toc nav stop`**
  - ::mdi:stop-circle /#FF9800:: 停止当前的导航。

- **`/toc lang <语言代码>`**
  - ::mdi:web:: 切换插件的显示语言。
  - *可用语言: `zh-CN` (简体中文), `zh-TW` (繁體中文), `en-US` (英语) 等。*
  - *示例: `/toc lang en-US`*

## ::mdi:alert-circle-outline /orange:: 注意事项

- ::mdi:karate:: 本插件不适用于高精度的跑酷寻路。
- ::mdi:ladder:: 目前，攀爬类的寻路仅支持梯子和脚手架。
- ::mdi:water-off:: 在水下的寻路可能会出现一些意料之外的情况，请谨慎使用。

如果您在使用中遇到任何问题，欢迎向服务器管理员反馈！
