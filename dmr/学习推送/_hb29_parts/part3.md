## 7. 台账卡模板（《本网室分电磁环境复测周期与变更触发台账卡》）

### 7.1 封面 · 拒签门槛（可贴值班台）

```text
  ┌──────── 拒签卡 · 贴纸 AB ────────┐
  │ 无书面周期或已超期未补     → 拒签仍合格 │
  │ 清单内变更未触发复测       → 拒签放行   │
  │ 无本站本期实测/套旧报告    → 拒签       │
  │ 方法与X不一致且无说明      → 拒签       │
  │ 假绿/功率战/只有结论       → 拒签+治理 │
  │ 公开包非 L3                → 拒发       │
  └─────────────────────────────────────┘
```

| 字段 | 填写 |
|------|------|
| 站点/室分角色 |  |
| 交维/起算日角色 |  |
| 周期（季/半年/年） |  |
| 下次应复测日 |  |
| 未关闭触发数 |  |
| 最近复测指针（脱敏） |  |
| 红字提示 | □周期未起跑 □已超期 □有冻结放行 |

### 7.2 周期与分工页（AB-周）

| 字段 | 填写 |
|------|------|
| 周期书面依据指针（脱敏） |  |
| 与 AA 分工说明 | 季巡抽测≠复测 □已书面 |
| X 方法锚指针 |  |
| I 口部/合路清单指针 |  |
| 应复测项目摘要 | 口部·噪底·上下行·两时隙… |

### 7.3 触发清单页（AB-触）

| 触发项 | 本期是否发生 | J 单指针 | 复测状态 |
|--------|--------------|----------|----------|
| 馈线/接头 |  |  | 未/待/已/未通过 |
| 合路/分路 |  |  |  |
| 增益/衰减 |  |  |  |
| 楼层/隧道拓扑 |  |  |  |
| 共址邻居 |  |  |  |
| 功率/载频角色 |  |  |  |
| 有源器件更换 |  |  |  |
| 其他 |  |  |  |

### 7.4 实测与签字页（AB-测 / AB-签）

| 字段 | 填写 |
|------|------|
| 复测时段角色 |  |
| 九字复测钉勾选 | 站□下□上□隙□口□噪□法□仪□判□ |
| 仪器有效期 |  |
| 与 X 方法一致 / 差异说明 |  |
| 结论对照判据 | 通过 / 未通过 |
| 签字人角色 · 本人签 |  |
| 未套旧□ 未假绿□ 未功率战□ |  |
| 互挂 I/X/AA/J/S/T/R/U |  |

### 7.5 夜班速填五行

1. 超期未复测站点数：____（拟签仍合格应为 0）  
2. 清单内变更裸放行：____（应为 0）  
3. 今日拒签仍合格/放行：____　原因 AB 子类：____  
4. 挂 S / 假绿挂 R：____  
5. 公开包抽查 L3：通过 / 不通过  

### 7.6 与总三联单字段对照

| 三联单栏 | 本卡对应 |
|----------|----------|
| 现象 | 拟复测/仍合格/放行 + AB 子类 |
| 证据 | AB2–AB7、九字钉、触发表 |
| 结论 | 待复测/冻结/合格/拒签 + 子类 |
| 动作 | 补周期、触发、补测、挂 S、拒签 |
| 脱敏 | 报告全文号与真实频点不进公开栏 |

---

## 8. 术语表（本篇约 18 词）+ 易错观念

| 术语 | 一句话 |
|------|--------|
| **室分电磁环境复测** | 对室内分布/隧道射频环境按书面周期或变更触发再次测量并对照判据，≠ 交维当天 X 报告本身 |
| **复测周期（AB-周）** | 季/半年/年等书面间隔与起算锚；超期未补禁签仍合格 |
| **变更触发（AB-触）** | 改馈线/合路/增益/拓扑/邻居/功率/载频等必须复测的条件清单 |
| **九字复测钉** | 站、下、上、隙、口、噪、法、仪、判（教学记忆） |
| **方法同 X** | 复测方法与交维/开站 X 报告方法一致，或书面差异说明并获批 |
| **仍合格** | 最近一次复测通过且未超期、无未关闭触发后的签字结论 |
| **套旧报告** | 把他期/他站/变更前报告当作本期仍合格依据，本篇红线 |
| **冻结放行** | 已变更未复测时限制使用的内部状态，≠ 已合格 |
| **噪底 / 底噪** | 接收机处的背景噪声水平；抬升常先打上行 |
| **口部** | 室分/隧道关键取样点角色（挂 I 清单） |
| **与 AA 分工** | 整站巡检抽测 ≠ 电磁环境正式复测，禁止互相顶替 |
| **假绿顶替** | 用监控全绿或假绿演练代替复测实测 |
| **功率战掩盖** | 用抬功率等方式制造「测好看」或顶覆盖，本篇红线 |
| **主贴 AB** | 室分复测周期与变更触发以 AB 为主键，可挂 I/X/Z/AA/J/S/T/R/U |
| **L3** | 公开包最高脱敏等级（本系列约定） |
| **消防定期检测隐喻** | 用大楼消防/防排烟年检+改管复检讲清周期、触发、禁套旧证 |
| **起算锚** | 周期从哪一日起算（常见交维日；以本网为准） |
| **裸变更** | 清单内变更未勾选触发、未复测就放行 |

**易错观念**

1. ✗ 交维 X 报告 = 永远合格 → ✓ 报告管「那天」；之后靠 AB 周期与触发。  
2. ✗ 改管子不大 = 可套旧报告 → ✓ 清单内变更必触发（规则2）。  
3. ✗ AA 季巡走过 = AB 复测完成 → ✓ 分工不同，禁止顶替（规则5）。  
4. ✗ 跳一季复测年终合并 = 没事 → ✓ 超期未补禁签仍合格（规则1）。  
5. ✗ 屏全绿 = 噪底没漂 → ✓ 假绿≠复测（规则6）。  
6. ✗ 边缘差就抬功率 → ✓ 禁功率战；查根因；跨网挂 S（规则7）。  
7. ✗ 只测下行场强即可 → ✓ 上行/口部/噪底几乎不可砍（规则3）。  
8. ✗ 方法换了没关系 → ✓ 须同 X 或书面说明（规则3）。  
9. ✗ 仪器过期但曲线好看 = 正式依据 → ✓ 过期拒签正式依据。  
10. ✗ 公开表扬可贴报告全文号与楼层坐标 → ✓ 规则8，L3。

---

## 9. 自测（12 题）+ 参考答案

1. 贴纸 AB 五个子类是什么？各用四个字以内说明。  
2. 「大楼消防/防排烟定期检测 + 装修改管复检」分别对应周、触、测、签中的哪段直觉？  
3. 八条硬规则里，哪一条要求复测周期书面钉死再签「仍合格」？  
4. 九字复测钉是哪九个字？为什么上行口部与噪底几乎不可砍？  
5. 无书面周期，只有交维 PDF，能否签「室分电磁环境仍合格」？  
6. 改合路增益后直接套用交维报告，能否放行？  
7. AA 季巡口部打勾后，能否把巡检表改日期当作 AB 复测？  
8. 屏全绿、旧噪底曲线还在，能否代替本期实测？主贴谁、次挂谁？  
9. 楼层装修后边缘变差，施工建议抬功率，应如何处置？跨网可疑挂什么？  
10. 复测方法与 X 不一致且无书面说明，能否签字？  
11. 仪器检定过期但曲线好看，能否作正式复测依据？  
12. 公开表扬稿能否出现报告全文号、楼层坐标、真实频点？

### 参考答案

1. 周/触/测/签/治：周期钉死、变更触发、本期实测、复测才签、跳测套旧治理。  
2. 检测周期书面→周；装修改管必复检→触；按规程实测仪器记录→测；合格才签设施完好→签（跳检套旧证功率顶着→治）。  
3. 规则1。  
4. 站、下、上、隙、口、噪、法、仪、判；室分上行常先塌，噪底抬升常先打上行。  
5. 不能；规则1，先补书面周期。  
6. 不能；规则2、4。  
7. 不能；规则3、5。  
8. 不能；主贴 AB，挂 R（规则6）。  
9. 禁止抬功率掩盖；触发复测查根因；跨网挂 S，投诉挂 T（规则7）。  
10. 不能（或须先补差异说明并获批后重走）；规则3。  
11. 不能；规则3。  
12. 不能；规则8。

---

## 10. 加深阅读与视频（均已用 curl / oEmbed 核对；以核验当时为准）

**本篇专项方法级阅读（室内覆盖 / DAS / 复测与变更；借方法，不替代本网周期与签字）**  
1. **[CommScope · In-building cellular: the Fact File](https://webresources.commscope.com/download/assets/In-building+cellular:+the+Fact+File/70289bae3bd611f0a7293e67199c332c)**——室内分布为何要多节点、头端/拉远直觉（通用蜂窝 DAS；借「改拓扑要再验证」）。  
2. **[Huawei · Indoor coverage 公开文章](https://www.huawei.com/en/technology-insights/industry-insights/outlook/mobile-broadband/wireless-for-sustainability/articles/indoor-coverage)**——室内覆盖挑战入门（通用）。  
3. **[TechTarget · 9 Steps for Wireless Network Planning and Design](https://www.techtarget.com/it-infrastructure/feature/9-steps-for-wireless-network-planning-and-design)**——覆盖规划与环境因素（通用 Wi-Fi/无线；借「环境变了要再评」）。  
4. **[TIA TSB-88 标准条目](https://tiaonline.org/standard/tia-tsb-88/)** · **[Softwright · TSB-88 FAQ](https://www.softwright.com/faq/engineering/tsb88faq.html)**——覆盖验证与可重复抽样思路（复测抽样可借方法，门限以合同/X方案为准）。  
5. **[Tait · The 6 Steps of Testing to get to "Final Acceptance"](https://www.taitcommunications.com/en/about-us/news/2012/10/25/the-6-steps-of-testing-to-get-to-final-acceptance)**——验收后仍要跟踪（与「交维报告≠永远合格」咬合）。  
6. **[P25 Best Practice · Field Acceptance Tests](https://www.p25bestpractice.com/implementing/field-acceptance-tests/)**——现场验收与 burn-in 方法级（回指 Z/X，服务复测意识）。  
7. **[Flowdit · Site Acceptance Test (SAT)](https://flowdit.com/site-acceptance-test/)** · **[Engineversity · FAT, SAT and commissioning](https://engineversity.com/courses/process-control-systems-for-beginners/fat-sat-and-commissioning/)**——到站合格≠永远合格。

**故事类比：建筑消防设施检测 / 维护保养（只借直觉，不是台站法定依据）**  
8. **[国务院公报相关消防安全责任制公开文本入口例](https://www.gov.cn/gongbao/content/2021/content_5623051.htm)**——设施完好有效、责任可追溯等直觉（以原文为准）。  
9. **[国家标准信息公共服务平台 · 建筑消防设施检测技术规范项目页](https://std.samr.gov.cn/gb/search/gbDetailed?id=58453A0FBFA6F897E06397BE0A0AAC1B)**——检测内容/技术要求/方法分章直觉（教学指针）。  
10. **[江苏省消防救援相关公开站点入口](https://js.119.gov.cn/)**——地方维护保养规程公开获取入口（以站点现行文件为准；只借「周期+记录+改管须管」）。  
11. Wikipedia：[Preventive maintenance](https://en.wikipedia.org/wiki/Preventive_maintenance)（定期维护 ≠ 一次性验收）。

**国内无线电法规与电磁环境（参数秩序；复测发现漂移要回挂，不私改）**  
12. **[《中华人民共和国无线电管理条例》（中国政府网）](https://www.gov.cn/zhengce/zhengceku/2016-11/25/content_5137687.htm)** · **[国务院公报版](https://www.gov.cn/gongbao/content/2016/content_5148745.htm)**。  
13. **[《无线电频率使用许可管理办法》（中国政府网）](https://www.gov.cn/zhengce/2022-08/23/content_5722706.htm)**。  
14. **[《地面无线电台（站）管理规定》（中国政府网）](https://www.gov.cn/zhengce/202310/content_6908889.htm)** · **[国务院公报 · 工信部令第60号](https://www.gov.cn/gongbao/content/2023/content_5745291.htm)**。  
15. **[国无办〔2025〕1号（工信部公开页，以现行为准）](https://www.miit.gov.cn/jgsj/wgj/wjfb/art/2025/art_31a0765b521e4dc493262188aea65618.html)** · **[无线电管理局首页](https://www.miit.gov.cn/jgsj/wgj/index.html)** · **[无线电管理局政策法规入口](https://www.miit.gov.cn/jgsj/wgj/zcfg/index.html)**（部分出口偶发 403，以官方可访问为准）。  
16. **[工信部无线电管理局 · 法律法规栏目例](https://www.miit.gov.cn/jgsj/wgj/flfg/art/2020/art_9e0f1197e2084ec19425ea2e0cd9586f.html)** · **[部门规章例一](https://www.miit.gov.cn/jgsj/wgj/bmgz/art/2020/art_a23d32952faa494095758a24b7326710.html)** · **[部门规章例二](https://www.miit.gov.cn/jgsj/wgj/bmgz/art/2024/art_ac48d45b89ef4706a0f7fd8fd7f70a13.html)**。  
17. **[生态环境部 · 《电磁环境控制限值》GB 8702—2014 公开页](https://www.mee.gov.cn/ywgz/fgbz/bz/bzwb/hxxhj/dcfsbz/201410/t20141022_290449.htm)** · **[GB 8702 PDF](https://www.mee.gov.cn/ywgz/fgbz/bz/bzwb/hxxhj/dcfsbz/201410/W020141022352826534956.pdf)** · **[全国标准信息平台条目](https://std.samr.gov.cn/gb/search/gbDetailed?id=71F772D7ECC9D3A7E05397BE0A0AB82A)**（限值以原文为准；与 X/复测咬合）。  
18. **[《电磁辐射环境保护管理办法》相关公开文本例](https://www.gov.cn/zhengce/2010-09/06/content_2602563.htm)** · **[国务院公报相关例](https://www.gov.cn/gongbao/content/2010/content_1702206.htm)**（程序以属地现行要求为准）。  
19. **[国家无线电监测中心 / SRRC 门户](https://www.srrc.org.cn/)** · **[工信部首页](https://www.miit.gov.cn/)**。

**ITU / ETSI / DMR（传播与参数指针；不替代复测签字）**  
20. **[ITU-R P.1238（室内传播模型推荐）](https://www.itu.int/rec/R-REC-P.1238/en)** · **[ITU-R P.1411（室外短距离/室外到室内相关）](https://www.itu.int/rec/R-REC-P.1411/en)**——室内/近场传播方法级指针。  
21. **[ITU-R SM.1753](https://www.itu.int/rec/R-REC-SM.1753/en)** · **[ITU-R SM.1880](https://www.itu.int/rec/R-REC-SM.1880/en)** · **[ITU-R SM.329](https://www.itu.int/rec/R-REC-SM.329/en)** · **[ITU-R SM.1879](https://www.itu.int/rec/R-REC-SM.1879/en)**——监测/测量相关推荐（方法级）。  
22. **[ITU-R Terrestrial 入口](https://www.itu.int/en/ITU-R/terrestrial/Pages/default.aspx)** · **[Monitoring 入口](https://www.itu.int/en/ITU-R/terrestrial/monitoring/Pages/default.aspx)** · **[National Spectrum Management 手册出版物页](https://www.itu.int/pub/R-HDB-21-2015)** · **[Spectrum Monitoring 手册出版物页](https://www.itu.int/pub/R-HDB-23)**。  
23. **[ETSI TS 102 361-1 V2.7.1（PDF）](https://www.etsi.org/deliver/etsi_TS/102300_102399/10236101/02.07.01_60/ts_10236101v020701p.pdf)** · **[ETSI TR 102 398](https://www.etsi.org/deliver/etsi_TR/102300_102399/102398/01.05.01_60/tr_102398v010501p.pdf)** · **[ETSI Standards 检索](https://www.etsi.org/standards)**。  
24. **[DMR Association · Standards](https://www.dmrassociation.org/dmr-standards.html)** · **[DMR Association 首页](https://www.dmrassociation.org/)** · **[Tait Communications 官网](https://www.taitcommunications.com/)**。

**测量仪器与 EMF 公开资料（看懂「测」，不是造假教程）**  
25. **[Rohde & Schwarz · EMF testing 方案页](https://www.rohde-schwarz.com/us/solutions/electronics-testing/emc-testing/emf-testing/emf-testing_253445.html)** · **[TS-EMF 便携系统产品页](https://www.rohde-schwarz.com/us/products/test-and-measurement/radiated-testing/rs-ts-emf-portable-emf-measurement-system_63493-8174.html)**。  
26. **[R&S EMF Measurement Application 选项说明 PDF](https://scdn.rohde-schwarz.com/ur/pws/dl_downloads/pdm/cl_brochures_and_datasheets/option_sheet/3683_7319_32/EMF-measurement-application-K105-for-FPH-and-ZPH-v0110.pdf)**。  
27. **[Keysight · EMF Triaxial Isotropic Antenna 资料](https://www.keysight.com/us/en/assets/3121-1035/data-sheets/Electromagnetic-Field-EMF-Triaxial-Isotropic-Antenna.pdf)**。

**名词垫脚石（定义级）**  
28. Wikipedia：[Distributed antenna system](https://en.wikipedia.org/wiki/Distributed_antenna_system) · [Noise floor](https://en.wikipedia.org/wiki/Noise_floor) · [Passive intermodulation](https://en.wikipedia.org/wiki/Passive_intermodulation) · [Received signal strength indication](https://en.wikipedia.org/wiki/Received_signal_strength_indication) · [Spectrum analyzer](https://en.wikipedia.org/wiki/Spectrum_analyzer) · [Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio) · [Land mobile radio system](https://en.wikipedia.org/wiki/Land_mobile_radio_system) · [Drive testing](https://en.wikipedia.org/wiki/Drive_testing) · [Spectrum management](https://en.wikipedia.org/wiki/Spectrum_management)。

**视频（YouTube，已用 oEmbed 核验标题与频道）**  
29. **[Rohde & Schwarz · Understanding Spectrum Analyzers – ACLR](https://www.youtube.com/watch?v=mco_BJ1mjNo)**——「看见」频谱；**不是**造假教程。  
30. **[Shure · What is Intermodulation?](https://www.youtube.com/watch?v=IrlyAei02_o)**——共址与抬功率的互调直觉；对照禁功率战。  
31. **[MPSCS · Site Maintenance Inspection and Preventative Maintenance on our Tower Sites](https://www.youtube.com/watch?v=4IRdxeXN1do)**——塔站预防性维护与巡检记录（借「定期还要做」，非室分专项）。  
32. **[Sunil Kashyap · How to perform site audit or RF audit in Telecom field](https://www.youtube.com/watch?v=7Awj0-rDfeA)**——电信机房/射频站点巡检直觉（通用）。  
33. **[NATEsafety · How to Conduct Tower Inspections](https://www.youtube.com/watch?v=dFs4At6-hhU)**——巡检安全与检查项入门。  
34. **[Engineered Vision · FAT and SAT Explained](https://www.youtube.com/watch?v=x7qNC6Rtp9I)** · **[Careers360 · FAT & SAT](https://www.youtube.com/watch?v=3aafLF9o0NA)**——出厂/到站合格直觉（回指交维≠永远）。  
35. **[Scanner School · What is DMR?](https://www.youtube.com/watch?v=aQX_JbTbXuY)**（弱项：时隙与数字话音）。

> **诚实说明**：没有找到「DMR 专网室分/隧道电磁环境复测周期与变更触发制度（含贴纸 AB + 插页 AB1–AB8 + 消防定期检测/改管复检隐喻 + 拒签卡 + 与 AA/X/I 分工表）」的专项中文公开视频或制度文章；上文最贴题的是 **室内 DAS/覆盖公开科普（CommScope Fact File 等）**、**TSB-88 覆盖抽样方法**、**消防设施检测/维保公开标准指针（仅类比）**，以及频谱仪/互调/塔站预防性维护等通用视频。其余为国内无线电法规、GB 8702、ITU 室内传播与监测推荐、ETSI/DMR 参数指针。需按贴纸 AB 与 AB1–AB8 拼进本网流程。`video_found=true`（通用频谱/互调/塔站巡检/FAT-SAT/DMR 基础），**非**室分复测专项。任何「教你如何把复测记录改好看」「如何抬功率应付抽测」「如何套旧报告过关」的页面即使 200，本篇也**不引用**。

**库内必回：** 手册10（I）、16（O）、25（X）、27（Z）、28（AA）、11（J）、19（R）、20（S）、21（T）、22（U）、06（脱敏）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子
- 贴纸 **AB** 五子类：周 / 触 / 测 / 签 / 治——双字母续写的第二张，负责室分/隧道「还合不合格、改了什么必须再测」。  
- 故事：大楼消防/防排烟定期检测 + 装修改管必复检——验收证管那天；周期要检；改管必复检；禁套旧证。  
- 阶段梯：X 方法锚 → 周期钉死 → 触发清单 → 本期实测 → 复测签字 → 未通过整改再测。  
- 八条硬规则：**周期书面钉死**；**变更必触发**；**本站本期实测且方法同 X**；**复测通过才签**；**与 AA/I/X 分工禁顶替**；**主贴 AB，假绿≠复测**；**跨网挂 S、禁功率战、变更走 J**；**脱敏 L3**。

### 11.2 下一篇手册候选（本篇不写正文）
- **应急通信车 / 机动站快速开站与撤收边界**（与 V/Y/Z 咬合，仍 L3）  
- **备件周转与金机轮换台账**（与 Q/AA/K/AB 咬合：金机、备件、复测漂移后基线更新）  
- **隧道/地铁区间电磁环境联测与换乘节点责任界面**（与 AB/I/S 咬合）

### 11.3 给带新人的三句话
1. 交维 X 报告不是终身免测凭证：室分电磁环境要有书面复测周期，改了管子必须触发复测。  
2. 季巡抽测发现口部变差可以报警，但不能用巡检表改日期顶替正式复测；方法要跟 X 对齐，上行和噪底几乎不可砍。  
3. 假绿不是复测合格；禁套旧报告；禁功率战；跨网挂 S；公开材料脱敏；主贴 AB。

### 11.4 一张图记住本篇（收工贴纸）
```text
  ┌────────── 贴纸 AB ──────────┐
  │ 周 周期钉死·与AA分工         │
  │ 触 改管必测·清单触发         │
  │ 测 本期实测·方法同X          │
  │ 签 复测通过·禁套旧报告       │
  │ 治 跳测套旧·功率战假绿泄密   │
  └────────────────────────────┘
    消防年检 · 改管复检 · 室分仍合格
```

---

## 12. 本篇检查清单（自学打勾）
- [ ] 能背贴纸 AB 五子类与消防/防排烟定期检测 + 装修改管复检故事  
- [ ] 能画 X 方法锚→周期→触发→实测→签字阶段梯  
- [ ] 能背八条硬规则（周期、触发、本期实测方法同X、复测才签、与AA分工、假绿≠复测、挂S禁功率战、L3）  
- [ ] 能背九字复测钉，并能讲清室分仍要测上行口部与噪底  
- [ ] 会填插页 AB1–AB8、触发清单与拒签卡  
- [ ] 12 题自测过关  
- [ ] 知道 §10 诚实说明：无专项室分复测视频，仅 DAS/覆盖科普 + 消防类比 + 通用频谱/巡检视频  
- [ ] 回库用 L3 重对一次本网最近一座带室分/隧道站点的：复测周期书面、触发清单、最近一次复测与 X 方法对照、未关闭触发

---

*手册29 · 室分电磁环境复测周期与变更触发 · 学习推送 · 2026-10-23 09:52 +08:00*
