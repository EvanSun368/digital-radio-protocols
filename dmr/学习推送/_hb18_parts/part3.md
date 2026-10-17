## 8. 术语表（本篇约 28 词）+ 易错观念

| 术语 | 白话 | 易错 |
|------|------|------|
| **金机** | 带档案的对照样终端 | ≠ 随便一台好机 |
| **基线 / 现服** | 当前批准的配置账本摘要 | ≠ 「机里现在是啥就算」 |
| **上一版** | 可回滚的先前基线 | 只留现服 = 书柜空 |
| **漂移** | 活体配置相对基线的未对齐偏差 | ≠ 一定是射频干扰 |
| **漂移判据** | 书面检验指标 | ≠ 感觉差不多 |
| **对照表** | 摘要/功能项/允许的核对表 | 公开包禁真实密钥频点 |
| **指纹摘要** | 教学层配置身份摘要 | ≠ 把密钥写进公开仓 |
| **巡检** | 按周期或事件核对是否漂 | ≠ 写完当天验一次就终身 |
| **强制抽检** | 大批量/OTAP 后必做的开袋抽 | ≠ 可用完成账替代 |
| **抽样比例** | 抽多少、怎么分层 | ≠ 只抽好说话的班组 |
| **并测** | 金机与抽检机同一剧本 | ≠ 单测抽检机 |
| **超阈** | 超过判据允许偏差 | → 禁放行 |
| **临界** | 未超阈但需缩短复检 | ≠ 假装过 |
| **回滚** | 写回上一版（指针 J-回） | ≠ 在失败稿上连续乱拧 |
| **隔离批次** | 超阈机退出勤务 | ≠ 先上勤再改 |
| **授牌 / 撤牌** | 给予或取消金机资格 | 金机漂了要先撤牌 |
| **自巡** | 金机自身按窗复检 | 金机也要被巡 |
| **假绿** | 监控/感觉正常但对不上对照 | 指针 N；主贴 Q 拒签 |
| **codeplug** | 电台配置工程/文件气质 | 跨机型禁互写（指针 J/M） |
| **CPS** | 客户编程软件气质 | 先读后写（指针 J） |
| **OTAP** | 空口写频 | 强稳覆盖+足电+完成账+本篇抽检 |
| **变更单** | 写什么、影响谁的审批单 | 指针 J-变 |
| **L3 脱敏** | 公开教学最高脱敏档 | 禁真实频点个号密钥站名 |
| **12.5 kHz** | 一条 DMR 信道宽度 | 漂移不改变它 |
| **4FSK** | 装货调制 | 漂移不改变它 |
| **30 ms / 60 ms** | 时隙与双时隙一轮 | 漂移不改变它 |
| **主贴 Q** | 漂移巡检主贴纸 | 可挂 J/M/G/N |
| **M 过 ≠ Q 过** | 完成账 ≠ 漂移抽检过 | 两道门槛 |

**易错观念（钉死）**

1. 「写完验过 = 永远不漂」——错；要周期与事件巡检。  
2. 「金机不会坏」——错；金机先漂更危险。  
3. 「感觉正常 / 监控绿 = 没漂」——错；要对照表。  
4. 「完成账全绿可放行」——错；大批量后还要 Q。  
5. 「机子怪就加功率」——错；规则2。  
6. 「漂移是 ETSI 某条款号」——本篇不发明条款号；借 CM 精神即可。

---

## 9. 自测（10 题）+ 参考答案

1. 贴纸 Q 五个子类各是什么？各用四个字以内概括。  
2. 「药监对照样 + 柜台货抽检」故事里，金机对应什么？大批量后零抽检像什么？  
3. 八条硬规则里，哪一条专门禁止用加功率/加信道/乱拧 Hangtime 掩盖机子怪？  
4. 手册14 完成账全绿，能否直接宣布放行？为什么？  
5. 金机无档案号，班长说「一直是好机」，可否当对照样？  
6. 抽检机怪、金机未并测就结案「干扰」，违反哪条子类？  
7. 漂移超阈时，正确动作顺序是什么？（放行 / 回滚隔离 / 加功率）  
8. 主贴 Q 时，常见次挂有哪些？假绿常叠哪张？  
9. 公开巡检报告能否写真实频点与个号？应落到哪条硬规则？  
10. 弱项：漂移巡检会不会把信道从 12.5 kHz 变成别的？时隙 30 ms 变不变？

### 参考答案

1. Q-金 样本身份；Q-漂 漂移判据；Q-巡 巡检抽样；Q-比 对照复测；Q-治 治理拒签。  
2. 金机=对照样；零抽检=空投完不打开包装就说合格。  
3. 规则2。  
4. 不能。M 过 ≠ Q 过；规则3 强制抽检。  
5. 不能。金机≠随便好机；规则6 / Q-金。  
6. Q-比（及规则7 精神）；应并测。  
7. 禁放行 → 回滚/重写/隔离；禁止加功率。规则5。  
8. 常挂 J/M/G；假绿挂 N，主仍 Q。  
9. 不能。规则8 / 脱敏 L3。  
10. 不会；不改变。漂移管配置账本对齐，不管物理台阶改宽。

---

## 10. 加深阅读与视频（均已用 curl 核对 HTTP 200；视频用 YouTube oEmbed 核对存在）

1. **[NIST SP 800-53 Rev.5 全文（PDF）](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf)**  
   - 配置管理 CM 章；对照「基线要维护、变更要控制」。**只借精神，不背条款当 ETSI。**  
2. **[NIST SP 800-128 · Security-Focused Configuration Management（PDF）](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-128.pdf)**  
   - SecCM 过程：识别基线、变更控制、监控漂移气质；对照 Q-漂/Q-巡。  
3. **[NIST CSRC · SP 800-128 条目页](https://csrc.nist.gov/pubs/sp/800/128/upd1/final)**  
   - 官方入口与摘要；同上，借精神。  
4. **[CSF Tools · CM-2 Baseline Configuration](https://csf.tools/reference/nist-sp-800-53/r5/cm/cm-2/)**  
   - 基线配置公开解释；对照 Q-金/现服。  
5. **[CSF Tools · CM-2(3) Retention of Previous Configurations](https://csf.tools/reference/nist-sp-800-53/r5/cm/cm-2/cm-2-3/)**  
   - 「保留先前配置以支持回滚」；指针 J-回 + 本篇超阈回滚。  
6. **[CSF Tools · CM-3 Configuration Change Control](https://csf.tools/reference/nist-sp-800-53/r5/cm/cm-3/)**  
   - 变更控制与未授权变更审查气质；对照漂移=未对齐变更。  
7. **[ATO Pathways · CM-2.3 条目](https://ato-pathways.com/catalogs/oscal/catalogs/NIST_SP-800-53_rev5_catalog:latest/items/cm-2.3)**  
   - 保留先前配置的 OSCAL 目录视图。  
8. **[GSA · Configuration Management (CM) 政策 PDF](https://www.gsa.gov/system/files/Configuration-Management-%28CM%29-%5BCIO-IT-Security-01-05-Rev-6%5D.pdf)**  
   - 机构 CM 制度样例：基线、变更、记录。  
9. **[EPA · Configuration Management Procedure PDF](https://www.epa.gov/system/files/documents/2023-06/information_security_configuration%20management%20_procedure.pdf)**  
   - 基线年审/重大变更更新与保留上一版气质。  
10. **[Daydream · NIST CM-2(2) 自动化与漂移检测白话](https://learn.daydream.ai/requirements/nist-sp-800-53-n80053-269)**  
    - 基线货币性与漂移报告气质；**不绑定某工具。**  
11. **[Daydream · ISO 27001 Annex A 8.9 Configuration Management](https://learn.daydream.ai/requirements/iso-27001-iso27001-68)**  
    - 基线+变更+持续漂移检测白话；对照 Q 五段。  
12. **[Microsoft Zero Trust · Implement drift detection（DS_081）](https://microsoft.github.io/zerotrustassessment/docs/workshop-guidance/devsecops/DS_081)**  
    - 活体相对声明基线的漂移检测顺序；只借「比对→分授权/未授权→修复或改基线」。  
13. **[DMRhub · Codeplug backup: how not to lose your radio settings](https://dmrhub.ru/tech/en/bekap-codeplug)**  
    - 先读后存、命名与副本气质；指针 J-备 + 本篇对照样要有备份。  
14. **[BridgeCom · Duplicate or Export DMR Codeplug](https://www.bridgecomsystems.com/blogs/bridgecom-official-blog/how-to-duplicate-or-export-the-codeplug-on-your-dmr-radio)**  
    - 导出/复制 codeplug 操作气质（业余实践；专网按其 CPS）。  
15. **[BTECH · Build a DMR 6X2 Code Plug](https://baofengtech.com/build-a-dmr-6x2-code-plug-a-basic-code-plug-for-your-dmr-radio/)**  
    - 信道/区域结构入门；提醒结构懂了仍要备份与巡检。  
16. **[MO Digital Group · DMR Code Plugs Demystified（PDF）](https://modigitalgroup.org/wp-content/uploads/2025/02/DMR-Code-Plugs-Demystified-20250213.pdf)**  
    - Codeplug 概念拆解；写「指纹摘要」字段时建词汇。  
17. **[Atlantic Radio · Hytera codeplug backup/restore tips](https://www.atlanticradiocorp.com/blogs/news/tips-for-backing-up-and-restoring-hytera-radio-code-plugs)**  
    - 备份命名、机型匹配、先刷样机气质；对照 Q-金/Q-比。  
18. **[RATS · DIY Codeplug Programming Basics](https://codeplugs.rats.net/diy)**  
    - 「先读出再改」公开实践；对齐先读后写 + 对照样。  
19. **[RMHAM · DMR Programming Workshop（PDF）](https://www.rmham.org/wp-content/uploads/2023/11/RMHAM-U_November2023_ProgrammingWorkshop-1.pdf)**  
    - 编程概念扫盲；提醒批量后仍要验证与抽检。  
20. **[Motorola · APX Radio Management Fact Sheet（PDF）](https://aem-cloud-prod-cdn.motorolasolutions.com/content/dam/msi/docs/business/product_lines/apx/documents/apx_radio_management_fact_sheet.pdf)**  
    - 车队配置仓库/版本气质；对照现服索引，**不绑定品牌强制**。  
21. **[Motorola Support · MOTOTRBO CPS & RM USB best practices](https://support.motorolasolutions.com/s/article/KB0058298?language=en_US)**  
    - 写频卫生（供电/库/工具版本）；指针 M/J，抽检仍要 Q。  
22. **[Motorola Support · MOTOTRBO RM OTAP Best Practices](https://support.motorolasolutions.com/s/article/KB0058548?language=en_US)**  
    - OTAP 强稳覆盖/勿关机/小批量/库一致；对照手册14 + 本篇抽检。  
23. **[Motorola Solutions · MOTOTRBO 入口](https://www.motorolasolutions.com/en_us/products/two-way-radios/mototrbo.html)**  
    - 查本网机型文档入口；本篇不绑定菜单课。  
24. **[HCI ITIL · Service Configuration Management](https://www.hci-itil.com/ITIL_v3/books/3_service_transition/service_transition_ch4_3.html)**  
    - CI/基线直觉；把 codeplug 当配置项管。  
25. **[Wikipedia · Configuration management](https://en.wikipedia.org/wiki/Configuration_management)** · **[Baseline (configuration management)](https://en.wikipedia.org/wiki/Baseline_%28configuration_management%29)**  
    - CM 与基线名词垫脚石。  
26. **[Wikipedia · Software configuration management](https://en.wikipedia.org/wiki/Software_configuration_management)** · **[Version control](https://en.wikipedia.org/wiki/Version_control)** · **[Configuration item](https://en.wikipedia.org/wiki/Configuration_item)**  
    - 版本与 CI；对照「现服+上一版」。  
27. **[Wikipedia · Change management](https://en.wikipedia.org/wiki/Change_management)** · **[ITIL](https://en.wikipedia.org/wiki/ITIL)**  
    - 变更管理与 ITIL 地图。  
28. **[Wikipedia · Gold master](https://en.wikipedia.org/wiki/Gold_master)** · **[Reference implementation](https://en.wikipedia.org/wiki/Reference_implementation)** · **[Master copy](https://en.wikipedia.org/wiki/Master_copy)**  
    - 「金样/母版」隐喻；对照 Q-金（物理电台语境，勿照搬软件发行流程）。  
29. **[Wikipedia · Acceptance sampling](https://en.wikipedia.org/wiki/Acceptance_sampling)** · **[Quality assurance](https://en.wikipedia.org/wiki/Quality_assurance)** · **[Statistical process control](https://en.wikipedia.org/wiki/Statistical_process_control)**  
    - 抽检与质控常识；对照 Q-巡比例直觉，**不抄工厂 AQL 数字当本网法规**。  
30. **[Wikipedia · Calibration](https://en.wikipedia.org/wiki/Calibration)** · **[Metrology](https://en.wikipedia.org/wiki/Metrology)** · **[Standard (metrology)](https://en.wikipedia.org/wiki/Standard_%28metrology%29)**  
    - 对照样要定期校准的隐喻；金机自巡。  
31. **[Wikipedia · Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio)** · **[Land mobile radio system](https://en.wikipedia.org/wiki/Land_mobile_radio_system)** · **[Two-way radio](https://en.wikipedia.org/wiki/Two-way_radio)** · **[Over-the-air programming](https://en.wikipedia.org/wiki/Over-the-air_programming)**  
    - DMR/专网/OTAP 垫脚石。  
32. **[DMR Association · Key Benefits](https://dmrassociation.org/dmr-key-benefits.html)** · **[Scanner School · Intro to DMR](https://www.scannerschool.com/introduction-to-dmr/)**  
    - 官方/白话入门；提醒漂移巡检不改变 12.5 kHz/两槽。

**视频：**

33. **[How to Create a Digital Codeplug for Your Radio!（YouTube）](https://www.youtube.com/watch?v=ycoQc8SbKoY)**  
    - 数字 codeplug 创建入门；配合「有工程仍要备份与巡检」。  
34. **[Amateur Radio & CPS Software A Beginner's Guide（YouTube）](https://www.youtube.com/watch?v=QOA_G7Q8hko)**  
    - CPS 新手向；先读后写气质。  
35. **[Basic DMR Programming with RT Systems software（YouTube）](https://www.youtube.com/watch?v=w5xrH7urisU)**  
    - 第三方编程气质；仍要机型匹配与抽检。  
36. **[DMR Programming for Amateur Radio（YouTube）](https://www.youtube.com/watch?v=a0yzn2rckEo)**  
    - 编程概念专场；提醒批量后验证与对照。  
37. **[Scanner School · What is DMR?（YouTube）](https://www.youtube.com/watch?v=aQX_JbTbXuY)**  
    - 双时隙入门弱项补。  
38. **[Scanner School · Why Digital Radio Sounds Like Robots（YouTube）](https://www.youtube.com/watch?v=-hLiTz7oSKE)**  
    - 数字悬崖/BER；「听感怪」别先骂干扰，先问是否刚写过。  

> **诚实说明**：没有找到「DMR 专网金机基线漂移巡检（档案授牌 + 书面判据 + 大批量后强制抽检 + 金机并测 + 超阈回滚 + 插页 Q）」专项中文/公开制度视频；上文为 NIST/ISO CM 与漂移精神、codeplug/CPS/OTAP 卫生、抽检隐喻与 DMR 基础，需按贴纸 Q 与 R1–R8 拼进巡检包。`video_found=true`（通用视频 + CM/漂移文档），**非**专项「DMR 金机漂移巡检制度」教程。

**库内必回：** `学习推送/手册11_写频变更回滚与金机基线制度.md`（J 母册）、`手册14_大批量写频与OTAP风险边界.md`（M；完成账≠抽检）、`手册08_测试实验室最小闭环.md`（G 并测气质）、`手册15_电源监控对时与告警风暴治理.md`（假绿 N）、`手册06_日志三联单深化.md`、`手册07_覆盖与同频干扰分诊.md` / `手册09_话务与容量分诊.md`（禁加功率/加信道）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子

- 贴纸 **Q** 五子类：金 / 漂 / 巡 / 比 / 治。  
- 故事：药监对照样 + 柜台货抽检。  
- 八条硬规则；**大批量后强制抽检**；**无判据禁签**；**超阈禁放行**；**金机也要自巡**；**禁加功率掩盖**。  
- 主贴 Q，可挂 J/M/G/N；M 过 ≠ Q 过。  
- 公开包脱敏 L3。

### 11.2 回库路径

```text
  写频后怪机 / 「配置正常」签字 / 金机对照说谎
       │
       ├─ 手册11（J 读写回滚 / 金机建档）
       ├─ 手册14（M 批量 OTAP / 完成账）
       ├─ 手册08/15（G 并测 / N 假绿）
       └─ 本篇手册18（贴纸Q + 插页Q + 漂移巡检卡）
```

### 11.3 下一篇手册候选（本篇不写正文）

- **网管采集高可用与假绿演练剧本**  
- **邻频协调与边界联测制度**  
- **（可选）干扰投诉分诊与证据链**  

### 11.4 给带新人的三句话

1. 对照样没瓶签、没复检，不许拿去验柜台货。  
2. 大批量写完不抽检，完成账再绿也不放行。  
3. 机子怪，先对基线——禁止加功率拧 Hangtime 结案。

### 11.5 运维一周里怎么用这篇（复印到周历）

| 日 | 动作 |
|----|------|
| 一 | 扫开口：批量后待抽检、金机自巡过期 |
| 三 | 抽检一例脱敏进对齐会 |
| 五 | 核现服索引与上一版指针 |
| 夜班 | 7.5 五行；禁私改金机 |

### 11.6 和弱项加餐的衔接

漂移巡检不改 12.5 kHz / 4FSK / 30 ms；只管账本对齐。加功率叙事 → 加餐 + 规则2。

### 11.7 一张图记住本篇（收工贴纸）

```text
  ┌────────── 贴纸 Q ──────────┐
  │ 金 = 对照样有瓶签·要自巡   │
  │ 漂 = 判据写在纸上          │
  │ 巡 = 开袋抽·批量后强制     │
  │ 比 = 金机与货上同一天平    │
  │ 治 = 超阈回滚·禁感觉·L3   │
  └────────────────────────────┘
```

### 11.8 十分钟给领导的电梯演讲

> 「金机是药监对照样，不是随便好机。档案可对、判据书面、大批量后必须抽检并测，超阈先回滚隔离；不接受感觉正常或假绿代替对照表；不加功率掩盖机子怪。这是配置治理，不是 CPS 菜单。」

### 11.9 和手册11 / 14 同时爆发时怎么分工

- 变更当天无备份 → **J 拒写**；写后还有 Q。  
- OTAP 完成账争议 → **M 管账** + **Q 抽检**放行门槛。  
- 写完两周对不上 → **Q 主责**；回滚走 **J-回**。  
- 禁用「先加功率」换「先对基线」。

## 12. 本篇检查清单（自学打勾）

- [ ] 能讲药监对照样 + 柜台货抽检故事  
- [ ] 能背贴纸 Q 五子类  
- [ ] 能背八条硬规则  
- [ ] 会填插页 Q 的 R1–R8  
- [ ] 会用拒签卡挡住「感觉正常 / 零抽检放行」  
- [ ] 能区分 Q 与 J/M/G/N 主次挂  
- [ ] 会做大批量后强制抽检口述  
- [ ] 会做金机并测口述  
- [ ] 自测 10 题过关  
- [ ] 知道下一篇候选不在本篇展开  
- [ ] 公开举例已脱敏 L3  
- [ ] 弱项 12.5 kHz/4FSK/30 ms 已口头复习  
- [ ] 能做「假干扰排除三问」  
- [ ] 明白 M 过 ≠ Q 过  
- [ ] 看过至少 2 篇 §10 配置管理/漂移或 codeplug 链接  
- [ ] 明白不发明 ETSI 条款号、不抄蜂窝 KPI 当本网法规  

---

*手册18 · 金机基线漂移巡检专项 · 学习推送 · 2026-10-17 18:52 +08:00*
