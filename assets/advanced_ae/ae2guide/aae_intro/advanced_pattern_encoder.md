---
navigation:
  parent: aae_intro/aae_intro-index.md
  title: 高級樣板編碼器
  icon: advanced_ae:adv_pattern_encoder
categories:
  - advanced items
item_ids:
  - advanced_ae:adv_pattern_encoder
  - advanced_ae:adv_processing_pattern
---

# 高級樣板編碼器

為了教導 ME 高級模式提供者將你的物品送到哪裡，需要一個特殊的設備來編碼資訊.您可以用手右鍵單擊來開啟其 GUI。

<ItemImage id="advanced_ae:adv_pattern_encoder" scale="4"></ItemImage>

可以將編碼的加工模式插入左側插槽，然後對其進行解碼，然後所有原料以列表形式顯示。

![PEGui1](../pic/ape_pattern.png)

每行包含一組按鈕，代表該成分的所有可能的方塊面可以發送到。將選擇保留在“A”按鈕中將把它發送到與模式提供程序，同時選擇特定的面將強制將該面作為項目插入的位置。重要的是請注意，高級模式只能透過 <ItemLink id="advanced_ae:adv_pattern_provider" /> 正確解碼，並且將如果在其他類型的模式提供者中使用，則行為就像正常模式一樣。此外，如果單一物品無法插入到指定的面，則不會有物品按方向插入，且將採用標準模式提供者行為。