## 8. 术语表（本篇约 28 词）+ 易错观念

| 术语 | 白话 |
|------|------|
| 口部 | 洞口/楼门/坡道/换乘等室内外或扇区过渡带 |
| 切换区 | 图上可指认的、从听 A 到听 B 的空间范围 |
| 切换窗 | 切换区里「允许换耳朵」的气质段落（制度层） |
| 驻留 | 终端在窗内停留是否够稳 |
| 乒乓 | 左右跳、两家喇叭来回抢客 |
| 切换失败气质 | 门口断话/重登/听感悬崖（不 dump 字段） |
| 邻站泄漏 | 邻站能量灌进洞/楼/库 |
| 外溢边界 | 邻站不该喊过界的书面边界（脱敏相对值） |
| 室内外过渡 | 门厅/闸机前从室外宏站优势到室内优势的转换 |
| 滞留区 | 排队/等人处；忌当扇区边界 |
| 金机口部走测 | 用基线终端做口部双向与滞留检查 |
| 优势区 | 某站/扇区应主导的区域 |
| 加站叙事 | 未证窗与泄就主张新站 |
| 12.5 kHz | DMR 信道带宽台阶 |
| 4FSK | DMR 调制 |
| 时隙 30 ms | TDMA 一格 |
| 三联单 | 手册06 证据写法 |
| 脱敏 L3 | 去掉真实频点楼名站号个号密钥 |
| 假绿交维 | 指标不全却显示可签 |
| 主贴/次挂 | 结案主因贴纸与次要贴纸 |
| 教学相对值 | 脱敏后的比较用读数 |
| 室分/DAS | 室内分布系统（指针 I） |
| 有源隔离 | 贴纸 O；口部有源时叠挂 |
| 井库 L-切 | 手册13 坡道/井道猎站气质 |
| 邻道/同频 | 手册07；先排除 P 再认定 |
| 话务忙 | 手册09；乒乓可假扮忙 |
| 带条件签 | 书面开口项+到期 |
| 拒加站 | 规则1 闸门动作 |

**易错观念**

1. 「洞内好 = 口部好」——假绿。  
2. 「乒乓是用户走快」——先查窗与外溢。  
3. 「加功率能压过门口」——规则2 禁止。  
4. 「加站总能解决抢客」——未证窗与泄时常常加乱。  
5. 「泄漏就是同频」——先 P-泄 后 F。  
6. 「公网满格 = DMR 口部好」——指标错位。  
7. 「手册13 写过切就不用 P」——L 管井库，P 钉口部与邻站泄漏。  
8. 「切换参数厂商自动最优」——本网仍要窗可指认与金机证据。

---

## 9. 自测（10 题）+ 参考答案

1. 贴纸 P 五个子类各一字？  
2. 为什么用「两家喇叭门口抢客」比喻？答一句。  
3. 八条硬规则里，哪一条禁止加功率/加增益掩盖泄漏与乒乓？  
4. 口部金机走测能否用「只测洞内」代替？依据哪条？  
5. 切换窗未定义时能否签字或盲目加站？  
6. 邻站泄漏未测能否签口部相关交维？  
7. 「洞内听到邻站」优先 P 还是 F？  
8. 插页 R3/R5/R7 不过时分别意味着什么？  
9. 主贴 P 时可挂哪些常见次贴纸？  
10. 公开包脱敏 L3 禁写哪些？  

### 参考答案

1. 口 / 切 / 泄 / 邻 / 治。  
2. 两家店喇叭对着门口抢客，过客左右跳，广告还灌进店里——对应切换窗与邻站泄漏。  
3. 规则2。  
4. 不能；规则3。  
5. 不能；规则4。  
6. 不能；规则5。  
7. 先 P-泄 排除泄漏，再视情况挂 F；规则6。  
8. R3→切换区未定义拒签；R5→泄漏未测拒签；R7→口部金机未测拒签。  
9. L/I/F/O（及必要时 H）；规则6。  
10. 真实频点、楼名、站号、个号、密钥等；规则8。

---

## 10. 加深阅读与视频（均已用 curl 核对 HTTP 200；视频用 YouTube oEmbed 核对存在）

1. **[AMTA · MCF Design Guidelines for DAS Draft 2.0（PDF）](https://amta.org.au/wp-content/uploads/2024/10/MCF-Design-Guidelines-for-Distributed-Antenna-Systems-Draft-2.0-IBC-Workgroup-11092024-1.pdf)**  
   - 出入口 handover zone、controlled leakage、扇区边界避开滞留区；对照 P-口/P-切/P-泄。**借精神，不背条款当 ETSI。**  
2. **[OUC DC · In-Building Radio System Technical Requirements（PDF）](https://ouc.dc.gov/sites/default/files/dc/sites/OUC/page_content/attachments/3-0-DC-In-Building-Radio-System-Technical-Requirements.pdf)**  
   - 室内增强不得有害影响公共安全网气质；交维清单思维；对照 P-治/P-邻。  
3. **[City of Seattle · BDA/DAS system acceptance（PDF）](https://www.seattle.gov/documents/departments/fire/business/systestdasaccept2021sfc.pdf)**  
   - 验收与隔离余量检查项气质；口部有源叠挂时可对照 O，泄漏治理对照 P。  
4. **[ETSI ETR 053 · Radio site engineering（PDF）](https://www.etsi.org/deliver/etsi_etr/001_099/053/02_60/etr_053e02p.pdf)**  
   - 站点工程与邻站兼容公开报告；**只借工程精神，不背条款号当 DMR ETSI 强制。**  
5. **[ETSI EG 200 053 V1.5.1 · Radio site engineering（PDF）](https://www.etsi.org/deliver/etsi_eg/200001_200099/200053/01.05.01_60/eg_200053v010501p.pdf)**  
   - 后续引导文件入口；同上，借精神。  
6. **[ETSI TR 100 053 · Radio site engineering（PDF）](https://www.etsi.org/deliver/etsi_tr/100001_100099/100053/01.03.01_60/tr_100053v010301p.pdf)**  
   - 同址/邻站兼容与邻道气质入口。  
7. **[ETSI TS 100 527 · Handover procedures（PDF）](https://www.etsi.org/deliver/etsi_ts/100500_100599/100527/06.00.00_60/ts_100527v060000p.pdf)**  
   - 蜂窝切换过程公开规范入口；**只了解「切换是制度+测量」气质，不背作 DMR 空口课。**  
8. **[ETSI TS 123 009 · Handover procedures（PDF）](https://www.etsi.org/deliver/etsi_TS/123000_123099/123009/19.00.00_60/ts_123009v190000p.pdf)**  
   - 切换程序后续版本入口；同上，借精神。  
9. **[City of Richmond · BDA final inspection & acceptance（PDF）](https://www.rva.gov/sites/default/files/2025-02/City%20of%20Richmond%20BDAs%20Inspection.pdf)**  
   - 验收表气质（含施主侧相关检查思维）；对照 P-治；有源场景可叠挂 O。  
10. **[Comba · What’s all the fuss about uplink noise?](https://combausa.com/pr/whats-all-the-fuss-about-uplink-noise/)**  
    - 上行噪声与外溢相关气质；口部有源场景可叠挂 O。  
11. **[Comba · Commissioning Tip #2 – Isolation resolution](https://combausa.com/pr/commissioning-tip-2-isolation-resolution/)**  
    - 隔离与天线位置；口部有源时指针 O。  
12. **[Radioactivity · DMR versus TETRA comparison（PDF）](https://www.radioactivity-tlc.it/pdf/dmrvstetra-comparison.pdf)**  
    - 邻道保护等差气质扫盲；**不把其数字当本网法规。**  
13. **[Wikipedia · Handover](https://en.wikipedia.org/wiki/Handover)** · **[Cell breathing](https://en.wikipedia.org/wiki/Cell_breathing)**  
    - 切换/小区呼吸名词垫脚石。  
14. **[Wikipedia · Ping-pong scheme](https://en.wikipedia.org/wiki/Ping-pong_scheme)** · **[Hysteresis](https://en.wikipedia.org/wiki/Hysteresis)**  
    - 乒乓与迟滞常识（工程借用，非 DMR 字段课）。  
15. **[Wikipedia · Distributed antenna system](https://en.wikipedia.org/wiki/Distributed_antenna_system)** · **[Femtocell](https://en.wikipedia.org/wiki/Femtocell)**  
    - 室分/室内小站与宏站边界直觉。  
16. **[Wikipedia · Adjacent-channel interference](https://en.wikipedia.org/wiki/Adjacent-channel_interference)** · **[Co-channel interference](https://en.wikipedia.org/wiki/Co-channel_interference)**  
    - 邻道/同频指针回 F；提醒先排除 P。  
17. **[Wikipedia · Radio propagation](https://en.wikipedia.org/wiki/Radio_propagation)** · **[Path loss](https://en.wikipedia.org/wiki/Path_loss)** · **[Shadow fading](https://en.wikipedia.org/wiki/Shadow_fading)**  
    - 口部过渡带传播弱项补。  
18. **[Wikipedia · Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio)** · **[Land mobile radio](https://en.wikipedia.org/wiki/Land_mobile_radio_system)** · **[Two-way radio](https://en.wikipedia.org/wiki/Two-way_radio)**  
    - DMR/专网垫脚石。  
19. **[Wikipedia · Decibel](https://en.wikipedia.org/wiki/Decibel)** · **[Signal-to-interference ratio](https://en.wikipedia.org/wiki/Signal-to-interference_ratio)** · **[Link budget](https://en.wikipedia.org/wiki/Link_budget)**  
    - 相对值与干扰比直觉；教学用相对值。  
20. **[Wikipedia · Repeater](https://en.wikipedia.org/wiki/Repeater)** · **[Leaky feeder](https://en.wikipedia.org/wiki/Leaky_feeder)**  
    - 直放/泄漏电缆；隧道口场景指针。  
21. **[DMR Association · Key Benefits](https://dmrassociation.org/dmr-key-benefits.html)** · **[Scanner School · Intro to DMR](https://www.scannerschool.com/introduction-to-dmr/)**  
    - 官方/白话入门；提醒切换不改变 12.5 kHz/两槽。  
22. **[Motorola Solutions · MOTOTRBO 入口](https://www.motorolasolutions.com/en_us/products/two-way-radios/mototrbo.html)**  
    - 查本网机型文档时用；本篇不绑定菜单课。  
23. **[Wikipedia · Soft handover](https://en.wikipedia.org/wiki/Soft_handover)** · **[Roaming](https://en.wikipedia.org/wiki/Roaming)** · **[Cellular network](https://en.wikipedia.org/wiki/Cellular_network)**  
    - 软切换/漫游/蜂窝网名词；提醒本篇讲制度气质，不 dump DMR 空口字段。  
24. **[ETSI ETS 300 578 · Radio subsystem link control（PDF）](https://www.etsi.org/deliver/etsi_i_ets/300500_300599/300578/13_60/ets_300578e13p.pdf)** · **[NAPCO · RF Distribution Primer（PDF）](https://www.napco.org/Resources/M108-Daniel.pdf)**  
    - 链路控制与切换测量气质入口 + 室内分布公开讲义；**只借精神，不背条款号当 DMR ETSI。**

**视频：**

25. **[Hysteresis Explained in 1 Min（YouTube）](https://www.youtube.com/watch?v=wps3i4LVNHo)**  
    - 迟滞避免乒乓的直观动画；对照 P-切「不要刚越线就跳」。  
26. **[Wireless Technology · Handoff Strategies（YouTube）](https://www.youtube.com/watch?v=cjP4j31468Q)**  
    - 切换阈值与门限直觉扫盲；非 DMR 专网课。  
27. **[Scanner School · What is DMR?（YouTube）](https://www.youtube.com/watch?v=aQX_JbTbXuY)**  
    - 双时隙入门弱项补；提醒口部切换不改变 12.5 kHz/两槽。  
28. **[Scanner School · Why Digital Radio Sounds Like Robots（YouTube）](https://www.youtube.com/watch?v=-hLiTz7oSKE)**  
    - 数字悬崖/BER 直觉；门口「突然差」别先骂同频。  
29. **[P25 vs DMR（YouTube）](https://www.youtube.com/watch?v=tsVFV_XTQw8)**  
    - 数字制式对比扫盲；避免把口部抢客说成「数字电台玄学」。

> **诚实说明**：没有找到「DMR 专网口部切换与邻站泄漏治理（含切换窗定义拒签 + 泄漏内外对照 + 金机口部走测 + 插页 P）」专项中文/公开制度视频教程；上面的视频与文档分别讲蜂窝/DAS 出入口切换与控泄、站点工程邻站兼容、迟滞与乒乓常识、专网室内增强干扰气质与 DMR 基础，需要你自己按本篇贴纸 P 与插页 R1–R8 把它们拼进口部交维包。`video_found=true`（通用切换/迟滞/DMR 入门视频 + 文档侧 DAS 口部切换与泄漏），**非**专项「DMR 口部切换制度」教程。

**库内必回：** `学习推送/手册13_电梯井地下车库专项.md`（L-切 与井库口）、`手册10_室分隧道覆盖交维清单.md`（I 交维母册）、`手册07_覆盖与同频干扰分诊.md`（假 F / 禁加功率）、`手册16_室分有源隔离与减敏台架.md`（口部有源叠挂 O）、`手册09_话务与容量分诊.md`、`手册06_日志三联单深化.md`、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子

- 贴纸 **P** 五子类：口 / 切 / 泄 / 邻 / 治。  
- 故事：两家喇叭门口抢客 / 换乘口两列车同时喊话。  
- 八条硬规则；**口部金机强制**；**窗未定义禁签**；**泄漏未测禁签**；**禁加功率/加站掩盖**。  
- 主贴 P，可挂 L/I/F/O；假干扰先问泄漏与乒乓。  
- 公开包脱敏 L3。

### 11.2 回库路径

```text
  现场口部异常 / 交维
       │
       ├─ 手册13（L 井库 / L-切）
       ├─ 手册10（I 交维母册）
       ├─ 手册07/16（F / O）
       └─ 本篇手册17（贴纸P + 插页P + 口部泄漏治理卡）
```

### 11.3 下一篇手册候选（本篇不写正文）

- **金机基线漂移巡检**（大批量写频后）  
- **网管采集高可用与假绿演练剧本**  
- **（可选）邻频协调与边界联测制度**  

### 11.4 给带新人的三句话

1. 门口两家喇叭要先划界——切换窗图上可指认。  
2. 没做口部金机双向，单子不签。  
3. 泄漏没测、就加功率抢客——禁止。

### 11.5 运维一周里怎么用这篇（复印到周历）

| 日 | 动作 |
|----|------|
| 一 | 扫口部开口项 R3/R5/R7 |
| 三 | 邻站功率变更有无书面外溢边界 |
| 五 | 一例脱敏复盘进对齐会 |
| 夜班 | 用 7.5 五行；禁夜班私加邻站功率 |

### 11.6 和弱项加餐的衔接

口部切换不改 12.5 kHz / 4FSK / 30 ms；它改的是「谁在门口主导、邻站有没有灌进来」。加功率叙事出现时，回加餐 + 本篇规则2。

### 11.7 一张图记住本篇（收工贴纸）

```text
  ┌────────── 贴纸 P ──────────┐
  │ 口 = 门口画在图上          │
  │ 切 = 窗可指认·防乒乓       │
  │ 泄 = 内外对照·防灌入       │
  │ 邻 = 外溢边界·禁抢客加功率 │
  │ 治 = 拒签 + 金机口部 + L3  │
  └────────────────────────────┘
```

### 11.8 十分钟给领导的电梯演讲

> 「口部最怕两家喇叭抢客。我们要求：切换区图上可指认、邻站泄漏测过、金机口部双向走过，才允许谈加站；不签字给只测洞内的包；不加功率掩盖乒乓和串音。这是交维制度，不是厂商邻区菜单。」

### 11.9 和手册13 / 16 同时爆发时怎么分工

- 坡道猎站 + 门口乒乓 → **L 管路径与门**，**P 管窗与泄漏**。  
- 口部有源啸叫 + 泄漏观感 → **O 管隔离与噪底**，**P 管是否真是邻站灌入**。  
- 不要用「先加功率」换「先画窗」——两个禁令叠加时，**两个都要守**。

## 12. 本篇检查清单（自学打勾）

- [ ] 能讲两家喇叭门口抢客 / 换乘口喊话故事  
- [ ] 能背贴纸 P 五子类  
- [ ] 能背八条硬规则  
- [ ] 会填插页 P 的 R1–R8  
- [ ] 会用拒签卡挡住「只测洞内」  
- [ ] 能区分 P 与 L/I/F/O 主次挂  
- [ ] 会做口部金机双向 + 滞留口述  
- [ ] 会做泄漏内外对照口述  
- [ ] 自测 10 题过关  
- [ ] 知道下一篇候选不在本篇展开  
- [ ] 公开举例已脱敏 L3  
- [ ] 弱项 12.5 kHz/4FSK/30 ms 已口头复习  
- [ ] 能做「假同频排除三问」  
- [ ] 知道 L/I 插页与 P 插页可叠挂、口部切换泄漏主贴 P  
- [ ] 看过至少 2 篇 §10 口部切换/控泄文档链接  
- [ ] 明白不 dump 空口切换字段、不抄蜂窝门限当本网法规  

---

*手册17 · 口部切换与邻站泄漏治理专项 · 学习推送 · 2026-10-17 09:52 +08:00*
