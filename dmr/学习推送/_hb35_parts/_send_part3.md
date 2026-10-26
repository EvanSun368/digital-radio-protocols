## 9. 自测（12 题）+ 参考答案

1. 贴纸 AH 五个子类是什么？各用四个字以内说明。  
2. 合用电梯机房「谁按谁修」故事里，「柜里有≠界面清」主要对应 AH 哪一段？  
3. 八条硬规则里，哪一条要求合路/POI 台账与业主界面钉死？  
4. 为什么合路窗要「先问界面再开射频工单」？与 12.5 kHz / 4FSK / 2-slot 及上行有什么关系？  
5. 「合路/POI 界面准用」至少要具备哪几样（九字合路钉里不可砍的）？  
6. 用 S 邻频签或 AE 区间签或 T 投诉签顶掉本期合路界面，违反哪条？主贴谁？  
7. AH 与 S / AE / T 的分工一句话？  
8. 套邻业主曲线或单边绿冒充整段，主贴什么？能不能改端口号交差？  
9. 大屏网管全绿想签界面准用，应挂什么提醒？主贴谁？  
10. 室分复测 AB 绿了，能不能代替 AH 合路界面准用？  
11. 私自增业主端口或改合路衰减后应走什么变更贴纸并怎样处理？  
12. 公开材料能不能贴真实业主单位名与机房全称？依据哪条规则？

### 参考答案

1. **合**（合路台账端口）、**界**（界面主人边界）、**诊**（分诊窗与方法）、**验**（本期本组实测）、**治**（假绿顶替套曲线功率战泄密）。  
2. **AH-合**（亦可答界：无主人则界面不清）。  
3. **规则1**。  
4. 合路/PIM/隔离不足常先抬上行底噪；上行更先掉；空口台阶（12.5 kHz/4FSK/2-slot）没变，先证界面/分诊再谈射频，避免误开功率战。  
5. **合路台账、界面主人、本组本机房本期实测、会签**（规则1–5；九字钉核心）。  
6. **规则6**；主贴仍是 **AH**。  
7. **S 邻频边界、AE 区间换乘、T 投诉证据、AH 管合路·界面·分诊能不能签准用**。  
8. **AH-治**（验）；**不能**。  
9. 挂 **R**；主贴 **AH**（规则6）。  
10. **不能**；室分复测≠合路界面准用。  
11. **J**，并重开 AH 分诊/验收窗（规则7；常挂 S/T/N）。  
12. **不能**；**规则8 脱敏 L3**。

---

## 10. 加深阅读与视频（均已用 curl / oEmbed 核对；以核验当时为准）

**本篇专项方法级阅读（DAS/POI/合路/PIM；借秩序，不替代本网 AH 签字）**  
1. **[SYMAIR · Point of Interface, DAS POI](https://www.symair.com/products/point-of-interface/)**——POI 如何汇合多运营商信号、监测口与合路直觉公开页（厂商向；**不是**本网 AH 法定制度）。  
2. **[Anritsu · Passive Intermodulation (PIM) in In-Building DAS（PDF）](https://dl.cdn-anritsu.com/en-us/test-measurement/files/Application-Notes/Application-Note/11410-00871B.pdf)**——室分中 PIM 与插入损耗直觉（**只借「合路处要当心非线性」**；门限以本网规程为准）。  
3. **[VIAVI · DAS Deployment Overview（PDF）](https://www.viavisolutions.com/en-us/literature/das-deployment-overview-streamlined-approaches-das-deployments-application-notes-en.pdf)**——DAS 部署与连接扭矩/低 PIM 施工公开摘要。  
4. **[AusDAS · MCF Design Specification for DAS 2022（PDF）](https://www.ausdas.dasworks.com.au/mcf2022.pdf)** · **[AMTA · MCF Design Guidelines for DAS Draft（PDF）](https://amta.org.au/wp-content/uploads/2024/10/MCF-Design-Guidelines-for-Distributed-Antenna-Systems-Draft-2.0-IBC-Workgroup-11092024-1.pdf)**——多网络合路（MNC）端口、终止负载与 PIM 抑制公开设计指引（**境外行业指引教学类比，非中国专网法定依据**）。  
5. **[SYNC · Distributed Antenna Systems Construction Standard · POI and Combining](https://synergyinconstruction.com/wiki/sync/distributed-antenna-systems)**——POI 为责任分界、监测口与合路额定功率公开条文（借「界面要写下来」）。  
6. **[Wikipedia · Distributed antenna system](https://en.wikipedia.org/wiki/Distributed_antenna_system)** · **[Passive intermodulation](https://en.wikipedia.org/wiki/Passive_intermodulation)** · **[Intermodulation](https://en.wikipedia.org/wiki/Intermodulation)** · **[Duplexer](https://en.wikipedia.org/wiki/Duplexer)** · **[Combiner](https://en.wikipedia.org/wiki/Combiner)** · **[Coaxial cable](https://en.wikipedia.org/wiki/Coaxial_cable)** · **[Noise floor](https://en.wikipedia.org/wiki/Noise_floor)** · **[Standing wave ratio](https://en.wikipedia.org/wiki/Standing_wave_ratio)** · **[RSSI](https://en.wikipedia.org/wiki/Received_signal_strength_indication)** · **[Spectrum analyzer](https://en.wikipedia.org/wiki/Spectrum_analyzer)**——室分/合路/互调/底噪基础词条。  
7. **[DMR Association · Standards](https://www.dmrassociation.org/dmr-standards.html)** · **[首页](https://www.dmrassociation.org/)** · **[TS 102 361-1 PDF](https://dmrassociation.org/public-downloads/standards/ts_10236101v020701p.pdf)**——空中接口标准入口（**不规定**合路界面台账）。  
8. **[Tait Radio Academy](https://www.taitradioacademy.com/)** · **[Tait Communications](https://www.taitcommunications.com/)** · **[Hytera](https://www.hytera.com/)** · **[Motorola Solutions](https://www.motorolasolutions.com/)** · **[Sepura](https://www.sepura.com/)**——专网厂商公开入口。

**故事类比：合用电梯机房 / 合用配电间责任界面（只借直觉，不是台站法定依据）**  
9. **[Wikipedia · Elevator](https://en.wikipedia.org/wiki/Elevator)** · **[Facility management](https://en.wikipedia.org/wiki/Facility_management)** · **[Preventive maintenance](https://en.wikipedia.org/wiki/Preventive_maintenance)**——设施合用与预防性维护直觉（借「谁按谁修要有书面主人」）。  
10. Wikipedia：[Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio) · [Land mobile radio system](https://en.wikipedia.org/wiki/Land_mobile_radio_system)。

**国内无线电法规（台站秩序指针；无合路乱签界面不是法外）**  
11. **[《中华人民共和国无线电管理条例》（中国政府网）](https://www.gov.cn/zhengce/zhengceku/2016-11/25/content_5137687.htm)** · **[国务院公报版](https://www.gov.cn/gongbao/content/2016/content_5148745.htm)**。  
12. **[《无线电频率使用许可管理办法》（中国政府网）](https://www.gov.cn/zhengce/2022-08/23/content_5722706.htm)**。  
13. **[《地面无线电台（站）管理规定》（中国政府网）](https://www.gov.cn/zhengce/202310/content_6908889.htm)** · **[国务院公报 · 工信部令第60号](https://www.gov.cn/gongbao/content/2023/content_5745291.htm)**。  
14. **[无线电管理局政策法规入口](https://www.miit.gov.cn/jgsj/wgj/zcfg/index.html)**（部分 MIIT 首页出口偶发 403，以可访问为准）。

**ITU / 验收方法级**  
15. **[ITU-R SM.1753](https://www.itu.int/rec/R-REC-SM.1753/en)** · **[ITU-R Monitoring](https://www.itu.int/en/ITU-R/terrestrial/monitoring/Pages/default.aspx)**。  
16. **[P25 Best Practice · Field Acceptance Tests](https://www.p25bestpractice.com/implementing/field-acceptance-tests/)** · **[Flowdit · SAT](https://flowdit.com/site-acceptance-test/)**——到站/现场合格直觉（合格步骤≠假绿）。

**测量相关公开资料（看懂「诊与记」，不是造假教程）**  
17. **[Rohde & Schwarz · EMF testing](https://www.rohde-schwarz.com/us/solutions/electronics-testing/emc-testing/emf-testing/emf-testing_253445.html)**——仪器公开入口。  
18. Wikipedia：[Multiplexer](https://en.wikipedia.org/wiki/Multiplexer)——合路/分路相关词条入口。

**视频（YouTube，已用 oEmbed 核验标题与频道）**  
19. **[Electronics Notes · Testing and Locating Passive Intermodulation PIM](https://www.youtube.com/watch?v=HU4y4HxbZRY)**——PIM 测试与定位公开讲解（借「合路处非线性要查」；**不是** AH 台账专项，门限以本网规程为准）。  
20. **[Shure · What is Intermodulation?](https://www.youtube.com/watch?v=IrlyAei02_o)**——互调基础（对照禁功率战、先分诊）。  
21. **[Rohde & Schwarz · Understanding Spectrum Analyzers – ACLR](https://www.youtube.com/watch?v=mco_BJ1mjNo)**——频谱仪/邻道直觉。  
22. **[MPSCS · Site Maintenance Inspection and Preventative Maintenance](https://www.youtube.com/watch?v=4IRdxeXN1do)**——站点维护与记录（借「要巡要记」）。  
23. **[Engineered Vision · FAT and SAT Explained](https://www.youtube.com/watch?v=x7qNC6Rtp9I)** · **[Careers360 · FAT & SAT](https://www.youtube.com/watch?v=3aafLF9o0NA)**——出厂/到站合格直觉（回指：假绿≠会签）。  
24. **[Scanner School · What is DMR?](https://www.youtube.com/watch?v=aQX_JbTbXuY)**（弱项：时隙与数字话音）。  
25. **[NATEsafety · How to Conduct Tower Inspections](https://www.youtube.com/watch?v=dFs4At6-hhU)** · **[Sunil Kashyap · How to perform site audit or RF audit](https://www.youtube.com/watch?v=7Awj0-rDfeA)**——巡检/审计通用视频。

> **诚实说明**：没有找到「DMR 专网多业主合路/POI 机房责任界面与干扰分诊制度（含贴纸 AH + 插页 AH1–AH8 + 合用电梯机房谁按谁修隐喻 + 拒签卡 + 与 S/AE/T 分工表）」的专项中文公开视频或制度文章；上文最贴题的是 **DAS/POI/多网络合路公开页与 PDF**、**PIM/互调公开 PDF 与视频**、**合用设施维护词条（故事类比）**，以及站点维护/FAT-SAT/DMR 基础与频谱视频。其余为国内无线电法规与 DMR/ITU 入口。需按贴纸 AH 与 AH1–AH8 拼进本网流程。`video_found=true`（PIM 专项视频 + 互调/频谱 + 通用巡检/FAT-SAT/DMR 基础），**非** AH 台账专项。部分境外站点（如部分 Kaelus/Anritsu 产品页、部分 MIIT 首页）在核验出口偶发 403，本篇以已 200/oEmbed 通过的链接为准。任何「教你如何伪造合路账」「如何套邻业主曲线过关」「如何抬功率压合路抖」「如何绕过告警」的页面即使 200，本篇也**不引用**。

**库内必回：** 手册20（S）、21（T）、32（AE）、室分复测 AB/X/I、19（R）、15（N）、06（脱敏）、34（AG）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子
- 贴纸 **AH** 五子类：合 / 界 / 诊 / 验 / 治——双字母续写的第八张，负责合路·界面·分诊「台账清不清、界面有没有主、本期过了没有」。  
- 故事：商场/医院共享楼宇合用电梯机房「谁按谁修」+ 合用配电间责任界面——柜里有设备≠界面清；网管绿≠分诊过；套邻业主曲线=拒签；S/AE/T 不顶替 AH；单边绿≠整段过。  
- 阶段梯：建合路账 → 钉界面主人 → 分诊窗钉死 → 本期实测 → 会签放行 → 变更再验。  
- 八条硬规则：**合路/POI 台账与业主界面钉死**；**责任界面有主人**；**干扰分诊窗与方法钉死**；**本组本机房本期实测禁套他业主他期（单边≠整段）**；**会签才放行**；**禁顶替 S/AE/T/AB 等，主贴 AH，假绿≠放行挂 R**；**合路窗禁功率战、监控风暴挂 N、变更走 J**；**脱敏 L3**。

### 11.2 下一篇手册候选（本篇不写正文）
- **机房温湿度与空调联锁巡检边界**（与 AF 供电巡检、AA 首年巡检咬合）  
- **天线驻波与跳线老化抽检台账**（与巡检/复测、AD 备件咬合）  
- **铁塔/桅杆爬塔作业与第三方交叉施工界面**（与安全交底、变更 J、监控 N 咬合）

### 11.3 给带新人的三句话
1. 合路不是柜里有就能签：台账有端口，界面有主人，本期实测。  
2. 网管绿不是分诊过：书面分诊窗与方法，会签才算准用。  
3. 假绿挂 R；主贴 AH；S/AE/T 不顶替；合路窗禁功率战；公开脱敏 L3。

### 11.4 一张图记住本篇（收工贴纸）
```text
  ┌────────── 贴纸 AH ──────────┐
  │ 合 合路/POI台账·端口贴签   │
  │ 界 界面主人·书面边界钉死   │
  │ 诊 分诊窗·方法·到场钉死   │
  │ 验 本期实测·禁套·单边≠整段 │
  │ 治 假绿顶替套曲线功率战泄密 │
  └────────────────────────────┘
    合用电梯谁按谁修 · 假绿≠准用
```

---

## 12. 本篇检查清单（自学打勾）
- [ ] 能背贴纸 AH 五子类与合用电梯机房「谁按谁修」故事  
- [ ] 能画 建合路→钉界面→分诊窗→实测→会签→变更再验 阶段梯  
- [ ] 能背八条硬规则（合路台账、界面主人、分诊窗方法、本期实测、会签才放、禁顶替假绿挂R、禁功率战挂N走J、L3）  
- [ ] 能背九字合路钉，并能讲清为什么合路窗要先问界面（上行更脆）  
- [ ] 会填插页 AH1–AH8、拒签卡与合路/POI 台账卡  
- [ ] 能说出 AH 与 S/AE/T 分工，以及假绿/套曲线/单边冒充三种拒签  
- [ ] 12 题自测过关  
- [ ] 知道 §10 诚实说明：无专项 AH 台账视频，仅 DAS/POI/PIM 公开文 + PIM/互调视频 + 通用巡检视频  
- [ ] 回库用 L3 重对一次本网最近合路/POI 增业主或干扰分诊：合路账、界面主人、分诊窗、本期实测、会签、未闭项

---

*手册35 · 多业主合路/POI 机房责任界面与干扰分诊 · 学习推送 · 2026-10-26 09:52 +08:00*
