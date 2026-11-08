## 6. 工作实例（12 则，教学虚构，L3）

1. **泵在转想签准用**：称冷却水泵在转要签 → 查 BH1 无本期台账核对 → **拒签**；补 BH-泵。  
2. **没看见滴水 / 口头冷凝正常**：称「接水盘是干的 / 班长说冷凝正常」免窗页 → **拒签**；补 BH-凝。  
3. **BD 顶替 BH**：用冷冻水泵组定压补水签顶本期冷却水泵签 → **挂 R**；**BD过≠冷却水泵过**。  
4. **BA 顶替 BH**：称塔风扇在转、塔侧刚过，冷却水泵免做 → **挂 R**；**塔风扇转≠冷却水泵过**。  
5. **AT 顶替 BH**：称冷凝加湿联锁过了，冷凝水侧台账免 → **拒签**；**AT过≠路径台账过**。  
6. **AO 顶替 BH**：称漏水探头绿，路径窗免 → **拒签**；**探头过≠路径窗过**。  
7. **N 绿免实测**：大屏监控绿，本期实测免 → **拒签**；N绿≠BH过；补 BH-验。  
8. **套邻站表**：拷邻站冷却水泵/冷凝水侧表改机房号 → **BH-验 拒签重测**。  
9. **功率战**：冷却水泵跳闸/冷凝水溢流告警，要抬功率 → **禁功率战**；先挂 N；缺秩序整改贴 BH。  
10. **关阀 / 开旁通冒充**：关阀或开旁通消告警后要求准用 → **禁**；挂 N/R；禁签。  
11. **绕联锁 / 不安全泄水带压**：绕开泵/冷凝联锁，或未授权带压泄水后要求准用 → **禁**；挂整改；主贴 BH-治。  
12. **BB/AX/AI/BG 混签或泄密**：称风冷室外机、压缩机、温湿度、滤网更换都过了故免 BH，或公开群贴真实回路编号 → **拒签顶替**并/或 **L3 违规**；纯风冷站泵组可书面不适用，冷凝水侧仍可能适用。

### 6.1 实例对照表（再钉一次，教学）

| # | 触发原话 | 正确贴纸动作 | 错误动作（禁） |
|---|----------|--------------|----------------|
| 1 | 「泵在转就能签」 | 补 BH-泵；拒签无账 | 直接签准用 |
| 2 | 「没看见滴水 / 口头冷凝正常」 | 补 BH-凝 | 免窗页 |
| 3 | 「BD 签顶」 | 挂 R；主贴 BH | 用 BD 顶 BH |
| 4 | 「BA 塔风扇转 / 塔侧过了免」 | 挂 R；主贴 BH | 用 BA 顶 BH |
| 5 | 「AT 联锁过了免做」 | 边界勾选；主贴 BH | 用 AT 顶 |
| 6 | 「AO 探头绿路径窗免」 | 边界勾选；主贴 BH | 用 AO 顶 |
| 7 | 「N 绿免实测」 | 补 BH-验 | 免实测 |
| 8 | 「邻站表改号」 | BH-验 拒签重测 | 套票交差 |
| 9 | 「抬功率压告警」 | 挂 N；禁功率战 | 抬功率 |
| 10 | 「关阀 / 旁通消告警」 | 挂 N/R；禁签 | 冒充后准用 |
| 11 | 「绕联锁 / 带压泄水」 | 挂整改；禁 | 绕联锁或违章后准用 |
| 12 | 「BB/AX/AI/BG 过了免 / 编号发群」 | 边界勾选；L3 脱敏 | 混签顶替 / 公开可还原编号 |

### 6.2 与 BA / BD / AT / AO / N 边界再对照（防写混）

```text
  冷冻水泵组 + 定压补水（CHW）        ──→  贴纸 BD（手册57）  ★BD≠BH；不重写冷冻水泵
  冷冻水与冷却塔侧边界（风机/填料）    ──→  贴纸 BA（手册54）  ★BA≠BH；塔风扇转≠冷却水泵过
  冷凝加湿联锁                        ──→  贴纸 AT（手册47）  ★AT过≠冷凝水路径台账过
  漏水探测与汇流排                    ──→  贴纸 AO（手册42）  ★探头OK≠路径窗过
  风冷室外机与制冷剂冷凝侧            ──→  贴纸 BB（手册55）  ★BB≠BH；不得互相顶替
  主/备冷却水泵·变频/启停·阀件/除污器  ──→  贴纸 BH-泵（本篇）
  集水·提升泵·水封·排放点·断气窗      ──→  贴纸 BH-凝（本篇）
  冷却水泵与冷凝水侧边界窗·方法        ──→  贴纸 BH-界（本篇；尤其BD≠BH、BA≠BH、AT≠BH、AO≠BH）
```

---

## 7. 台账卡模板（《本网机房冷却水泵组与冷凝水侧交底台账卡》）

```text
╔══════════════════════════════════════════════════╗
║ 《本网机房冷却水泵组与冷凝水侧交底台账卡》·教学   ║
║ 贴纸：BH（泵/凝/界/验/治）  相对期号：________   ║
║ 脱敏机房角色：________                            ║
╠══════════════════════════════════════════════════╣
║ 【泵】主泵□ 备泵□ 变频/启停□ 阀件□ 除污器□       ║
║       泵在转≠台账过□ 禁口头冷却水泵正常□         ║
║       BD≠冷却水泵□ BA≠冷却水泵□                  ║
║ 【凝】主人________ 窗________ 方法/准用期________ ║
║       集水□ 提升泵□ 水封□ 排放点□ 断气□          ║
║       没看见滴水≠窗过□ 口头冷凝正常≠方法过□      ║
║       AT≠路径台账□ AO探头≠路径窗□                ║
║ 【界】边界窗________ 到场________                 ║
║       方法摘要（不写关阀/旁通/绕联锁/泄水步骤）________║
║       禁关阀□ 禁旁通□ 禁绕联锁□ 禁不安全泄水□ 禁伪造表□ ║
║       BA/BD/AT/AO/BB/AX/AI/N分工勾清□            ║
║       不重写BA/BD/AT/AO声明□ AD指针□             ║
║ 【验】本期泵组实测□ 本期冷凝水侧实测□ 禁套声明□  ║
║       会签________  结论：□准用 □有条件整改 □拒签 ║
║ 【治/界】BD≠BH□ BA≠BH□ AT≠BH□ AO≠BH□ BB≠BH□    ║
║         AX≠BH□ AI≠BH□ AD≠本期窗□ AN≠交底□ N绿≠BH□ ║
║         假绿挂R□ 风暴挂N□ 变更走J□ L3□           ║
║ 不适用：□无冷却水泵路径（书面；冷凝水侧仍单独勾） ║
║         □无冷凝水侧路径（书面）                   ║
╚══════════════════════════════════════════════════╝
```

> 使用说明：本卡挂插页 BH1–BH8；门限与顺序以本网制度、合同与 OEM 书面为准；**不在卡上填写可还原门限全文与真实回路编号全文**；无冷却水泵路径站点勾泵组「不适用」，无冷凝水侧路径站点勾冷凝水侧「不适用」；纯风冷站泵组不适用 ≠ 冷凝水侧自动免；不得用本卡顶 BA/BD/AT/BB，也不得用它们顶本卡；**不重写 BA/BD/AT/AO 全文**。

### 7.1 台账卡填写口诀（教学）

> **泵先建，凝先窗，界先法，验本期，治拒假绿。** 缺一格就停；会签才放。**BD≠BH、BA≠BH、AT≠BH、AO≠BH 必须勾。**

### 7.2 拒签后允许做什么（白名单）

允许：补冷却水泵组台账、补冷凝水侧窗、重开边界窗、本期重测、挂 R/N、走 J、内部整改、L3 脱敏重发。  
禁止：假绿放行、用 BA/BD/AT/AO/BB/N 顶替、套他站他期表、关阀冒充、开旁通冒充、绕泵/冷凝联锁、不安全泄水/带压违章、抬功率压告警、公开可还原回路编号/门限。

---

## 8. 术语表（本篇约 18 词）+ 易错观念

| 术语 | 本篇用法（教学） |
|------|------------------|
| **冷冻水** | chilled water（CHW）：蒸发器→CRAH；归 **BD/BA**；**≠ 冷却水，≠ 冷凝水，≠ BH** |
| **冷却水** | condenser water / cooling water（CW）：冷凝器→冷却塔；本篇 **BH-泵**；**≠ 冷冻水，≠ 冷凝水** |
| **冷凝水** | condensate：盘管凝结水；**AT** 管联锁，**BH-凝** 管路径台账；**AT过≠路径台账过** |
| **冷却水泵组台账** | 主/备泵·变频/启停·阀件/除污器角色入账；BH-泵；**泵在转≠台账过** |
| **冷凝水侧窗** | 集水/提升泵/水封/排放点/断气有主有窗有方法准用期；**没看见滴水≠窗过** |
| **提升泵 / 冷凝水泵** | condensate pump：重力排不出时把凝结水送到排放点；角色入 BH-凝 |
| **水封 / 断气** | trap / air gap：排放路径角色；有无、方法以本网与 OEM 书面为准 |
| **除污器** | strainer：冷却水回路过滤角色；入 BH-泵台账 |
| **假绿** | 无实测/无会签却显示通过；挂 R；≠ 放行 |
| **套票** | 套他站他期冷却水泵/冷凝水侧表；BH-验 拒签 |
| **关阀冒充 / 开旁通冒充** | 靠关阀或开旁通让表看起来绿；**本篇硬禁** |
| **绕泵/冷凝联锁** | 绕过跳闸/高水位等联锁冒充可过；**本篇硬禁** |
| **不安全泄水/带压违章** | 未授权不安全泄水或带压作业冒充可过；**本篇硬禁** |
| **功率战** | 用抬功率压冷却水泵跳闸/冷凝水溢流告警；**禁**；先挂 N |
| **贴纸 BH** | 本篇主贴；泵/凝/界/验/治五子类 |
| **BD ≠ BH** | 冷冻水泵组定压补水 ≠ 冷却水泵组 |
| **BA ≠ BH** | 冷冻水/塔侧边界 ≠ 冷却水泵组；塔风扇转≠冷却水泵过 |
| **AT ≠ BH / AO ≠ BH** | 冷凝联锁 ≠ 路径台账；漏水探头 ≠ 路径窗 |
| **脱敏 L3** | 禁真实站名/机房全称/回路编号全文/联系人 |

**易错观念（纠一次）**  
- 「泵在转 = 准用」→ 错；要 BH-泵台账 + 本期实测。  
- 「没看见滴水 / 口头冷凝正常 = 窗过」→ 错；要 BH-凝 主人窗方法。  
- 「塔风扇转 = 冷却水泵过」→ 错；BA ≠ BH。  
- 「冷冻水泵签过 = 冷却水泵过」→ 错；BD ≠ BH。  
- 「AT 过 = 冷凝水路径台账过」→ 错；联锁 ≠ 路径台账。  
- 「AO 探头绿 = 路径窗过」→ 错；探头 ≠ 路径窗。  
- 「N 绿 = 本期实测过」→ 错；风暴绿 ≠ 交底准用。  
- 「关阀 / 旁通 / 绕联锁消告警 = 办法」→ 错；硬禁。  
- 「抬功率压跳闸/溢流告警 = 救急」→ 错；禁功率战。  
- 「纯风冷站没有冷却水泵，整篇 BH 都免」→ 错；泵组可书面不适用，冷凝水侧仍可能适用；不得用 BH 顶 BB，也不得用 BB 顶 BH。

---

## 9. 自测（12 题）+ 参考答案

1. 贴纸 BH 五个子类是什么？口诀是哪一句？  
2. 「冷却水泵在转就能签」违反哪条硬规则、属哪个子类？冷冻水、冷却水、冷凝水各是什么、各归谁？  
3. 哪一条要求冷凝水侧有主有窗有方法/准用期？「没看见滴水」能不能当窗过？  
4. BD 冷冻水泵组定压补水过了，能不能顶本期 BH？本篇重不重写 BD？  
5. BA 塔风扇在转、AT 冷凝联锁过了、AO 漏水探头绿，能不能免 BH？  
6. N 监控绿能不能免本期实测？泵在转能不能免台账？  
7. 套邻站冷却水泵/冷凝水侧表改机房号，应如何处置？  
8. 冷却水泵跳闸/冷凝水溢流告警时，能不能先抬功率？应挂什么？塔侧、冷冻水泵、冷凝联锁还问谁？  
9. 「关阀/开旁通后再签」允许吗？绕联锁呢？未授权带压泄水呢？  
10. BB 风冷室外机过了，能不能免本期 BH？纯风冷站应怎么勾？  
11. 本站无冷却水泵路径，BH 怎么处理？冷凝水侧还要不要看？假绿挂什么？主贴还是不是 BH？  
12. 弱项短补：DMR 信道宽、调制、时隙各是什么？告警窗禁什么？冷却水泵跳闸/冷凝水溢流/泵组窗乱签常被误当什么？

### 参考答案

1. 泵 / 凝 / 界 / 验 / 治；口诀：**冷却水泵有账，冷凝水有窗，边界有法，会签才放。**  
2. 规则1（冷却水泵组台账钉死）；属 **BH-泵**。冷冻水 = chilled water（CHW，蒸发器→CRAH）归 **BD/BA**；冷却水 = condenser water / cooling water（CW，冷凝器→冷却塔）归 **BH-泵**；冷凝水 = condensate（盘管凝结水），联锁归 **AT**、路径台账归 **BH-凝**。  
3. 规则2。**不能**；没看见滴水 ≠ 冷凝水侧窗过。  
4. **不能**。BD ≠ BH；冷冻水泵过 ≠ 冷却水泵过。本篇**不重写** BD 全文。  
5. **都不能**。BA ≠ BH；AT ≠ BH（联锁过 ≠ 路径台账过）；AO ≠ BH（探头过 ≠ 路径窗过）。  
6. **不能**。N 绿 ≠ BH 过；泵在转 ≠ 泵组台账过。  
7. **BH-验 拒签重测**；禁套他站他期。  
8. **不能**抬功率；先挂 **N**；缺秩序整改贴 **BH**；塔侧问 **BA**，冷冻水泵问 **BD**，冷凝联锁问 **AT**；**禁功率战**。  
9. **不允许**；禁关阀冒充、开旁通冒充、绕泵/冷凝联锁、不安全泄水/带压违章；挂 N/R，禁签准用。  
10. **不能**互相顶替。纯风冷站泵组可书面勾「不适用」，冷凝水侧仍可能适用。  
11. 泵组项书面勾「不适用」；冷凝水侧按有无路径单独勾选，不得自动免。不得用 BH 顶 BA/BD/AT/BB。假绿挂 **R**；主贴仍 **BH**。  
12. **12.5 kHz** / **4FSK** / **2-slot TDMA**；告警窗 **禁功率战**；常被误当**覆盖病**→禁功率战，挂 N，变更走 J。

## 10. 加深阅读与视频（均已用 curl / oEmbed 核对；以核验当时为准）

**本篇专项方法级阅读（冷却水泵 / 冷凝器循环水 / 冷凝水排放路径；借秩序，不替代本网 BH 签字；不教关阀冒充、不教开旁通、不教绕联锁、不教不安全泄水/带压违章；不重写 BA/BD/AT/AO 全文）**  
1. **[Wikipedia · Condensate pump](https://en.wikipedia.org/wiki/Condensate_pump)**——冷凝水泵/提升泵公开词条（借「凝结水有集水、有提升、有排放」；**没看见滴水≠路径窗过**；**不是**本网 BH 法定制度）。  
2. **[Wikipedia · Cooling tower](https://en.wikipedia.org/wiki/Cooling_tower)** · **[Chiller](https://en.wikipedia.org/wiki/Chiller)** · **[Condenser (heat transfer)](https://en.wikipedia.org/wiki/Condenser_(heat_transfer))**——冷却塔 / 冷水机组 / 冷凝器（借「冷凝器一侧靠冷却水带走热量」；塔侧归 BA，泵组归 BH）。  
3. **[Wikipedia · Centrifugal pump](https://en.wikipedia.org/wiki/Centrifugal_pump)** · **[Circulator pump](https://en.wikipedia.org/wiki/Circulator_pump)** · **[Strainer](https://en.wikipedia.org/wiki/Strainer)** · **[Variable-frequency drive](https://en.wikipedia.org/wiki/Variable-frequency_drive)**——离心泵 / 循环泵 / 除污器 / 变频器（借「泵有主备与进出口」；**泵在转≠台账过**）。  
4. **[Wikipedia · Air gap (plumbing)](https://en.wikipedia.org/wiki/Air_gap_(plumbing))** · **[Trap (plumbing)](https://en.wikipedia.org/wiki/Trap_(plumbing))** · **[Condensation](https://en.wikipedia.org/wiki/Condensation)**——断气 / 水封 / 凝结（借「排放路径有水封与断气角色」）。  
5. **[Wikipedia · Chilled water](https://en.wikipedia.org/wiki/Chilled_water)** · **[Water cooling](https://en.wikipedia.org/wiki/Water_cooling)** · **[HVAC](https://en.wikipedia.org/wiki/Heating,_ventilation,_and_air_conditioning)**——冷冻水 / 水冷 / HVAC（借「冷冻水≠冷却水」；CHW 归 BD/BA，CW 归 BH-泵）。  
6. **[The Engineering Mindset · How Cooling Towers work](https://theengineeringmindset.com/how-cooling-towers-work/)** · **[How a Chiller, Cooling Tower and AHU work together](https://theengineeringmindset.com/chiller-cooling-tower-air-handling-unit-work-together/)** · **[Chiller Condenser](https://theengineeringmindset.com/chiller-condensers-explained/)** · **[Chilled Water Schematics](https://theengineeringmindset.com/chilled-water-schematics/)**——冷却塔/冷水机组/冷凝器/原理图公开文（借「冷却水由泵送往冷却塔、冷冻水是另一圈」；**不教关阀/旁通**）。  
7. **[ACCA · The Ultimate Guide to HVAC Condensate](https://hvac-blog.acca.org/the-ultimate-guide-to-hvac-condensate/)** · **[Airconergy · How a Condensate Pump Works](https://airconergy.com/air-conditioning/how-a-condensate-pump-works.php)**——HVAC 冷凝水与冷凝水泵公开文（借「有盘、有管、有泵、有排放点」；**口头冷凝正常≠方法过**）。  
8. **[Construct & Commission · Cooling Tower Piping Layout](https://constructandcommission.com/cooling-tower-piping-layout-and-diagrams/)**——冷却塔配管公开文（借「冷凝器循环水供回、泵有角色」；**不教不安全泄水排污**）。  
9. **[MEP Academy · CRAC vs CRAH](https://mepacademy.com/crac-vs-crah-units-explained-data-center-cooling/)** · **[HVAC Software · CRAC/CRAH PM Checklist](https://hvacsoftware.com/data-center/crac-crah-preventive-maintenance-checklist/)**——CRAC/CRAH 对比与维护公开页（借「水路与机内冷媒要分层」）。  
10. **[Bell & Gossett](https://www.bellgossett.com/)** · **[Armstrong Fluid Technology](https://www.armstrongfluidtechnology.com/)** · **[SPX Cooling](https://www.spxcooling.com/cooling-towers/)** · **[Baltimore Aircoil](https://www.baltimoreaircoil.com/)** · **[EVAPCO](https://www.evapco.com/)**——泵组/冷却塔厂商公开入口（**不教不安全泄水/带压违章**）。  
11. **[DMR Association · Standards](https://www.dmrassociation.org/dmr-standards.html)** · **[首页](https://www.dmrassociation.org/)**——空中接口标准入口（**不规定**冷却水泵/冷凝水侧台账）。  
12. **[Tait Radio Academy](https://www.taitradioacademy.com/)** · **[Hytera](https://www.hytera.com/)** · **[Motorola Solutions](https://www.motorolasolutions.com/)** · **[Sepura](https://www.sepura.com/)** · **[SRRC](https://www.srrc.org.cn/)**——专网厂商与型号核准公开入口。

**故事类比：医院手术室/ICU / 数据中心冷却水泵与冷凝水路径（只借直觉，不是台站法定依据）**  
13. **[Wikipedia · Operating room](https://en.wikipedia.org/wiki/Operating_room)** · **[Intensive care unit](https://en.wikipedia.org/wiki/Intensive_care_unit)** · **[Data center](https://en.wikipedia.org/wiki/Data_center)** · **[Server room](https://en.wikipedia.org/wiki/Server_room)**——借「泵在转≠准用、没看见滴水≠窗过、塔风扇转≠冷却水泵过、冷冻水泵过≠冷却水泵过、AT过≠路径台账过、AO过≠路径窗过、N绿≠BH过」。  
14. Wikipedia：[Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio) · [Land mobile radio system](https://en.wikipedia.org/wiki/Land_mobile_radio_system) · [Noise floor](https://en.wikipedia.org/wiki/Noise_floor)。

**国内无线电法规（台站秩序指针；无账乱签冷却水泵/冷凝水侧不是法外）**  
15. **[《中华人民共和国无线电管理条例》（中国政府网）](https://www.gov.cn/zhengce/zhengceku/2016-11/25/content_5137687.htm)** · **[国务院公报版](https://www.gov.cn/gongbao/content/2016/content_5148745.htm)**。  
16. **[《无线电频率使用许可管理办法》（中国政府网）](https://www.gov.cn/zhengce/2022-08/23/content_5722706.htm)**。  
17. **[《地面无线电台（站）管理规定》（中国政府网）](https://www.gov.cn/zhengce/202310/content_6908889.htm)** · **[国务院公报 · 工信部令第60号](https://www.gov.cn/gongbao/content/2023/content_5745291.htm)**。

**ITU / 验收方法级**  
18. **[ITU-R SM.1753](https://www.itu.int/rec/R-REC-SM.1753/en)** · **[ITU-R Monitoring](https://www.itu.int/en/ITU-R/terrestrial/monitoring/Pages/default.aspx)**。  
19. **[P25 Best Practice · Field Acceptance Tests](https://www.p25bestpractice.com/implementing/field-acceptance-tests/)** · **[Flowdit · SAT](https://flowdit.com/site-acceptance-test/)**——到站/现场合格（合格步骤≠假绿）。

**视频（YouTube，已用 oEmbed 核验标题与频道）**  
20. **[The Engineering Mindset · How Cooling Towers Work](https://www.youtube.com/watch?v=UzHJWNL2OtM)**——冷却塔公开片（借「冷却水由泵送往冷却塔」；**非** BH 台账专项）。  
21. **[The Engineering Mindset · Chiller Basics](https://www.youtube.com/watch?v=0rzQhSXVq60)**——冷水机组公开片（借「冷冻水是一圈、冷却水去冷却塔是另一圈」；对照 **BD≠BH**）。  
22. **[The Engineering Mindset · Centrifugal Pump Basics](https://www.youtube.com/watch?v=XpcCUtYzwy0)**——离心泵公开片（借「泵在转≠台账过」；**不教关阀/旁通**）。  
23. **[The Engineering Mindset · How Chiller, AHU, RTU work](https://www.youtube.com/watch?v=UmWWZdJR1hQ)**——冷水机组/AHU/RTU 公开片（借「水冷机组需要冷却塔与冷凝器循环水」）。  
24. **[AMRE Supply · How Do Condensate Pumps Work?](https://www.youtube.com/watch?v=S-Z2B89RHsA)**——冷凝水泵公开片（借「凝结水有集水与提升」；**没看见滴水≠窗过**）。  
25. **[The Engineering Mindset · Data Center HVAC](https://www.youtube.com/watch?v=xBxyhxmhigc)**——数据中心 HVAC 公开片（借「机房冷却有分层」）。  
26. **[Ctrltech · Inside components of CCU / CRAC](https://www.youtube.com/watch?v=PY4NU0aNUQo)**——精密空调内部组件公开片（借「机内有接水盘与排水角色」）。  
27. **[Primary Secondary Chilled Water System Working](https://www.youtube.com/watch?v=MqSFcSxxdfw)**——一二次冷冻水泵公开片（**对照用**：冷冻水侧分层归 BD/BA，**不是**冷却水泵）。  
28. **[MPSCS · Site Maintenance Inspection and Preventative Maintenance](https://www.youtube.com/watch?v=4IRdxeXN1do)**——站点维护与记录（借「要巡要记」）。  
29. **[Engineered Vision · FAT and SAT Explained](https://www.youtube.com/watch?v=x7qNC6Rtp9I)** · **[Careers360 · FAT & SAT](https://www.youtube.com/watch?v=3aafLF9o0NA)**——出厂/到站合格直觉（假绿≠会签）。  
30. **[Scanner School · What is DMR?](https://www.youtube.com/watch?v=aQX_JbTbXuY)**（弱项：时隙与数字话音）。  
31. **[Rohde & Schwarz · Understanding Spectrum Analyzers – ACLR](https://www.youtube.com/watch?v=mco_BJ1mjNo)**——频谱仪直觉；对照禁功率战。  

> **诚实说明**：没有找到「DMR 专网机房冷却水泵组与冷凝水侧交底台账（贴纸 BH + BH1–BH8 + 拒签卡 + BD≠BH / BA≠BH / AT≠BH / AO≠BH）」的专项中文公开视频或制度文章。最贴题的是 Wikipedia Condensate pump / Cooling tower / Centrifugal pump / Chiller、Engineering Mindset 冷却塔/冷水机组/冷凝器公开文、ACCA / Airconergy 冷凝水公开文、Construct & Commission 冷却塔配管、MEP Academy CRAC vs CRAH，以及 How Cooling Towers Work + Chiller Basics + Centrifugal Pump Basics + Condensate Pumps Work + Data Center HVAC 公开片，加上站点维护/FAT-SAT/DMR 基础视频。需按贴纸 BH 与 BH1–BH8 拼进本网流程。`video_found=true`（冷却塔/冷水机组/离心泵/冷凝水泵/数据中心 HVAC + 通用巡检/FAT-SAT/DMR），**非** BH 台账专项。Hartell 冷凝水泵文返回 429、condensatepump.org 失败，本篇未引用。任何「教关阀冒充 / 开旁通 / 绕联锁 / 不安全泄水或带压违章 / 伪造台账 / 抬功率压告警」的页面即使 200，本篇也**不引用**。

**库内必回：** 手册57（BD）、54（BA）、47（AT）、42（AO）、55（BB）、51（AX）、36（AI）、60（BG）、15（N）、31（AD）、41（AN）、19（R）、06（脱敏）、`加餐_频率带宽与调制解调.md`。

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子
- 贴纸 **BH** 五子类：泵 / 凝 / 界 / 验 / 治——BG 之后第一张 **BH**，负责冷却水泵组与冷凝水侧「有没有账、冷凝水侧有没有窗、边界有没有法、本期过了没有」。  
- 口诀：**冷却水泵有账，冷凝水有窗，边界有法，会签才放。**  
- 故事：医院手术室/ICU / 数据中心冷却水泵 + 冷凝水排放路径——泵在转≠台账过；塔风扇转≠冷却水泵过；冷冻水泵签过≠冷却水泵过；没看见滴水≠窗过；AT 联锁过≠路径台账过；AO 探头过≠路径窗过。  
- 三个汉字：**冷冻水 ≠ 冷却水 ≠ 冷凝水**。冷冻水归 BD/BA，冷却水归 BH-泵，冷凝水联锁归 AT、路径台账归 BH-凝。  
- 八条硬规则：**冷却水泵组台账钉死**；**冷凝水侧有主有窗有方法/准用期**；**边界窗与方法钉死**；**本期实测禁套**；**会签才放行**；**禁顶替 BA/BD/AT/AO/BB/…，主贴 BH，假绿≠放行挂 R**；**风暴挂 N、变更走 J、禁功率战/关阀/旁通/绕联锁/不安全泄水/伪造台账**；**脱敏 L3**。  
- **BH 不替代 BA / BD / AT / AO**。**BD ≠ BH；BA ≠ BH；AT ≠ BH；AO ≠ BH。本篇不重写它们的全文。**

### 11.2 下一篇手册候选（本篇不写正文）
- **机房柴油发电机日用/储油罐油位与泄漏巡检交底台账**（与 AF 油机市电、AV 油品净化加油、AR 油机房通风燃油、N 监控、AN 门禁咬合；适用于要单独钉油位/泄漏巡检秩序的站点）  
- **机房精密空调压缩机吸排气压力与过热度过冷度巡检交底台账**（与 AX 压缩机冷媒边界、AT 冷凝加湿、AI 温湿度、N 监控咬合；适用于要单独钉吸排气/过热度过冷度秩序的站点；**不重写 AX 制冷剂边界全文**）  
- **机房精密空调蒸发器盘管清洗与翅片完好交底台账**（与 AU 气流组织、BG 滤网更换、AT 冷凝、AI 温湿度、AX 压缩机、N 监控咬合；适用于要单独钉盘管清洗/翅片完好秩序的站点；**不重写 AU/BG/AX 全文**）

### 11.3 给带新人的三句话
1. 冷却水泵不是转着就能签：冷却水泵有账，本期核对钉死；**冷冻水泵过≠冷却水泵过，塔风扇转≠冷却水泵过**。  
2. 冷凝水侧不是没看见滴水就算过、也不是 AT 联锁过了就能顶：主人窗方法准用期，集水/提升泵/水封/排放点/断气书面方法，本期实测会签才算准用；禁关阀、禁旁通、禁绕联锁、禁不安全泄水。  
3. 假绿挂 R；主贴 BH；BA/BD/AT/AO/N 不顶替；异常窗禁功率战；公开脱敏 L3。

### 11.4 一张图记住本篇（收工贴纸）
```text
  ┌────────── 贴纸 BH ──────────┐
  │ 泵 冷却水泵组台账钉死       │
  │ 凝 冷凝水侧有主有窗有方法   │
  │ 界 冷却水泵与冷凝水侧边界窗·方法钉死 │
  │ 验 本期实测·禁套·会签       │
  │ 治 假绿顶替套票关阀旁通绕联锁功率战 │
  └────────────────────────────┘
    泵在转≠台账过 · 没看见滴水≠窗过 · 口头正常≠方法过 · 假绿≠准用
    BD≠BH（冷冻水泵 ≠ 冷却水泵）  BA≠BH（塔风扇转 ≠ 冷却水泵）
    AT≠BH（冷凝联锁 ≠ 路径台账）  AO≠BH（漏水探头 ≠ 路径窗）
    BB≠BH（风冷室外机不得互相顶替）  N≠BH（风暴绿 ≠ 本期实测）
```

## 12. 本篇检查清单（自学打勾）
- [ ] 能背贴纸 BH 五子类与医院手术室/ICU 或数据中心冷却水泵 + 冷凝水路径故事  
- [ ] 能背口诀：冷却水泵有账，冷凝水有窗，边界有法，会签才放  
- [ ] 能分清冷冻水 / 冷却水 / 冷凝水三个词，并说出各归谁  
- [ ] 能背八条硬规则（冷却水泵组台账钉死、冷凝水侧有主窗方法、边界窗方法钉死、本期实测、会签才放、禁顶替假绿挂R、禁功率战禁关阀禁旁通禁绕联锁禁不安全泄水挂N走J、L3）  
- [ ] 能分清 BH 与 BA / BD / AT / AO / BB / AX / AI / BG / N / R / J 边界；尤其 **BD≠BH、BA≠BH、AT≠BH、AO≠BH**；知道本篇不重写 BA/BD/AT/AO 全文  
- [ ] 会填插页 BH1–BH8 与台账卡封面/泵/凝/界/验/会签页  
- [ ] 会用拒签卡卡住无账、套票、顶替、假绿、关阀、旁通、绕联锁  
- [ ] 自测 12 题过关；知道 video_found=true 但是非 BH 台账专项  
- [ ] 回库用 L3 对一遍最近一次机房冷却水泵组与冷凝水侧交底：台账、窗、方法、本期实测、会签、拒签项（无冷却水泵路径则勾泵组不适用；冷凝水侧单独判断）  
- [ ] 弱项短补记得：12.5 kHz / 4FSK / 2-slot TDMA；冷却水泵跳闸/冷凝水溢流/泵组窗乱签常被误当覆盖病→禁功率战；挂 N；变更走 J  
- [ ] 知道下一篇三个候选（柴油发电机油位与泄漏巡检 / 精密空调吸排气压力与过热度过冷度 / 精密空调蒸发器盘管清洗与翅片完好）尚未写正文  

---

*手册 61 · 贴纸 BH（泵 / 凝 / 界 / 验 / 治）· 口诀：冷却水泵有账，冷凝水有窗，边界有法，会签才放 · BD≠BH · BA≠BH · AT≠BH · 教学虚构 L3 · 2026-11-08*
