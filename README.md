# The Elder Scrolls V Skyrim Special Edition (ver 1.6.1170.0)

## 安裝前必須知道的事

1. 查看Skyrim的主執行檔版本, 確認你使用的版本, 這會影響日後想要安裝的「模組版本」搭配問題.
2. 決定你想要使用的模型架構, 大約如下:

    | 型態 | 說明 |
    | --- | --- |
    | UNP/UUNP | 一種女性身形模組, 線條自然, 身形相對纖細.可搭配模組: BodySlide、RaceMenu、HDT、CBP. |
    | CBBE | 大家都一定裝的身形模組, 線條更豐滿, 並且有很多服裝模組支援. |
    | CBBE 3BA | 高階物理支援身形, 也支援布料物理、乳搖、臀搖. |
    | 3BBB | 同時支援胸部、臀部、陰部三部位的物理. |
    | BHUNP | UNP的3BBB擴展版本, 支援HDT-SMP、CBPC. |
    | COCO Body | 特殊自訂身形架構, 通常用於性感模組(例如18禁), 支援高解析度貼圖與3BBB效果. |
    | TBD | 另一種支援BodySlide的女性身形, 風格比較性感, 但很誇張, 常搭配3BBB使用. |
    | Vanilla Body | 原始的遊戲身型. |
    | SOS | 男性身形與下體. |
    | SAM | 可自定義身形的高品質男性身形. |
    | HIMBO | 支援物理、BodySlide. |

3. 了解身形可支援的物理特性, 大約如下:

    | 型態 | 說明 |
    | --- | --- |
    | CBPC (Collision-Based Physics for Clothes) | 輕量化物理模擬. |
    | SMP (Skinned Mesh Physics)| 更真實的物理模擬|
    | HDT-SMP (Havok Digital Technology - Skinned Mesh Physics) | 布料與身體物理模擬. |
    | FSMP (Faster SMP) | HDT-SMP的效能增強版, 也支援3BBB/3BA. |

4. 本篇文章使用的模組啟動器為MO2 (Mod Organizer 2), 目前使用的版本為 2.5.2  
作者的網址: <https://github.com/ModOrganizer2/modorganizer/releases>  
請下載 Mod.Organizer-2.5.2.exe 這個執行檔回來自行安裝.

## 在安裝下面那些模組之前,必須先安裝這些前置模組

- SKSE ([Skyrim Script Extender](https://skse.silverlock.org/)) - 必須使用檔案總管手動安裝
- Address Library ([Address Library for SKSE Plugins](https://www.nexusmods.com/skyrimspecialedition/mods/32444)) - 可由模組啟動器安裝
- USSEP ([Unofficial Skyrim Special Edition Patch](https://www.nexusmods.com/skyrimspecialedition/mods/266)) - 可由模組啟動器安裝

_「Caliente's Beautiful Bodies Enhancer」的模組作者強烈建議玩家要安裝USSEP._

## **SKSE的安裝過程**  

:derelict_house:SKSE作者網址 : <https://skse.silverlock.org/>  
:exclamation:在 Steam 購買Skyrim的請下載 Current Anniversary Edition build 2.2.6 (game version 1.6.1170) 這個版本.  
:exclamation:在 GOG 購買Skyrim的請下載 Current GOG Anniversary Edition build 2.2.6 (game version 1.6.1179) 這個版本.

1. 將下載回來的壓縮檔解開, 把裡面的 skse64_1_6_1170.dll 和 skse64_loader.exe 這兩個檔案丟進你的Skyrim安裝的主目錄裡.
例如: "..\steamapps\common\Skyrim Special Edition", 也就是SkyrimSE.exe這個檔案會存在的那個目錄.
2. 接著, 再把壓縮檔裡的Data目錄整個丟進你的Skyrim安裝的主目錄裡, 跟上面一樣的路徑, 直接讓它覆蓋原有的Data目錄即可.
3. 再來, 使用 skse64_loader.exe 啟動遊戲, 在遊戲開頭主畫面時, 可以先不用開始遊戲, 直接按鍵盤「~鍵」(在鍵盤的左上角那個按鍵), 此時會進入控制台模式.
輸入 getskseversion 它會顯示出你目前用的SKSE版本號碼, 有出現就代表安裝成功了, 接著再按一次「~鍵」就可以關閉控制台模式.

## 進行美化角色的安裝順序

:gear: [BodySlide and Outfit Studio](https://www.nexusmods.com/skyrimspecialedition/mods/201)  
&nbsp;&nbsp;&nbsp;&nbsp;⬇️  
:gear: [CBBE ( Caliente's Beautiful Bodies Enhancer )](https://www.nexusmods.com/skyrimspecialedition/mods/198)  
&nbsp;&nbsp;&nbsp;&nbsp;⬇️  
:gear: [XPMSSE (XP32 Maximum Skeleton Special Extended)](https://www.nexusmods.com/skyrimspecialedition/mods/1988)  
&nbsp;&nbsp;&nbsp;&nbsp;⬇️  
下面兩個物理系統二選一
<table cellpadding="2">
  <tr>
    <th>主模組</th>
    <th>前置模組</th>
  </tr>
  <tr>
    <td rowspan="4">
      <a href="https://www.nexusmods.com/skyrimspecialedition/mods/21224">CBPC (Physics with Collisions)</a>
      <br>遊戲中的物件和角色動作更加真實和互動性更強, 例如角色動作時的碰撞反應等.
    </td>
    <td>
      <a href="https://skse.silverlock.org/">SKSE64</a>
    </td>
  </tr>
  <tr><td><a href="https://www.nexusmods.com/skyrimspecialedition/mods/1988">XPMSSE</a></td></tr>
</table>
<br>
<table cellpadding="4">
  <tr>
    <th>主模組</th>
    <th>前置模組</th>
  </tr>
  <tr>
    <td rowspan="4">
      <a href="https://www.nexusmods.com/skyrimspecialedition/mods/57339">HDT-SMP (Faster HDT-SMP)</a>
      <br>改善遊戲的性能，使得物理效果更流暢，特別是在有多個物理模擬效果同時運行時.
      <br>推薦使用在乳搖、搖臀、飄髮、服裝等等效果.
    </td>
    <td>
      <a href="https://www.nexusmods.com/skyrimspecialedition/mods/91616">SMP-NPC crash fix</a>
    </td>
  </tr>
  <tr><td><a href="https://www.nexusmods.com/skyrimspecialedition/mods/13048">PapyrusUtil SE</a></td></tr>
  <tr><td><a href="https://www.nexusmods.com/skyrimspecialedition/mods/16495">JContainers SE</a></td></tr>
  <tr><td><a href="https://www.nexusmods.com/skyrimspecialedition/mods/76649">ConsoleUtilSSE NG</a></td></tr>
</table>

&nbsp;&nbsp;&nbsp;&nbsp;⬇️  
:gear: [3BA (CBBE 3BA)](https://www.nexusmods.com/skyrimspecialedition/mods/30174)  
&nbsp;&nbsp;&nbsp;&nbsp;⬇️  
:gear: [RaceMenu](https://www.nexusmods.com/skyrimspecialedition/mods/19080)  
&nbsp;&nbsp;&nbsp;&nbsp;⬇️  
:gear: 安裝自訂的身形模組(例如: [Curvy Queen - CBBE 3BA Bodyslide Preset](https://www.nexusmods.com/skyrimspecialedition/mods/148924))  
&nbsp;&nbsp;&nbsp;&nbsp;⬇️  
:gear: 使用[BodySlide](https://www.nexusmods.com/skyrimspecialedition/mods/201)軟體替換遊戲內建的身形檔案 (使用模組啟動器啟動BodySlide x64.exe執行檔案)

---
<details>
<summary><h2>CBBE的安裝過程選項</h2></summary>

### **Body Shape (體形)**

- Slim : 苖條的, CBBE預設的身形, 女性身形較苖條.
- Curvy : 豐滿的, 基於原版的CBBE架構, 身形比例較逼真.
- Vanilla : Skyrim的內建身形, 腰部較粗, 胸部較低, 骨盆較寬.

### **Underwear Options (內衣選項)**  

- Underwear : Skyrim的內建身形, 也就是脫光衣服後還是保持有穿內衣的外觀.
- NeverNude : Skyrim的內建身形, 不穿內衣.
- None : 都不使用.

### **Outfit Optionis (服裝選項)**  

- Vanilla Outfits : Skyrim的內建服裝.

### **Face Options (臉部選項)**  

- Face Pack : 面膜
- Dirt to Beauty Marks : 添加污垢與美人痣

### **Eyebrow Options (眉毛選項)**  

- Thin + Trimmed Brows : 稀疏加修剪的眉毛.
- Thin + Trimmed Brows (Light) : 稀疏加修剪的眉毛 (淡色).
- Trimmed Brows : 修剪的眉毛.
- Trimmed Brows (Light) : 修剪的眉毛 (淡色)
- Bushier Brows : 濃密的眉毛
- Bushier Brows (Light) : 濃密的眉毛 (淡色)
- None: 不使用

### **Miscellaneous (其他)**  

- Pubic Hair : 陰毛

### **SKEE (RaceMenu)**  

- RaceMenu Morphs (BodyMorph) : 搭配RaceMenu模組的變形功能.

### **Morph Files (變形檔案)**  

- Morph Files (Body) : 變形檔案, 針對身體
- Morph Files (Outfits) : 變形檔案, 針對服裝

</details>

<details>
<summary><h2>XPMSSE的安裝過程選項</h2></summary>

### **Installation (安裝)**  

- Extended : 擴充版
- Basic : 基本版
- Minimal : 最低需求版

### **Animation Rig Map (動畫綁定貼圖)**  

- XPMS(S)E Latest : 最新的動畫綁定貼圖, 完全支援所有實體插件的身體物理效果,例如HDT和CBP(C), 支援最新的動畫資料格式.  
需要FNIS或Nemesis模組.
- XPMS(S)E 4.51 : 較舊的動畫綁定貼圖, 完全支援所有實體插件的身體物理效果,例如HDT和CBP(C), 某些模組可能需要這種舊的綁定格式.  
需要FNIS或Nemesis模組.
- XPMS(S)E TBBP : 老舊的動畫綁定貼圖, 支援動畫中綁定身體物理, 可能會與HDT和CBP(C)等實體插件有衝突, 某些模組可能需要這種舊的綁定格式.  
需要FNIS或Nemesis模組.
- None : 不使用.

### **Character and Weapons (角色和武器)**  

- **Ingame Customizing (遊戲內自訂)**  
  - RaceMenu + XPMS(S)E MCM : 為RaceMenu用戶使用XPMSE的外掛程式在遊戲內進行自訂的功能.  
  需要RaceMenu, SkyUI, SKSE, FNIS.
  - RaceMenu + XPMS(S)E MCM + Weapon Styles : 為RaceMenu用戶使用XPMSE的外掛程式在遊戲內進行自訂的功能. GiraPomba的武器風格用於改變裝備動畫, 需要在XPMSE MCM中關閉樣式符合的動畫選項.  
  需要RaceMenu, SkyUI, SKSE, FNIS.
  - RaceMenu : 為RaceMenu用戶使用XPMSE的外掛程式在遊戲內進行自訂的功能, 武器位置或動畫不受XPMS控制, 需要其他模組來替代此功能.  
  需要RaceMenu模組.
  - XPMS(S)E MCM : ECE或Vanilla用戶可以使用XPMSE MCM在遊戲內進行自訂.  
  需要RaceMenu或NetImmerse Override Standalone, SkyUI, SKSE, FNIS 的 SKEE.
  - XPMS(S)E MCM + Weapon Styles : ECE或Vanilla用戶可以使用XPMSE MCM在遊戲內進行自訂. GiraPomba的武器風格用於改變裝備動畫,  
  需要在XPMSE MCM中關閉樣式符合的動畫選項.  
  需要RaceMenu或NetImmerse Override Standalone, SkyUI, SKSE, FNIS 的 SKEE.
  - None or other mods : 不使用, 或者使用其他模組.

- **Animation Replacers for First Person (第一人稱動畫替換)**

  - **Axe - Warning! Missing Sounds! Replacer not XPMS(S)E style! (斧頭的裝備風格)**  
    - Axes on Back : 斧頭收起來時, 裝備在背部.

  - **Sword - Warning! Missing Sounds! Replacer not XPMS(S)E style! (劍的裝備風格)**  

    - FSM de Gozaru : 將預設的腰間佩劍第一人稱動畫替換為FSM de Gozaru模組的第一人稱動畫.
    - Swords on Back : 將預設的腰間佩劍第一人稱動畫替換為背上佩劍的第一人稱動畫.
    - None : 不使用

- **Animation Replacers for Mounted Combat (騎乘戰鬥動畫替換)**

  - **Axe - Warning! Missing Sounds! Replacer not XPMS(S)E style! (斧頭的裝備風格)**  
    - Axes on Back : 斧頭收起來時, 裝備在背部.

  - **Sword - Warning! Missing Sounds! Replacer not XPMS(S)E style! (劍的裝備風格)**  
    - FSM de Gozaru : 將預設的腰間佩劍第一人稱動畫替換為FSM de Gozaru模組的第一人稱動畫.
    - Swords on Back : 將預設的腰間佩劍第一人稱動畫替換為背上佩劍的第一人稱動畫.
    - None : 不使用

- **Compatibility Patches (相容性修正)**
  - The Joy of Perspective : 如果有安裝這個模組才啟用, 不然會破壞第一人稱視角的畫面.
  - Schlongs of Skyrim : 如果有安裝這個模組才啟用, 啟用後必須停用該模組的縮放功能, 並改用XPMSE RaceMenu的外掛程式.
  - Deadly Mutilation : 如果有安裝這個模組才啟用,不然會導致生命檢測中的身體部位消失.
  - Deadly Mutilation + The Joy of Perspective : 上述兩種都有安裝時才啟用, 不然會破壞第一人稱視角, 以及生命檢測中的身體部位消失.
  - Enderal + XPMS(S)E MCM : 只有Enderal有安裝時才啟用.
  警告只能在Enderal使用, 不能在Skyrim使用.
  - Enderal + RaceMenu + XPMS(S)E MCM : 只有Enderal有安裝時才啟用,並改用XPMSE RaceMenu的外掛程式在遊戲中進行自訂.
  警告只能在Enderal使用, 不能在Skyrim使用.

</details>

<details>
<summary><h2>HDT-SMP的安裝過程選項</h2></summary>

### **Skyrim version (上古卷軸天際線版本)**  

- VR : 使用Skyrim VR版本才選這個.
- 1.5.97 :
- 1.6.353 - Unsupported :
- 1.6.640 :
- 1.6.659 - Unsupported :
- 1.6.1130 - Unsupported :
- 1.6.1170 : 在Steam購買的版本會是這一個.
- 1.6.1179 : 在GOG購買的版本會是這一個.
- Not yet supported : FSMP不支援你目前的 Skyrim 版本.

### **CUDA or not (使用CUDA加速運算, 或不使用)**  

- CUDA : 使用NVidia API的通用處理來加速GPU的運算.
如果你希望使用CUDA GPU加速, 就必須在 configs.xml 檔案裡啟用CUDA. 但目前CUDA GPU加速功能還沒能夠做到最佳化.
根據部分使用者回饋反應, FSMP的CUDA版本與NVidia的Linux驅動程式不相容, 如果你使用Linux的運作環境, 建議使用Not CUDA版本.
- NOT CUDA (recommended) : 不使用CUDA (建議)

### **AVX (Advanced Vector Extensions 進階向量擴充指令集)**  

建議你拿CPU型號去問ChatGPT, 它會告訴你是否有支援你想搭配的指令集.

- No AVX : 不使用AVX指令集, 如果你的CPU不支援AVX指令集, 請選擇此項.
- AVX (recommended) : 使用AVX指令集 (建議), 可以改善運算性能.
- AVX2 : 使用AVX2指令集, 可以使用更好的效能.
- AVX512 : 使用AVX-512指令集 (不支援Intel的CPU), 可以帶來更好的效能.

### **Configuration (配置)**  

- Install FSMPM - The FSMP MCM (recommended) : 在MCM裡增加可調整FSMP的環境配置選單(建議)
- No MCM - Extreme performance (recommended) : 不使用MCM調整, 使用configs.xml檔案進行最佳化物理模擬.
  - 如果FPS在60以下時, 物理速度會變慢.
  - 最大風距為2000.
  - 每幀給FSMP最多分配3毫秒.
  - 同時計算最多5個骨架.
  - 使用真實時間,而非世界時間.
  - 在同時擁有SMP頭髮和SMP假髮時, 只有假髮會進行物理計算.
- No MCM - Reasonable configuration : 不使用MCM調整, 使用合適的configs.xml檔案平衡性能和品質.
  - 如果FPS在30以下時, 物理速度會變慢.
  - 最大風距為3000.
  - 每幀給FSMP最多分配5毫秒.
  - 同時計算最多10個骨架.
  - 使用真實時間,而非世界時間.
  - 在同時擁有SMP頭髮和SMP假髮時, 只有假髮會進行物理計算.
- No MCM - Maximum compatibility : 不使用MCM調整, 使用最大相容性的configs.xml檔案進行最佳化.
  - 如果FPS在20以下時, 物理速度會變慢.
  - 最大風距為4000.
  - 每幀給FSMP最多分配5毫秒.
  - 同時計算最多20個骨架.
  - 使用真實時間,而非世界時間.
  - 在同時擁有SMP頭髮和SMP假髮時, 兩者都會進行物理計算.
- No MCM - Extreme quality : 不使用MCM調整, 針對物理模擬品質使用configs.xml檔案最佳化.如果你的顯示卡非常的不夠力才需要使用這個選項.
  - 如果FPS在30以下時, 物理速度會變慢.(物理計算頻率為原來的兩倍)
  - 最大風距為4000.
  - 每幀給FSMP最多分配10毫秒.
  - 同時計算最多60個骨架.
  - 使用真實時間,而非世界時間.
  - 在同時擁有SMP頭髮和SMP假髮時, 兩者都會進行物理計算.

### **User guide and validator (使用者指南和驗證器)**  

- **FSMPU - The FSMP User guide (FSMP的使用者指南)**  

  - FSMPU - The FSMP User Guide.pdf : FSMP的使用說明.
  該說明檔放在 data\FSMPU 的目錄下.

- **FSMPV - The FSMP Validator (FSMP的驗證器)**  

  - hdtSMP64.xsd : FSMP的驗證器檔案.
    - 該檔案放在 data\SKSE\Plugins\hdtSkinnedMeshConfigs 的目錄下.
    - 當你在編寫HDT-SMP XML主體和服裝實體文件時, 可以用來檢查它們的有效性.
    - 它不適用 configs.xml 檔案.
    - 如果你在使用FSMP時遇到特定模組的物理問題時, 第一步驟就是檢查XML物理文件的有效性.
    - 該驗證器的功能:
      - Faster HDT-SMP 支援所有標籤和屬性.
      - 檢查是否使用正確的標籤和屬性, 以及正確的文字拼寫.
      - 檢查是否使用正確的資料類型.
      - 檢查是否提供了強制標籤和屬性.
      - 檢查名稱是否唯一性.
      - 檢查模板和擴充功能是否引用聲明的名稱.
      - 提供大量標籤和屬性的文件檔.

### **該模組作者最後推薦幾個模組, 可以視個人需求去安裝**  

| 模組名稱 | 說明 |
| --- | --- |
| CC Bone Colossus Skeleton Fix | 修正長久以來的巨像骨頭骨架的漏洞. |
| Clean up the physics outfit - Collision reset | 清理實體的物理服裝, 重置碰撞設定. |
| Dynamic HDT - Papyrus Script Extension for Faster HDT-SMP | 動態HDT-Papyrus腳本的擴展, 用於更快的HDT-SMP, 能夠在遊戲運行時透過Papyrus更改物理配置. |
| HDT-SMP Force Fields | 實現HDT-SMP力場, 允許咒語和特效能與HDT-SMP互動, 例如火球不僅可以將起司塊炸飛, 並且還會弄亂你的頭髮這種效果. |
| SMP Wind | 風吹的另一種實現方式. |

</details>

<details>
<summary><h2>3BA的安裝過程選項</h2></summary>

### **CBBE 3BBB Advanced Main (安裝主要進階檔案)**  

- **CBBE 3BA Base (基本安裝)**  
  - Base install : 基本安裝
  - Nevernude : 安裝裸體的BodySlide文件, 不包括預先建立的裸體身體網格.
  - Underwear : 安裝內衣的BodySlide文件, 不包括預先建立的內衣身體網格.
  - Pre-built Body mesh : 安裝帶有預設曲線的裸體網格.
  - ECE Slider compatible : 相容ECE(Enhanced Character Edit)裡的3BBB乳房.

- **CBBE 3BA ygNord (將人類舌頭轉為SSE格式的模組)**  
  - Base install : 專為ygNord模組的基本安裝
  - Pre-built Body mesh : 安裝帶有預設曲線的裸體網格.

- **CBBE 3BA Unique Character (創造自己的獨特角色)**  
  - Base install : 基本安裝
  - Pre-built Body mesh : 安裝帶有預設曲線的裸體網格.

### **Base CBPC (基本的)**  

- **Physics Type Select (物理類型選擇)**
  - Base CBPC : 安裝基本的CBPC.
  不使用SMP的情況下, 通常可以在CBPC上運行.
  必須使用咒語或熱鍵才能使用SMP.

- **CBPC ini file (CBPC設定檔)**
  - Not install : 不安裝, 只使用現有的CBPC ini, 而不使用經過特別調整的CBPC ini.
  - Performance (improved) : 改進的性能.
  在不可見的地方停用NPC的物理特性, 這會給你更多的FPS.
  - Performance (Balanced) : 平衡的性能.
  在可見但難以察覺的地方停用NPC的物理特性, 這會給你更多的FPS.
  - Performance (Limited) : 最低需求的性能.
  在可見的地方停用NPC的物理特性, 但物理作用在玩家周圍仍然有效, 如果你不想損失任何FPS, 請使用這個選項.

### **Physics Selecting (物理選擇)**  

- **Physics Select (物理選擇)**  
  - SMP and CBPC (Lite) : 精簡版
    SMP : 乳房.
    CBPC : 腹部, 陰道口, 臀部, 腿部.
    要使用選定的SMP物理效果, 必須在遊戲中使咒語或熱鍵切換.
  - SMP and CBPC (Lite2) : 精簡強化版
    SMP : 陰道口.
    CBPC : 乳房, 腹部, 臀部, 腿部.
    要使用選定的SMP物理效果, 必須在遊戲中使咒語或熱鍵切換.
  - SMP and CBPC (Heavy) : 濃厚版
    SMP : 乳房, 陰道口, 臀部, 腿部.
    CBPC : 腹部.
    要使用選定的SMP物理效果, 必須在遊戲中使咒語或熱鍵切換.
  - SMP and CBPC (Heavy2) : 濃厚強化版
    SMP : 乳房, 臀部, 腿部, 腹部.
    CBPC : 陰道口.
    要使用選定的SMP物理效果, 必須在遊戲中使咒語或熱鍵切換.
  - Full SMP : 全部的SMP
    SMP : 乳房, 臀部, 腿部, 陰道口, 腹部.
    CBPC : 無.
    要使用選定的SMP物理效果, 必須在遊戲中使咒語或熱鍵切換.
  - Only CBPC : 只有CBPC
    SMP : X.
    CBPC : 腹部, 陰道口, 臀部, 腿部, 乳房.
    不增加SMP切換(咒語和熱鍵)和MCM.

### **(CBPC) Boobs Physics Preset (胸部物理預設值)**  

- **Boobs Physics Preset (CBBE 3BBB) (胸部實體預設值)**
  - Very Softness : 非常極度柔軟的搖晃.
  - Elasticity : 有彈性並且有一些柔軟的搖晃.
  - Realistic : 推薦給大胸部使用, 現實中對大胸部來說, 重力和重量都很強. 即使你選擇不添加重力選項, 重力只會減弱, 但不會完全消失.
- **Boobs Physics strength (High) (胸部物理強度, 最高值)**
  - A cup (A bit or no jiggle) : A罩杯, 高重量時會輕微搖晃, 或沒有搖晃.
  - B cup (Small jiggle) : B罩杯, 高重量下會輕微搖晃.
  - C cup (Medium jiggle) : C罩杯, 高重量下會中等幅度的搖晃.
  - D cup (Big jiggle) : D罩杯, 高重量下會大搖晃.
- **Boobs Physics strength (Low) (胸部物理強度, 最低值)**
  - A cup (A bit or no jiggle) : A罩杯, 低重量時會輕微搖晃, 或沒有搖晃.
  - B cup (Small jiggle) : B罩杯, 低重量下會輕微搖晃.
  - C cup (Medium jiggle) : C罩杯, 低重量下會中等幅度的搖晃.
  - D cup (Big jiggle) : D罩杯, 低重量下會大搖晃.
- **Boobs Collision Select (胸部碰撞選擇)**
  - Small : 乳房的碰撞箱設定為小尺寸.
  - Medium : 乳房的碰撞箱設定為中等尺寸.
  - Big : 乳房的碰撞箱設定為大尺寸.
  - (Low)Small~(High)Big : 乳房的碰撞箱依權重為基準, 低權重時為小尺寸, 高權重時為大尺寸.
  除非乳房的大小隨體重而有很大的差異, 否則請選擇大, 中, 小的尺寸.
  - (Low)Big~(High)Small : 乳房的碰撞箱依權重為基準, 低權重時為大尺寸, 高權重時為小尺寸.
  除非乳房的大小隨體重而有很大的差異, 否則請選擇大, 中, 小的尺寸.
- **Boobs Gravity (胸部的重力)**
  - Add Gravity : 乳房增加重力.
  - Don't add Gravity : 不增加乳房重力.
- **Boobs More Gravity (胸部更多的重力)**
  - Add more Gravity effect : 彎腰或躺下時增加重力效果.
  - Don't add more Gravity effect : 不增加重力效果.
- **Boobs Push-Up (胸部上提)**
  - Add auto Push-Up : 穿著服裝和盔甲時增加乳房推高效果.
  - Don't add auto Push-Up : 不添加乳房推高效果.

### **(CBPC-NewType) Belly, Butt, Leg Physics Preset (腹部, 臀部, 腿部物理預設值)**  

- **Belly Physics Preset (腹部物理預設值)**
  - Very Soft (Big jiggle) : 非常柔軟, 像脂肪一樣, 而且搖晃很大.
  - Very Soft (Small jiggle) : 非常柔軟, 像脂肪一樣, 輕微搖晃.
  - Elastic (Big jiggle) : 彈性大, 而且抖動大.
  - Elastic (Small jiggle) : 有彈性, 而且輕微晃動.
- **Butt Physics Preset (臀部物理預設值)**
  - Very Soft (Big jiggle) : 非常柔軟, 像脂肪一樣, 而且搖晃很大.
  - Very Soft (Small jiggle) : 非常柔軟, 像脂肪一樣, 輕微搖晃.
  - Elastic (Big jiggle) : 彈性大, 而且抖動大.
  - Elastic (Small jiggle) : 有彈性, 而且輕微晃動.
- **Leg Physics Preset (腿部物理預設值)**
  - Very Soft (Big jiggle) : 非常柔軟, 像脂肪一樣, 而且搖晃很大.
  - Very Soft (Small jiggle) : 非常柔軟, 像脂肪一樣, 輕微搖晃.
  - Elastic (Big jiggle) : 彈性大, 而且抖動大.
  - Elastic (Small jiggle) : 有彈性, 而且輕微晃動.

### **(SMP) Player Physics Preset (玩家物理預設值)**  

- **Boobs Physics Preset (胸部物理預設值)**
  - Option 1 : 平穩搖晃, 乳房幾乎不會下垂, 所以衣服和身材不會受到影響.
  - Option 2 : 彈性搖晃, 乳房有些下垂, 只有乳房上下跳動時才不會那麼下垂.
  - Realistic : 逼真的大乳房抖動, 配置乳房下垂度較大, 模擬重力的真實感, 因此抖動的幅度也不會那麼明顯.
- **Boobs Physics Strength (胸部物理強度預設值)**
  - Big jiggle (D cup) : 搖晃幅度大, 而且柔軟, 推薦給大胸部使用.
  - Medium jiggle (C cup) : 適度的搖晃和柔軟度, 推薦給中等胸部使用.
  - Small jiggle (B cup) : 輕微的搖晃和柔軟度, 推薦給小胸部使用.
  - A bit or no jiggle (A cup) : 有一點晃動, 或沒有晃動, 推薦給扁平胸部使用.

### **(CBPC) Extra Physics (額外物理作用)**  

- **SOS Physics (Schlongs of Skyrim SE模組的物理)**
  - CBPC - RegularSOS : 增加陰莖和陰囊的彈性, 陰莖通常呈現鬆軟狀態, 但在性交過程中會變硬, 這與SexLab和Osex模組相容.
  - CBPC - FloppySOS : 增加陰莖和陰囊的彈性, 即使勃起, 陰莖也是鬆弛狀態.
  - No SOS : 不要添加陰莖和陰囊的搖晃.
- **Change vagina collision (改變陰道口碰撞)**
  - Don't change : 不改變陰道口碰撞, 利用骨盆碰撞穩定打開陰道.
  - Change : CBPC的陰道口碰撞變成直接碰撞, 無需骨盆碰撞, 請注意, 如果你不知道這個選項的意思, 不要選擇它!
- **Add anal collision (增加肛門碰撞)**
  - Don't add anal collision : 按照動畫打開肛門, 無需使用肛門碰撞, 相容性較佳.
  - Add anal collision : 使用肛門CBPC物理碰撞, 而不是用動畫來打開肛門.
    安裝XPMSSE時, 請確保使用4.51 rig檔案的選項.

### **Extra Textures (額外紋理)**  

- **Vagina Textures (陰道口紋理)**
  - Pink - 1K : 粉紅色, 使用粉紅色的陰道口紋理, 平衡眾多類型以匹配大多數的顏色.
  - Pink - 2K : 粉紅色
  - Pink - 4K : 粉紅色
  - Pale Pink - 1K : 淡粉紅色, 使用淡粉紅色的陰道口紋理
  - Pale Pink - 2K : 淡粉紅色
  - Pale Pink - 4K : 淡粉紅色
  - Dark Red - 1K : 暗紅色, 使用暗紅色的陰道口紋理
  - Dark Red - 2K : 暗紅色
  - Dark Red - 4K : 暗紅色
  - Deep Pink - 1K : 深粉紅色, 使用深粉紅色的陰道口紋理
  - Deep Pink - 2K : 深粉紅色
  - Deep Pink - 4K : 深粉紅色
  - Deep Red - 1K : 深紅色, 使用深紅色的陰道口紋理
  - Deep Red - 2K : 深紅色
  - Deep Red - 4K : 深紅色
  - Pale - 1K : 淡膚色, 使用淡膚色的陰道口紋理
  - Pale - 2K : 淡膚色
  - Pale - 4K : 淡膚色
-**Vagina - SSS (陰道口貼圖Bug的修正)**
  - SSS Black : 修正青銅色光澤的錯誤, 將身體鏡面反射貼圖紋理替換為黑色貼圖.
  當你有遇到角色身體有"青銅色光澤"這種情況時才需要這個選項.

### **Extra Patches (額外修正)**  

- **Compatible Patch (相容性修正)**
  - FlowerGirls : 修正與FlowerGirls模組一起使用時, 身體的SMP有時會移除的問題.
  如果你沒有使用FlowerGirls模組, 請勿選取.
  - VRIK : 與VRIK模組的相容性修正.
  如果你沒有使用VRIK模組, 請勿選取.
- **Racemenu (Racemenu模組)**
  - None : 不安裝與Racemenu模組的相容性修正.
  - CBBE 3BA v1.6.x Morph Sliders : 為Racemenu模組增加CBBE 3BA的變形滑桿.
  - Add 3BBB Morph Slider : 建立新的CBBE 3BA的變形滑桿.
  如果你在之前版本有用過這個選項, 才選用, 不然它會自動停用.

</details>

<details>
<summary><h2>操作BodySlide軟體變換自訂的身形</h2></summary>

1. 開啟Steam, 先登入.
2. 開啟MO2, 點擊選單「工具」→「可執行檔」.
3. 設定一個新的執行項目, 點擊➕圖示「增加一個可執行檔」.
名稱 : 隨便自己定義, 例如 BodySlide x64.
執行檔位置 : 看你的MO2安裝BodySlide時的安裝位置來決定, 例如
MO2Game\Skyrim Special Edition\mods\BodySlide and Outfit Studio\CalienteTools\BodySlide\BodySlide x64.exe
4. 完成後, 執行 BodySlide x64, 它會另外開啟一個編輯視窗.
5. 在從未執行過BodySlide時, 它會先出現一個設定視窗, 你必須先設定好, 日後再開啟時它就不會再顯示了.  
    因為我玩的是Skyrim, 所以在那個視窗裡確認Skyrim的Data路徑是否正確, 例如

    | 遊戲名稱 | 資料夾路徑 |
    | --- | --- |
    | Skyrim Special Edition | C:\Steam\steamapps\common\Skyrim Special Edition\Data |

    確認路徑無誤後, 點擊「Choose Game」, 它會開啟一個編輯視窗出來<br>
    ![Snapshot](/BodySlide_editor.jpg "BodySlide的編輯畫面")
6. 在 Outfit/Body 欄位選擇你想轉換的目標類型

    - 如果你只想轉換玩家的角色外觀, 就選擇 CBBE 3BBB Amazing SMP Object - Player
    - 如果你只想轉換所有女性NPC的角色外觀, 直接選擇 CBBE 3BBB Body Amazing

7. 在 Preset 欄位選擇你想套用的身形, 前面我安裝的自訂身形模組是 Curvy Queen - CBBE 3BA Bodyslide Preset, 所以要找到 Curvy Queen 這一項.
你也可以先指定 Curvy Queen 這一項, 然後在下面的各部位調整滑桿, 調出你想要的身形, 然後另存新檔(例如MyBigBreasts), 然後重新點擊Preset欄位, 選擇你自訂的MyBigBreasts身形.
8. 接著在編輯畫面的下面有一個 「Build Morphs」選項, 將它打勾.
9. 因為我想轉換的是每一個NPC,所以接著點擊「Batch Build」按鈕.
如果你只想轉換玩家自己(Player), 就只需要點擊「Build」按鈕即可.
10. 因為Batch Build是進行批次轉換, 所以它會開啟另一個新視窗(Batch Build)出來.
它預設會將列出的物件清單都打勾, 這些被列出來的清單也就是你想要把 Curvy Queen 身形套用進來的目標 ,你也可以選擇不想要套用變形的物件, 例如我不想要玩家自己的身形被套用, 就將 CBBE 3BBB Amazing SMP Object - Player 的打勾取消.
全部確認沒有問題了, 再點擊「Build」按鈕.
11. 接著會出現另一個視窗(Choose output set), 這個視窗會列出剛才所有打勾的物件清單的身形設定, 你可以指定該項目是否要使用物理的身形, 例如手的部位有 CBBE Hands 和 CBBE 3BBB Hands 可以選擇, 腳有 CBBE Feet 和 CBBE 3BBB Feet 可以選擇, 都確定選擇你想要的項目後, 再點擊「OK」就會出現開始轉換的處理視窗.
12. 最後都處理完成時, 會出現 Complete 視窗, 寫著 All sets processed successfully! 就代表轉換成功, 結束!

</details>
