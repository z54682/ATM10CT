---
navigation:
  parent: aae_intro/aae_intro-index.md
  title: ME吞吐量監控器
  icon: advanced_ae:throughput_monitor
categories:
  - advanced items
item_ids:
  - advanced_ae:throughput_monitor
  - advanced_ae:throughput_monitor_configurator
---

# ME吞吐量監控器

<GameScene zoom="8" background="transparent">
<ImportStructure src="../structure/throughput_monitors.snbt"></ImportStructure>
<IsometricCamera yaw="195" pitch="30" />
</GameScene>

吞吐量監控器是監視器的亞型。他們提供相同的功能 <itemLink ID ="AE2:storege_monitor" />確實，加上吞吐量儀表。將跟踪單個項目/流體類型，並將監視器更改為其數量，向用戶顯示每秒的流量。

它*不需要*一個頻道。

## 操作

*   右鍵單擊一個物品或雙右鍵單擊，然後用流體容器將監視器設置為該項目/流體。
*   用空手右鍵單擊以清除監視器。
*   用空手SHIFT+右鍵單擊以鎖定監視器。

## 吞吐量監控器配置器

<ItemImage id="advanced_ae:throughput_monitor_configurator" scale="4"></ItemImage>

吞吐量監控器配置器是一種可用於更改顯示的數據的工具。右鍵單擊顯示器手中的一個將在三個選項之間循環：

* 每tick的物品
* 每秒的物品
* 每分鐘的物品

注意：更改模式時的讀數穩定可能需要一些時間，因此不要相信初始值！