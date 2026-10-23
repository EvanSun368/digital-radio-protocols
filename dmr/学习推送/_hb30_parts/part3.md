## 7. 台账卡模板（《本网应急通信车/机动站开撤台账卡》）

### 7.1 封面 · 拒开 / 拒放行 / 拒撤签门槛（可贴值班台）

```text
  ┌──────── 拒签卡 · 贴纸 AC ────────┐
  │ 拒开：许可/贴签/写频/场地缺一项   │
  │ 拒放行：无本车本期九字冒烟钉      │
  │ 拒放行：假绿/套旧测/他车测        │
  │ 拒撤签：清场不全/临时参数未回写   │
  │ 拒撤签：无台账无主人无时限口头撤  │
  │ 治理：套贴·功率战·公开泄密       │
  │ 主贴 AC · 假绿≠放行 · 脱敏 L3    │
  └──────────────────────────────────┘
```

### 7.2 边界与展开页（AC-界 / AC-开）

| 字段（教学） | 填写 |
|--------------|------|
| 车/机动站角色编号（L3） | |
| 任务角色 / 场地角色 | |
| 许可/机动边界指针（U/V） | □齐 □缺→拒开 |
| 检测贴签（Y）本车本场有效 | □齐 □套/过期→拒开 |
| 写频复核（K） | □齐 □缺→拒开 |
| 摆车/天线/电源/接地安全勾选 | □齐 □停在开 |
| 共址预案（必要时 S） | □有 □不适用 |
| 展开完成时间角色 / 操作人角色 | |

### 7.3 冒烟与放行页（AC-验）

| 字段（教学） | 填写 |
|--------------|------|
| 本车本期标识核对 | □一致 |
| 下行抽测 | □过 □不过 |
| 上行边缘抽测 | □过 □不过 |
| 两时隙抽测 | □过 □不过 |
| 驻波/馈线直觉勾选 | □过 □不过 |
| 与许可/写频边界一致 | □是 □否→挂U/K |
| 测人/复核人角色 · 时间角色 | |
| 仪器有效期指针 | |
| 「机动站可放行」签字 | 授权角色本人：______ |
| 台账主人角色 · 执勤时限至 | |

### 7.4 撤收清场页（AC-撤）

| 字段（教学） | 填写 |
|--------------|------|
| 天线拆收运输态 | □ |
| 馈线接头清点回装 | □ |
| 电源油机线缆归位 | □ |
| 临时频点/增益/功率回写 | □（不可砍） |
| 开站与冒烟记录归档 | □ |
| 金机/备件回库指针（Q） | □ |
| 场地恢复（按要求） | □ |
| 「撤完」签字 · 时间角色 | 本人：______ |

### 7.5 夜班速填五行

1. 阶段：待开 / 待放行 / 可放行 / 待撤清 / 已撤完  
2. 先证缺项：无 / 有（写角色）  
3. 冒烟指针：在 / 不在  
4. 时限：×× 前须撤或评估延期（走 J）  
5. 公开材料：已 L3 / 需撤回

### 7.6 与总三联单字段对照

| 台账卡 | 三联单 |
|--------|--------|
| 车/站角色 + 阶段 | 现象栏角色描述 |
| 主贴 AC + 支撑贴 | 贴纸栏 |
| 拒开/拒放行/拒撤签原因 | 处置栏 |
| 主人/时限/回写 | 闭环栏 |
| 脱敏后摘要 | 公开/交班栏 |

---

## 8. 术语表（本篇约 18 词）+ 易错观念

| 术语 | 一句话（教学） |
|------|----------------|
| **应急通信车** | 车载可机动展开的通信平台（中继/调度等角色以本网为准） |
| **机动站 / 机动中继** | 非永久固定、按任务开撤的中继或基站角色 |
| **COW 类** | 公开资料中的 Cell on Wheels 等可运输部署站；本篇借「可运、可开、可收」直觉，非法定标签 |
| **AC-界** | 开站前许可/贴签/写频/场地边界 |
| **AC-开** | 摆车架设上电等展开动作 |
| **AC-验** | 本车本期冒烟测与可放行签字 |
| **AC-撤** | 清场回写归档与撤完签字 |
| **AC-治** | 套贴、假绿、口头撤、功率战、泄密等治理 |
| **冒烟测最小集** | 开站后放行前的最小实测（上下行、两时隙、驻波直觉等） |
| **可放行** | 冒烟通过且授权本人签、台账有主人有时限 |
| **撤完** | 清场回写归档齐后的销单状态 |
| **假绿** | 监控屏/远程状态绿，但无本期实测支撑 |
| **套贴** | 把他车他场过期检测贴用到本车本场 |
| **回写** | 把临时频点/增益/功率等恢复到许可与基线 |
| **准固定** | 机动站超时趴窝，实际接近固定使用，须评估 J/AB |
| **与 Z 分工** | 固定交维 ≠ 机动开撤 |
| **九字冒烟钉** | 车下上隙驻电界人邻（教学记忆） |
| **撤清七字钉** | 天线馈线电源回、参数回写账归档（教学记忆） |

**易错观念**

- ❌「车到了就能放行」→ ✅ 先证再开，点检才放行。  
- ❌「固定站交维过了，机动不用测」→ ✅ Z 与 AC 不同对象。  
- ❌「撤了当没开过」→ ✅ 无台账的开站是治理项。  
- ❌「临时增益留着下次方便」→ ✅ 不回写不得签撤完。  
- ❌「屏绿 = 合格」→ ✅ 假绿挂 R，主贴 AC。

---

## 9. 自测（12 题）+ 参考答案

1. 贴纸 AC 五个子类是什么？各用四个字以内说明。  
2. 消防车出警故事里，「出水前点检」对应 AC 哪一段？  
3. 八条硬规则里，哪一条要求先证许可/贴签/写频/场地再开站？  
4. 九字冒烟钉里，为什么机动站特别不能省上行？  
5. 「可放行」至少要具备哪三样（除冒烟通过外）？  
6. 撤收时「临时增益先留着」能不能签撤完？为什么？  
7. AC 与 Z 的分工一句话？  
8. 套他车检测贴签，主贴什么？还能不能开？  
9. 屏全绿想放行，应挂什么提醒贴纸？主贴谁？  
10. 机动站趴窝三周仍称临时，应评估挂回哪两类指针？  
11. 跨网互相抬功率，违反哪条硬规则？应挂什么？  
12. 公开材料能不能贴车号全文与临时频点？依据哪条规则？

### 参考答案

1. **开**（展开摆车架设）、**验**（本期冒烟放行）、**撤**（清场回写）、**界**（许可贴签写频场地）、**治**（假绿套贴功率战泄密）。  
2. **AC-验**（点检才出水 ≈ 冒烟测才放行）。  
3. **规则1**。  
4. 临时天馈与手台上行余量小，下行「还行」常掩盖上行先塌。  
5. **授权本人签字**、**台账主人**、**执勤时限**（规则3）。  
6. **不能**；违反规则4，回写是撤清不可砍项。  
7. **Z 管固定站交维；AC 管机动这一趟开撤**——互不顶替。  
8. **AC-治（+Y）**；**拒开**。  
9. 挂 **R**；主贴 **AC**（规则6）。  
10. **J** 与 **AB**（准固定/变更复测评估）。  
11. **规则7**；挂 **S**，禁功率战。  
12. **不能**；**规则8 脱敏 L3**。

---

## 10. 加深阅读与视频（均已用 curl / oEmbed 核对；以核验当时为准）

**本篇专项方法级阅读（可运输部署 / COW / 便携中继 / 应急电信；借部署秩序，不替代本网许可与签字）**  
1. **[DHS SAVER · Portable Radio Repeaters TechNote（PDF）](https://www.dhs.gov/sites/default/files/saver_radio_repeaters_technote_18sept2020_approved-508.pdf)**——便携中继与 COW 变体、供电与天线位置直觉（通用公共安全；借「可运可开」）。  
2. **[DHS · Portable Cellular Systems Application Note（PDF）](https://www.dhs.gov/sites/default/files/publications/Port-Cell-Sys_AppN_0714-508.pdf)**——COW / COLT / 人背系统分类与应用场景（通用蜂窝便携；借「展开与回收」）。  
3. **[FirstNet · Understanding the FirstNet Deployable Program（PDF）](https://firstnet.gov/sites/default/files/Deployables_factsheet_2023.pdf)**——Deployable / SatCOW 等公开说明（境外公网公共安全；借「按请求部署、有目标时限」；**非法定依据**）。  
4. **[FirstNet Operations Manual（PDF）](https://firstnet.gov/sites/default/files/FirstNet_Operations_Manual_2026_0.pdf)**——灾害与重大活动补网公开运营说明入口。  
5. **[FirstNet Response Operations Group 公开页](https://www.firstnet.com/response-operations-group.html)** · **[FirstNet 门户](https://firstnet.gov/)**——部署请求与资产类型公开介绍。  
6. **[CISA · SAFECOM](https://www.cisa.gov/safecom)**——应急互通与公共安全通信治理入口（方法级）。  
7. **[ITU-D · Emergency Telecommunications](https://www.itu.int/en/ITU-D/Emergency-Telecommunications/Pages/default.aspx)** · **[Publications](https://www.itu.int/en/ITU-D/Emergency-Telecommunications/Pages/Publications.aspx)** · **[ITU-R emergency information](https://www.itu.int/en/ITU-R/information/Pages/emergency.aspx)**——应急电信公开入口。

**故事类比：消防车 / 应急车辆 / 事件指挥（只借直觉，不是台站法定依据）**  
8. Wikipedia：[Fire apparatus](https://en.wikipedia.org/wiki/Fire_apparatus) · [Emergency vehicle](https://en.wikipedia.org/wiki/Emergency_vehicle) · [Incident Command System](https://en.wikipedia.org/wiki/Incident_Command_System) · [Incident command post](https://en.wikipedia.org/wiki/Incident_command_post)——到场展开、指挥单元、撤场秩序直觉。  
9. **[NFPA 1901 标准发展页](https://www.nfpa.org/codes-and-standards/nfpa-1901-standard-development/1901)**——消防车辆相关标准入口（只借「车辆与器材要按规范管」；**不是**无线电开站依据）。  
10. **[Ready.gov](https://www.ready.gov/)** · **[Ready.gov kit](https://www.ready.gov/kit)** · **[FEMA](https://www.fema.gov/)** · **[NFPA emergency-response 教育入口](https://www.nfpa.org/education-and-research/emergency-response)**——应急准备与响应公开入口。  
11. Wikipedia：[Cell on wheels](https://en.wikipedia.org/wiki/Cell_on_wheels) · [Cell site](https://en.wikipedia.org/wiki/Cell_site) · [Base station](https://en.wikipedia.org/wiki/Base_station) · [Repeater](https://en.wikipedia.org/wiki/Repeater) · [Mobile radio](https://en.wikipedia.org/wiki/Mobile_radio)。

**国内无线电法规（参数与设台秩序；机动开站不是法外）**  
12. **[《中华人民共和国无线电管理条例》（中国政府网）](https://www.gov.cn/zhengce/zhengceku/2016-11/25/content_5137687.htm)** · **[国务院公报版](https://www.gov.cn/gongbao/content/2016/content_5148745.htm)**。  
13. **[《无线电频率使用许可管理办法》（中国政府网）](https://www.gov.cn/zhengce/2022-08/23/content_5722706.htm)**。  
14. **[《地面无线电台（站）管理规定》（中国政府网）](https://www.gov.cn/zhengce/202310/content_6908889.htm)** · **[国务院公报 · 工信部令第60号](https://www.gov.cn/gongbao/content/2023/content_5745291.htm)**。  
15. **[国无办〔2025〕1号（工信部公开页，以现行为准；部分出口偶发 403）](https://www.miit.gov.cn/jgsj/wgj/wjfb/art/2025/art_31a0765b521e4dc493262188aea65618.html)** · **[无线电管理局首页](https://www.miit.gov.cn/jgsj/wgj/index.html)** · **[政策法规入口](https://www.miit.gov.cn/jgsj/wgj/zcfg/index.html)**。  
16. **[国家无线电监测中心 / SRRC 门户](https://www.srrc.org.cn/)** · **[工信部首页](https://www.miit.gov.cn/)**（首页出口偶发 403，以可访问为准）。  
17. **[生态环境部 · GB 8702—2014 公开页](https://www.mee.gov.cn/ywgz/fgbz/bz/bzwb/hxxhj/dcfsbz/201410/t20141022_290449.htm)** · **[全国标准信息平台条目](https://std.samr.gov.cn/gb/search/gbDetailed?id=71F772D7ECC9D3A7E05397BE0A0AB82A)**（环境限值指针；与长期设站/X 咬合）。

**验收 / 放行方法级（借「到站合格与现场确认」，服务冒烟测意识）**  
18. **[Tait · The 6 Steps of Testing to get to "Final Acceptance"](https://www.taitcommunications.com/en/about-us/news/2012/10/25/the-6-steps-of-testing-to-get-to-final-acceptance)**。  
19. **[P25 Best Practice · Field Acceptance Tests](https://www.p25bestpractice.com/implementing/field-acceptance-tests/)**。  
20. **[Flowdit · Site Acceptance Test (SAT)](https://flowdit.com/site-acceptance-test/)** · **[Engineversity · FAT, SAT and commissioning](https://engineversity.com/courses/process-control-systems-for-beginners/fat-sat-and-commissioning/)**。  
21. **[TIA TSB-88](https://tiaonline.org/standard/tia-tsb-88/)** · **[Softwright · TSB-88 FAQ](https://www.softwright.com/faq/engineering/tsb88faq.html)**——覆盖验证抽样思路（机动承诺区抽测可借方法）。

**ITU / ETSI / DMR（参数指针；不替代开撤签字）**  
22. **[ITU-R SM.1875](https://www.itu.int/rec/R-REC-SM.1875/en)** · **[ITU-R M.2009](https://www.itu.int/rec/R-REC-M.2009/en)**。  
23. **[ITU-R Terrestrial](https://www.itu.int/en/ITU-R/terrestrial/Pages/default.aspx)** · **[Monitoring](https://www.itu.int/en/ITU-R/terrestrial/monitoring/Pages/default.aspx)** · **[National Spectrum Management 手册](https://www.itu.int/pub/R-HDB-21-2015)** · **[Spectrum Monitoring 手册](https://www.itu.int/pub/R-HDB-23)**。  
24. **[ETSI TS 102 361-1 V2.7.1（PDF；部分出口 403）](https://www.etsi.org/deliver/etsi_TS/102300_102399/10236101/02.07.01_60/ts_10236101v020701p.pdf)** · **[ETSI TR 102 398](https://www.etsi.org/deliver/etsi_TR/102300_102399/102398/01.05.01_60/tr_102398v010501p.pdf)** · **[ETSI Standards](https://www.etsi.org/standards)**。  
25. **[DMR Association · Standards](https://www.dmrassociation.org/dmr-standards.html)** · **[DMR Association](https://dmrassociation.org/)** · **[Tait Communications](https://www.taitcommunications.com/)** · **[Tait Radio Academy](https://www.taitradioacademy.com/)**。  
26. **[Motorola Solutions 官网](https://www.motorolasolutions.com/)** · **[Command center 产品入口例](https://www.motorolasolutions.com/en_us/products/command-center-software.html)** · **[Hytera](https://www.hytera.com/)** · **[Sepura](https://www.sepura.com/)**——厂商公开入口（不引内部开站秘技）。

**测量与驻波相关公开资料（看懂「测」，不是造假教程）**  
27. Wikipedia：[Standing wave ratio](https://en.wikipedia.org/wiki/Standing_wave_ratio) · [Noise floor](https://en.wikipedia.org/wiki/Noise_floor) · [Passive intermodulation](https://en.wikipedia.org/wiki/Passive_intermodulation) · [Drive testing](https://en.wikipedia.org/wiki/Drive_testing) · [Spectrum management](https://en.wikipedia.org/wiki/Spectrum_management) · [Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio) · [Land mobile radio system](https://en.wikipedia.org/wiki/Land_mobile_radio_system) · [Preventive maintenance](https://en.wikipedia.org/wiki/Preventive_maintenance) · [Emergency management](https://en.wikipedia.org/wiki/Emergency_management)。  
28. **[Rohde & Schwarz · EMF testing](https://www.rohde-schwarz.com/us/solutions/electronics-testing/emc-testing/emf-testing/emf-testing_253445.html)** · **[TS-EMF 便携系统](https://www.rohde-schwarz.com/us/products/test-and-measurement/radiated-testing/rs-ts-emf-portable-emf-measurement-system_63493-8174.html)** · **[EMF Measurement Application PDF](https://scdn.rohde-schwarz.com/ur/pws/dl_downloads/pdm/cl_brochures_and_datasheets/option_sheet/3683_7319_32/EMF-measurement-application-K105-for-FPH-and-ZPH-v0110.pdf)**。  
29. **[Keysight · EMF Triaxial Isotropic Antenna PDF](https://www.keysight.com/us/en/assets/3121-1035/data-sheets/Electromagnetic-Field-EMF-Triaxial-Isotropic-Antenna.pdf)**。

**视频（YouTube，已用 oEmbed 核验标题与频道）**  
30. **[Rohde & Schwarz · Understanding Spectrum Analyzers – ACLR](https://www.youtube.com/watch?v=mco_BJ1mjNo)**——「看见」频谱；**不是**造假教程。  
31. **[Shure · What is Intermodulation?](https://www.youtube.com/watch?v=IrlyAei02_o)**——共址与抬功率的互调直觉；对照禁功率战。  
32. **[MPSCS · Site Maintenance Inspection and Preventative Maintenance](https://www.youtube.com/watch?v=4IRdxeXN1do)**——站点维护与记录（借「展开后还要管」，非机动专项）。  
33. **[NATEsafety · How to Conduct Tower Inspections](https://www.youtube.com/watch?v=dFs4At6-hhU)**——高处/塔站检查安全入门（架设安全直觉）。  
34. **[Sunil Kashyap · How to perform site audit or RF audit](https://www.youtube.com/watch?v=7Awj0-rDfeA)**——射频站点巡检直觉（通用）。  
35. **[Engineered Vision · FAT and SAT Explained](https://www.youtube.com/watch?v=x7qNC6Rtp9I)** · **[Careers360 · FAT & SAT](https://www.youtube.com/watch?v=3aafLF9o0NA)**——出厂/到站合格直觉（回指：合格≠今晚可免测）。  
36. **[Scanner School · What is DMR?](https://www.youtube.com/watch?v=aQX_JbTbXuY)**（弱项：时隙与数字话音）。

> **诚实说明**：没有找到「DMR 专网应急通信车/机动站快速开站与撤收制度（含贴纸 AC + 插页 AC1–AC8 + 消防车出警摆车/点检/撤场隐喻 + 拒开拒放行拒撤签卡 + 与 Z/Y/V 分工表）」的专项中文公开视频或制度文章；上文最贴题的是 **DHS 便携中继/COW 公开 TechNote 与 Application Note**、**FirstNet Deployable 公开说明（境外，非法定依据）**、**ITU 应急电信入口**，以及频谱仪/互调/站点巡检/FAT-SAT/DMR 基础等通用视频。其余为国内无线电法规、驻波与覆盖方法指针、消防车/ICS 故事类比。需按贴纸 AC 与 AC1–AC8 拼进本网流程。`video_found=true`（通用频谱/互调/站点巡检/FAT-SAT/DMR 基础），**非**应急车开撤专项。任何「教你如何无证先开」「如何伪造开站记录」「如何套他车贴过关」「如何抬功率压邻居」的页面即使 200，本篇也**不引用**。

**库内必回：** 手册22（U）、23（V）、26（Y）、27（Z）、11（J）、19（R）、20（S）、21（T）、08/相关 K 写频、25（X）、28（AA）、29（AB）、06（脱敏）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子
- 贴纸 **AC** 五子类：开 / 验 / 撤 / 界 / 治——双字母续写的第三张，负责应急车/机动站「这一趟开没开清、放没放清、撤没撤清」。  
- 故事：消防车出警——到场摆车 → 出水前点检 → 撤场收装归位；固定站交维像消防站建成验收，不能和出警单混用。  
- 阶段梯：先证边界 → 开站展开 → 冒烟放行 → 执勤（有主人有时限）→ 撤收清场回写 → 归档销单。  
- 八条硬规则：**先证再开**；**本车本期冒烟才放行**；**有台账有主人有时限**；**撤清才签撤**；**禁套他车他场**；**主贴 AC，假绿≠放行**；**跨网挂 S、禁功率战、变更走 J**；**脱敏 L3**。

### 11.2 下一篇手册候选（本篇不写正文）
- **备件周转与金机轮换台账**（与 Q/AA/K/AC 咬合：金机、备件、开撤回库、复测漂移后基线更新）  
- **隧道/地铁区间联测与换乘责任界面**（与 AB/I/S 咬合）  
- **油机/市电切换与机房供电巡检边界**（与 AC 展开电源勾选、AA 巡检咬合，仍 L3）

### 11.3 给带新人的三句话
1. 应急车开站不是法外之地：许可、贴签、写频、场地先齐，再谈摆车架天线。  
2. 屏绿不能出水：本车本期上下行冒烟测过了，有主人有时限，才能签可放行；撤场必须回写清场留台账。  
3. 机动开撤 ≠ 固定交维；假绿挂 R；禁套他车；禁功率战；跨网挂 S；公开脱敏；主贴 AC。

### 11.4 一张图记住本篇（收工贴纸）
```text
  ┌────────── 贴纸 AC ──────────┐
  │ 开 摆车架设·上电接地         │
  │ 验 本期冒烟·可放行签字       │
  │ 撤 清场回写·台账归档         │
  │ 界 许可贴签写频场地·异于Z    │
  │ 治 假绿套贴·功率战口头撤泄密 │
  └────────────────────────────┘
    消防车出警 · 点检才出水 · 撤清才归队
```

---

## 12. 本篇检查清单（自学打勾）
- [ ] 能背贴纸 AC 五子类与消防车出警摆车/点检/撤场故事  
- [ ] 能画 先证→展开→冒烟放行→执勤→撤收 阶段梯  
- [ ] 能背八条硬规则（先证、本期冒烟、台账主人时限、撤清才签、禁套贴、假绿≠放行、挂S禁功率战、L3）  
- [ ] 能背九字冒烟钉与撤清七字钉，并能讲清为什么要测上行、为什么必须回写  
- [ ] 会填插页 AC1–AC8、拒开/拒放行/拒撤签卡与开撤台账卡  
- [ ] 12 题自测过关  
- [ ] 知道 §10 诚实说明：无专项应急车开撤视频，仅 COW/Deployable 公开资料 + 消防车类比 + 通用频谱/巡检视频  
- [ ] 回库用 L3 重对一次本网最近一趟机动开站：先证链、冒烟测、放行签、撤收回写与台账

---

*手册30 · 应急通信车机动站快速开站与撤收 · 学习推送 · 2026-10-23 18:52 +08:00*
