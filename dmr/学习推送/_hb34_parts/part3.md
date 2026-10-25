## 9. 自测（12 题）+ 参考答案

1. 贴纸 AG 五个子类是什么？各用四个字以内说明。  
2. 医院抢救车/AED + 近效期药柜故事里，「近效先出≠随便挑新」主要对应 AG 哪一段？  
3. 八条硬规则里，哪一条要求梯队入库与轮换顺序钉死？  
4. 为什么切换间隙要「先问电池健康再开射频工单」？与 12.5 kHz / 4FSK / 2-slot 有什么关系？  
5. 「电池/充电器准用」至少要具备哪几样（九字电池钉里不可砍的）？  
6. 用 AD 备件签或 AF 供电签顶掉本期容量抽检，违反哪条？主贴谁？  
7. AG 与 AD / AF / N 的分工一句话？  
8. 套邻站放电曲线，主贴什么？能不能改组号交差？  
9. 大屏浮充全绿想签准用，应挂什么提醒？主贴谁？  
10. 机动站 AC 手台电池勾选，能不能代替库房 AG 容量抽检？  
11. 私自改浮充定值或换充电器型号后应走什么变更贴纸并怎样处理？  
12. 公开材料能不能贴真实电池序列号与机房全称？依据哪条规则？

### 参考答案

1. **梯**（梯队入库轮换）、**充**（充电器准用期）、**抽**（抽检窗与方法）、**验**（本期本组实测）、**治**（假绿顶替套曲线功率战泄密）。  
2. **AG-梯**（亦可答治：禁挑新弃旧）。  
3. **规则1**。  
4. 切换间隙常靠电池浮充；低健康度时上行更先掉；空口台阶（12.5 kHz/4FSK/2-slot）没变，先证电池/供电再谈射频，避免误开功率战。  
5. **梯队账、充电器准用期、本组本机房本期实测、会签**（规则1–5；九字钉核心）。  
6. **规则6**；主贴仍是 **AG**。  
7. **AD 备件账期、AF 切换供电巡检、N 监控风暴、AG 管梯队·充电器·容量抽检能不能签准用**。  
8. **AG-治**；**不能**。  
9. 挂 **R**；主贴 **AG**（规则6）。  
10. **不能**；AC 勾选≠ AG 库房/机房抽检窗。  
11. **J**，并重开 AG 抽检窗（规则7；常挂 N/AF）。  
12. **不能**；**规则8 脱敏 L3**。

---

## 10. 加深阅读与视频（均已用 curl / oEmbed 核对；以核验当时为准）

**本篇专项方法级阅读（VRLA/浮充/容量抽检/电信机房电池；借秩序，不替代本网 AG 签字）**  
1. **[Exponential Power · VRLA Battery Capacity/Discharge Testing（PDF）](https://www.exponentialpower.com/wp-content/uploads/2024/04/VRLA-Battery-Testing.pdf)**——容量/放电测试公开摘要（厂商向；浮充记录≠容量结论；**不是**本网 AG 法定制度）。  
2. **[Blue Box Batteries · A Guide To VRLA Battery Discharge Testing](https://www.blueboxbatteries.co.uk/blog/a-guide-to-vrla-battery-discharge-testing)**——放电测试窗与记录要点公开文（**只借「要测要记」**）。  
3. **[TYCORUN · Mastering Float Voltage](https://www.tycorun.com/blogs/news/float-voltage)**——浮充电压公开科普（强调浮充维持满充，**不等于**健康度已测）。  
4. **[Mitsubishi Critical · VRLA Installation/Operating Procedures（PDF）](https://mitsubishicritical.com/wp-content/uploads/2025/06/CD-Battery-Condensed-Installation-Operating-Procedures-MR-PLP-PLM.pdf)**——浮充区间、周期维护与容量测试公开转述（厂商向；门限以本网规程为准）。  
5. **[Wikipedia · VRLA battery](https://en.wikipedia.org/wiki/VRLA_battery)** · **[Lead–acid battery](https://en.wikipedia.org/wiki/Lead%E2%80%93acid_battery)** · **[Battery room](https://en.wikipedia.org/wiki/Battery_room)** · **[Battery charger](https://en.wikipedia.org/wiki/Battery_charger)** · **[Float voltage](https://en.wikipedia.org/wiki/Float_voltage)** · **[State of health](https://en.wikipedia.org/wiki/State_of_health)** · **[State of charge](https://en.wikipedia.org/wiki/State_of_charge)** · **[Internal resistance](https://en.wikipedia.org/wiki/Internal_resistance)** · **[Ampere hour](https://en.wikipedia.org/wiki/Ampere_hour)** · **[Depth of discharge](https://en.wikipedia.org/wiki/Depth_of_discharge)** · **[Trickle charging](https://en.wikipedia.org/wiki/Trickle_charging)** · **[Battery management system](https://en.wikipedia.org/wiki/Battery_management_system)**——电池健康与充电基础词条。  
6. **[Wikipedia · Uninterruptible power supply](https://en.wikipedia.org/wiki/Uninterruptible_power_supply)** · **[Rectifier](https://en.wikipedia.org/wiki/Rectifier)** · **[Emergency power system](https://en.wikipedia.org/wiki/Emergency_power_system)** · **[Automatic transfer switch](https://en.wikipedia.org/wiki/Automatic_transfer_switch)**——UPS/整流/应急电源/ATS（切换间隙电池扛，接 AF）。  
7. **[Vertiv · Telecom solutions](https://www.vertiv.com/en-us/solutions/telecom/)** · **[Eltek](https://www.eltek.com/)** · **[EnerSys](https://www.enersys.com/)** · **[UL · Battery safety testing](https://www.ul.com/services/battery-safety-testing)**——机房/电信电源与电池安全公开入口（科普级）。  
8. **[Cummins 公开 PDF · NFPA 110 Testing and Service Requirements for Standby Power Systems](https://www.cummins.com/sites/default/files/2021-02/External%20%28Final%29%20NFPA%20110%20Testing%20and%20service%20requirements%20for%20Standby%20Power%20Systems_12.15.2020.pdf)** · **[NFPA · NFPA 110 标准入口](https://www.nfpa.org/codes-and-standards/all-codes-and-standards/list-of-codes-and-standards/detail?code=110)**——备用电源要测要记公开转述（**境外标准教学类比，非中国专网法定依据**）。  
9. **[Wikipedia · Preventive maintenance](https://en.wikipedia.org/wiki/Preventive_maintenance)** · **[Facility management](https://en.wikipedia.org/wiki/Facility_management)** · **[Telephone exchange](https://en.wikipedia.org/wiki/Telephone_exchange)**——预防性维护与机房直觉。  
10. **[DMR Association · Standards](https://www.dmrassociation.org/dmr-standards.html)** · **[首页](https://www.dmrassociation.org/)** · **[TS 102 361-1 PDF](https://dmrassociation.org/public-downloads/standards/ts_10236101v020701p.pdf)**——空中接口标准入口（**不规定**电池梯队台账）。  
11. **[Tait Communications](https://www.taitcommunications.com/)** · **[Tait Radio Academy](https://www.taitradioacademy.com/)** · **[Hytera](https://www.hytera.com/)** · **[Motorola Solutions](https://www.motorolasolutions.com/)** · **[Sepura](https://www.sepura.com/)**——专网厂商公开入口（手台电池/充电器常与 AD/AG 同读）。

**故事类比：医院 AED / 抢救车电池与近效期秩序（只借直觉，不是台站法定依据）**  
12. **[Wikipedia · Automated external defibrillator](https://en.wikipedia.org/wiki/Automated_external_defibrillator)** · **[Defibrillation](https://en.wikipedia.org/wiki/Defibrillation)** · **[First aid](https://en.wikipedia.org/wiki/First_aid)**——AED/除颤基础词条（借「柜子在≠电池有效期内抽检过」）。  
13. **[American Red Cross · AED 培训入口](https://www.redcross.org/take-a-class/aed)**——公开培训入口（**故事类比：要训要检，非无线电 AG 依据**）。  
14. Wikipedia：[Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio) · [Land mobile radio system](https://en.wikipedia.org/wiki/Land_mobile_radio_system)。

**国内无线电法规（台站秩序指针；无梯队乱顶岗不是法外）**  
15. **[《中华人民共和国无线电管理条例》（中国政府网）](https://www.gov.cn/zhengce/zhengceku/2016-11/25/content_5137687.htm)** · **[国务院公报版](https://www.gov.cn/gongbao/content/2016/content_5148745.htm)**。  
16. **[《无线电频率使用许可管理办法》（中国政府网）](https://www.gov.cn/zhengce/2022-08/23/content_5722706.htm)**。  
17. **[《地面无线电台（站）管理规定》（中国政府网）](https://www.gov.cn/zhengce/202310/content_6908889.htm)** · **[国务院公报 · 工信部令第60号](https://www.gov.cn/gongbao/content/2023/content_5745291.htm)**。  
18. **[无线电管理局政策法规入口](https://www.miit.gov.cn/jgsj/wgj/zcfg/index.html)**（部分 MIIT 首页出口偶发 403，以可访问为准）。

**ITU / 验收方法级**  
19. **[ITU-R SM.1753](https://www.itu.int/rec/R-REC-SM.1753/en)** · **[ITU-R Monitoring](https://www.itu.int/en/ITU-R/terrestrial/monitoring/Pages/default.aspx)**。  
20. **[P25 Best Practice · Field Acceptance Tests](https://www.p25bestpractice.com/implementing/field-acceptance-tests/)** · **[Flowdit · SAT](https://flowdit.com/site-acceptance-test/)**——到站/现场合格直觉（合格步骤≠假绿）。

**测量 / 站点维护相关公开资料（看懂「巡与记」，不是造假教程）**  
21. Wikipedia：[Standing wave ratio](https://en.wikipedia.org/wiki/Standing_wave_ratio) · [Noise floor](https://en.wikipedia.org/wiki/Noise_floor) · [RSSI](https://en.wikipedia.org/wiki/Received_signal_strength_indication) · [Spectrum analyzer](https://en.wikipedia.org/wiki/Spectrum_analyzer)。  
22. **[Rohde & Schwarz · EMF testing](https://www.rohde-schwarz.com/us/solutions/electronics-testing/emc-testing/emf-testing/emf-testing_253445.html)**——仪器公开入口。  
23. **[Generac · Automatic transfer switches](https://www.generac.com/industrial/products/automatic-transfer-switches)**——ATS 公开入口（切换间隙接 AF/AG）。

**视频（YouTube，已用 oEmbed 核验标题与频道）**  
24. **[UPS Trader · Riello 1500 UPS Battery test procedure to find a bad battery](https://www.youtube.com/watch?v=VQEwqPwORLE)**——UPS 电池带载比对示意（厂商/维修向；借「浮充在位≠每节都健康」；**不是** AG 台账专项，门限以本网规程为准）。  
25. **[Cummins · Integrated Power Systems Ep.8: Transfer Switch Functionalities & Applications](https://www.youtube.com/watch?v=6idadtpqSrg)** · **[Eaton PSEC · Automatic transfer switch (ATS) fundamentals](https://www.youtube.com/watch?v=yjphp4SBkSA)**——ATS 与切换（借切换间隙电池心跳，接 AF）。  
26. **[Standby Power Solutions · Transfer Switch Sequence of Operation OTIII](https://www.youtube.com/watch?v=-g5C_LP39ys)** · **[RJCONTROL · Anatomy of an Automatic Transfer Switch ASCO](https://www.youtube.com/watch?v=y8AmrnCSRDE)** · **[S Snider · Generac automatic transfer switch explained, demo](https://www.youtube.com/watch?v=rT_3JYZS9Mg)**——转换开关动作顺序。  
27. **[MPSCS · Site Maintenance Inspection and Preventative Maintenance](https://www.youtube.com/watch?v=4IRdxeXN1do)**——站点维护与记录（借「要巡要记」）。  
28. **[Engineered Vision · FAT and SAT Explained](https://www.youtube.com/watch?v=x7qNC6Rtp9I)** · **[Careers360 · FAT & SAT](https://www.youtube.com/watch?v=3aafLF9o0NA)**——出厂/到站合格直觉（回指：假绿≠会签）。  
29. **[Scanner School · What is DMR?](https://www.youtube.com/watch?v=aQX_JbTbXuY)**（弱项：时隙与数字话音）。  
30. **[Rohde & Schwarz · Understanding Spectrum Analyzers – ACLR](https://www.youtube.com/watch?v=mco_BJ1mjNo)** · **[Shure · What is Intermodulation?](https://www.youtube.com/watch?v=IrlyAei02_o)**——频谱/互调；对照禁功率战。  
31. **[NATEsafety · How to Conduct Tower Inspections](https://www.youtube.com/watch?v=dFs4At6-hhU)** · **[Sunil Kashyap · How to perform site audit or RF audit](https://www.youtube.com/watch?v=7Awj0-rDfeA)**——巡检/审计通用视频。

> **诚实说明**：没有找到「DMR 专网电池与充电器梯队轮换与容量抽检制度（含贴纸 AG + 插页 AG1–AG8 + 医院抢救车/AED/近效期药柜隐喻 + 拒签卡 + 与 AD/AF 分工表）」的专项中文公开视频或制度文章；上文最贴题的是 **VRLA/浮充/容量放电测试公开 PDF 与博文**、**UPS 电池比对视频**、**AED/急救公开词条（故事类比）**、**ATS/备用电源公开文与视频（切换间隙接 AF）**，以及站点维护/FAT-SAT/DMR 基础与频谱互调视频。其余为国内无线电法规与 DMR/ITU 入口。需按贴纸 AG 与 AG1–AG8 拼进本网流程。`video_found=true`（UPS 电池测试视频 + ATS/切换专项 + 通用巡检/FAT-SAT/DMR 基础），**非** AG 台账专项。部分境外站点（如 Battery University、部分 CDC/ETSI 页）在核验出口偶发 403，本篇以已 200/oEmbed 通过的链接为准。任何「教你如何伪造容量账」「如何套邻站曲线过关」「如何抬功率压抽检抖」「如何绕过告警」的页面即使 200，本篇也**不引用**。

**库内必回：** 手册12（K）、15（N）、28（AA）、30（AC）、31（AD）、32（AE）、33（AF）、19（R）、21（T）、06（脱敏）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子
- 贴纸 **AG** 五子类：梯 / 充 / 抽 / 验 / 治——双字母续写的第七张，负责梯队·充电器·容量抽检「梯队清不清、充电器有没有期、本期过了没有」。  
- 故事：医院抢救车/AED 电池 + 近效期药柜梯队轮换抽检——入库贴签≠永远准用；近效/低健康度须先轮出或隔离；浮充绿≠容量过；套邻站曲线=拒签；AD/AF 不顶替 AG。  
- 阶段梯：建梯队账 → 充电器准用 → 抽检窗钉死 → 本期实测 → 会签准用 → 变更再验。  
- 八条硬规则：**梯队入库与轮换顺序钉死**；**充电器与线缆有主人有准用期**；**容量抽检窗与方法钉死**；**本组本机房本期实测禁套他站他组**；**抽检通过才签准用**；**禁顶替 AD/AF/K/N/AA 等，主贴 AG，假绿≠放行挂 R**；**抽检窗禁功率战、监控风暴挂 N、变更走 J**；**脱敏 L3**。

### 11.2 下一篇手册候选（本篇不写正文）
- **多业主合路/POI 机房责任界面与干扰分诊**（与 S/AE 界面咬合延伸）  
- **机房温湿度与空调联锁巡检边界**（与 AF 供电巡检、AA 首年巡检咬合）  
- **天线驻波与跳线老化抽检台账**（与巡检/复测、AD 备件咬合）

### 11.3 给带新人的三句话
1. 电池不是柜里有就能上岗：梯队有账，近效/低健康度先出或隔离，本期实测。  
2. 浮充绿不是容量过：书面抽检窗与方法，会签才算准用。  
3. 假绿挂 R；主贴 AG；AD/AF 不顶替；抽检窗禁功率战；公开脱敏 L3。

### 11.4 一张图记住本篇（收工贴纸）
```text
  ┌────────── 贴纸 AG ──────────┐
  │ 梯 梯队入库·近效先出·隔离   │
  │ 充 充电器线缆·主人·准用期 │
  │ 抽 抽检窗·方法·到场钉死   │
  │ 验 本组本机房本期·禁套曲线 │
  │ 治 假绿顶替套曲线功率战泄密 │
  └────────────────────────────┘
    医院AED/药柜 · 假绿≠准用
```

---

## 12. 本篇检查清单（自学打勾）
- [ ] 能背贴纸 AG 五子类与医院抢救车/AED + 近效期药柜梯队故事  
- [ ] 能画 建梯队→充电器准用→抽检窗→实测→会签→变更再验 阶段梯  
- [ ] 能背八条硬规则（梯队、充电器准用期、抽检窗方法、本期实测、抽检才签、禁顶替假绿挂R、禁功率战挂N走J、L3）  
- [ ] 能背九字电池钉，并能讲清为什么切换间隙要先问电池健康  
- [ ] 会填插页 AG1–AG8、拒签卡与电池/充电器台账卡  
- [ ] 能说出 AG 与 AD/AF/N 分工，以及假绿/套曲线/过期顶岗三种拒签  
- [ ] 12 题自测过关  
- [ ] 知道 §10 诚实说明：无专项 AG 台账视频，仅 VRLA/浮充公开文 + UPS 电池视频 + ATS/通用巡检视频  
- [ ] 回库用 L3 重对一次本网最近电池抽检或手台电池轮换：梯队、充电器、抽检窗、本期实测、会签、未闭项

---

*手册34 · 电池与充电器梯队轮换与容量抽检台账 · 学习推送 · 2026-10-25 18:52 +08:00*
