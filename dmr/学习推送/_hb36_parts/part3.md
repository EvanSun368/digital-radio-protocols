## 8. 术语表（本篇约 18 词）+ 易错观念

| 术语 | 一句话（教学） |
|------|----------------|
| **温湿度台账** | 测点、采集频率、报警门限的书面入账 |
| **测点** | 机房温湿度传感器位置角色 |
| **精密空调 / CRAC** | 机房专用温湿度控制单元（公开常识词） |
| **联锁** | 高温/高湿/主备/消防等联动逻辑角色项 |
| **准用期** | 滤网、加湿、传感器校准等到期前可用 |
| **AI-温** | 温湿度台账与测点/频率钉死 |
| **AI-湿** | 精密空调/湿度侧有主人有准用期 |
| **AI-联** | 联锁巡检窗与方法、到场齐全 |
| **AI-验** | 本组本机房本期实测禁套 |
| **AI-治** | 假绿、顶替、套曲线、功率战、旁路、泄密治理 |
| **假绿** | 系统/大屏显示正常，但无本期联锁会签 |
| **套曲线** | 把他站他期记录改号当本期 |
| **旁路联锁** | 为消音或省事绕过联锁动作（本篇严禁） |
| **九字环境钉** | 温湿窗法房仪签闭密（教学记忆） |
| **与 AF/AA/AG 分工** | 供电 / 首年日历 / 电池；AI 管温湿度联锁门卫 |
| **降额** | 过热时设备主动或被动降低能力（教学词） |
| **手术室隐喻** | 感觉不热≠台账过；联锁要有书面主人与窗 |
| **上行更脆** | 环境恶化时常先伤可用性与上行体验 |

**易错观念**

- ❌「网管环境绿=联锁过」→ ✅ 假绿挂 R，主贴 AI。  
- ❌「AF/AA/AG 签=永远不用贴 AI」→ ✅ 均不顶替 AI 本期。  
- ❌「电池抽检绿=环境联锁过」→ ✅ AG≠AI。  
- ❌「拷邻站曲线更快」→ ✅ 禁套；本窗本组本机房实测。  
- ❌「高温告警就抬功率」→ ✅ 禁功率战；先 AI/N。  
- ❌「联锁响了先旁路」→ ✅ 禁旁路；挂整改。

---

## 9. 自测（12 题）+ 参考答案

1. 贴纸 AI 五个子类是什么？各用四个字以内说明。  
2. 医院手术室/药库温湿度联锁故事里，「感觉不热≠台账过」主要对应 AI 哪一段？  
3. 八条硬规则里，哪一条要求温湿度台账与测点/频率钉死？  
4. 为什么高温高湿窗要「先问环境再开射频工单」？与 12.5 kHz / 4FSK / 2-slot 及上行、电池（AG）有什么关系？  
5. 「温湿度/联锁准用」至少要具备哪几样（九字环境钉里不可砍的）？  
6. 用 AF 供电签或 AA 首年签或 AG 电池签顶掉本期温湿度联锁，违反哪条？主贴谁？  
7. AI 与 AF / AA / AG / N 的分工一句话？  
8. 套邻站曲线或假绿想签准用，主贴什么？能不能改机房号交差？  
9. 大屏环境全绿想签联锁准用，应挂什么提醒？主贴谁？  
10. 电池抽检 AG 绿了，能不能代替 AI 温湿度联锁准用？  
11. 私自换精密空调或改采集频率/联锁逻辑后应走什么变更贴纸并怎样处理？  
12. 公开材料能不能贴真实机房全称与空调序列号？依据哪条规则？

### 参考答案

1. **温**（温湿度台账测点）、**湿**（空调主人准用期）、**联**（联锁窗与方法）、**验**（本期本组实测）、**治**（假绿顶替套曲线功率战旁路泄密）。  
2. **AI-温**（亦可答湿：无主人则联锁不清）。  
3. **规则1**。  
4. 过热过湿可致降额、误告警、电池寿命缩短（挂 AG）；上行更先伤可用性；空口台阶（12.5 kHz/4FSK/2-slot）没变，先证环境/联锁再谈射频，避免误开功率战。  
5. **温湿度台账、空调联锁主人、本组本机房本期实测、会签**（规则1–5；九字钉核心）。  
6. **规则6**；主贴仍是 **AI**。  
7. **AF 供电切换、AA 首年日历、AG 电池梯队、N 监控风暴、AI 管温湿度·联锁能不能签准用**。  
8. **AI-治**（验）；**不能**。  
9. 挂 **R**；主贴 **AI**（规则6）。  
10. **不能**；电池抽检≠温湿度联锁准用。  
11. **J**，并重开 AI 联锁/验收窗（规则7；常挂 N/AF/AG）。  
12. **不能**；**规则8 脱敏 L3**。

---

## 10. 加深阅读与视频（均已用 curl / oEmbed 核对；以核验当时为准）

**本篇专项方法级阅读（精密空调/CRAC/数据中心环境；借秩序，不替代本网 AI 签字）**  
1. **[Wikipedia · Computer room air conditioner](https://en.wikipedia.org/wiki/Computer_room_air_conditioner)** · **[Data center environmental control](https://en.wikipedia.org/wiki/Data_center_environmental_control)** · **[Data center](https://en.wikipedia.org/wiki/Data_center)** · **[Raised floor](https://en.wikipedia.org/wiki/Raised_floor)**——机房精密空调与环境控制词条。  
2. **[Wikipedia · HVAC](https://en.wikipedia.org/wiki/HVAC)** · **[Air conditioning](https://en.wikipedia.org/wiki/Air_conditioning)** · **[Psychrometrics](https://en.wikipedia.org/wiki/Psychrometrics)** · **[Relative humidity](https://en.wikipedia.org/wiki/Relative_humidity)** · **[Dew point](https://en.wikipedia.org/wiki/Dew_point)** · **[Hygrometer](https://en.wikipedia.org/wiki/Hygrometer)** · **[Thermostat](https://en.wikipedia.org/wiki/Thermostat)** · **[Chiller](https://en.wikipedia.org/wiki/Chiller)** · **[Free cooling](https://en.wikipedia.org/wiki/Free_cooling)**——温湿度与暖通基础词条。  
3. **[Wikipedia · Building management system](https://en.wikipedia.org/wiki/Building_management_system)** · **[Building automation](https://en.wikipedia.org/wiki/Building_automation)** · **[SCADA](https://en.wikipedia.org/wiki/SCADA)** · **[Direct digital control](https://en.wikipedia.org/wiki/Direct_digital_control)** · **[Interlock (engineering)](https://en.wikipedia.org/wiki/Interlock_(engineering))** · **[Environmental monitoring](https://en.wikipedia.org/wiki/Environmental_monitoring)**——联锁与楼宇监控直觉。  
4. **[TechTarget · Mechanical refrigeration primer for admins](https://www.techtarget.com/it-infrastructure/feature/A-mechanical-refrigeration-system-primer-for-admins)**——CRAC/CRAH 制冷直觉公开文（**不是**本网 AI 法定制度）。  
5. **[MEP Academy · CRAC vs CRAH](https://mepacademy.com/crac-vs-crah-units-explained-data-center-cooling/)** · **[Behind The Tech · CRAC](https://behindthetech.in/learn/non-it/cooling/crac)** · **[Data Center Knowledge · Crash Course in CRAC Cooling](https://www.datacenterknowledge.com/cooling/a-crash-course-in-crac-cooling)**——精密空调公开科普。  
6. **[OSU Extension · Inside data centers](https://extension.oregonstate.edu/catalog/em-9913-inside-data-centers-what-they-do-how-they-operate-why-more-are-being-built)**——数据中心气候控制公开概述。  
7. **[ASHRAE · Datacom Series](https://www.ashrae.org/technical-resources/bookstore/datacom-series)** · **[ASHRAE TC 9.9](https://tc0909.ashraetcs.org/)** · **[ASHRAE 首页](https://www.ashrae.org/)**——数据中心热环境公开入口（**境外行业资料教学类比，非中国专网法定依据**；门限以本网规程为准）。  
8. **[Vertiv · Thermal management](https://www.vertiv.com/en-us/products-catalog/thermal-management/)** · **[APC · Data center cooling](https://www.apc.com/us/en/solutions/system/data-center-cooling.cfm)** · **[Schneider Electric · Data centers](https://www.schneider-electric.com/en/work/solutions/for-business/data-centers-and-networks/)** · **[STULZ](https://www.stulz.com/)** · **[Uptime Institute Journal](https://journal.uptimeinstitute.com/)** · **[ENERGY STAR · Data center equipment](https://www.energystar.gov/products/data_center_equipment)** · **[U.S. DOE · Data centers and servers](https://www.energy.gov/eere/buildings/data-centers-and-servers)**——厂商/能效公开入口（借「环境要管、要记」）。  
9. **[DMR Association · Standards](https://www.dmrassociation.org/dmr-standards.html)** · **[首页](https://www.dmrassociation.org/)** · **[TS 102 361-1 PDF](https://dmrassociation.org/public-downloads/standards/ts_10236101v020701p.pdf)**——空中接口标准入口（**不规定**温湿度联锁台账）。  
10. **[Tait Radio Academy](https://www.taitradioacademy.com/)** · **[Tait Communications](https://www.taitcommunications.com/)** · **[Hytera](https://www.hytera.com/)** · **[Motorola Solutions](https://www.motorolasolutions.com/)** · **[Sepura](https://www.sepura.com/)**——专网厂商公开入口。

**故事类比：医院手术室/药库温湿度联锁（只借直觉，不是台站法定依据）**  
11. **[Wikipedia · Operating theater](https://en.wikipedia.org/wiki/Operating_theater)** · **[Pharmacy](https://en.wikipedia.org/wiki/Pharmacy)** · **[Cold chain](https://en.wikipedia.org/wiki/Cold_chain)** · **[Facility management](https://en.wikipedia.org/wiki/Facility_management)** · **[Preventive maintenance](https://en.wikipedia.org/wiki/Preventive_maintenance)** · **[Fire alarm system](https://en.wikipedia.org/wiki/Fire_alarm_system)** · **[Smoke detector](https://en.wikipedia.org/wiki/Smoke_detector)**——手术室/药库环境与设施维护直觉（借「测点要记、联锁要验」）。  
12. **[STERIS · SONICU Environmental Monitoring](https://www.steris.com/healthcare/products/or-environment/sonicu-environmental-monitoring-system)**——手术室环境连续监测公开产品页（**故事类比，非无线电法定依据**）。  
13. Wikipedia：[Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio) · [Land mobile radio system](https://en.wikipedia.org/wiki/Land_mobile_radio_system) · [Battery (electricity)](https://en.wikipedia.org/wiki/Battery_(electricity)) · [Noise floor](https://en.wikipedia.org/wiki/Noise_floor) · [Uninterruptible power supply](https://en.wikipedia.org/wiki/Uninterruptible_power_supply)。

**国内无线电法规（台站秩序指针；无环境乱签准用不是法外）**  
14. **[《中华人民共和国无线电管理条例》（中国政府网）](https://www.gov.cn/zhengce/zhengceku/2016-11/25/content_5137687.htm)** · **[国务院公报版](https://www.gov.cn/gongbao/content/2016/content_5148745.htm)**。  
15. **[《无线电频率使用许可管理办法》（中国政府网）](https://www.gov.cn/zhengce/2022-08/23/content_5722706.htm)**。  
16. **[《地面无线电台（站）管理规定》（中国政府网）](https://www.gov.cn/zhengce/202310/content_6908889.htm)** · **[国务院公报 · 工信部令第60号](https://www.gov.cn/gongbao/content/2023/content_5745291.htm)**。

**ITU / 验收方法级**  
17. **[ITU-R SM.1753](https://www.itu.int/rec/R-REC-SM.1753/en)** · **[ITU-R Monitoring](https://www.itu.int/en/ITU-R/terrestrial/monitoring/Pages/default.aspx)**。  
18. **[P25 Best Practice · Field Acceptance Tests](https://www.p25bestpractice.com/implementing/field-acceptance-tests/)** · **[Flowdit · SAT](https://flowdit.com/site-acceptance-test/)** · **[IEEE Standards](https://standards.ieee.org/)** · **[NIST](https://www.nist.gov/)**——到站/现场合格与计量直觉（合格步骤≠假绿）。  
19. **[Rohde & Schwarz · EMF testing](https://www.rohde-schwarz.com/us/solutions/electronics-testing/emc-testing/emf-testing/emf-testing_253445.html)**——仪器公开入口。

**视频（YouTube，已用 oEmbed 核验标题与频道）**  
20. **[HVAC On Air · Inside a Full-Scale Demo Surgery Suite: Healthcare HVAC](https://www.youtube.com/watch?v=07w5nqhLk4g)**——医院手术室暖通公开讲解（借「手术室温湿度要管」故事类比；**不是** AI 台账专项）。  
21. **[Professor Butler HVAC · Surgical suite HVAC in a hospital](https://www.youtube.com/watch?v=XlQ6YOwSQcY)**——医院手术室 HVAC 现场向（故事类比）。  
22. **[Johnson Controls · Deep Dive Into Critical Environment Controls](https://www.youtube.com/watch?v=4fNs1MjNXIk)**——关键环境监控公开讲解（借「环境要连续监测」；门限以本网为准）。  
23. **[MPSCS · Site Maintenance Inspection and Preventative Maintenance](https://www.youtube.com/watch?v=4IRdxeXN1do)**——站点维护与记录（借「要巡要记」）。  
24. **[Engineered Vision · FAT and SAT Explained](https://www.youtube.com/watch?v=x7qNC6Rtp9I)** · **[Careers360 · FAT & SAT](https://www.youtube.com/watch?v=3aafLF9o0NA)**——出厂/到站合格直觉（回指：假绿≠会签）。  
25. **[Scanner School · What is DMR?](https://www.youtube.com/watch?v=aQX_JbTbXuY)**（弱项：时隙与数字话音）。  
26. **[NATEsafety · How to Conduct Tower Inspections](https://www.youtube.com/watch?v=dFs4At6-hhU)** · **[Sunil Kashyap · How to perform site audit or RF audit](https://www.youtube.com/watch?v=7Awj0-rDfeA)**——巡检/审计通用视频。  
27. **[Rohde & Schwarz · Understanding Spectrum Analyzers – ACLR](https://www.youtube.com/watch?v=mco_BJ1mjNo)**——频谱仪直觉。

> **诚实说明**：没有找到「DMR 专网机房温湿度与空调联锁巡检制度（含贴纸 AI + 插页 AI1–AI8 + 医院手术室/药库温湿度联锁隐喻 + 拒签卡 + 与 AF/AA/AG 分工表）」的专项中文公开视频或制度文章；上文最贴题的是 **CRAC/数据中心环境控制公开词条与科普文**、**ASHRAE Datacom/厂商热管理公开入口**、**医院手术室 HVAC/关键环境监控视频（故事类比）**，以及站点维护/FAT-SAT/DMR 基础视频。其余为国内无线电法规与 DMR/ITU 入口。需按贴纸 AI 与 AI1–AI8 拼进本网流程。`video_found=true`（医院手术室 HVAC + 关键环境监控 + 通用巡检/FAT-SAT/DMR 基础），**非** AI 台账专项。部分境外站点（如部分 Uptime 根域、部分 MIIT/ISO 首页）在核验出口偶发 302/403，本篇以已 200/oEmbed 通过的链接为准。任何「教你如何伪造温湿度账」「如何套邻站曲线过关」「如何抬功率压高温告警」「如何旁路联锁消音」「如何绕过告警」的页面即使 200，本篇也**不引用**。

**库内必回：** 手册33（AF）、28（AA）、34（AG）、15（N）、19（R）、31（AD）、06（脱敏）、35（AH）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子
- 贴纸 **AI** 五子类：温 / 湿 / 联 / 验 / 治——双字母续写的第九张，负责温湿度·联锁·巡检「台账清不清、联锁有没有主、本期过了没有」。  
- 故事：医院手术室/药库温湿度联锁 + 机房精密空调联锁巡检——感觉不热≠台账过；网管绿≠联锁过；套邻站曲线=拒签；AF/AA/AG 不顶替 AI；假绿≠会签放行。  
- 阶段梯：建温湿度账 → 钉空调主人 → 联锁窗钉死 → 本期实测 → 会签放行 → 变更再验。  
- 八条硬规则：**温湿度台账与测点/频率钉死**；**空调联锁有主人有准用期**；**联锁巡检窗与方法钉死**；**本组本机房本期实测禁套他站他期**；**会签才放行**；**禁顶替 AF/AA/AG/N 等，主贴 AI，假绿≠放行挂 R**；**告警窗禁功率战、监控风暴挂 N、变更走 J**；**脱敏 L3**。

### 11.2 下一篇手册候选（本篇不写正文）
- **天线驻波与跳线老化抽检台账**（与巡检/复测、AD 备件咬合）  
- **铁塔/桅杆爬塔作业与第三方交叉施工界面**（与安全交底、变更 J、监控 N 咬合）  
- **机房消防气灭与应急疏散联锁交底**（与联锁 AI、变更 J、夜班交班咬合）

### 11.3 给带新人的三句话
1. 温湿度不是感觉不热就能签：测点有账，频率钉死，本期实测。  
2. 网管绿不是联锁过：书面联锁窗与方法，会签才算准用。  
3. 假绿挂 R；主贴 AI；AF/AA/AG 不顶替；告警窗禁功率战禁旁路；公开脱敏 L3。

### 11.4 一张图记住本篇（收工贴纸）
```text
  ┌────────── 贴纸 AI ──────────┐
  │ 温 温湿度台账·测点频率钉死 │
  │ 湿 空调主人·准用期钉死     │
  │ 联 联锁窗·方法·到场钉死   │
  │ 验 本期实测·禁套他站他期   │
  │ 治 假绿顶替套曲线功率战旁路 │
  └────────────────────────────┘
    手术室不摸额头 · 假绿≠准用
```

---

## 12. 本篇检查清单（自学打勾）
- [ ] 能背贴纸 AI 五子类与医院手术室/药库温湿度联锁故事  
- [ ] 能画 建温湿度账→钉空调主人→联锁窗→实测→会签→变更再验 阶段梯  
- [ ] 能背八条硬规则（温湿度台账、空调主人准用期、联锁窗方法、本期实测、会签才放、禁顶替假绿挂R、禁功率战挂N走J、L3）  
- [ ] 能背九字环境钉，并能讲清为什么高温高湿窗要先问环境（上行更脆、电池挂 AG）  
- [ ] 会填插页 AI1–AI8、拒签卡与温湿度/联锁台账卡  
- [ ] 能说出 AI 与 AF/AA/AG/N 分工，以及假绿/套曲线/旁路联锁三种拒签  
- [ ] 12 题自测过关  
- [ ] 知道 §10 诚实说明：无专项 AI 台账视频，仅 CRAC/环境控制公开文 + 医院 HVAC 视频 + 通用巡检视频  
- [ ] 回库用 L3 重对一次本网最近机房温湿度巡检或空调联锁演练：温湿度账、空调主人、联锁窗、本期实测、会签、未闭项

---

*手册36 · 机房温湿度与空调联锁巡检边界 · 学习推送 · 2026-10-26 18:52 +08:00*
