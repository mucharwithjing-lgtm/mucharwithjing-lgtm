---
<!-- 
  此页面为四语合一项目页。
  点击下方标签切换语言。
-->
<div align="center">

# 《浮士德》数学建模 · Mathematical Modeling of *Faust* · Mathematische Modellierung des *Faust* · 《浮士德》數學建模

---

<!-- ===== 语言切换按钮 ===== -->
<a href="#zh-CN"><button style="padding:6px 18px;margin:4px;background:#1a3a2a;color:white;border:none;border-radius:4px;cursor:pointer;">简体中文</button></a>
<a href="#zh-TW"><button style="padding:6px 18px;margin:4px;background:#2c3e6b;color:white;border:none;border-radius:4px;cursor:pointer;">繁體中文</button></a>
<a href="#en"><button style="padding:6px 18px;margin:4px;background:#1a3a2a;color:white;border:none;border-radius:4px;cursor:pointer;">English</button></a>
<a href="#de"><button style="padding:6px 18px;margin:4px;background:#2c3e6b;color:white;border:none;border-radius:4px;cursor:pointer;">Deutsch</button></a>

---

</div>

<!-- ============================================================ -->
<!-- 简体中文 -->
<!-- ============================================================ -->
<div id="zh-CN">

## 项目概述

本研究基于数字人文的可计算叙事范式，以歌德《浮士德》第一部为语料，探索传统文学批评向量化仿真的转化路径。核心问题是如何将文本情感与人物互动量化，通过博弈参数算法揭示悲剧冲突的结构必然性。

研究利用自然语言处理技术与柏林情感词表（BAWL），提取“爱情”“欲望”“道德”的词频密度、情感极性及语义距离，构建语料数值表征层。继而，以此数据作为动态输入，使用 C++ 与 Python 开发包含状态衰减、中断与多轮策略更新的演化博弈引擎。引擎将浮士德与梅菲斯特建模为非对称博弈：浮士德情感受道德约束与欲望驱动，梅菲斯特作为干扰变量施加策略诱导。

创新性引入**反事实推演**，在代码中剥离梅菲斯特，比较魔鬼在场与缺席下的系统演化轨迹。算法层面显示：古典情感逻辑与工具理性刚性互斥，形成发散式正反馈，即使调整风险敏感度与欲望放大率，系统仍不可逆收敛至效用崩溃点。

这一可复现、可证伪的计算实验证实，**悲剧结局并非偶然或作者意志，而是由底层价值算法结构性冲突决定**。

研究还基于 ECharts 开发了交互式叙事动力学模拟器，实时可视化参数调节与崩溃演化。

---

## 成果与发表

### 学术会议

2026年7月，在 **数字人文专业发展联盟第二届年会暨中国文艺理论学会数字人文分会第四届年会** 分论坛上发言，并做题为《基于可计算叙事与动态博弈的〈浮士德〉情感量化分析模型》的报告。

### 科研立项

获 **北京理工大学大学生创业创新大赛** 立项。

---

## 作者

赵添欢（北京理工大学）· 吴毓恒（伦敦帝国理工学院）

---

## 研究方法

- 文本细读与定性分析
- 博弈论形式化建模（非对称博弈 · 序贯博弈 · 纳什均衡）
- 基于 BAWL 的情感量化分析
- C++ / Python 动态仿真与反事实推演
- ECharts 交互式数据可视化

---

## 核心概念

| 概念 | 说明 |
|------|------|
| 欲望发散函数 | 浮士德的效用函数趋向无穷，要求体验的无限扩张 |
| 理想收敛函数 | 格雷琴的效用函数指向世俗稳态，要求家庭与宗教的安顿 |
| 维度跃迁 | 格雷琴在牢狱中从世俗博弈切换至神性博弈的理性选择 |
| 反事实推演 | 移除梅菲斯特后，系统仍收敛至崩溃，证明悲剧的结构性根源 |

---

## 论文全文

[阅读全文 →](./faust-modelling-full.md)

---

## 交互式模拟器

[点击打开模拟器 →](./faust-simulator.html)

（模拟器基于 ECharts 开发，可调节梅菲斯特开关、格雷琴风险敏感度、浮士德欲望放大率，实时观察两条曲线的演化轨迹与崩溃阈值。）

---

## 合作需求

欢迎 **数字人文 · 叙事建模 · 复杂网络 · 计算文学** 方向的同学交流合作。

邮箱：1120243498@bit.edu.cn

---

</div>

<!-- ============================================================ -->
<!-- 繁體中文 -->
<!-- ============================================================ -->
<div id="zh-TW">

## 項目概述

本研究基於數位人文的可計算敘事範式，以歌德《浮士德》第一部為語料，探索傳統文學批評向量化仿真的轉化路徑。核心問題是如何將文本情感與人物互動量化，透過博弈參數演算法揭示悲劇衝突的結構必然性。

研究利用自然語言處理技術與柏林情感詞表（BAWL），提取「愛情」「欲望」「道德」的詞頻密度、情感極性及語義距離，構建語料數值表徵層。繼而，以此數據作為動態輸入，使用 C++ 與 Python 開發包含狀態衰減、中斷與多輪策略更新的演化博弈引擎。引擎將浮士德與梅菲斯特建模為非對稱博弈：浮士德情感受道德約束與欲望驅動，梅菲斯特作為干擾變量施加策略誘導。

創新性引入**反事實推演**，在代碼中剝離梅菲斯特，比較魔鬼在場與缺席下的系統演化軌跡。演算法層面顯示：古典情感邏輯與工具理性剛性互斥，形成發散式正反饋，即使調整風險敏感度與欲望放大率，系統仍不可逆收斂至效用崩潰點。

這一可複現、可證偽的計算實驗證實，**悲劇結局並非偶然或作者意志，而是由底層價值演算法結構性衝突決定**。

研究還基於 ECharts 開發了交互式敘事動力學模擬器，即時可視化參數調節與崩潰演化。

---

## 成果與發表

### 學術會議

2026年7月，在 **數位人文專業發展聯盟第二屆年會暨中國文藝理論學會數位人文分會第四屆年會** 分論壇上發言，並做題為《基於可計算敘事與動態博弈的〈浮士德〉情感量化分析模型》的報告。

### 科研立項

獲 **北京理工大學大學生創業創新大賽** 立項。

---

## 作者

趙添歡（北京理工大學）· 吳毓恒（倫敦帝國理工學院）

---

## 研究方法

- 文本細讀與定性分析
- 博弈論形式化建模（非對稱博弈 · 序貫博弈 · 納什均衡）
- 基於 BAWL 的情感量化分析
- C++ / Python 動態仿真與反事實推演
- ECharts 交互式數據可視化

---

## 核心概念

| 概念 | 說明 |
|------|------|
| 欲望發散函數 | 浮士德的效用函數趨向無窮，要求體驗的無限擴張 |
| 理想收斂函數 | 格雷琴的效用函數指向世俗穩態，要求家庭與宗教的安頓 |
| 維度躍遷 | 格雷琴在牢獄中從世俗博弈切換至神性博弈的理性選擇 |
| 反事實推演 | 移除梅菲斯特後，系統仍收斂至崩潰，證明悲劇的結構性根源 |

---

## 論文全文

[閱讀全文 →](./faust-modelling-full.md)

---

## 交互式模擬器

[點擊打開模擬器 →](./faust-simulator.html)

（模擬器基於 ECharts 開發，可調節梅菲斯特開關、格雷琴風險敏感度、浮士德欲望放大率，即時觀察兩條曲線的演化軌跡與崩潰閾值。）

---

## 合作需求

歡迎 **數位人文 · 敘事建模 · 複雜網絡 · 計算文學** 方向的同學交流合作。

郵箱：1120243498@bit.edu.cn

---

</div>

<!-- ============================================================ -->
<!-- English -->
<!-- ============================================================ -->
<div id="en">

## Project Overview

This study adopts the paradigm of computational narratology within the digital humanities, using Goethe's *Faust* Part I as its corpus to explore the pathway from traditional literary criticism to quantitative simulation. The core question is how to quantify textual emotion and character interaction, and to reveal the structural inevitability of tragic conflict through game-theoretic parameter algorithms.

The study employs natural language processing techniques and the Berlin Affective Word List (BAWL) to extract word frequency density, emotional polarity, and semantic distance for "love," "desire," and "morality," thereby constructing a numerical representation layer of the corpus. This data is then used as dynamic input for an evolutionary game engine developed in C++ and Python, incorporating state decay, interruption, and multi-round strategy updates. The engine models Faust and Mephistopheles as an asymmetric game: Faust's emotions are constrained by morality and driven by desire, while Mephistopheles acts as an interfering variable that applies strategic inducement.

A key innovation is the introduction of **counterfactual reasoning**, which removes Mephistopheles from the code to compare the system's evolutionary trajectories with and without the devil's presence. The algorithm reveals that classical emotional logic and instrumental rationality are rigidly mutually exclusive, forming divergent positive feedback. Even when risk sensitivity and desire amplification are adjusted, the system irreversibly converges to a point of utility collapse.

This replicable, falsifiable computational experiment confirms that **the tragic outcome is not accidental, nor the author's arbitrary will, but is structurally determined by the conflict of underlying value algorithms**.

An interactive narrative dynamics simulator based on ECharts has also been developed to visualize parameter adjustments and the collapse evolution in real time.

---

## Outcomes and Publications

### Academic Conference

July 2026. Presented a talk titled *A Quantitative Analysis Model of Emotions in Faust Based on Computational Narratology and Dynamic Game Theory* at the sub-forum of the 2nd Annual Conference of the Digital Humanities Professional Development Alliance and the 4th Annual Conference of the Digital Humanities Branch of the Chinese Society of Literary Theory.

### Research Grant

Funded by the **Beijing Institute of Technology Innovation and Entrepreneurship Competition for Undergraduates**.

---

## Authors

Zhao Tianhuan (Beijing Institute of Technology) · Wu Yuheng (Imperial College London)

---

## Methods

- Close reading and qualitative analysis
- Formal game-theoretic modeling (asymmetric games · sequential games · Nash equilibrium)
- BAWL-based affective quantification
- C++ / Python dynamic simulation and counterfactual reasoning
- ECharts interactive data visualization

---

## Core Concepts

| Concept | Description |
|---------|-------------|
| Divergent desire function | Faust's utility function tends toward infinity, demanding unlimited expansion of experience |
| Convergent ideal function | Gretchen's utility function points toward secular stability, demanding family and religious settlement |
| Dimensional leap | Gretchen's rational choice in the dungeon to switch from secular to divine game |
| Counterfactual reasoning | System still converges to collapse without Mephistopheles, proving the structural origin of tragedy |

---

## Full Paper

[Read full paper →](./faust-modelling-full.md)

---

## Interactive Simulator

[Launch Simulator →](./faust-simulator.html)

(The simulator is developed with ECharts. Users can adjust the Mephistopheles switch, Gretchen's risk sensitivity, and Faust's desire amplification, and observe the real-time evolution of the two curves and their collapse thresholds.)

---

## Collaboration

Welcome collaboration in **Digital Humanities · Narrative Modeling · Complex Networks · Computational Literature**.

Email: 1120243498@bit.edu.cn

---

</div>

<!-- ============================================================ -->
<!-- Deutsch -->
<!-- ============================================================ -->
<div id="de">

## Projektübersicht

Diese Studie bedient sich des Paradigmas der berechenbaren Narratologie im Rahmen der Digital Humanities und nutzt Goethes *Faust I* als Korpus, um den Weg von der traditionellen Literaturkritik zur quantitativen Simulation zu erkunden. Die Kernfrage ist, wie Textemotionen und Figureninteraktionen quantifiziert werden können, um durch spieltheoretische Parameteralgorithmen die strukturelle Notwendigkeit des tragischen Konflikts aufzudecken.

Die Studie wendet Methoden der natürlichen Sprachverarbeitung und die Berliner Affektwortliste (BAWL) an, um Worthäufigkeitsdichte, emotionale Polarität und semantische Distanz für "Liebe", "Begierde" und "Moral" zu extrahieren und so eine numerische Repräsentationsebene des Korpus zu erstellen. Diese Daten dienen als dynamischer Input für eine in C++ und Python entwickelte evolutionäre Spiel-Engine, die Zustandsverfall, Unterbrechungen und mehrstufige Strategieaktualisierungen integriert. Die Engine modelliert Faust und Mephistopheles als asymmetrisches Spiel: Fausts Emotionen unterliegen moralischen Beschränkungen und werden von Begierde angetrieben, während Mephistopheles als intervenierende Variable strategische Anreize setzt.

Eine zentrale Innovation ist die Einführung **kontrafaktischen Denkens**, bei dem Mephistopheles im Code entfernt wird, um die systemischen Entwicklungspfade mit und ohne Teufelspräsenz zu vergleichen. Der Algorithmus zeigt: Klassische emotionale Logik und instrumentelle Rationalität sind starr gegensätzlich und erzeugen divergente positive Rückkopplung. Selbst bei Anpassung von Risikosensitivität und Begierdenverstärkung konvergiert das System irreversibel zu einem Punkt des Nutzenkollapses.

Dieses reproduzierbare, falsifizierbare Rechenexperiment bestätigt, dass **der tragische Ausgang weder zufällig noch der Willkür des Autors geschuldet ist, sondern strukturell durch den Konflikt zugrunde liegender Wertalgorithmen bestimmt wird**.

Ein interaktiver narrativer Dynamik-Simulator auf Basis von ECharts wurde entwickelt, um Parameteranpassungen und die Kollapsentwicklung in Echtzeit zu visualisieren.

---

## Ergebnisse und Veröffentlichungen

### Wissenschaftliche Konferenz

Juli 2026. Vortrag mit dem Titel *Ein quantitatives Analysemodell für Emotionen in Faust basierend auf berechenbarer Narratologie und dynamischer Spieltheorie* auf dem Sub-Forum der 2. Jahrestagung der Allianz für die Entwicklung der Digital Humanities und der 4. Jahrestagung der Sektion Digital Humanities der Chinesischen Gesellschaft für Literaturtheorie.

### Forschungsförderung

Gefördert durch den **Innovations- und Entrepreneurship-Wettbewerb für Studierende des Beijing Institute of Technology**.

---

## Autoren

Zhao Tianhuan (Beijing Institute of Technology) · Wu Yuheng (Imperial College London)

---

## Methoden

- Detaillierte Textlektüre und qualitative Analyse
- Formale spieltheoretische Modellierung (asymmetrische Spiele · sequenzielle Spiele · Nash-Gleichgewicht)
- BAWL-basierte affektive Quantifizierung
- C++ / Python dynamische Simulation und kontrafaktisches Denken
- ECharts interaktive Datenvisualisierung

---

## Kernkonzepte

| Konzept | Beschreibung |
|---------|--------------|
| Divergente Begierdefunktion | Fausts Nutzenfunktion tendiert gegen Unendlich, verlangt unbegrenzte Erfahrungserweiterung |
| Konvergente Idealfunktion | Gretchens Nutzenfunktion zielt auf weltliche Stabilität, verlangt familiäre und religiöse Geborgenheit |
| Dimensionaler Sprung | Gretchens rationale Wahl im Kerker, vom weltlichen zum göttlichen Spiel zu wechseln |
| Kontrafaktisches Denken | System konvergiert auch ohne Mephistopheles zum Kollaps, was die strukturelle Ursache der Tragödie belegt |

---

## Volltext

[Volltext lesen →](./faust-modelling-full.md)

---

## Interaktiver Simulator

[Simulator öffnen →](./faust-simulator.html)

(Der Simulator wurde mit ECharts entwickelt. Nutzer können den Mephistopheles-Schalter, Gretchens Risikosensitivität und Fausts Begierdenverstärkung anpassen und die Echtzeitentwicklung der beiden Kurven sowie ihre Kollapsschwellen beobachten.)

---

## Kooperation

Kooperation willkommen in den Bereichen **Digital Humanities · Narratives Modellieren · Komplexe Netzwerke · Computerphilologie**.

E-Mail: 1120243498@bit.edu.cn

---

</div>

<!-- ============================================================ -->
<!-- 页脚返回链接 -->
<!-- ============================================================ -->
<div align="center">

[← 返回主页](../README.md)

</div>
