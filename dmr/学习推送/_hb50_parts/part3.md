## 8. 术语表（本篇约 18 词）+ 易错观念

| 术语 | 本篇用法（教学） |
|------|------------------|
| **AW** | 本篇贴纸：列头柜·末端配电·巡检交底 |
| **AW-列** | 列头柜台账（柜体·进线/母线·馈出回路） |
| **AW-末** | 末端配电有主有窗有方法准用期（支路·插座·PDU 单元） |
| **AW-巡** | 巡检窗与书面方法（到场、目视、测温、紧固指针等） |
| **AW-验** | 本组本机房本期实测·禁套·会签 |
| **AW-治** | 假绿·顶替·绕联锁·未授权带电违章·功率战·泄密治理 |
| **列头柜 / PDU / 列头配电柜** | 机房行末或列头配电柜角色；本篇钉台账与巡检交底，不替代 AF 的油机市电切换 |
| **末端配电 / 支路 / 插座 / PDU 单元** | 馈出到机柜/设备的支路与末端单元角色；灯绿≠窗过 |
| **进线 / 母线 / 馈出回路** | 列头柜进线、母排/母线、馈出回路角色；编号脱敏 |
| **支路监测 / BCM** | 按支路监测电流/功率的角色（公开资料借「映射要对、门限要设」）；本篇不写死门限 |
| **热成像 / 测温指针** | 按本网书面规程的测温/热成像留痕角色（本篇不写逐步带电教条） |
| **列头末端准用** | 会签后允许宣称本期列头柜与末端配电巡检交底合格；假绿≠准用 |
| **假绿** | 监控绿/指示灯绿/标签在冒充准用；挂 R |
| **套票** | 套他站他期曲线/照片/热成像；AW-验拒签 |
| **L3** | 对外脱敏等级：禁真实站名/全称/序列号/单位名/联系人 |
| **AF / AS / AD / N** | 油机市电 / UPS 旁路 / 备件仪表 / 监控风暴——均不顶替 AW |
| **R / J** | 假绿挂 R；变更走 J 后再验 AW |
| **电气安全联锁** | 本网书面电气安全联锁角色；**禁绕过冒充准用** |

**易错观念（纠一次）**

1. 「指示灯绿 = 支路准用」→ **错**。要有台账与本期回路核对。  
2. 「标签还在 = 窗过」→ **错**。要有主人、窗、方法、准用期。  
3. 「AF 油机市电过 = AW 过」→ **错**。AF≠AW。  
4. 「AS UPS 旁路过 = AW 过」→ **错**。AS≠AW。  
5. 「AD 仪表入库过 = 本期实测过」→ **错**。AD≠AW。  
6. 「N 监控绿 = 本期配电实测过」→ **错**。N≠AW。  
7. 「配电告警烦，先旁路联锁 / 未授权带电」→ **禁**。绕联锁/带电违章挂 N/R。  
8. 「支路跳闸/配电告警先抬功率」→ **禁功率战**。  
9. 「邻站热成像改机房号能交差」→ **套票拒签**。  

---

## 9. 自测（12 题）+ 参考答案

1. 贴纸 AW 的五个子类是什么？口诀是哪一句？  
2. 「指示灯绿就能签」违反哪条硬规则？属哪个子类？  
3. 八条硬规则里，哪一条要求末端配电有主有窗有方法/准用期？  
4. AF（手册33）、AS（手册46）和 AW 各管什么？能不能互相顶替？  
5. AD（手册31）仪表入库过了，能不能免做本期实测？  
6. N 监控绿了，能不能免本期列头末端实测？  
7. 套邻站热成像改机房号，主贴哪个子类？怎么处置？  
8. 改配电策略或门限或巡检规程未走变更，应补什么贴纸路径？  
9. 支路跳闸/配电告警一片，能不能先抬功率？应先贴什么？能不能绕电气安全联锁？  
10. 插页 AW1–AW8 分别对应哪一类检查？  
11. 频谱弱项：DMR 信道间隔、调制、时隙各是什么？和本篇禁功率战有何关系？  
12. L3 禁写哪些？允许写哪些？

### 参考答案

1. 列 / 末 / 巡 / 验 / 治；口诀：**列头有账，末端有窗，巡检有法，会签才放。**  
2. 违反规则1（列头柜台账钉死）；属 **AW-列**。  
3. 规则2。  
4. AF 管**油机市电切换与供电巡检**；AS 管 **UPS 旁路**；AW 管列头柜**台账·末端配电窗·巡检交底准用**；**不能**互相顶替；AF 过≠AW 过；AS 过≠AW 过。  
5. **不能**。AD 入库过≠本期实测过；主贴仍 AW。  
6. **不能**。N 绿≠AW 过；要有本期列头/末端/巡检实测与会签。  
7. **AW-验**；拒签；重测本期本组本机房。  
8. 走 **J**，再验 **AW**。  
9. **不能**抬功率（禁功率战）；先挂 **N** 理风暴；缺列头/末端/巡检秩序整改贴 **AW**；**禁绕电气安全联锁**；**禁未授权带电违章**。  
10. AW1 列；AW2 末；AW3 巡；AW4 验；AW5 与 AF/AS/AD/N 等边界；AW6 会签；AW7 拒签触发；AW8 15 分钟夜班。  
11. **12.5 kHz**、**4FSK**、**2-slot TDMA**；支路跳闸/配电告警常被误当成覆盖病去抬功率——**禁功率战**；先 AW/N 证秩序。  
12. 禁：真实站名、机房全称、列头柜序列号全文、单位名、联系人、真实频点、未脱敏可还原编号；允许：脱敏角色、现象、贴纸、动作（补账/重测/拒签）。

---

## 10. 加深阅读与视频（均已用 curl / oEmbed 核对；以核验当时为准）

**本篇专项方法级阅读（列头柜/末端配电/PDU 巡检；借秩序，不替代本网 AW 签字）**  
1. **[Wikipedia · Power distribution unit](https://en.wikipedia.org/wiki/Power_distribution_unit)**——PDU 公开词条（借「列头/机架配电有角色、有监测有标签」直觉；**不是**本网 AW 法定制度；**不发明条款号**）。  
2. **[POPProbe · PDU Power Distribution Unit Inspection Checklist](https://www.popprobe.com/checklist-library/data-center-operations/power-systems/b27-dat-pdu-inspection-checklist)**——PDU 巡检清单公开页（借「相电流、断路器状态、热成像、计量核对有清单」；门限以本网与 OEM 书面为准）。  
3. **[Anvilfield · Data center PDU and RPP commissioning field guide](https://anvilfield.com/field-guides/datacenter/pdu-rpp-commissioning/)**——PDU/RPP 调试公开指南（借「BCM 映射要对、门限要设、热成像要留痕」；**只作方法类比**；**不教绕联锁/带电违章**）。  
4. **[Energy Compere · Data Center Branch Circuit Power Monitoring](https://www.energycompere.com/solution/data-center-branch-circuit-power-monitoring.html)**——支路功率监测公开文（借「支路有账、映射要验、告警要设」）。  
5. **[TestGuy · Power Distribution Unit (PDU) Applications, Testing & Maintenance](https://wiki.testguy.net/t/power-distribution-unit-pdu-applications-testing-maintenance/73)**——PDU 应用与维护公开文（借「投运前验收、在役看过热与螺栓连接」；现场以本网书面为准）。  
6. **[Titan Power · Importance of Consistent Data Center PDU Maintenance & Repair](https://www.titanpower.com/importance-of-consistent-data-center-pdu-maintenance-repair/)**——PDU 维护公开文（借「目视全覆盖、除尘、红外扫描、接地检查有周期」）。  
7. **[Infodeck · Data Center Compliance Checklist](https://www.infodeck.io/resources/datacenter-compliance-checklist/)**——数据中心合规清单公开页（借「PDU 巡检/热成像有周期指针」；**不是**中国专网 AW 法定依据）。  
8. **[NFPA 70B Standard Development 公开页](https://www.nfpa.org/codes-and-standards/nfpa-70b-standard-development/70b)**——电气设备维护标准公开入口（借「电气盘柜维护有秩序」；全文以 NFPA/属地为准）。  
9. **[Vertiv · Power Distribution 公开入口](https://www.vertiv.com/en-us/products-catalog/critical-power/power-distribution/)** · **[Raritan · Power 公开入口](https://www.raritan.com/products/power)**——厂商配电/机架 PDU 公开入口（现场以本网授权与该机型书面为准）。  
10. **[Wikipedia · Busbar](https://en.wikipedia.org/wiki/Busbar)** · **[Electrical panel](https://en.wikipedia.org/wiki/Electrical_panel)** · **[Uninterruptible power supply](https://en.wikipedia.org/wiki/Uninterruptible_power_supply)**——母线/配电盘/UPS 基础词条（UPS 旁路细节回手册46 AS）。  
11. **[DMR Association · Standards](https://www.dmrassociation.org/dmr-standards.html)** · **[首页](https://www.dmrassociation.org/)**——空中接口标准入口（**不规定**列头末端配电台账）。  
12. **[Tait Radio Academy](https://www.taitradioacademy.com/)** · **[Tait Communications](https://www.taitcommunications.com/)** · **[Hytera](https://www.hytera.com/)** · **[Motorola Solutions](https://www.motorolasolutions.com/)** · **[Sepura](https://www.sepura.com/)**——专网厂商公开入口。

**故事类比：医院手术室/ICU 保供电机房列头柜与末端配电（只借直觉，不是台站法定依据）**  
13. **[Wikipedia · Operating room](https://en.wikipedia.org/wiki/Operating_room)** · **[Intensive care unit](https://en.wikipedia.org/wiki/Intensive_care_unit)**——手术室/ICU 直觉（借「指示灯绿≠支路准用、标签在≠窗过、口头测过电≠方法过、AF 过≠AW 过、AS 过≠AW 过、AD 过≠本期实测过、N 绿≠AW 过、AQ 过≠AW 过」）。  
14. Wikipedia：[Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio) · [Land mobile radio system](https://en.wikipedia.org/wiki/Land_mobile_radio_system) · [Noise floor](https://en.wikipedia.org/wiki/Noise_floor)。

**国内无线电法规（台站秩序指针；无账乱签列头末端不是法外）**  
15. **[《中华人民共和国无线电管理条例》（中国政府网）](https://www.gov.cn/zhengce/zhengceku/2016-11/25/content_5137687.htm)** · **[国务院公报版](https://www.gov.cn/gongbao/content/2016/content_5148745.htm)**。  
16. **[《无线电频率使用许可管理办法》（中国政府网）](https://www.gov.cn/zhengce/2022-08/23/content_5722706.htm)**。  
17. **[《地面无线电台（站）管理规定》（中国政府网）](https://www.gov.cn/zhengce/202310/content_6908889.htm)** · **[国务院公报 · 工信部令第60号](https://www.gov.cn/gongbao/content/2023/content_5745291.htm)**。

**ITU / 验收方法级**  
18. **[ITU-R SM.1753](https://www.itu.int/rec/R-REC-SM.1753/en)** · **[ITU-R Monitoring](https://www.itu.int/en/ITU-R/terrestrial/monitoring/Pages/default.aspx)**。  
19. **[P25 Best Practice · Field Acceptance Tests](https://www.p25bestpractice.com/implementing/field-acceptance-tests/)** · **[Flowdit · SAT](https://flowdit.com/site-acceptance-test/)**——到站/现场合格与公开入口（合格步骤≠假绿）。

**视频（YouTube，已用 oEmbed 核验标题与频道）**  
20. **[Raritan · PX Series of Intelligent Rack PDUs](https://www.youtube.com/watch?v=foXPx8Jehcs)**——机架 PDU 公开片（借「进线/支路计量、支路过载预警有产品角色」；**不是** AW 台账专项；机型以本网授权书面为准）。  
21. **[clabretro · Enterprise Power Distribution Units](https://www.youtube.com/watch?v=nOBoWs438yI)**——企业级 PDU 公开片（借「机架配电有角色要认得」；**不是** AW 台账专项）。  
22. **[ICP DAS · How This Data Center Automated 24/7 Monitoring](https://www.youtube.com/watch?v=bkyU2Qh88pw)**——机房 24/7 监测公开片（借「配电/环境要有监测留痕」；**不教绕联锁**）。  
23. **[MPSCS · Site Maintenance Inspection and Preventative Maintenance](https://www.youtube.com/watch?v=4IRdxeXN1do)**——站点维护与记录（借「要巡要记」）。  
24. **[Engineered Vision · FAT and SAT Explained](https://www.youtube.com/watch?v=x7qNC6Rtp9I)** · **[Careers360 · FAT & SAT](https://www.youtube.com/watch?v=3aafLF9o0NA)**——出厂/到站合格直觉（回指：假绿≠会签）。  
25. **[Scanner School · What is DMR?](https://www.youtube.com/watch?v=aQX_JbTbXuY)**（弱项：时隙与数字话音）。  
26. **[Rohde & Schwarz · Understanding Spectrum Analyzers – ACLR](https://www.youtube.com/watch?v=mco_BJ1mjNo)**——频谱仪直觉；对照禁功率战。  
27. **[NATEsafety · How to Conduct Tower Inspections](https://www.youtube.com/watch?v=dFs4At6-hhU)** · **[Sunil Kashyap · How to perform site audit or RF audit](https://www.youtube.com/watch?v=7Awj0-rDfeA)**——巡检/审计通用视频。

> **诚实说明**：没有找到「DMR 专网机房列头柜与末端配电巡检交底台账（含贴纸 AW + 插页 AW1–AW8 + 医院手术室/ICU 保供电机房列头末端隐喻 + 拒签卡 + 与 AF/AS/AD/N 分工表）」的专项中文公开视频或制度文章；上文最贴题的是 **Wikipedia PDU**、**POPProbe PDU 巡检清单**、**Anvilfield PDU/RPP 调试指南**、**Energy Compere 支路监测**、**TestGuy/Titan Power PDU 维护文**、**Raritan/企业级 PDU 公开视频**，以及站点维护/FAT-SAT/DMR 基础视频。其余为国内无线电法规与 DMR/ITU 入口。需按贴纸 AW 与 AW1–AW8 拼进本网流程。`video_found=true`（机架 PDU 产品片 + 企业级 PDU + 机房监测 + 通用巡检/FAT-SAT/DMR 基础），**非** AW 台账专项。部分境外站点（如部分 Flir/Eaton PDF/个别厂商页）在核验出口偶发 403/失败，本篇以已 200/oEmbed 通过的链接为准。任何「教你如何绕过电气安全联锁」「如何未授权带电违章」「如何伪造配电巡检台账」「如何抬功率压配电告警」的页面即使 200，本篇也**不引用**。

**库内必回：** 手册33（AF）、46（AS）、31（AD）、41（AN）、28（AA）、15（N）、44（AQ）、49（AV）、45（AR）、36（AI）、47（AT）、48（AU）、42（AO）、34（AG）、43（AP）、39（AL）、19（R）、06（脱敏）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子
- 贴纸 **AW** 五子类：列 / 末 / 巡 / 验 / 治——双字母续写的第二十三张，负责列头柜与末端配电「台账清不清、末端有没有窗、巡检有没有法、本期过了没有」。  
- 口诀：**列头有账，末端有窗，巡检有法，会签才放。**  
- 故事：医院手术室/ICU 保供电机房列头柜与末端配电——指示灯绿≠支路准用；标签在≠窗过；口头说测过电≠方法过。  
- 八条硬规则：**列头柜台账钉死**；**末端配电有主有窗有方法/准用期**；**巡检窗与方法钉死**；**本组本机房本期实测禁套他站他期**；**会签才放行「列头柜与末端配电巡检准用」**；**禁顶替 AF/AS/AD/AN/AA/N/AQ/AV/AR/AI/AT/AU/AO/AG/AP/AL 等，主贴 AW，假绿≠放行挂 R**；**列头/末端/配电异常风暴挂 N、配电策略/门限/巡检规程变更走 J、禁功率战、禁绕电气安全联锁、禁未授权带电违章**；**脱敏 L3**。  
- **AW 不替代 AF，也不替代 AS，也不替代 AD**：AF=油机市电切换与供电巡检；AS=UPS 旁路；AD=备件仪表准用；AW=列头柜与末端配电巡检交底准用。

### 11.2 下一篇手册候选（本篇不写正文）
- **机房精密空调压缩机与制冷剂边界交底台账**（与 AI 温湿度、AT 冷凝加湿、AU 滤网压差气流、N 监控、AN 门禁咬合）  
- **机房新风正压与防火阀交底台账**（与 AI 温湿度、AL 气灭、AU 气流、N 监控、AN 门禁咬合）  
- **机房冷通道封闭与机柜进出风交底台账**（与 AU 滤网压差气流、AI 温湿度、AO 漏水、N 监控、AN 门禁咬合）

### 11.3 给带新人的三句话
1. 列头不是指示灯绿就能签：列头有账，本期回路核对钉死。  
2. 末端不是标签在就算过、巡检不是口头说测过电就算过：主人窗方法准用期，巡检书面方法，本期实测会签才算准用。  
3. 假绿挂 R；主贴 AW；AF/AS/AD/N 不顶替；异常窗禁功率战禁绕联锁禁未授权带电违章；公开脱敏 L3。

### 11.4 一张图记住本篇（收工贴纸）
```text
  ┌────────── 贴纸 AW ──────────┐
  │ 列 列头台账钉死             │
  │ 末 末端有主有窗有方法       │
  │ 巡 巡检窗·方法钉死         │
  │ 验 本期实测·禁套·会签       │
  │ 治 假绿顶替套票绕联锁功率战 │
  └────────────────────────────┘
    指示灯绿≠支路准用 · 标签在≠窗过 · 口头测过电≠方法过 · 假绿≠准用
    AF≠AW（油机市电 ≠ 列头末端）
    AS≠AW（UPS旁路 ≠ 列头末端）
    AD≠AW（仪表入库 ≠ 本期实测）
    N≠AW（风暴秩序 ≠ 本期实测）
    AQ≠AW（巡检视频 ≠ 列头准用）
```

---

## 12. 本篇检查清单（自学打勾）
- [ ] 能背贴纸 AW 五子类与医院手术室/ICU 保供电机房列头柜与末端配电故事  
- [ ] 能背口诀：列头有账，末端有窗，巡检有法，会签才放  
- [ ] 能背八条硬规则（列头台账钉死、末端有主窗方法、巡检窗方法、本期实测、会签才放、禁顶替假绿挂R、禁功率战禁绕联锁禁未授权带电违章挂N走J、L3）  
- [ ] 能分清 AW 与 AF / AS / AD / N / AN / AQ / R / J 边界  
- [ ] 会填插页 AW1–AW8 与台账卡封面/列/末/巡/验/会签页  
- [ ] 会用拒签卡卡住无账、套票、顶替、假绿、绕联锁、未授权带电违章  
- [ ] 自测 12 题过关；知道 video_found=true 但是非 AW 台账专项  
- [ ] 回库用 L3 对一遍最近一次列头柜与末端配电巡检交底：台账、窗、方法、本期实测、会签、拒签项  
- [ ] 弱项短补记得：12.5 kHz / 4FSK / 2-slot TDMA；告警窗禁功率战  
- [ ] 知道下一篇三个候选（压缩机与制冷剂边界 / 新风正压与防火阀 / 冷通道封闭与机柜进出风）尚未写正文  

---

*手册50 · 贴纸 AW · 2026-11-02 晚间推送（Asia/Shanghai）· 教学用 · L3*
