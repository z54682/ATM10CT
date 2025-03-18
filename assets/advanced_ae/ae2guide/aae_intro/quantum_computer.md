---
navigation:
  parent: aae_intro/aae_intro-index.md
  title: 量子計算機
  icon: advanced_ae:quantum_core
categories:
  - advanced devices
item_ids:
  - advanced_ae:quantum_unit
  - advanced_ae:quantum_core
  - advanced_ae:quantum_structure
  - advanced_ae:quantum_accelerator
  - advanced_ae:quantum_multi_threader
  - advanced_ae:quantum_storage_128
  - advanced_ae:quantum_storage_256
  - advanced_ae:data_entangler
---

# 量子計算機

量子計算機是一種特殊的合成電腦。它能夠進行無限量的製作請求，只要它有足夠的製作儲存空間。

<GameScene zoom="2" background="transparent">
  <ImportStructure src="../structure/quantum_computer_multiblock.snbt"></ImportStructure>
</GameScene>

## 量子計算機核心

<BlockImage id="advanced_ae:quantum_core" p:powered="true" p:formed="true" scale="4"></BlockImage>

量子計算機核心是量子計算機的核心。它擁有 256M 的製作儲存空間和 8 個處理器線程。它是唯一能夠自行創建成形量子電腦並提供所有優點的模組量子計算機。然而，如果用來創建多方塊，則可以創建功能更強大的計算機。當用作獨立計算機，必須透過連接器所在的上側或下側提供電源。

## 量子計算機合成存儲器

<Row gap="20">
<BlockImage id="advanced_ae:quantum_storage_128" scale="4"></BlockImage>
<BlockImage id="advanced_ae:quantum_storage_256" scale="4"></BlockImage>
</Row>

這些方塊擴展了量子核心的製作儲存。它們有效地增加了並發任務的數量
量子計算機能夠運作。有兩種版本，容量分別為 128M 和 256M。

## 量子數據糾纏器

<BlockImage id="advanced_ae:data_entangler" scale="4"></BlockImage>

數據糾纏器是一個特殊的方塊，它會影響多個區塊中存在的所有儲存區塊。它們支援存儲區塊在多個維度上儲存數據，有效地將其儲存空間乘以 4。在每個量子電腦多方塊中。

## 量子計算機加速器

<BlockImage id="advanced_ae:quantum_accelerator" scale="4"></BlockImage>

量子加速器為量子計算機多方塊增加了 8 個並行處理器。值得注意的是，所有手工製作量子計算機運作的模式能夠共享所有處理器，因此投資其中很大一部分。

## 量子計算機多線程處理器

<BlockImage id="advanced_ae:quantum_multi_threader" scale="4"></BlockImage>

與資料糾纏器類似，多線程器使加速器能夠在不同的維度上運行額外的線程，將它們的處理能力乘以 4。

## 量子計算機外殼

<Row gap="20">
<BlockImage id="advanced_ae:quantum_structure" scale="4"></BlockImage>
<BlockImage id="advanced_ae:quantum_structure" p:formed="true" scale="4"></BlockImage>
<BlockImage id="advanced_ae:quantum_structure" p:formed="true" p:powered="true" scale="4"></BlockImage>
</Row>

這些方塊提供了量子計算機的框架。它們被用作量子計算機的構建模組，將一切連結在一起。

## 多方塊

要創建多方塊量子計算機，必須遵循一些規則：
- 最大尺寸為 7x7x7（外部尺寸）；
- 多方塊內部不能有空白空間。它們可以用 <ItemLink id="advanced_ae:quantum_unit" /> 填充，不享有任何額外福利；
- 恰好一個 <ItemLink id="advanced_ae:quantum_core" />;
- 最多一個 <ItemLink id="advanced_ae:data_entangler" />;
- 最多一個 <ItemLink id="advanced_ae:quantum_multi_threader" />;
- 所有外層的區塊必須是<ItemLink id="advanced_ae:quantum_structure" />;
- 裡面沒有區塊可以是<ItemLink id="advanced_ae:quantum_structure" />。

## 伺服器配置

可以透過伺服器配置調整幾個值。例如：
- 最大結構大小；
- 每個量子加速器中的協處理器；
- 最大數量的量子多線程器；
- Multi-Threader 執行緒乘法值；
- 資料糾纏器的最大數量；
- Data Entangler 儲存乘法值；

您可以使用項目的工具提示來檢查實例的限制。