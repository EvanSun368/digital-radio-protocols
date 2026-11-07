## 6. 工作实例（12 则，教学虚构，L3）

1. **看着干净想签准用**：运维称滤网看着干净要签更换准用 → 查 BG1，无滤网台账本期核对 → **拒签**；补 BG-账。  
2. **口头换过 / 滤网还在当窗过**：外包称「换过了 / 滤网还在」免窗页 → **拒签**；补 BG-换 主人/窗/方法/准用期。  
3. **AU 顶替 BG**：班长用 AU 滤网压差气流签顶本期滤网更换签 → **挂 R**；主贴仍 BG；**AU过≠本期更换窗过**。  
4. **AI / AT 顶替**：站务称温湿度与冷凝加湿过了更换免做 → **拒签顶替**；AI≠BG、AT≠BG。  
5. **N 绿免实测**：大屏监控绿，本期更换/压差实测免 → **拒签**；N绿≠BG过；补 BG-验。  
6. **套邻站表**：外包拷邻站更换/压差表改机房号 → **BG-验 拒签重测**；禁套。  
7. **功率战**：滤网堵塞/高温告警，网优要抬功率 → **禁功率战**；先挂 N；缺秩序整改贴 BG；气流组织另问 AU。  
8. **旁通滤网冒充**：外包拆旁通滤网消告警后要求更换准用 → **禁**；挂 N/R；禁签。  
9. **绕压差联锁**：新人绕开压差高告警联锁再要求准用 → **禁**；挂整改；主贴 BG-治。  
10. **AD / AZ / BF 混签**：环境班称 AD 入库与 AZ 冷通道、BF 接地过了，更换免 → **拒签**；AD≠本期窗、AZ≠BG、BF≠BG。  
11. **不安全带电违章**：外包未授权带电拆滤网要求准用 → **禁**；挂 N/R；禁签。  
12. **泄密发群**：新人公开群贴真实精密空调序列号与压差门限 → **L3 违规**；脱敏重发；挂 BG-治。

### 6.1 实例对照表（再钉一次，教学）

| # | 触发原话 | 正确贴纸动作 | 错误动作（禁） |
|---|----------|--------------|----------------|
| 1 | 「看着干净就能签」 | 补 BG-账；拒签无账 | 直接签准用 |
| 2 | 「口头换过 / 滤网还在」 | 补 BG-换 | 免窗页 |
| 3 | 「AU 签顶」 | 挂 R；主贴 BG | 用 AU 顶 BG |
| 4 | 「AI/AT 过了免做」 | 边界勾选；主贴 BG | 用 AI/AT 顶 |
| 5 | 「N 绿免实测」 | 补 BG-验 | 免实测 |
| 6 | 「邻站表改号」 | BG-验 拒签重测 | 套票交差 |
| 7 | 「抬功率压告警」 | 挂 N；禁功率战 | 抬功率 |
| 8 | 「旁通滤网消告警」 | 挂 N/R；禁签 | 旁通后准用 |
| 9 | 「绕压差联锁」 | 挂整改；禁 | 绕联锁后准用 |
| 10 | 「AD/AZ/BF 过了免」 | 边界勾选；主贴 BG | 混签顶替 |
| 11 | 「带电拆滤网」 | 挂 N/R；禁 | 不安全带电违章 |
| 12 | 「序列号/门限发群」 | L3 脱敏 | 公开可还原编号 |

### 6.2 与 AU / AI / AT / AD / N 边界再对照（防写混）

```text
  滤网台账+压差本体窗+气流组织交底  ──→  贴纸 AU（手册48）  ★AU≠BG；不重写气流组织
  温湿度与空调联锁                  ──→  贴纸 AI（手册36）
  冷凝加湿联锁                      ──→  贴纸 AT（手册47）
  备件仪表入库准用                  ──→  贴纸 AD（手册31）
  机型·级次·位置·备件台账            ──→  贴纸 BG-账（本篇）
  更换窗·到场·准用期·更换前后ΔP      ──→  贴纸 BG-换（本篇）
  压差与更换边界窗·方法（勾清分工）  ──→  贴纸 BG-差（本篇；尤其AU≠BG）
```

---

## 7. 台账卡模板（《本网精密空调过滤器压差与滤网更换交底台账卡》）

```text
╔══════════════════════════════════════════════════╗
║ 《本网精密空调过滤器压差与滤网更换交底台账卡》·教学 ║
║ 贴纸：BG（账/换/差/验/治）  相对期号：________   ║
║ 脱敏机房角色：________                            ║
╠══════════════════════════════════════════════════╣
║ 【账】机型□ 级次□ 位置□ 备件指针□                 ║
║       外观干净≠窗过□ 禁口头滤网正常□ AU≠本期更换窗□ ║
║ 【换】主人________ 窗________ 方法/准用期________ ║
║       到场________ 换前ΔP□ 换后ΔP□ AD指针□       ║
║       口头换过≠方法过□ 滤网还在≠窗过□ 外观干净≠窗过□ ║
║ 【差】边界窗________ 到场________                 ║
║       方法摘要（不写绕联锁/旁通滤网/带电违章步骤）________║
║       压差表/开关角色□ 压差绿≠更换准用□           ║
║       禁绕联锁□ 禁旁通滤网□ 禁带电违章□ 禁伪造表□ ║
║       AU/AI/AT/AO/AD/N分工勾清□ 不重写AU气流组织□ ║
║ 【验】本期实测□ 禁套声明□ 会签________            ║
║       结论：□准用 □有条件整改 □拒签               ║
║ 【治/界】AU≠BG□ AI≠BG□ AT≠BG□ AO≠BG□ AD≠本期窗□ ║
║         AN≠交底□ N绿≠BG□ AZ/BF/…不顶替□         ║
║         假绿挂R□ 风暴挂N□ 变更走J□ L3□           ║
║ 不适用：□无精密空调滤网更换路径（书面）           ║
╚══════════════════════════════════════════════════╝
```

> 使用说明：本卡挂插页 BG1–BG8；门限与顺序以本网制度、合同与 OEM 书面为准；**不在卡上填写可还原门限全文与真实精密空调序列号全文**；无精密空调滤网更换路径站点勾「不适用」，不得用本卡顶 AU，也不得用 AU 顶本卡；**不重写 AU 气流组织全文**。

### 7.1 台账卡填写口诀（教学）

> **账先建，换先窗，差先法，验本期，治拒假绿。** 缺一格就停；会签才放。**AU≠BG 必须勾。**

### 7.2 拒签后允许做什么（白名单）

允许：补滤网台账、补更换窗、重开压差边界窗、本期重测、挂 R/N、走 J、内部整改、L3 脱敏重发。  
禁止：假绿放行、用 AU/AI/AT/AD/N 顶替、套他站他期表、旁通滤网冒充、绕压差联锁、不安全带电违章、抬功率压告警、公开可还原序列号/门限。

---

## 8. 术语表（本篇约 18 词）+ 易错观念

| 术语 | 本篇用法（教学） |
|------|------------------|
| **滤网/过滤器台账** | 机型·级次·位置·备件角色入账；BG-账；**≠ AU 气流组织用途的全文重写** |
| **滤网更换窗** | 有主有窗有方法准用期；**口头换过≠窗过**；**滤网还在≠窗过** |
| **更换前后ΔP** | Before/after differential pressure；以本网与 OEM 书面门限为准 |
| **压差（ΔP）** | Differential pressure across filter；**压差绿≠更换准用** |
| **外观干净** | 仅目视；**≠ 更换窗过、≠ 准用** |
| **旁通滤网** | 擅自拆旁通滤网冒充更换过；**本篇硬禁** |
| **绕压差联锁** | 绕过压差高告警联锁冒充可过；**本篇硬禁** |
| **假绿** | 无实测/无会签却显示通过；挂 R；≠ 放行 |
| **套票** | 套他站他期更换/压差表；BG-验 拒签 |
| **不安全带电违章** | 未授权不安全带电拆装滤网冒充可过；**本篇硬禁** |
| **功率战** | 用抬功率压滤网堵塞/高温告警；**禁**；先挂 N |
| **贴纸 BG** | 本篇主贴；账/换/差/验/治五子类 |
| **AU ≠ BG** | 滤网压差气流准用 ≠ 滤网更换专项准用 |
| **AI ≠ BG** | 温湿度联锁 ≠ 更换准用 |
| **AD ≠ BG** | 备件入库 ≠ 本期更换窗 |
| **N ≠ BG** | 风暴秩序 ≠ 本期实测 |
| **CRAC / CRAH** | 机房精密空调 / 机房空调处理机组；故事类比对象 |
| **脱敏 L3** | 禁真实站名/机房全称/精密空调序列号全文/联系人 |

**易错观念（纠一次）**  
- 「看着干净 = 准用」→ 错；要 BG-账台账 + 本期实测。  
- 「口头换过 / 滤网还在 / 外观干净 = 窗过」→ 错；要 BG-换 主人窗方法。  
- 「压差绿 = 更换准用」→ 错；要 BG-换 + BG-差 + BG-验。  
- 「AU 过 = BG 过」→ 错；气流组织 ≠ 本期更换窗。  
- 「AI 过 = 更换过」→ 错；温湿度 ≠ 更换准用。  
- 「AD 入库签 = 本期窗过」→ 错；备件入库 ≠ 本期更换窗。  
- 「N 绿 = 本期实测过」→ 错；风暴绿 ≠ 交底准用。  
- 「旁通滤网 / 绕联锁消告警 = 办法」→ 错；硬禁。  
- 「抬功率压堵塞/高温告警 = 救急」→ 错；禁功率战。

---

## 9. 自测（12 题）+ 参考答案

1. 贴纸 BG 五个子类是什么？口诀是哪一句？  
2. 「滤网看着干净就能签」违反哪条硬规则？属哪个子类？  
3. 八条硬规则里，哪一条要求换网有主有窗有方法/准用期？  
4. AU 滤网压差气流过了，能不能顶本期 BG？为什么？本篇重不重写 AU 气流组织？  
5. AI 温湿度过了，能不能免滤网更换准用？AD 备件入库签还在呢？  
6. N 监控绿，能不能免本期更换/压差实测？压差绿能不能免更换窗？  
7. 套邻站更换/压差表改机房号，应如何处置？  
8. 滤网堵塞/高温告警时，能不能先抬功率？应挂什么？气流组织还问谁？  
9. 「旁通滤网消告警后再签」允许吗？绕压差联锁呢？带电拆滤网呢？  
10. AT/AO/AZ/BF 过了，能不能免本期滤网更换？  
11. 本站无精密空调滤网更换路径，BG 怎么处理？假绿放行应挂什么？主贴还是不是 BG？  
12. 弱项短补：DMR 信道宽、调制、时隙各是什么？告警窗禁什么？滤网堵塞/压差异常常被误当什么？

### 参考答案

1. 账 / 换 / 差 / 验 / 治；口诀：**滤网有账，换网有窗，压差有法，会签才放。**  
2. 规则1（滤网台账钉死）；属 **BG-账**。  
3. 规则2。  
4. **不能**。AU ≠ BG；AU 过 ≠ 本期滤网更换窗过。本篇**不重写** AU 气流组织全文。  
5. **不能**。AI ≠ BG；AD ≠ 本期更换窗（备件入库 ≠ 本期窗）。  
6. **不能**。N 绿 ≠ BG 过；压差绿 ≠ 更换准用；要有本期实测与会签。  
7. **BG-验 拒签重测**；禁套他站他期。  
8. **不能**抬功率；先挂 **N** 理风暴；缺秩序整改贴 **BG**；气流组织另问 **AU**；**禁功率战**。  
9. **不允许**；禁旁通滤网冒充更换过；禁绕压差联锁；禁不安全带电违章；挂 N/R，禁签准用。  
10. **不能**；AT/AO/AZ/BF 各过 ≠ BG 过。  
11. 书面勾「不适用」；不得用 BG 顶 AU，也不得用 AU 顶 BG。假绿挂 **R**；主贴仍 **BG**。  
12. **12.5 kHz** / **4FSK** / **2-slot TDMA**；告警窗 **禁功率战**；常被误当**覆盖病**→禁功率战，挂 N，变更走 J。

---

## 10. 加深阅读与视频（均已用 curl / oEmbed 核对；以核验当时为准）

**本篇专项方法级阅读（CRAC/CRAH 滤网更换 / 过滤器压差 ΔP；借秩序，不替代本网 BG 签字；不教绕联锁、不教旁通滤网冒充、不教不安全带电违章；不重写 AU 气流组织全文）**  
1. **[Air Filter Systems · Air Filtration FAQ for Facilities Technicians — Data Centers](https://www.myafsva.com/air-filtration-resources/data-centers/facilities-technician/)**——数据中心滤网更换与压差 FAQ（借「外观干净≠更换过、压差要有监测与更换秩序」；门限以本网与 OEM 书面为准；**不是**本网 BG 法定制度）。  
2. **[Synetica · Differential pressure monitoring for data centre cooling](https://synetica.net/blog/differential-pressure-monitoring-for-data-centre-cooling)**——数据中心压差监测公开文（借「ΔP有监测秩序」；**压差绿≠更换准用**）。  
3. **[AKCP · Enhance data center cooling with differential pressure sensors](https://www.akcp.com/2023/07/01/enhance-data-center-cooling-performance-with-differential-pressure-sensors/)**——压差传感与冷却公开文（借「压差有传感角色」；气流组织深潜仍回 AU）。  
4. **[Northern Link · CRAC management using differential pressure (ΔP) sensors](https://northernlink.com/crac-management-using-differential-pressure-%CE%B4p-sensors-in-data-centers/)**——CRAC 与 ΔP 传感公开文（借「CRAC有压差管理直觉」；**AU≠BG**）。  
5. **[HVAC Software · CRAC/CRAH Preventive Maintenance Checklist](https://hvacsoftware.com/data-center/crac-crah-preventive-maintenance-checklist/)** · **[Oxmaint · Data Center CRAC/CRAH Predictive Maintenance Checklist](https://oxmaint.com/industries/hvac/data-center-crac-crah-predictive-maintenance-checklist)**——CRAC/CRAH 预防性维护清单公开页（借「滤网DP要巡要记」；**不是** BG 台账专项）。  
6. **[TechTarget · Best practices for maintaining a data center CRAC unit](https://www.techtarget.com/searchdatacenter/tip/Best-practices-for-maintaining-a-data-center-CRAC-unit)**——CRAC 维护公开文（借「滤网更换仍是必要秩序」；**不教旁通滤网/绕联锁**）。  
7. **[Wikipedia · Air filter](https://en.wikipedia.org/wiki/Air_filter)** · **[MERV](https://en.wikipedia.org/wiki/MERV)** · **[Differential pressure](https://en.wikipedia.org/wiki/Differential_pressure)** · **[Particulates](https://en.wikipedia.org/wiki/Particulates)**——空气过滤器 / MERV / 压差 / 颗粒物公开词条（借「过滤器有级次与压差直觉」；**外观干净≠合格**）。  
8. **[Wikipedia · Computer room air handler](https://en.wikipedia.org/wiki/Computer_room_air_handler)** · **[CRAC](https://en.wikipedia.org/wiki/CRAC)** · **[Data center environmental control](https://en.wikipedia.org/wiki/Data_center_environmental_control)** · **[HVAC](https://en.wikipedia.org/wiki/Heating,_ventilation,_and_air_conditioning)** · **[Air handler](https://en.wikipedia.org/wiki/Air_handler)**——CRAH/CRAC/机房环境控制/HVAC 公开词条（借「机房精密空调有分层交底」；更换专项回 BG，气流组织回 AU）。  
9. **[Vertiv · Thermal Management 公开入口](https://www.vertiv.com/en-us/products-catalog/thermal-management/)**——热管理公开入口（借「机房空调有厂商维护入口」；门限以本网书面为准）。  
10. **[DMR Association · Standards](https://www.dmrassociation.org/dmr-standards.html)** · **[首页](https://www.dmrassociation.org/)**——空中接口标准入口（**不规定**滤网更换台账）。  
11. **[Tait Radio Academy](https://www.taitradioacademy.com/)** · **[Hytera](https://www.hytera.com/)** · **[Motorola Solutions](https://www.motorolasolutions.com/)** · **[Sepura](https://www.sepura.com/)**——专网厂商公开入口。  
12. **[SRRC 公开入口](https://www.srrc.org.cn/)**——无线电型号核准公开入口（台站设备秩序指针；**不替代**本网 BG）。

**故事类比：医院手术室/ICU / 数据中心 CRAC 滤网更换（只借直觉，不是台站法定依据）**  
13. **[Wikipedia · Operating room](https://en.wikipedia.org/wiki/Operating_room)** · **[Intensive care unit](https://en.wikipedia.org/wiki/Intensive_care_unit)** · **[Data center](https://en.wikipedia.org/wiki/Data_center)** · **[Server room](https://en.wikipedia.org/wiki/Server_room)**——手术室/ICU/数据中心直觉（借「外观干净≠更换过、压差绿≠更换准用、AU过≠BG过、AI过≠BG过、AD过≠本期窗过、N绿≠BG过」）。  
14. Wikipedia：[Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio) · [Land mobile radio system](https://en.wikipedia.org/wiki/Land_mobile_radio_system) · [Noise floor](https://en.wikipedia.org/wiki/Noise_floor)。

**国内无线电法规（台站秩序指针；无账乱签滤网更换不是法外）**  
15. **[《中华人民共和国无线电管理条例》（中国政府网）](https://www.gov.cn/zhengce/zhengceku/2016-11/25/content_5137687.htm)** · **[国务院公报版](https://www.gov.cn/gongbao/content/2016/content_5148745.htm)**。  
16. **[《无线电频率使用许可管理办法》（中国政府网）](https://www.gov.cn/zhengce/2022-08/23/content_5722706.htm)**。  
17. **[《地面无线电台（站）管理规定》（中国政府网）](https://www.gov.cn/zhengce/202310/content_6908889.htm)** · **[国务院公报 · 工信部令第60号](https://www.gov.cn/gongbao/content/2023/content_5745291.htm)**。

**ITU / 验收方法级**  
18. **[ITU-R SM.1753](https://www.itu.int/rec/R-REC-SM.1753/en)**。  
19. **[P25 Best Practice · Field Acceptance Tests](https://www.p25bestpractice.com/implementing/field-acceptance-tests/)** · **[Flowdit · SAT](https://flowdit.com/site-acceptance-test/)**——到站/现场合格与公开入口（合格步骤≠假绿）。

**视频（YouTube，已用 oEmbed 核验标题与频道）**  
20. **[Recommended timing for bag filter replacement in AHU](https://www.youtube.com/watch?v=KYVo-F9qFDc)**——AHU 袋式滤网更换时机与压差公开片（借「更换看压差、要有监测秩序」；门限以本网与 OEM 书面为准；**不是** BG 台账专项；**不教旁通滤网/绕联锁**）。  
21. **[Substituição de Filtros de Ar dos Ares-Condicionados de um Data Center](https://www.youtube.com/watch?v=QEUaORy2owI)**——数据中心空调滤网更换公开片（借「滤网更换有现场步骤直觉」；**外观干净≠准用**；现场方法以本网书面为准）。  
22. **[Testo Smart Probes Filter Pressure Drop with testo 510i](https://www.youtube.com/watch?v=GNL9Oi-ZLRI)**——滤网压差测量公开片（借「更换前后ΔP可测」；**压差绿≠更换准用**；仪表准用回 AD）。  
23. **[Tut 2 · Inside components of CCU / Precision AC / CRAC](https://www.youtube.com/watch?v=PY4NU0aNUQo)**——精密空调/CRAC 内部组件公开片（借「滤网在机组里有位置角色」；对照 BG-账）。  
24. **[Method Statement for CRAC Unit Installation, Testing & Commissioning](https://www.youtube.com/watch?v=m6Lm-xh2rLU)**——CRAC 安装测试调试公开片（借「要有书面方法与记录」；回指会签≠假绿）。  
25. **[The Engineering Mindset · Data Center HVAC](https://www.youtube.com/watch?v=xBxyhxmhigc)** · **[Fundamentals of HVAC](https://www.youtube.com/watch?v=klggop60vlM)**——数据中心/HVAC 公开片（借「机房有分层交底」；滤网更换专项仍 BG；气流组织回 AU）。  
26. **[MPSCS · Site Maintenance Inspection and Preventative Maintenance](https://www.youtube.com/watch?v=4IRdxeXN1do)**——站点维护与记录（借「要巡要记」）。  
27. **[Engineered Vision · FAT and SAT Explained](https://www.youtube.com/watch?v=x7qNC6Rtp9I)** · **[Careers360 · FAT & SAT](https://www.youtube.com/watch?v=3aafLF9o0NA)**——出厂/到站合格直觉（回指：假绿≠会签）。  
28. **[Scanner School · What is DMR?](https://www.youtube.com/watch?v=aQX_JbTbXuY)**（弱项：时隙与数字话音）。  
29. **[Rohde & Schwarz · Understanding Spectrum Analyzers – ACLR](https://www.youtube.com/watch?v=mco_BJ1mjNo)**——频谱仪直觉；对照禁功率战。  
30. **[NATEsafety · How to Conduct Tower Inspections](https://www.youtube.com/watch?v=dFs4At6-hhU)** · **[Sunil Kashyap · How to perform site audit or RF audit](https://www.youtube.com/watch?v=7Awj0-rDfeA)**——巡检/审计通用视频（借「要巡要记」；**不是**旁通滤网/绕联锁/带电违章教条）。

> **诚实说明**：没有找到「DMR 专网机房精密空调过滤器压差与滤网更换交底台账（含贴纸 BG + 插页 BG1–BG8 + 医院手术室/ICU 或数据中心 CRAC/CRAH 滤网更换+ΔP 隐喻 + 拒签卡 + 与 AU/AI/AT/AD/N 分工 + AU≠BG）」的专项中文公开视频或制度文章；最贴题的是 **Air Filter Systems 数据中心滤网 FAQ + Synetica/AKCP/Northern Link 压差监测 + HVAC Software/Oxmaint CRAC PM + TechTarget CRAC 维护**、**Wikipedia Air filter / MERV / Differential pressure / CRAH / CRAC / Data center environmental control**，以及 **AHU bag filter replacement timing + Data Center filter replacement + Testo filter pressure drop + CRAC components + CRAC T&C** 公开片，加上站点维护/FAT-SAT/DMR 基础视频。其余为国内无线电法规与 DMR/ITU 入口。需按贴纸 BG 与 BG1–BG8 拼进本网流程。`video_found=true`（AHU袋滤更换压差片 + 数据中心滤网更换片 + Testo滤网压差片 + CRAC组件/调试片 + Data Center HVAC + 通用巡检/FAT-SAT/DMR），**非** BG 台账专项。ACHR News 滤网压差告警文返回 403，本篇未引用；部分厂商产品子路径可能 403，本篇以已 200/oEmbed 通过的链接为准。任何「教旁通滤网 / 绕压差联锁 / 不安全带电违章 / 伪造滤网更换台账 / 抬功率压告警」的页面即使 200，本篇也**不引用**。

**库内必回：** 手册48（AU）、36（AI）、47（AT）、42（AO）、31（AD）、41（AN）、28（AA）、15（N）、44（AQ）、53（AZ）、58（BE）、57（BD）、51（AX）、52（AY）、59（BF）、55（BB）、54（BA）、50（AW）、46（AS）、33（AF）、49（AV）、45（AR）、34（AG）、43（AP）、37（AJ）、38（AK）、35（AH）、39（AL）、19（R）、06（脱敏）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子
- 贴纸 **BG** 五子类：账 / 换 / 差 / 验 / 治——双字母续写在 BF 之后的第一张 **BG**，负责精密空调过滤器压差与滤网更换「台账清不清、更换有没有窗、压差与更换边界有没有法、本期过了没有」。  
- 口诀：**滤网有账，换网有窗，压差有法，会签才放。**  
- 故事：医院手术室/ICU / 数据中心 CRAC/CRAH 空气过滤器更换 + 更换前后压差（ΔP）——外观干净≠更换窗过；滤网还在≠窗过；口头换过≠方法过；压差绿≠更换准用。  
- 八条硬规则：**滤网台账钉死**；**换网有主有窗有方法/准用期**；**压差与更换边界窗与方法钉死**；**本期实测禁套**；**会签才放行**；**禁顶替 AU/AI/AT/AO/AD/AN/AA/N/AQ/AZ/…，主贴 BG，假绿≠放行挂 R**；**异常风暴挂 N、变更走 J、禁功率战/绕联锁/旁通滤网冒充/不安全带电违章/伪造台账**；**脱敏 L3**。  
- **BG 不替代 AU，也不替代 AI，也不替代 AD，也不替代 N**：AU=滤网压差气流组织；AI=温湿度联锁；AD=备件仪表准用；BG=滤网更换专项·更换前后ΔP准用。**AU ≠ BG；AI ≠ BG；AD ≠ BG；N ≠ BG。本篇不重写 AU 气流组织全文。**

### 11.2 下一篇手册候选（本篇不写正文）
- **机房冷却水泵组与冷凝水侧交底台账**（与 BA 冷冻水冷却塔、BD 冷冻水泵组定压补水、AO 漏水、AT 冷凝加湿、N 监控咬合；适用于要单独钉冷却水泵与冷凝水侧秩序的站点）  
- **机房柴油发电机日用/储油罐油位与泄漏巡检交底台账**（与 AF 油机市电、AV 油品净化加油、AR 油机房通风燃油、N 监控、AN 门禁咬合；适用于要单独钉油位/泄漏巡检秩序的站点）  
- **机房精密空调压缩机吸排气压力与过热度过冷度巡检交底台账**（与 AX 压缩机冷媒边界、AT 冷凝加湿、AI 温湿度、N 监控咬合；适用于要单独钉吸排气/过热度过冷度秩序的站点；**不重写 AX 制冷剂边界全文**）

### 11.3 给带新人的三句话
1. 滤网不是看着干净就能签：滤网有账，本期核对钉死；**AU过≠本期滤网更换窗过**。  
2. 更换不是口头换过就算过、压差不是绿灯就算更换准用：主人窗方法准用期，更换前后ΔP书面方法，本期实测会签才算准用；禁旁通滤网、禁绕压差联锁、禁不安全带电违章。  
3. 假绿挂 R；主贴 BG；AU/AI/AD/N 不顶替；异常窗禁功率战禁旁通滤网；公开脱敏 L3。

### 11.4 一张图记住本篇（收工贴纸）
```text
  ┌────────── 贴纸 BG ──────────┐
  │ 账 滤网/过滤器台账钉死     │
  │ 换 换网有主有窗有方法       │
  │ 差 压差与更换边界窗·方法钉死 │
  │ 验 本期实测·禁套·会签       │
  │ 治 假绿顶替套票旁通滤网绕联锁功率战 │
  └────────────────────────────┘
    外观干净≠窗过 · 滤网还在≠窗过 · 口头换过≠方法过 · 压差绿≠更换准用 · 假绿≠准用
    AU≠BG（滤网压差气流 ≠ 滤网更换专项）
    AI≠BG（温湿度 ≠ 更换准用）
    AT≠BG（冷凝加湿 ≠ 更换）
    AO≠BG（漏水 ≠ 更换）
    AD≠BG（备件入库 ≠ 本期更换窗）
    N≠BG（风暴秩序 ≠ 本期实测）
    AZ≠BG（冷通道 ≠ 更换）
    BF≠BG（接地等电位 ≠ 滤网更换）
```

---

## 12. 本篇检查清单（自学打勾）
- [ ] 能背贴纸 BG 五子类与医院手术室/ICU 或数据中心 CRAC/CRAH 滤网更换+ΔP 故事  
- [ ] 能背口诀：滤网有账，换网有窗，压差有法，会签才放  
- [ ] 能背八条硬规则（滤网台账钉死、换网有主窗方法、压差与更换边界窗方法、本期实测、会签才放、禁顶替假绿挂R、禁功率战禁绕联锁禁旁通滤网禁带电违章挂N走J、L3）  
- [ ] 能分清 BG 与 AU / AI / AT / AO / AD / AN / N / AZ / BF / R / J 边界；尤其 **AU≠BG、AI≠BG、AD≠BG、N≠BG**；知道本篇不重写 AU 气流组织全文  
- [ ] 会填插页 BG1–BG8 与台账卡封面/账/换/差/验/会签页  
- [ ] 会用拒签卡卡住无账、套票、顶替、假绿、旁通滤网、绕联锁  
- [ ] 自测 12 题过关；知道 video_found=true 但是非 BG 台账专项  
- [ ] 回库用 L3 对一遍最近一次精密空调过滤器压差与滤网更换交底：台账、窗、方法、本期实测、会签、拒签项（无路径则勾不适用）  
- [ ] 弱项短补记得：12.5 kHz / 4FSK / 2-slot TDMA；滤网堵塞/压差异常/更换窗乱签常被误当覆盖病→禁功率战；挂 N；变更走 J  
- [ ] 知道下一篇三个候选（冷却水泵组与冷凝水侧 / 柴油发电机油位与泄漏巡检 / 精密空调吸排气压力与过热度过冷度）尚未写正文  

---

*手册 60 · 贴纸 BG（账 / 换 / 差 / 验 / 治）· 口诀：滤网有账，换网有窗，压差有法，会签才放 · AU≠BG · 教学虚构 L3 · 2026-11-07*
