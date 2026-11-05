## 8. 术语表（本篇约 18 词）+ 易错观念

| 术语 | 本篇用法（教学） |
|------|------------------|
| **机柜配电** | 机柜侧电源分配角色（机柜·机架PDU·支路/插座）；BC-柜 |
| **机架 PDU** | Rack PDU；机柜内配电单元角色（脱敏编号）；≠ AW 列头柜本身 |
| **PUE** | Power Usage Effectiveness；能效秩序直觉；**口头PUE正常≠窗过**；门限以本网书面为准 |
| **负载** | IT/设备侧用电负荷角色；有测点、有窗、有方法 |
| **负载分区** | 按区/按列/按回路划分的负载边界；BC-区 |
| **能效窗** | PUE/能效相关书面维护窗；有主人有准用期 |
| **分区计量** | 分区级功率/电能计量角色；脱敏；不写可还原门限全文 |
| **灯绿** | 指示灯/监控绿；**≠ 台账过、≠ 窗过、≠ 本期实测过** |
| **假绿** | 无实测/无会签却显示通过；挂 R；≠ 放行 |
| **套票** | 套他站他期机柜/PUE/分区表；BC-验 拒签 |
| **绕电气联锁** | 绕过电气安全联锁冒充可过；**本篇硬禁** |
| **未授权带电** | 未经授权的带电作业冒充可过；**本篇硬禁** |
| **功率战** | 用抬功率压机柜/PUE/分区告警；**禁**；先挂 N |
| **贴纸 BC** | 本篇主贴；柜/荷/区/验/治五子类 |
| **AW ≠ BC** | 列头末端巡检 ≠ 机柜配电与PUE/负载分区 |
| **AF ≠ BC** | 油机市电 ≠ 机柜/PUE/分区 |
| **AS ≠ BC** | UPS 旁路 ≠ 机柜/PUE/分区 |
| **N ≠ BC** | 风暴秩序 ≠ 本期实测 |
| **脱敏 L3** | 禁真实站名/机房全称/机柜序列号全文/回路编号全文/联系人 |

**易错观念（纠一次）**  
- 「灯绿 = 准用」→ 错；要 BC-柜台账 + 本期实测。  
- 「口头PUE正常 = 窗过」→ 错；要 BC-荷 主人窗方法。  
- 「AW 过 = BC 过」→ 错；列头末端 ≠ 机柜PDU/PUE/分区。  
- 「N 绿 = 本期实测过」→ 错；风暴绿 ≠ 交底准用。  
- 「绕联锁消告警 = 办法」→ 错；硬禁。  
- 「抬功率压分区告警 = 救急」→ 错；禁功率战。

---

## 9. 自测（12 题）+ 参考答案

1. 贴纸 BC 五个子类是什么？口诀是哪一句？  
2. 「灯绿就能签」违反哪条硬规则？属哪个子类？  
3. 八条硬规则里，哪一条要求 PUE/负载有主有窗有方法/准用期？  
4. AW 列头末端过了，能不能顶本期 BC？为什么？  
5. N 监控绿，能不能免本期机柜/PUE实测？  
6. 套邻站机柜/PUE表改机房号，应如何处置？  
7. 分区过载告警时，能不能先抬功率？应挂什么？  
8. 「绕电气联锁消告警后再签」允许吗？  
9. AD 仪表入库签还在，能不能免本期实测窗？  
10. 本站无独立机柜PDU/PUE/分区计量，BC 怎么处理？  
11. 假绿放行应挂什么贴纸？主贴还是不是 BC？  
12. 弱项短补：DMR 信道宽、调制、时隙各是什么？告警窗禁什么？

### 参考答案

1. 柜 / 荷 / 区 / 验 / 治；口诀：**机柜有账，负载有窗，分区有法，会签才放。**  
2. 规则1（机柜配电台账钉死）及规则2相关；属 **BC-柜**（常连带 BC-荷）。  
3. 规则2。  
4. **不能**。AW ≠ BC；列头末端过 ≠ 机柜配电与PUE/负载分区过。  
5. **不能**。N 绿 ≠ BC 过；要有本期实测与会签。  
6. **BC-验 拒签重测**；禁套他站他期。  
7. **不能**抬功率；先挂 **N** 理风暴；缺秩序整改贴 **BC**；**禁功率战**。  
8. **不允许**；禁绕电气联锁；挂 N/R，禁签准用。  
9. **不能**；AD 只支撑仪表准用，不顶本期 BC 窗/实测。  
10. 书面勾「不适用」；不得用 BC 顶 AW/AF/AS。  
11. 挂 **R**；主贴仍 **BC**。  
12. **12.5 kHz** / **4FSK** / **2-slot TDMA**；告警窗 **禁功率战**。

---
## 10. 加深阅读与视频（均已用 curl / oEmbed 核对；以核验当时为准）

**本篇专项方法级阅读（机柜配电 / PUE / 负载分区 / Rack PDU；借秩序，不替代本网 BC 签字；不教绕电气联锁、不教未授权带电、不教伪造台账）**  
1. **[Wikipedia · Power usage effectiveness](https://en.wikipedia.org/wiki/Power_usage_effectiveness)**——PUE 公开词条（借「总设施功率/IT功率有比值、有测量边界、口头说PUE正常≠窗过」直觉；**不是**本网 BC 法定制度；**不发明条款号**；门限以本网书面为准）。  
2. **[Wikipedia · Power distribution unit](https://en.wikipedia.org/wiki/Power_distribution_unit)**——PDU 公开词条（借「机架配电有角色、有监测有标签」；**对照 AW≠BC**：列头/末端巡检归 AW，机柜PDU·PUE·负载分区归 BC）。  
3. **[Wikipedia · Data center](https://en.wikipedia.org/wiki/Data_center)** · **[Electrical load](https://en.wikipedia.org/wiki/Electrical_load)** · **[Data center infrastructure efficiency](https://en.wikipedia.org/wiki/Data_center_infrastructure_efficiency)**——数据中心 / 电气负载 / DCiE 公开词条（借「负载有分区、能效有度量边界」；现场以本网与 OEM 书面为准）。  
4. **[ENERGY STAR · Data Center Equipment](https://www.energystar.gov/products/data_center_equipment)** · **[ENERGY STAR · Tools and Resources](https://www.energystar.gov/buildings/tools-and-resources)**——数据中心设备与工具公开入口（借「机房能效与设备有维护秩序」指针；**不是**中国专网 BC 法定依据）。  
5. **[The Green Grid · Library and Tools](https://www.thegreengrid.org/en/resources/library-and-tools)**——The Green Grid 公开资源入口（借「PUE 等能效度量有公开讨论边界」；程序以原文与本网制度为准）。  
6. **[Google Data Centers · Efficiency / PUE](https://datacenters.google/efficiency/)**——公开能效/PUE 说明页（借「PUE 有测量边界、设施功率与IT功率要分清」；**只作故事类比**；本网门限以书面为准）。  
7. **[Raritan · PDU Metering at Inlet, Outlet, and Branch Circuits](https://www.raritan.com/products/feature/pdu-metering-at-the-inlet-outlet-and-branch-circuits)**——机架 PDU 进线/出线/支路计量公开文（借「机柜侧有多层计量、过载要有预警秩序」；**不教绕联锁/未授权带电**；机型以本网授权书面为准）。  
8. **[Raritan · Power Management 公开入口](https://www.raritan.com/products/power-management)** · **[Vertiv · Power Distribution 公开入口](https://www.vertiv.com/en-us/products-catalog/critical-power/power-distribution/)**——厂商功率管理/配电公开入口（现场以本网授权与该机型书面为准）。  
9. **[Anvilfield · Data center field guides 入口](https://anvilfield.com/field-guides/datacenter/)**——数据中心现场指南入口（借「机房配电/能效有分层交底」；机柜/PUE/分区专项仍以本篇 BC 为准）。  
10. **[DMR Association · Standards](https://www.dmrassociation.org/dmr-standards.html)** · **[首页](https://www.dmrassociation.org/)**——空中接口标准入口（**不规定**机柜配电与PUE台账）。  
11. **[Tait Radio Academy](https://www.taitradioacademy.com/)** · **[Tait Communications](https://www.taitcommunications.com/)** · **[Hytera](https://www.hytera.com/)** · **[Motorola Solutions](https://www.motorolasolutions.com/)** · **[Sepura](https://www.sepura.com/)**——专网厂商公开入口。

**故事类比：医院手术室/ICU 保供电机房机柜配电与负载分区/能效巡检 / 数据中心 rack PDU + PUE（只借直觉，不是台站法定依据）**  
12. **[Wikipedia · Operating room](https://en.wikipedia.org/wiki/Operating_room)** · **[Intensive care unit](https://en.wikipedia.org/wiki/Intensive_care_unit)** · **[Data center](https://en.wikipedia.org/wiki/Data_center)**——手术室/ICU/数据中心直觉（借「灯绿≠准用、口头PUE正常≠窗过、口头机柜电正常≠方法过、AW 过≠BC 过、AF 过≠BC 过、AS 过≠BC 过、AD 过≠本期实测过、N 绿≠BC 过、AQ 过≠BC 过」）。  
13. Wikipedia：[Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio) · [Land mobile radio system](https://en.wikipedia.org/wiki/Land_mobile_radio_system) · [Noise floor](https://en.wikipedia.org/wiki/Noise_floor)。

**国内无线电法规（台站秩序指针；无账乱签机柜/PUE/分区不是法外）**  
14. **[《中华人民共和国无线电管理条例》（中国政府网）](https://www.gov.cn/zhengce/zhengceku/2016-11/25/content_5137687.htm)** · **[国务院公报版](https://www.gov.cn/gongbao/content/2016/content_5148745.htm)**。  
15. **[《无线电频率使用许可管理办法》（中国政府网）](https://www.gov.cn/zhengce/2022-08/23/content_5722706.htm)**。  
16. **[《地面无线电台（站）管理规定》（中国政府网）](https://www.gov.cn/zhengce/202310/content_6908889.htm)** · **[国务院公报 · 工信部令第60号](https://www.gov.cn/gongbao/content/2023/content_5745291.htm)**。

**ITU / 验收方法级**  
17. **[ITU-R SM.1753](https://www.itu.int/rec/R-REC-SM.1753/en)** · **[ITU-R Monitoring](https://www.itu.int/en/ITU-R/terrestrial/monitoring/Pages/default.aspx)**。  
18. **[P25 Best Practice · Field Acceptance Tests](https://www.p25bestpractice.com/implementing/field-acceptance-tests/)** · **[Flowdit · SAT](https://flowdit.com/site-acceptance-test/)**——到站/现场合格与公开入口（合格步骤≠假绿）。

**视频（YouTube，已用 oEmbed 核验标题与频道）**  
19. **[Data Center Power Explained (It's simpler than you think)](https://www.youtube.com/watch?v=giNYYY0DnJw)**——数据中心电力链路公开片（借「从市电到机架PDU、PUE是记分牌、灯绿≠准用」；**不是** BC 台账专项；**不教绕联锁/未授权带电**）。  
20. **[PUE Levels of Measurement: What You Need to Know](https://www.youtube.com/watch?v=BU2K43VGdU0)**——PUE 测量层级公开片（借「测量边界要书面固定、口头PUE正常≠窗过」；门限以本网书面为准）。  
21. **[PUE: The Score That Defines Data Center Efficiency](https://www.youtube.com/watch?v=PycfsJtI154)**——PUE 能效记分公开短片（借「能效有账要验」；**不是** BC 专项）。  
22. **[Understanding Rack Power Distribution (PDU)](https://www.youtube.com/watch?v=DrK8wjePVO8)**——机架配电/PDU 公开片（借「机柜侧配电有角色」；对照 AW≠BC）。  
23. **[Raritan · PX Series of Intelligent Rack PDUs](https://www.youtube.com/watch?v=foXPx8Jehcs)**——智能机架 PDU 公开片（借「进线/支路计量、过载预警有产品角色」；机型以本网授权书面为准）。  
24. **[Data Center Power Flow: From Utility Grid to Server Rack](https://www.youtube.com/watch?v=Y_8P3wzxsqY)**——从市电到机架的电力流公开片（借「分层配电、末级在机柜PDU」；列头末端回 AW，机柜/PUE/分区回 BC）。  
25. **[How Google Data Centers Achieve Energy Efficiency](https://www.youtube.com/watch?v=xIbkqpRDlVA)**——数据中心能效策略公开片（只借「能效有秩序」；**不是** BC 台账专项）。  
26. **[MPSCS · Site Maintenance Inspection and Preventative Maintenance](https://www.youtube.com/watch?v=4IRdxeXN1do)**——站点维护与记录（借「要巡要记」）。  
27. **[Engineered Vision · FAT and SAT Explained](https://www.youtube.com/watch?v=x7qNC6Rtp9I)** · **[Careers360 · FAT & SAT](https://www.youtube.com/watch?v=3aafLF9o0NA)**——出厂/到站合格直觉（回指：假绿≠会签）。  
28. **[Scanner School · What is DMR?](https://www.youtube.com/watch?v=aQX_JbTbXuY)**（弱项：时隙与数字话音）。  
29. **[Rohde & Schwarz · Understanding Spectrum Analyzers – ACLR](https://www.youtube.com/watch?v=mco_BJ1mjNo)**——频谱仪直觉；对照禁功率战。  
30. **[NATEsafety · How to Conduct Tower Inspections](https://www.youtube.com/watch?v=dFs4At6-hhU)** · **[Sunil Kashyap · How to perform site audit or RF audit](https://www.youtube.com/watch?v=7Awj0-rDfeA)**——巡检/审计通用视频（借「要巡要记」；**不是**绕联锁/未授权带电教条）。

> **诚实说明**：没有找到「DMR 专网机柜配电与PUE/负载分区巡检交底台账（含贴纸 BC + 插页 BC1–BC8 + 医院/数据中心 rack PDU + PUE 隐喻 + 拒签卡 + 与 AW/AF/AS/N 分工）」的专项中文公开视频或制度文章；最贴题的是 **Wikipedia PUE / PDU / Data center / Electrical load**、**ENERGY STAR Data Center**、**The Green Grid**、**Google Data Centers Efficiency**、**Raritan PDU Metering**、**Anvilfield**、**Data Center Power / PUE Levels / Rack PDU / Power Flow 公开片**，以及站点维护/FAT-SAT/DMR 基础视频。其余为国内无线电法规与 DMR/ITU 入口。需按贴纸 BC 与 BC1–BC8 拼进本网流程。`video_found=true`（数据中心电力/PUE/机架PDU + 通用巡检/FAT-SAT/DMR），**非** BC 台账专项。ASHRAE 官网与部分 Schneider 页面核验返回 403，本篇以已 200/oEmbed 通过的链接为准。任何「教绕电气联锁 / 未授权带电 / 伪造台账 / 抬功率压告警」的页面即使 200，本篇也**不引用**。

**库内必回：** 手册50（AW）、33（AF）、46（AS）、31（AD）、41（AN）、28（AA）、15（N）、44（AQ）、49（AV）、45（AR）、34（AG）、43（AP）、36（AI）、47（AT）、48（AU）、42（AO）、39（AL）、55（BB）、51（AX）、54（BA）、52（AY）、53（AZ）、19（R）、06（脱敏）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子
- 贴纸 **BC** 五子类：柜 / 荷 / 区 / 验 / 治——双字母续写在 BB 之后的第一张 **BC**，负责机柜配电与PUE/负载分区「台账清不清、负载有没有窗、分区有没有法、本期过了没有」。  
- 口诀：**机柜有账，负载有窗，分区有法，会签才放。**  
- 故事：医院手术室/ICU 保供电机房机柜配电与负载分区/能效巡检（或数据中心 rack PDU + PUE / load-zone metering）——灯绿≠准用；口头说机柜电正常≠方法过；口头PUE正常≠窗过。  
- 八条硬规则：**机柜配电台账钉死**；**PUE/负载有主有窗有方法/准用期**；**负载分区边界窗与方法钉死**；**本期实测禁套**；**会签才放行**；**禁顶替 AW/AF/AS/AD/AN/AA/N/AQ/AV/AR/AG/AP/AI/AT/AU/AO/AL/BB/AX/BA/AY/AZ，主贴 BC，假绿≠放行挂 R**；**异常风暴挂 N、变更走 J、禁功率战/绕联锁/未授权带电/伪造台账**；**脱敏 L3**。  
- **BC 不替代 AW，也不替代 AF，也不替代 AS，也不替代 N**：AW=列头柜与末端配电巡检；AF=油机市电；AS=UPS 旁路；N=监控风暴；BC=机柜配电与PUE/负载分区巡检准用。

### 11.2 下一篇手册候选（本篇不写正文）
- **机房冷冻水泵组与定压补水交底台账**（与 BA 冷冻水冷却塔侧、AX 压缩机制冷剂、AO 漏水、AI 温湿度、N 监控、AN 门禁咬合；适用于有泵组/定压补水的冷冻水站点）  
- **机房加湿器水质与电极/电极罐更换交底台账**（与 AT 冷凝加湿、AI 温湿度、AO 漏水、AD 备件、N 监控、AN 门禁咬合；适用于电极加湿/蒸汽加湿有水质与更换窗的站点）  
- **机房接地与等电位/浪涌保护巡检交底台账**（与 AM 接地浪涌指针、AF 油机市电、AW 列头末端、BC 机柜配电、N 监控、AN 门禁咬合；适用于要单独钉接地/SPD 巡检秩序的站点）

### 11.3 给带新人的三句话
1. 机柜不是灯绿就能签：机柜有账，本期核对钉死。  
2. 负载不是口头PUE正常就算过、分区不是口头测过就算过：主人窗方法准用期，分区书面方法，本期实测会签才算准用；禁绕电气联锁、禁未授权带电。  
3. 假绿挂 R；主贴 BC；AW/AF/AS/N 不顶替；异常窗禁功率战禁绕联锁禁未授权带电；公开脱敏 L3。

### 11.4 一张图记住本篇（收工贴纸）
```text
  ┌────────── 贴纸 BC ──────────┐
  │ 柜 机柜配电台账钉死         │
  │ 荷 PUE/负载有主有窗有方法   │
  │ 区 分区窗·方法钉死         │
  │ 验 本期实测·禁套·会签       │
  │ 治 假绿顶替套票绕联锁未授权带电功率战 │
  └────────────────────────────┘
    灯绿≠准用 · 口头PUE正常≠窗过 · 口头机柜电正常≠方法过 · 假绿≠准用
    AW≠BC（列头末端 ≠ 机柜配电与PUE/分区）
    AF≠BC（油机市电 ≠ 机柜/PUE/分区）
    AS≠BC（UPS旁路 ≠ 机柜/PUE/分区）
    AD≠BC（仪表入库 ≠ 本期实测）
    N≠BC（风暴秩序 ≠ 本期实测）
    BB≠BC（室外机冷凝侧 ≠ 机柜/PUE）
    AZ≠BC（冷通道进出风 ≠ 负载分区）
```

---

## 12. 本篇检查清单（自学打勾）
- [ ] 能背贴纸 BC 五子类与医院手术室/ICU 保供电机房机柜配电与负载分区/能效或数据中心 rack PDU + PUE 故事  
- [ ] 能背口诀：机柜有账，负载有窗，分区有法，会签才放  
- [ ] 能背八条硬规则（机柜配电台账钉死、PUE/负载有主窗方法、分区窗方法、本期实测、会签才放、禁顶替假绿挂R、禁功率战禁绕联锁禁未授权带电挂N走J、L3）  
- [ ] 能分清 BC 与 AW / AF / AS / AD / AN / N / AQ / BB / AZ / R / J 边界  
- [ ] 会填插页 BC1–BC8 与台账卡封面/柜/荷/区/验/会签页  
- [ ] 会用拒签卡卡住无账、套票、顶替、假绿、绕联锁、未授权带电  
- [ ] 自测 12 题过关；知道 video_found=true 但是非 BC 台账专项  
- [ ] 回库用 L3 对一遍最近一次机柜配电与PUE/负载分区巡检交底：台账、窗、方法、本期实测、会签、拒签项（无独立路径则勾不适用）  
- [ ] 弱项短补记得：12.5 kHz / 4FSK / 2-slot TDMA；告警窗禁功率战  
- [ ] 知道下一篇三个候选（冷冻水泵组与定压补水 / 加湿器水质与电极罐更换 / 接地与等电位浪涌巡检）尚未写正文  

---

*手册56 · 贴纸 BC · 2026-11-05 晚间推送（Asia/Shanghai）· 教学用 · L3*
