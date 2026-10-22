
---

## 8. 术语表（本篇约 15 词）+ 易错观念

| 术语 | 一句话 |
|------|--------|
| **开站（教学用语）** | 前置闸门齐后允许本站发射、入网；≠ 验收 |
| **开站前置闸门** | U 执照、X 环境报告、S 通知、K 倒换、N 接入、J/Q 基线（保障站加 V/Y） |
| **SAT / 站点验收（初验）** | 设备装到本站后逐项实测；本篇 Z-验 主场 |
| **下行 / 上行** | 基站→手台 / 手台→基站；上行常先不够，必须双向测 |
| **覆盖验证** | 按承诺区系统抽样、事先约定判据的实测（TSB-88 思路可借） |
| **试运行 / 观察期（Burn-in）** | 真实业务跑一段；重大尾项可重启观察期 |
| **终验** | 全部分项 + 观察期无重大尾项后的合同交付确认 |
| **交维** | 把站「交给运维」：资料包 + 责任边界 + 告警归属 + 尾项移交 |
| **交维资料包** | 竣工资料、设备清单、配置与金机基线、实测原件、告警、备件巡检、边界表、尾项 |
| **尾项清单（punch list）** | 每条有编号、等级、主人、期限、复验方式；口头答应不算 |
| **条件交维** | 仅限一般尾项、书面列明后交维；重大尾项不适用 |
| **带病交维** | 重大尾项未闭环仍签交维，本篇红线 |
| **逼签 / 代签** | 被工期压着签、替别人签，本篇红线 |
| **交维后变更复验** | 改频、改功率角色、换天馈、改基线须走 J + 局部复验 + 重对 U/X/Y/S |
| **主贴 Z** | 开站验收与交维签字以 Z 为主键，可挂 I/K/Q/N/U/X/Y/J/M/G/R/S |

**易错观念**

1. ✗ 开通当天打通 = 验收合格 → ✓ 打通只说明「能发能收」，验收要七字验钉。  
2. ✗ 下行满格 = 覆盖好 → ✓ 上行必须单独测，边缘点更要测。  
3. ✗ 开站 = 交维 → ✓ 开站、初验、覆盖、试运行、终验、交维六个签字点。  
4. ✗ 资料以后补 → ✓ 缺项要清单 + 书面期限；关键项（配置基线）缺则禁交维。  
5. ✗ 尾项口头答应就行 → ✓ 每条主人、期限、复验写进清单。  
6. ✗ 工期到了运维就得签 → ✓ 工期不是签字理由；签了坏了是你的。  
7. ✗ 屏全绿 = 验收通过 → ✓ 假绿≠验收（挂 R）。  
8. ✗ 交维后小改不用报 → ✓ 走 J 变更 + 复验 + 重对 U/X。  
9. ✗ 覆盖不够抬功率就行 → ✓ 抬下行救不了上行，还可能伤邻居；禁功率战。  

---

## 9. 自测（12 题）+ 参考答案

1. 贴纸 Z 五个子类是什么？各用四个字以内说明。  
2. 「新房交付验房 + 物业承接查验」分别对应开、验、交、签中的哪段直觉？  
3. 八条硬规则里，哪一条要求先证前置闸门再开站？前置闸门至少有哪六项？  
4. 验收实测最小集「七字验钉」是哪七个字？  
5. 为什么上行往往比下行先不够？只测下行能否签验收？  
6. 开站、初验、覆盖验证、试运行、终验、交维——能否一张单一次签完？  
7. 竣工图和配置备份未到，施工方口头说月底给，能否签交维？应该怎么写？  
8. 合同节点当天被要求「先签交维、尾项后补」，重大尾项未闭环，怎么办？  
9. 交维后施工方回访时调高了功率角色，应走什么路径？要重对哪些贴纸？  
10. 屏全绿、假绿演练通过，能否代替现场验收？主贴谁？  
11. 新站与邻网共址，未通知能否先开？开站后投诉挂什么？  
12. 公开表扬稿能否出现验收单全文号、合同号、站点坐标、真实频点？

### 参考答案

1. 开/验/交/签/治：前置齐全、实测为准、资料尾项、分段签字、逼签私改治理。  
2. 竣工验收与认可文件、水电通→开；逐户验房→验；资料移交与问题清单→交；承接查验协议与交接记录各方签字→签（逼收房、串通弄虚作假→治）。  
3. 规则1；U 执照覆盖本站本参数、X 环境报告本站本期、S 通知或协调、K 倒换剧本已演、N 接入对时、J/Q 配置与金机基线（保障站加 V/Y）。  
4. 站、下、上、隙、倒、分、法。  
5. 手台功率小、天线短、贴近人体；不能，规则2。  
6. 不能；规则3，分阶段签，禁跳签。  
7. 不能直接签；列未移交资料清单 + 书面补交期限 + 责任角色；配置备份属关键项，到位前禁签交维（规则4）。  
8. 拒签交维；一般尾项可条件交维并书面列明；重大尾项闭环前不签；如实记录分歧并上报授权角色（规则4、5）。  
9. 走 J 变更（或先回滚到金机基线）+ 局部复测上下行；重对 U、X（必要时 S），更新 Q 基线（规则5）。  
10. 不能；主贴 Z，挂 R（规则6）。  
11. 不能；先通知或挂 S；投诉挂 T；禁功率战私了（规则7）。  
12. 不能；规则8。

---

## 10. 加深阅读与视频（均已用 curl / oEmbed 核对；以核验当时为准）

**本篇专项方法级阅读（验收阶段、FAT/SAT、覆盖验收思路；借方法，不替代本网合同与签字）**  
1. **[Tait Communications · The 6 Steps of Testing to get to "Final Acceptance"](https://www.taitcommunications.com/en/about-us/news/2012/10/25/the-6-steps-of-testing-to-get-to-final-acceptance)**——专网无线系统验收六阶段（FAT、CAT、SAT、覆盖验证、系统终验、试运行 + 尾项清单，重大尾项可重启观察期）。**本篇阶段梯的主要方法参考，强烈建议通读。**  
2. **[Engineversity · FAT, SAT and commissioning](https://engineversity.com/courses/process-control-systems-for-beginners/fat-sat-and-commissioning/)**——每个阶段证明前一阶段证明不了的东西；每阶段有书面程序、签字和尾项清单。  
3. **[Bioprocess Online · FAT, SAT & Commissioning Activities, Oh My!](https://www.bioprocessonline.com/doc/factory-acceptance-testing-site-acceptance-testing-commissioning-activities-oh-my-0001)**——FAT/SAT 与调试分工、尾项与授权把关（借方法）。  
4. **[FAT/SAT work instructions（electrical-engineering-portal 公开 PDF）](https://electrical-engineering-portal.com/res3/FAT-SAT-OF-electrical-and-automation-systems.pdf)**——FAT/SAT 作业模板；SAT 记录由**客户与调试方双方签字**。  
5. **[TIA TSB-88 标准条目（TIA 官网）](https://tiaonline.org/standard/tia-tsb-88/)** · **[Softwright · TSB-88 FAQ](https://www.softwright.com/faq/engineering/tsb88faq.html)** · **[Drive Test Guidelines（Pericle 公开 PDF）](https://www.pericle.com/wp-content/uploads/Drive_Test-Guidelines031210.pdf)**——LMR 覆盖预测与验证、网格抽样与可重复路测思路（**门限与样本数以合同为准**）。

**国内无线电法规（开站合法前提；以官方原文为准）**  
6. **[《中华人民共和国无线电管理条例》（中国政府网）](https://www.gov.cn/zhengce/zhengceku/2016-11/25/content_5137687.htm)** · **[国务院公报版](https://www.gov.cn/gongbao/content/2016/content_5148745.htm)** · **[工信部无线电管理局转载](https://www.miit.gov.cn/jgsj/wgj/flfg/art/2020/art_9e0f1197e2084ec19425ea2e0cd9586f.html)**。  
7. **[《无线电频率使用许可管理办法》（中国政府网）](https://www.gov.cn/zhengce/2022-08/23/content_5722706.htm)** · **[国务院公报 · 工信部令第40号](https://www.gov.cn/gongbao/content/2017/content_5240087.htm)**。  
8. **[《地面无线电台（站）管理规定》（中国政府网）](https://www.gov.cn/zhengce/202310/content_6908889.htm)** · **[国务院公报 · 工信部令第60号](https://www.gov.cn/gongbao/content/2023/content_5745291.htm)** · **[工信部转载](https://www.miit.gov.cn/jgsj/wgj/bmgz/art/2024/art_ac48d45b89ef4706a0f7fd8fd7f70a13.html)**。  
9. **[《无线电台执照管理规定》（工信部无线电管理局）](https://www.miit.gov.cn/jgsj/wgj/bmgz/art/2020/art_a23d32952faa494095758a24b7326710.html)**（以现行有效规定为准）。  
10. **[《中华人民共和国无线电管制规定》（中国政府网）](https://www.gov.cn/zhengce/2010-09/06/content_2602563.htm)** · **[国无办〔2025〕1号（工信部）](https://www.miit.gov.cn/jgsj/wgj/wjfb/art/2025/art_31a0765b521e4dc493262188aea65618.html)** · **[无线电管理局政策法规目录](https://www.miit.gov.cn/jgsj/wgj/zcfg/index.html)** · **[无线电管理局首页](https://www.miit.gov.cn/jgsj/wgj/index.html)**。  
11. **[生态环境部 · 《电磁环境控制限值》GB 8702—2014 公开页](https://www.mee.gov.cn/ywgz/fgbz/bz/bzwb/hxxhj/dcfsbz/201410/t20141022_290449.htm)**（与 X 前置咬合）。

**故事类比用的房建与物业公开文件（只借流程直觉，不是台站法定依据）**  
12. **[《物业承接查验办法》（建房〔2010〕165号，国务院公报）](https://www.gov.cn/gongbao/content/2011/content_1808607.htm)** · **[广东省政府门户转载](https://www.gd.gov.cn/zwgk/wjk/zcfgk/content/post_2531763.html)**——承接查验七步、资料移交与未移交清单、查验记录签字、问题书面通知复验、**不得以交付期限届满为由逼收**。  
13. **[《建设工程质量管理条例》（2019 修订，国务院公报）](https://www.gov.cn/gongbao/content/2019/content_5468867.htm)** · **[2000 年原发布公报](https://www.gov.cn/gongbao/content/2000/content_60658.htm)** · **[国家行政法规库](https://xzfg.moj.gov.cn/front/law/detail?LawID=776)**——验收合格方可交付使用、质量保修。  
14. **[《房屋建筑和市政基础设施工程竣工验收规定》（建质〔2013〕171号，国务院公报）](https://www.gov.cn/gongbao/content/2014/content_2629947.htm)**——验收组签署意见、意见不一致协商后重新验收。

**ITU / ETSI / DMR（参数与频谱管理指针；不替代验收签字）**  
15. **[ITU Handbook on National Spectrum Management（PDF）](https://www.itu.int/dms_pub/itu-r/opb/hdb/R-HDB-21-2015-PDF-E.pdf)** · **[出版物页](https://www.itu.int/pub/R-HDB-21-2015)** · **[ITU-R Report SM.2093-4（PDF）](https://www.itu.int/dms_pub/itu-r/opb/rep/R-REP-SM.2093-4-2021-PDF-E.pdf)** · **[ITU-R Terrestrial 入口](https://www.itu.int/en/ITU-R/terrestrial/Pages/default.aspx)**。  
16. **[ETSI EN 300 113 V3.1.1（PDF）](https://www.etsi.org/deliver/etsi_en/300100_300199/300113/03.01.01_60/en_300113v030101p.pdf)** · **[ETSI TS 102 361-1 V2.7.1（PDF）](https://www.etsi.org/deliver/etsi_TS/102300_102399/10236101/02.07.01_60/ts_10236101v020701p.pdf)** · **[ETSI TR 102 398 V1.5.1（PDF）](https://www.etsi.org/deliver/etsi_TR/102300_102399/102398/01.05.01_60/tr_102398v010501p.pdf)** · **[ETSI Standards 检索](https://www.etsi.org/standards)**。  
17. **[DMR Association · Standards](https://www.dmrassociation.org/dmr-standards.html)** · **[DMR Association 首页](https://www.dmrassociation.org/)** · **[Tait Communications 官网](https://www.taitcommunications.com/)** · **[R&S 测试测量入口](https://www.rohde-schwarz.com/us/products/test-and-measurement/network-analyzers_63665.html)**（有仪器≠已验收）。

**名词垫脚石（定义级）**  
18. Wikipedia：[Acceptance testing](https://en.wikipedia.org/wiki/Acceptance_testing) · [Commissioning](https://en.wikipedia.org/wiki/Commissioning) · [Building commissioning](https://en.wikipedia.org/wiki/Building_commissioning) · [Punch list](https://en.wikipedia.org/wiki/Punch_list) · [Operational acceptance testing](https://en.wikipedia.org/wiki/Operational_acceptance_testing) · [Burn-in](https://en.wikipedia.org/wiki/Burn-in) · [Drive testing](https://en.wikipedia.org/wiki/Drive_testing) · [Land mobile radio](https://en.wikipedia.org/wiki/Land_mobile_radio_system) · [Professional mobile radio](https://en.wikipedia.org/wiki/Professional_mobile_radio) · [Spectrum management](https://en.wikipedia.org/wiki/Spectrum_management)。

**视频（YouTube，已用 oEmbed 核验标题与频道）**  
19. **[Engineered Vision · FAT and SAT Explained for Manufacturers](https://www.youtube.com/watch?v=x7qNC6Rtp9I)**——**SAT 重复 FAT 同一套测试**，证明运输安装没改变任何东西（出厂合格≠到站合格）。  
20. **[Careers360 · FAT & SAT, why it's important](https://www.youtube.com/watch?v=3aafLF9o0NA)**——FAT/SAT 入门讲解（通用工程领域）。  
21. **[Scanner School · What is DMR? Digital Mobile Radio Explained for Beginners](https://www.youtube.com/watch?v=aQX_JbTbXuY)**（弱项：时隙与数字话音基础）。  
22. **[Rohde & Schwarz · Understanding Spectrum Analyzers – ACLR](https://www.youtube.com/watch?v=mco_BJ1mjNo)**（「看见」频谱的基础；**不是**验收造假教程）。  
23. **[Shure · What is Intermodulation?](https://www.youtube.com/watch?v=IrlyAei02_o)**（共址开站与抬功率的互调直觉；对照禁功率战与挂 S）。

> **诚实说明**：没有找到「DMR 专网开站验收与交维签字边界制度（含贴纸 Z + 插页 Z1–Z8 + 验房/物业承接查验隐喻 + 拒签卡）」的专项中文公开视频或制度文章；上文最贴题的是 **Tait 的验收六阶段公开文章**（专网无线领域）和 FAT/SAT 通用讲解视频，其余为国内无线电法规原文、房建与物业公开文件（仅作类比）、TSB-88 覆盖验证方法指针、ITU/ETSI/DMR 参数与通用射频视频，需按贴纸 Z 与 Z1–Z8 拼进本网流程。`video_found=true`（通用 FAT/SAT 与 DMR/射频基础），**非**专项。检索到的某厂商 BTS 开站 YouTube 视频仅有背景音乐无讲解，**未列入**；Scribd 上的覆盖验收方案样例需登录且非官方发布，**未列入**；维基「Snagging」条目 404，**未列入**。任何「教你如何把验收记录改好看」的页面即使 200，本篇也**不引用**。

**库内必回：** 手册10（I）、12（K）、11（J）、18（Q）、14（M）、15（N）、19（R）、20（S）、21（T）、22（U）、23（V）、25（X）、26（Y）、08（G）、06（脱敏）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子
- 贴纸 **Z** 五子类：开 / 验 / 交 / 签 / 治——字母表最后一张，负责把各分项闸门收拢成签字总单。  
- 故事：新房交付验房 + 物业承接查验——开发商说能住不算数；验房、资料移交、问题清单、双方签字；交付期限到了也不能逼收。  
- 阶段梯：FAT → 开站 → 初验（SAT）→ 覆盖验证 → 试运行 → 终验 → 交维 → 变更复验，**六个签字点不能一笔带过**。  
- 八条硬规则：**先证前置再开站**；**本站本期实测、上下行双向**；**分阶段禁跳签**；**资料尾项齐才交维、禁带病交维**；**各签各的禁代签禁逼签、交维后变更须复验**；**主贴 Z，假绿≠验收**；**跨网挂 S、禁功率战**；**脱敏 L3**。

### 11.2 下一篇手册候选（本篇不写正文）
- **交维后首年巡检与保修期尾项闭环**（与 Z/Q/N/K 咬合：保修期内谁修、尾项怎么关、首年巡检看什么）  
- **室分电磁环境复测周期与变更触发**（与 I/X/Z 咬合）  
- （可选）**应急通信车 / 机动站快速开站与撤收边界**（与 V/Y/Z 咬合，仍 L3）

### 11.3 给带新人的三句话
1. 打通不是验收，满格不是覆盖：上行、两个时隙、倒换、告警都测了、记录是本站本期的，才叫验收。  
2. 开站、验收、交维是不同的签字；资料缺项要清单和期限，重大尾项不闭环就不交维。  
3. 工期不是签字的理由；交维后任何改动都走变更复验；跨网挂 S；公开材料脱敏；主贴 Z。

### 11.4 一张图记住本篇（收工贴纸）
```text
  ┌────────── 贴纸 Z ──────────┐
  │ 开 前置齐：U·X·S·K·N·J/Q   │
  │ 验 本站本期·上下行·倒换告警 │
  │ 交 资料九项·尾项有主有期   │
  │ 签 分段签·本人签·不被逼签  │
  │ 治 跳签·带病·私改·假绿     │
  └────────────────────────────┘
    验房单 · 物业承接 · 签字有界
```


---

## 12. 本篇检查清单（自学打勾）
- [ ] 能背贴纸 Z 五子类与验房 + 物业承接查验故事  
- [ ] 能画阶段梯并说出六个签字点各回答什么问题  
- [ ] 能背八条硬规则（先证前置、实测双向、分段禁跳签、资料尾项齐才交、禁代签逼签与私改、假绿≠验收、挂 S、L3）  
- [ ] 能背「站、下、上、隙、倒、分、法」七字验钉，并能讲清上行为什么常先不够  
- [ ] 会填插页 Z1–Z8、资料包九项与尾项清单  
- [ ] 12 题自测过关  
- [ ] 知道 §10 诚实说明：无专项视频，仅 Tait 验收阶段文章 + 通用 FAT/SAT 视频  
- [ ] 回库用 L3 重对一次本网最近一座新站或改造站的开站—验收—交维材料（前置、上行记录、资料缺项期限、尾项主人、交维后变更）

---

*手册27 · 开站验收与交维签字边界 · 学习推送 · 2026-10-22 09:52 +08:00*
