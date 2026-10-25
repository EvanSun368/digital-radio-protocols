<!-- handbook33 part 3/3 · 油机市电切换与机房供电巡检 · 接上一部分继续 -->

## 7. 台账卡模板（《本网油机市电切换与机房供电巡检台账卡》）

> 教学模板，可复印；字段用角色标签；**L3**。

### 7.1 封面

| 项 | 填写（角色） |
|----|--------------|
| 脱敏机房编号 | |
| 本期窗编号 | |
| 主贴 | **AF** |
| 支撑贴 | K / N / AA / R / J（勾选） |
| 拒签卡 | 已贴 □ / 触发项： |

### 7.2 切换窗页（AF-切）

| 项 | 是/否/角色值 |
|----|--------------|
| 书面窗日期时段 | |
| 书面切倒方案附件号 | |
| 到场角色勾选 | 电源□ 网管□ 站务□ 其他□ |
| 业务影响告知 | 已□ 不涉及□ |

### 7.3 油机账页（AF-油）

| 项 | 角色值 |
|----|--------|
| 油机主人角色 | |
| 燃油/日用箱 | 油位角色 / 记录日 |
| 机油 / 冷却 | 状态角色 / 记录日 |
| 电瓶 | 状态角色 / 记录日 |
| 上次试车日与结果角色 | |

### 7.4 巡检路线页（AF-巡）

| 对象 | 勾选 | 异常简述（L3） |
|------|------|----------------|
| 市电进线 | □ | |
| ATS/切换装置 | □ | |
| 整流 / UPS | □ | |
| 直流屏 / −48 V 角色 | □ | |
| 油机侧外观与附件 | □ | |
| 环境/接地角色项 | □ | |

### 7.5 实测页（AF-验）

| 项 | 角色记录 |
|----|----------|
| 切出时刻角色 | |
| 电压/频率观察角色 | |
| 负载观察角色 | |
| 稳载时长角色 | |
| 回切时刻与结果 | |
| 告警联动核对（N 指针） | |
| 禁套声明：本机房本期 | 签 |

### 7.6 会签页（AF7）

| 角色 | 本人签 | 日期角色 |
|------|--------|----------|
| 电源授权 | | |
| 网管/值班授权 | | |
| 结论：合格□ 有条件整改□ 拒签□ | | |
| 重大未闭项主人与期 | | |

### 7.7 夜班速填五行

1. 窗：有 / 无  
2. 油账：正常 / 断档项××  
3. 巡检：完成 / 漏××  
4. 实测：有 / 无 / 拒签原因××  
5. 挂牌：R/N/J 有无  

---

## 8. 术语表（本篇约 18 词）+ 易错观念

| 术语 | 一句话（教学） |
|------|----------------|
| **市电** | 正常公用或进线电源（角色称谓） |
| **油机** | 柴油（或本网规定燃料）发电机组备用电源 |
| **ATS** | 自动转换开关；监测市电并协调切向备用源 |
| **切倒方案** | 书面规定的切出、稳载、回切、中止顺序 |
| **AF-切** | 窗钉死、方案书面、到场齐全 |
| **AF-油** | 油机本体与试车台账有主人 |
| **AF-巡** | 机房供电巡检路线与周期钉死 |
| **AF-验** | 本机房本期切换/试车实测 |
| **AF-治** | 假绿、顶替、套报告、功率战、泄密治理 |
| **假绿** | 系统/大屏显示正常，但无本期切换/试车会签 |
| **套报告** | 把他站他期记录改号当本期 |
| **回切** | 市电恢复后从油机侧切回市电侧并确认 |
| **告警联动** | 切换过程告警是否与 N 监控语义一致可解释 |
| **九字供电钉** | 窗案油巡房回签闭密（教学记忆） |
| **−48 V** | 电信机房常见直流供电标称（公开常识） |
| **整流** | 交流转直流供负载并浮充电池 |
| **与 K/N/AA 分工** | 交维剧本 / 监控风暴 / 首年日历；AF 管切换巡检门卫 |
| **倒换窗冲击** | 切换瞬间电压/相位变化可能导致基站抖动或重启 |

**易错观念**

- ❌「网管绿=备电过」→ ✅ 假绿挂 R，主贴 AF。  
- ❌「交维 K 签过=永远不用试」→ ✅ K 不顶替 AF 本期。  
- ❌「拷邻站报告更快」→ ✅ 禁套；本窗本机房实测。  
- ❌「随便按一下练手」→ ✅ 无窗拒切。  
- ❌「倒换抖就抬功率」→ ✅ 禁功率战；先供电与 N。

---

## 9. 自测（12 题）+ 参考答案

1. 贴纸 AF 五个子类是什么？各用四个字以内说明。  
2. 医院备用发电机试车故事里，「试车窗钉死≠随便踩油门」主要对应 AF 哪一段？  
3. 八条硬规则里，哪一条要求切换/试车窗与书面方案钉死？  
4. 为什么倒换窗要「先问供电再开射频工单」？与 12.5 kHz / 4FSK / 2-slot 有什么关系？  
5. 「供电合格」至少要具备哪几样（九字供电钉里不可砍的）？  
6. 用 K 交维签顶掉本期油机试车，违反哪条？主贴谁？  
7. AF 与 K / N / AA 的分工一句话？  
8. 套邻站试车报告，主贴什么？能不能改号交差？  
9. 大屏全绿想签供电合格，应挂什么提醒？主贴谁？  
10. 机动站 AC 电源勾选，能不能代替固定机房 AF 月度试车？  
11. 私自改 ATS 定值后应走什么变更贴纸并怎样处理？  
12. 公开材料能不能贴真实油机序列号与机房全称？依据哪条规则？

### 参考答案

1. **切**（窗与方案到场）、**油**（油机账与试车）、**巡**（供电巡检周期对象）、**验**（本机房本期实测）、**治**（假绿顶替套报告功率战泄密）。  
2. **AF-切**（亦可答治：禁随便踩）。  
3. **规则1**。  
4. 切换冲击可能导致重启/假绿/话务抖；空口台阶（12.5 kHz/4FSK/2-slot）没变，先证供电再谈射频，避免误开功率战。  
5. **书面窗、油机账、本机房本期实测、会签**（规则1–5；九字钉核心）。  
6. **规则6**；主贴仍是 **AF**。  
7. **K 交维剧本、N 监控风暴、AA 首年日历、AF 管切换窗·油机试车·供电巡检能不能签合格**。  
8. **AF-治**；**不能**。  
9. 挂 **R**；主贴 **AF**（规则6）。  
10. **不能**；AC 勾选≠ AF 机房试车窗。  
11. **J**，并重开 AF 验窗（规则7）。  
12. **不能**；**规则8 脱敏 L3**。

---

## 10. 加深阅读与视频（均已用 curl / oEmbed 核对；以核验当时为准）

**本篇专项方法级阅读（ATS / 油机试车 / 电信机房电源；借秩序，不替代本网 AF 签字）**  
1. **[DIYPowers · What Is an ATS for a Diesel Generator](https://www.diypowers.com/news/what-is-an-ats-for-a-diesel-generator)**——ATS 监测市电→启机→切载→回切→停机六步直觉（厂商科普；**不是**本网 AF 法定制度）。  
2. **[Wikipedia · Automatic transfer switch](https://en.wikipedia.org/wiki/Automatic_transfer_switch)** · **[Transfer switch](https://en.wikipedia.org/wiki/Transfer_switch)** · **[Diesel generator](https://en.wikipedia.org/wiki/Diesel_generator)** · **[Standby generator](https://en.wikipedia.org/wiki/Standby_generator)**——转换开关与备用发电机基础词条。  
3. **[Wikipedia · Uninterruptible power supply](https://en.wikipedia.org/wiki/Uninterruptible_power_supply)** · **[Rectifier](https://en.wikipedia.org/wiki/Rectifier)** · **[Emergency power system](https://en.wikipedia.org/wiki/Emergency_power_system)** · **[Power outage](https://en.wikipedia.org/wiki/Power_outage)**——UPS/整流/应急电源/停电基础。  
4. **[Wikipedia · Battery room](https://en.wikipedia.org/wiki/Battery_room)** · **[VRLA battery](https://en.wikipedia.org/wiki/VRLA_battery)** · **[Lead–acid battery](https://en.wikipedia.org/wiki/Lead%E2%80%93acid_battery)** · **[Switchgear](https://en.wikipedia.org/wiki/Switchgear)** · **[Circuit breaker](https://en.wikipedia.org/wiki/Circuit_breaker)**——电池室/开关设备相关词条。  
5. **[Cummins 公开 PDF · NFPA 110 Testing and Service Requirements for Standby Power Systems](https://www.cummins.com/sites/default/files/2021-02/External%20%28Final%29%20NFPA%20110%20Testing%20and%20service%20requirements%20for%20Standby%20Power%20Systems_12.15.2020.pdf)**——备用电源月度试车/维护公开转述（**境外标准教学类比，非中国专网法定依据**）。  
6. **[Minnesota Dept. of Health · Inspection and Testing of Emergency Generators（PDF）](https://www.health.mn.gov/facilities/regulation/engineering/lscgensets24.pdf)**——医院应急发电机周检/月度带载试车公开检查要点（**故事类比：窗、油、冷却、电瓶、要留记录**）。  
7. **[NFPA · NFPA 110 标准入口](https://www.nfpa.org/codes-and-standards/all-codes-and-standards/list-of-codes-and-standards/detail?code=110)** · **[产品页入口](https://www.nfpa.org/product/nfpa-110-standard/p0110code)**——备用电源系统标准公开入口（**只借「要测要记」秩序**）。  
8. **[ChatDiagram · Telecom site DC battery backup SLD 例](https://www.chatdiagram.com/example/sld-telecom-site-dc-battery-backup)**——电信站市电/油机/ATS/整流/−48 V/电池单线图公开例（借「切换间隙电池扛」）。  
9. **[Vertiv · Telecom solutions](https://www.vertiv.com/en-us/solutions/telecom/)** · **[Eltek](https://www.eltek.com/)** · **[Generac · Automatic transfer switches](https://www.generac.com/industrial/products/automatic-transfer-switches)**——机房/电信电源与 ATS 厂商公开入口（科普级）。  
10. **[Wikipedia · Preventive maintenance](https://en.wikipedia.org/wiki/Preventive_maintenance)** · **[Facility management](https://en.wikipedia.org/wiki/Facility_management)** · **[Telephone exchange](https://en.wikipedia.org/wiki/Telephone_exchange)**——预防性维护与机房直觉。  
11. **[DMR Association · Standards](https://www.dmrassociation.org/dmr-standards.html)** · **[首页](https://www.dmrassociation.org/)** · **[TS 102 361-1 PDF](https://dmrassociation.org/public-downloads/standards/ts_10236101v020701p.pdf)**——空中接口标准入口（**不规定**油机试车台账）。  
12. **[Tait Communications](https://www.taitcommunications.com/)** · **[Tait Radio Academy](https://www.taitradioacademy.com/)** · **[Hytera](https://www.hytera.com/)** · **[Motorola Solutions](https://www.motorolasolutions.com/)** · **[Sepura](https://www.sepura.com/)**——专网厂商公开入口（电源交维常与 K 同读）。

**故事类比：医院应急电源 / 双电源演练（只借直觉，不是台站法定依据）**  
13. 上文第 5–7 条（NFPA 110 / 医院发电机检查 PDF）即故事主锚。  
14. **[应急消防相关公开入口例 · 119 消防宣传](https://js.119.gov.cn/)** · **[国务院公报相关消防法规公开例](https://www.gov.cn/gongbao/content/2021/content_5623051.htm)**——只借「要演练、要记录」秩序（**消防/应急规范，非无线电 AF 依据**）。  
15. Wikipedia：[Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio) · [Land mobile radio system](https://en.wikipedia.org/wiki/Land_mobile_radio_system)。

**国内无线电法规（台站秩序指针；无窗乱切不是法外）**  
16. **[《中华人民共和国无线电管理条例》（中国政府网）](https://www.gov.cn/zhengce/zhengceku/2016-11/25/content_5137687.htm)** · **[国务院公报版](https://www.gov.cn/gongbao/content/2016/content_5148745.htm)**。  
17. **[《无线电频率使用许可管理办法》（中国政府网）](https://www.gov.cn/zhengce/2022-08/23/content_5722706.htm)**。  
18. **[《地面无线电台（站）管理规定》（中国政府网）](https://www.gov.cn/zhengce/202310/content_6908889.htm)** · **[国务院公报 · 工信部令第60号](https://www.gov.cn/gongbao/content/2023/content_5745291.htm)**。  
19. **[无线电管理局首页](https://www.miit.gov.cn/jgsj/wgj/index.html)** · **[政策法规入口](https://www.miit.gov.cn/jgsj/wgj/zcfg/index.html)** · **[工信部首页](https://www.miit.gov.cn/)**（部分出口偶发 403，以可访问为准）。

**ITU / ETSI / 验收方法级**  
20. **[ITU-R SM.1753](https://www.itu.int/rec/R-REC-SM.1753/en)** · **[ITU-R Monitoring](https://www.itu.int/en/ITU-R/terrestrial/monitoring/Pages/default.aspx)**。  
21. **[ETSI Standards](https://www.etsi.org/standards)**。  
22. **[P25 Best Practice · Field Acceptance Tests](https://www.p25bestpractice.com/implementing/field-acceptance-tests/)** · **[Flowdit · SAT](https://flowdit.com/site-acceptance-test/)**——到站/现场合格直觉（合格步骤≠假绿）。

**测量 / 站点维护相关公开资料（看懂「巡与记」，不是造假教程）**  
23. Wikipedia：[Standing wave ratio](https://en.wikipedia.org/wiki/Standing_wave_ratio) · [Noise floor](https://en.wikipedia.org/wiki/Noise_floor) · [RSSI](https://en.wikipedia.org/wiki/Received_signal_strength_indication) · [Spectrum analyzer](https://en.wikipedia.org/wiki/Spectrum_analyzer)。  
24. **[Rohde & Schwarz · EMF testing](https://www.rohde-schwarz.com/us/solutions/electronics-testing/emc-testing/emf-testing/emf-testing_253445.html)**——仪器公开入口。

**视频（YouTube，已用 oEmbed 核验标题与频道）**  
25. **[Cummins · Integrated Power Systems Ep.8: Transfer Switch Functionalities & Applications](https://www.youtube.com/watch?v=6idadtpqSrg)**——ATS 功能与应用（厂商向；借「切载/回切/试车行使」）。  
26. **[Eaton PSEC · Automatic transfer switch (ATS) fundamentals](https://www.youtube.com/watch?v=yjphp4SBkSA)**——ATS 基础（厂商向；**不是** AF 台账专项）。  
27. **[Standby Power Solutions · Transfer Switch Sequence of Operation OTIII](https://www.youtube.com/watch?v=-g5C_LP39ys)**——转换开关动作顺序演示。  
28. **[RJCONTROL · Anatomy of an Automatic Transfer Switch ASCO](https://www.youtube.com/watch?v=y8AmrnCSRDE)**——ATS 结构直观（厂商/集成向）。  
29. **[S Snider · Generac automatic transfer switch explained, demo](https://www.youtube.com/watch?v=rT_3JYZS9Mg)**——家用/小型 ATS 演示（借「有转换才有备电闭环」）。  
30. **[MPSCS · Site Maintenance Inspection and Preventative Maintenance](https://www.youtube.com/watch?v=4IRdxeXN1do)**——站点维护与记录（借「要巡要记」）。  
31. **[Engineered Vision · FAT and SAT Explained](https://www.youtube.com/watch?v=x7qNC6Rtp9I)** · **[Careers360 · FAT & SAT](https://www.youtube.com/watch?v=3aafLF9o0NA)**——出厂/到站合格直觉（回指：假绿≠会签）。  
32. **[Scanner School · What is DMR?](https://www.youtube.com/watch?v=aQX_JbTbXuY)**（弱项：时隙与数字话音）。  
33. **[Rohde & Schwarz · Understanding Spectrum Analyzers – ACLR](https://www.youtube.com/watch?v=mco_BJ1mjNo)** · **[Shure · What is Intermodulation?](https://www.youtube.com/watch?v=IrlyAei02_o)**——频谱/互调；对照禁功率战。  
34. **[NATEsafety · How to Conduct Tower Inspections](https://www.youtube.com/watch?v=dFs4At6-hhU)** · **[Sunil Kashyap · How to perform site audit or RF audit](https://www.youtube.com/watch?v=7Awj0-rDfeA)**——巡检/审计通用视频。

> **诚实说明**：没有找到「DMR 专网油机/市电切换与机房供电巡检制度（含贴纸 AF + 插页 AF1–AF8 + 医院备用发电机月度试车隐喻 + 拒签卡 + 与 K/N/AA 分工表）」的专项中文公开视频或制度文章；上文最贴题的是 **ATS/柴油机公开科普与视频**、**NFPA 110 / 医院应急发电机检查公开 PDF（故事类比）**、**电信 −48 V / ATS 单线图公开例**，以及站点维护/FAT-SAT/DMR 基础与频谱互调视频。其余为国内无线电法规与 ETSI/DMR 入口。需按贴纸 AF 与 AF1–AF8 拼进本网流程。`video_found=true`（ATS/转换开关专项视频 + 通用巡检/FAT-SAT/DMR 基础），**非** AF 台账专项。部分境外厂商长文页（如部分 Eaton/Analog 域名）在核验出口偶发不可达，本篇以已 200/oEmbed 通过的链接为准。任何「教你如何伪造试车账」「如何套邻站报告过关」「如何抬功率压倒换抖」「如何绕过告警」的页面即使 200，本篇也**不引用**。

**库内必回：** 手册12（K）、15（N）、28（AA）、30（AC）、31（AD）、32（AE）、19（R）、21（T）、06（脱敏）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子
- 贴纸 **AF** 五子类：切 / 油 / 巡 / 验 / 治——双字母续写的第六张，负责切换窗·油机试车·机房供电巡检「窗清不清、账清不清、本期过了没有」。  
- 故事：医院备用发电机月度试车 + 配电室双电源切换演练——窗钉死≠随便踩油门；市电掉了才发现没油=拒签；网管绿但半年没实车=假绿；套邻站报告=拒签。  
- 阶段梯：钉窗 → 清油机账 → 巡检到位 → 本期实测 → 会签合格 → 变更再验。  
- 八条硬规则：**切换/试车窗与书面方案钉死**；**油机与燃油/冷却/电瓶有主人有账**；**机房供电巡检周期与对象钉死**；**本机房本期实测禁套他站**；**切换/试车通过才签**；**禁顶替 K/N/AA/AC/AD 等，主贴 AF，假绿≠放行挂 R**；**倒换窗禁功率战、监控风暴挂 N、变更走 J**；**脱敏 L3**。

### 11.2 下一篇手册候选（本篇不写正文）
- **电池与充电器梯队轮换与容量抽检台账**（与 AF 油机/直流屏、AD 备件周转咬合，仍 L3）  
- **多业主合路/POI 机房责任界面与干扰分诊**（与 S/AE 界面咬合延伸）  
- **机房温湿度与空调联锁巡检边界**（与 AF 供电巡检、AA 首年巡检咬合）

### 11.3 给带新人的三句话
1. 备电不是网管绿就过：窗钉死，油机有账，本期实测，含回切。  
2. 试车不是随便踩油门：书面方案，到场齐全，会签才算供电合格。  
3. 假绿挂 R；主贴 AF；K/N 不顶替；倒换窗禁功率战；公开脱敏 L3。

### 11.4 一张图记住本篇（收工贴纸）
```text
  ┌────────── 贴纸 AF ──────────┐
  │ 切 窗钉死·书面方案·到场     │
  │ 油 燃油冷却电瓶·试车有账   │
  │ 巡 供电路线·对象·周期钉死 │
  │ 验 本机房本期·回切告警核   │
  │ 治 假绿顶替套报告功率战泄密 │
  └────────────────────────────┘
    医院油机试车 · 假绿≠供电合格
```

---

## 12. 本篇检查清单（自学打勾）
- [ ] 能背贴纸 AF 五子类与医院备用发电机月度试车 / 双电源切换演练故事  
- [ ] 能画 钉窗→清油机账→巡检→实测→会签→变更再验 阶段梯  
- [ ] 能背八条硬规则（窗方案、油机账、巡检周期、本期实测、切换才签、禁顶替假绿挂R、禁功率战挂N走J、L3）  
- [ ] 能背九字供电钉，并能讲清为什么倒换窗要先问供电  
- [ ] 会填插页 AF1–AF8、拒签卡与供电巡检台账卡  
- [ ] 能说出 AF 与 K/N/AA 分工，以及假绿/套报告/随便按三种拒签  
- [ ] 12 题自测过关  
- [ ] 知道 §10 诚实说明：无专项 AF 台账视频，仅 ATS/医院试车公开文 + 通用巡检视频 + ATS 专项视频  
- [ ] 回库用 L3 重对一次本网最近油机试车或市电切换：窗、油机账、巡检、本期实测、会签、未闭项

---

*手册33 · 油机市电切换与机房供电巡检 · 学习推送 · 2026-10-25 09:52 +08:00*
