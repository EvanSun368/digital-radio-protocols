## 8. 术语表（本篇约 30 词）+ 易错观念

| 术语 | 白话 |
|------|------|
| **OTAP** | Over-The-Air Programming，经空口下发配置/部分固件类变更的能力（厂商实现各异；本篇讲制度边界，不讲密钥） |
| **无线写频** | 与 OTAP 同类气质的空中配置通道；相对有线 CPS |
| **有线写频** | 电缆/写频座连接的 CPS 写入；岸边换装 |
| **大批量写频** | 一次作业覆盖多台；须分批与进度账（M-批） |
| **分批** | 把舰队拆成可冻结、可验证的小段 |
| **冻结窗** | 暂停继续写入的时间盾，用于验证或止损 |
| **试点 / 小样本** | 全量前的试投闭环对象（M-试） |
| **金机** | 有档案的基线样机（指针手册11 J-基）；≠随便好机 |
| **完成报表** | 成功/失败/未达（或厂商等价状态）清单 |
| **未达** | 空投未送达或状态未知——不得默认当成功 |
| **半成功 / 半砖** | 配置不完整或功能残缺态；须隔离回滚 |
| **货封** | 本篇比喻：密钥/鉴权/库一致性 |
| **投放区** | 本篇比喻：强稳覆盖窗 |
| **油量** | 本篇比喻：电量与勿关机约束 |
| **管理台权限** | 谁能发起 OTAP/批量；须最小化与复核 |
| **脏库** | 管理台终端库与现服不一致 |
| **错钥** | OTAP 相关密钥/鉴权材料不匹配（不写具体值） |
| **机型族** | 可共用同一模板策略的型号集合（本网定义） |
| **固件族** | 重大固件世代；跨族互写禁止 |
| **模板 / codeplug 策略** | 批量下发的配置包；须分族 |
| **进度账** | 实时或近实时的批次完成记录 |
| **有线回滚路径** | 失败机必须能回到岸边重装上一版 |
| **忙时全网空口写** | 话务高峰对全舰队空投——本篇禁止 |
| **弱覆盖写** | 在投放区不合格处空投——本篇禁止 |
| **低电写** | 电量门槛下空投——本篇禁止 |
| **脱敏 L3** | 手册06：公开材料去掉频点/个号/密钥/站名/单位名 |
| **贴纸 M** | 本篇批量/OTAP 主贴 |
| **插页 M** | R1–R8 证据栅格 |
| **CPS** | Customer Programming Software 一类写频软件统称（不绑菜单） |
| **空口占用** | OTAP 争用语音/信令资源的事实 |

**易错观念**：

- 「OTAP 成功弹窗」≠ 完成报表。  
- 「重试」≠ 覆盖治理。  
- 「批量」≠ J 规则豁免。  
- 「机型差不多」≠ 可通刷。  
- 「用户会拿来修」≠ 有线回滚路径。  
- 「加功率让 OTAP 稳」= 禁令。  
- 「忙时写省事」= 用话务事故换便利。

---

## 9. 自测（10 题）+ 参考答案

**题 1.** 贴纸 M 五个子类各用一句话说明；各举一个拒写/拒放行触发。  
**题 2.** 画出「空投物资 + 分批换装」链：岸边、投放区、油量、货封、试投、完成账各在哪。  
**题 3.** 八条硬规则默写（大意正确即可）。  
**题 4.** 为何「无小样本就全网 OTAP」必须拒写？R5 缺什么？  
**题 5.** 手册11 J 规则在批量场景是否豁免？举例。  
**题 6.** 插页 M 的 R4、R5、R6、R7 各挡住哪种胡说？  
**题 7.** 假成功 / 假覆盖窗 / 假忙时 各举一例真因；错误处置是什么？  
**题 8.** 失败机为什么必须有有线回滚路径？只靠 OTAP 重推有什么风险？  
**题 9.** 有线分批与 OTAP 如何选型？高风险变更优先哪条？  
**题 10.** 下一篇候选你记住哪两个？本篇写了它们正文吗？

### 参考答案

1. M-批编排分批；M-空覆盖/电量/勿关机窗；M-钥货封；M-试试点闭环；M-界拒写边界。触发见表 2.4。  
2. 见 §2.1 ASCII；岸边=有线；投放区/油量=M-空；货封=M-钥；试投=M-试；完成账=M-界。  
3. 见 §4.1 八条。  
4. 试投不过则全量事故半径不可接受；R5 业务闭环空。  
5. **不豁免**。例如无备份仍禁写；验失败仍必回滚；跨机型仍禁。  
6. R4 挡错钥硬开写；R5 挡无试点全量；R6 挡弱覆盖/低电/忙时；R7 挡无报表放行。  
7. 进度条当成功；边缘统推；OTAP 占空口。错：直接放行/加功率重推/加信道。  
8. 半砖与未达常需岸边复活；只靠空口重推可能反复落海并污染话务。  
9. 高风险优先有线分批；OTAP 仅在强覆盖、已验证模板、可冻结窗。  
10. 电源监控对时与告警风暴治理；以及其它（如室分有源隔离等）。**本篇未写正文。**

---

## 10. 加深阅读与视频（均已用 curl 核对 HTTP 200；视频用 YouTube oEmbed 核对存在）

1. **[Motorola Solutions Support · MOTOTRBO Radio Management OTAP Best Practices（KB0058548）](https://support.motorolasolutions.com/s/article/KB0058548?language=en_US)**  
   - 厂商 OTAP 最佳实践公开文：窗口规划、监控完成状态等气质；对照 M-空 / M-界。**只借精神，不背菜单当本网制度。**  
2. **[NCSC · Secure RF Communications · Principle 4（OTA）](https://www.ncsc.gov.uk/collection/operational-technology/secure-rf-communications/principle-4)**  
   - 英国国安 OT 场景下 OTA 固件/配置的鉴权与完整性原则；对照 M-钥（制度边界，非密钥教程）。  
3. **[DCS · Glossary · Over The Air Programming (OTAP)](https://www.dcs2way.co.uk/glossary/over-the-air-programming-otap/)**  
   - OTAP 名词白话入口；适合新人建立「空中写频 ≠ 魔法」直觉。  
4. **[NIJ / OJP · Public Safety Radio Encryption（PDF，224791）](https://www.ojp.gov/pdffiles1/nij/224791.pdf)**  
   - 公共安全无线加密与密钥管理公开读物；借「密钥治理要严肃」精神，**不提取可操作密钥步骤**。  
5. **[Motorola Solutions · MXP600 OTAP Use Case（PDF）](https://www.motorolasolutions.com/content/dam/msi/images/products/mxp600/mxp600_otap_use_case_eng_emea.pdf)**  
   - 厂商用例白皮书气质：场景化 OTAP；对照「先场景窗口、再便利」。  
6. **[NIST SP 800-128 · Guide for Security-Focused Configuration Management（PDF）](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-128.pdf)**  
   - 配置管理：变更可控、基线、回滚气质；对齐 M-批 / 手册11 J。  
7. **[NIST · SP 800-128 发布页（upd1）](https://csrc.nist.gov/pubs/sp/800/128/upd1/final)**  
   - 同上文档入口页，便于核对版本。  
8. **[NIST SP 800-40r4 · Guide to Enterprise Patch Management Planning（PDF）](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-40r4.pdf)**  
   - 企业补丁/变更规划：试点、分批、回滚；与「先试投后全量」同构。  
9. **[NIST · SP 800-40 Rev.4 发布页](https://csrc.nist.gov/pubs/sp/800/40/r4/final)**  
   - 发布页备份入口。  
10. **[NIST SP 800-70r4 · National Checklist Program（PDF）](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-70r4.pdf)**  
    - 安全配置检查清单生态；借「配置要可检查」精神。  
11. **[NIST · SP 800-53 Rev.5 upd1 发布页](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)**  
    - 控制族总览入口（CM 等）；**不背控件编号当 ETSI**。  
12. **[NCSC · Operational Technology 专题合集](https://www.ncsc.gov.uk/collection/operational-technology)**  
    - OT 安全总览；把无线专网放进「运行技术」语境。  
13. **[NCSC · Device Security Guidance · Managing Deployed Devices](https://www.ncsc.gov.uk/collection/device-security-guidance/managing-deployed-devices)**  
    - 已部署设备的变更与管理气质；对照舰队写频治理。  
14. **[NCSC · Device Security Guidance 合集入口](https://www.ncsc.gov.uk/collection/device-security-guidance)**  
    - 设备安全指导总入口。  
15. **[CISA · Secure by Design](https://www.cisa.gov/resources-tools/resources/secure-by-design)**  
    - 默认安全与供应商责任讨论；借「便利功能默认要有边界」语气。  
16. **[CISA · Cybersecurity Best Practices](https://www.cisa.gov/topics/cybersecurity-best-practices)**  
    - 最佳实践主题入口。  
17. **[NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)**  
    - 识别-保护-检测-响应-恢复总图；批量事故的「响应/恢复」要对完成账与回滚。  
18. **[Wikipedia · Over-the-air programming](https://en.wikipedia.org/wiki/Over-the-air_programming)**  
    - OTA/OTAP 百科地图。  
19. **[Wikipedia · Configuration management](https://en.wikipedia.org/wiki/Configuration_management)**  
    - 配置管理名词垫脚石。  
20. **[Wikipedia · Change management (ITSM)](https://en.wikipedia.org/wiki/Change_management_(ITSM))** · **[ITIL](https://en.wikipedia.org/wiki/ITIL)**  
    - 变更管理 / ITIL 直觉；对照冻结窗与放行。  
21. **[Wikipedia · Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio)** · **[Firmware](https://en.wikipedia.org/wiki/Firmware)** · **[Patch (computing)](https://en.wikipedia.org/wiki/Patch_(computing))**  
    - DMR / 固件 / 补丁定义级复习。  
22. **[Wikipedia · Land mobile radio system](https://en.wikipedia.org/wiki/Land_mobile_radio_system)** · **[Two-way radio](https://en.wikipedia.org/wiki/Two-way_radio)** · **[Authentication](https://en.wikipedia.org/wiki/Authentication)**  
    - 专网电台与鉴权气质补强。  
23. **[DMR Association · Key Benefits of DMR Technology](https://dmrassociation.org/dmr-key-benefits.html)**  
    - 官方白话弱项补；与频谱短补对齐。  
24. **[Scanner School · An Introduction to DMR](https://www.scannerschool.com/introduction-to-dmr/)**  
    - 文文入门；避免把批量事故说成「数字电台玄学」。  
25. **[Motorola Solutions · MOTOTRBO 产品入口](https://www.motorolasolutions.com/en_us/products/two-way-radios/mototrbo.html)** · **[Support 门户](https://support.motorolasolutions.com/)**  
    - 厂商产品/支持入口（查找本网机型文档时用；本篇不绑定菜单课）。  
26. **[AXELOS · ITIL 4 Foundation](https://www.axelos.com/certifications/itil-service-management/itil-4-foundation)**  
    - 变更与发布管理学习入口之一（商业认证页；只借「变更要可控」精神）。

**视频：**

27. **[Scanner School · What is DMR?（YouTube）](https://www.youtube.com/watch?v=aQX_JbTbXuY)**  
    - 双时隙入门弱项补；提醒批量/OTAP 不改变 12.5 kHz/两槽物理。  
28. **[Scanner School · Why Digital Radio Sounds Like Robots（YouTube）](https://www.youtube.com/watch?v=-hLiTz7oSKE)**  
    - 数字悬崖/BER 直觉；半砖与弱覆盖「突然卡」和模拟「渐渐差」的差别。

> **诚实说明**：没有找到「DMR 专网舰队 OTAP / 大批量写频风险边界（含试投闭环 + 完成报表拒放行 + 失败机有线回滚制度 + 插页拒写）」专项中文/公开视频教程；上面的视频与文档分别讲厂商 OTAP 最佳实践、OTA 安全原则、配置/补丁管理与 DMR 基础，需要你自己按本篇贴纸 M 与插页 R1–R8 把它们拼进作业包。`video_found=true`（通用 DMR 入门视频 + 文档侧 OTAP/CM），**非**专项「DMR 舰队 OTAP 制度」教程。

**库内必回：** `学习推送/手册11_写频变更回滚与金机基线制度.md`（本篇的母册 J）、`手册06_日志三联单深化.md`（对时/脱敏）、`手册07_覆盖与同频干扰分诊.md`（假 F / 禁加功率）、`手册08_测试实验室最小闭环.md`（试点闭环气质）、`手册09_话务与容量分诊.md`（假 H）、`手册01_登记失败三问.md` / `手册02_Grant了没声.md` / `手册05_鉴权失败分诊.md`（写后次挂）、`手册10_室分隧道覆盖交维清单.md` / `手册13_电梯井地下车库专项.md`（弱覆盖点）、`手册12_基站电源与后备切换交维.md`（管理台/信源掉电）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子

- 贴纸 **M** 五子类：批 / 空 / 钥 / 试 / 界。  
- 故事：有线批量 = 岸边分批换装；OTAP = 空投；先投放区、油量、货封、试投，再舰队空投；无完成账不放行。  
- 八条硬规则；**J 规则批量不豁免**。  
- 禁忙时全网空口写；禁弱覆盖/低电 OTAP；禁错钥开写；禁跨机型/跨重大固件通刷；禁无报表放行。  
- 症状可挂 J/F/H/A/B，**主贴 M**（批量/OTAP 路径问题）。

### 11.2 回库路径

```text
总索引.md
  └─ 集群 / Tier III → 运维手册
       ├─ 手册01–05（A–E）06（总单）07（F）08（G）09（H）10（I）11（J）12（K）13（L）
       └─ 本篇手册14（贴纸M + 插页M + 大批量写频与 OTAP 风险边界卡）
            └─ 回：手册11（母册）、06–10、12–13、加餐弱项
```

### 11.3 下一篇手册候选（本篇不写正文）

- **电源监控对时与告警风暴治理**（手册12 K-告 的加深册）。  
- **（可选）其它**：例如室分有源隔离与减敏台架专项、口部切换与邻站泄漏治理、大批量写频后的金机基线漂移巡检等（按现场痛点再排）。

### 11.4 给带新人的三句话

> 没有试投闭环，就没有全网空投。  
> 没有完成报表与失败机有线路径，就没有放行。  
> OTAP 是便利通道，不是 J 规则的豁免券，更不是覆盖/干扰的止痛药。

### 11.5 运维一周里怎么用这篇（复印到周历）

```text
周一  默写 M 五子类 + 「无试投/无报表禁止放行」卡
周二  对一份旧 OTAP/批量包：有无 R5/R7
周三  演练脚本 C（错钥）与脚本 D（忙时）
周四  抽查电量门槛与勿关机通知模板
周五  对齐会：本周失败机有线回滚是否闭环；统计拒写次数
```

### 11.6 和弱项加餐的衔接

把 12.5 kHz / 4FSK / 30 ms 两槽背熟，你才说得清「批量/OTAP 改的是配置账本与空口窗口，不是调制台阶」。有人要用空口大批量写或加功率开 OTAP 窗时，回加餐 + 手册07/09/11。

### 11.7 一张图记住本篇（收工贴纸）

```text
        要大批量写频 / 要 OTAP
                      │
          ┌───────────┴───────────┐
          │ 机型族/固件族已拆分？    │否 → 拒写（M-界）
          ▼
        钥/权/库一致？──否──▶ 拒开写（M-钥）
          │是
          ▼
        小样本业务闭环过？──否──▶ 禁全量（M-试）
          │是
          ▼
        强稳覆盖+足电+勿关机+非忙时？──否──▶ 改窗（M-空/M-界）
          │是
          ▼
        执行 + 进度账 → 完成报表有成功/失败/未达？
          │否 → 拒放行（M-界）
          ▼
        失败机有线回滚路径就绪？──否──▶ 拒放行
          │是
          ▼
        更新现服/金机基线（指针 J）；主贴 M；可挂 J/F/H/A/B
        禁令：无试点全量；弱覆盖/低电；错钥；忙时全网空口；通刷；无报表放行；加功率开窗
```

---

## 12. 本篇检查清单（自学打勾）

- [ ] 能背 M 五子类并各举一个拒写/拒放行例子  
- [ ] 能画「空投物资 + 分批换装」链并指出五段  
- [ ] 能背八条硬规则  
- [ ] 能说明货封→试投→窗口→完成账的顺序直觉  
- [ ] 能拒绝「无试点全量 / 弱覆盖 OTAP / 错钥继续 / 忙时全网空口 / 无报表放行」  
- [ ] 会填插页 M 的 R1–R8  
- [ ] 会用 §7 封面拒写门槛 + 试投剧本页 + 完成账页做一次模拟作业  
- [ ] 知道假成功/假覆盖窗/假忙时如何主贴 M  
- [ ] 知道写后如何次挂手册01/02/05/07/09/11 而不改主贴  
- [ ] 自测 10 题达标；回库重对至少 1 次批量/OTAP 事件（L3）  
- [ ] 知道下一篇候选且**本篇未写它们的正文**  
- [ ] 外链打开过至少 3 个（含 1 个 OTAP/OTA 文 + 1 个 NIST CM/补丁文或 DMR 入门视频）

---

*手册模式第 14 篇 · 贴纸 M · 2026-10-15 · 教学用 · 脱敏 L3*
