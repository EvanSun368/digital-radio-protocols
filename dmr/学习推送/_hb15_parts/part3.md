
## 7. 《本网电源监控对时与告警风暴治理卡》模板

### 7.1 封面 · 拒签 / 拒静音门槛（贴网管）

```text
本网电源监控对时与告警风暴治理卡（脱敏 L3）
站类/作业代号：__________  日期：__________  填写人：__________

拒签：□ 假绿未排除  □ 最小对象清单缺失
拒秒级结论：□ 三钟差未写清
拒静音：□ 拟全静音交班  □ 抑制窗无审批/无到期
禁令勾选：□ 不加功率  □ 不加信道掩盖  □ 不逐条拆射频病
```

### 7.2 主表（与插页 N 对齐）

| 行 | 项 | 结果 | 备注（脱敏） |
|----|----|------|--------------|
| R1 | 最小对象清单 | 过/否 |  |
| R2 | 非假绿抽查 | 过/否 |  |
| R3 | 三钟差 | __分__秒 | 时区： |
| R4 | 对时状态 | 同步/否 |  |
| R5 | 顶级铃语义 | 过/否 |  |
| R6 | 根因事件 | 有/无 | 一句话： |
| R7 | 抑制窗 | 无/有（起止） | 审批人： |
| R8 | 结案与脱敏 | 过/否 | 主贴 N-__ |

### 7.3 根因事件页（N-风）

```text
根因候选：□市电闪断 □整流模块 □电池低 □油机未起/演练
         □链路抖 □NTP跳变 □环境高温 □其它：______
时间窗（以网管钟）：______ → ______
关联铃族数量（约）：______
是否误拆 F/H 单：□是 □否  → 已撤回/合并：______
```

### 7.4 抑制窗与升级页（N-治）

```text
抑制范围（非全墙）：________________
起止：______ → ______  到期恢复提醒：□已设
升级路径：L1 夜班 → L2 电源值班 → L3 ______
结案号：______  公开包：□已脱敏 L3
```

### 7.5 夜班速填（5 行）

```text
1. 假绿抽查：过/否
2. 三钟差：
3. 风暴？根因一句：
4. 抑制窗：无/有（起止）
5. 主贴 N-__；次挂：
```

---

## 8. 术语表（本篇约 30 词）+ 易错观念

| 术语 | 白话 |
|------|------|
| 监控对象 | 被采集的电源/环境/链路点 |
| 采集链 | 传感器→代理/RTU→网管的路径 |
| 假绿 | 断采仍显示正常 |
| NTP | 网络时间协议（常用对时） |
| PTP | 精密时间协议（更高精度场景） |
| 偏移/抖动 | 相对参考钟的偏差与波动 |
| 三钟 | 网管钟、分析仪钟、终端/基站日志钟 |
| 时区/夏令 | 显示层陷阱；要写明 |
| 告警语义 | 这条铃到底说什么 |
| 级别 | 紧急/重要/次要等本网分级 |
| 可行动告警 | 有人该在时限内做什么 |
| 告警风暴 | 短时海量铃超出有效处置 |
| 抖动/闪断风暴 | 同一条件反复跳变刷屏 |
| 关联 | 多铃归到同一根因事件 |
| 抑制窗 | 声明期内降噪；非永久静音 |
| 静音过度 | 把真火一起关掉 |
| 合理化 | 按哲学删改无动作/重复铃（借精神） |
| 根因事件 | 风暴背后的那一个触发 |
| 升级路径 | 谁在何时接手 |
| 结案 | 关闭或书面挂起并留证 |
| 脱敏 L3 | 去站名/频点/个号/密钥 |
| 整流 | AC→DC 模块（指针 K） |
| 电池组 | 后备储能（指针 K） |
| 油机/ATS | 发电与切换（指针 K） |
| SNMP trap | 设备主动上送的告警消息（概念） |
| NOC/网管墙 | 中控室告警呈现面 |
| 倒换窗 | 市电↔后备切换时段（指针 K） |
| 加功率禁令 | 不得用抬功率治假干扰（指针 F） |
| 加信道禁令 | 不得用加信道治假忙（指针 H） |
| 12.5 kHz / 4FSK / 30 ms | 弱项物理台阶提醒 |

**易错观念**

1. 「全绿=健康」→ 可能假绿。  
2. 「铃多=灵敏=好事」→ 无关联的风暴掩盖真火。  
3. 「静音=消缺」→ 只是把火警灯拧掉。  
4. 「有手册12 就不用监控治理」→ K 管物理，N 管监控与钟。  
5. 「时间差不多就行」→ 秒级结论必须暴露钟差。  
6. 「风暴就派射频单」→ 先根因事件。  
7. 「加功率让用户舒服点」→ 禁。  
8. 「公开分享可以带站名方便」→ L3 禁。

---

## 9. 自测（10 题）+ 参考答案

1. 贴纸 N 五个子类叫什么？各举一个拒签/拒静音触发。  
2. 为什么假绿比铃响更危险？  
3. 三钟差未写清时，能否写「干扰先于登记失败」？  
4. 市电闪断引发上百条铃，应主贴什么？能否拆成二十个同频单？  
5. 交班一键静音全部是否允许？例外要写什么？  
6. 倒换演练铃爆，K 与 N 怎么分工？  
7. 多站间歇掉电像话务忙，能否加信道？  
8. 插页 R1–R8 里哪两行不过必须拒签？哪两行不过禁秒级结论？  
9. 本篇与手册12/06/07/09 的指针关系各一句。  
10. 公开包脱敏 L3 要去掉哪些？

### 参考答案

1. 监/时/告/风/治；例：假绿拒签、漂移禁秒级、无语义坏铃、风暴禁拆单、禁全静音交班。  
2. 断采仍显示正常会让人签字放行，真故障零可见。  
3. 不能；规则2 / 手册06。  
4. 主贴 N-风（可挂 K）；禁止逐条拆 F。  
5. 不允许当常态；例外要起止、原因、审批、到期恢复。  
6. 物理倒换挂 K；监控风暴与对时主贴 N；可声明抑制窗。  
7. 不能；先 N/K，禁加信道（规则4 / 手册09）。  
8. R1–R2 拒签；R3–R4 禁秒级结论。  
9. 12=物理母册；06=对时证据；07=假 F/禁加功率；09=假 H/禁加信道。  
10. 真实站名、频点、个号、密钥、可识别单位名等。

---

## 10. 加深阅读与视频（均已用 curl 核对 HTTP 200；视频用 YouTube oEmbed 核对存在）

1. **[RFC 8633 · Network Time Protocol Best Current Practices](https://datatracker.ietf.org/doc/html/rfc8633)**  
   - NTP 运维 BCP：多源、监控、安全意识；对照 N-时。**只借精神，不背成 ETSI。**  
2. **[RFC Editor · RFC 8633 信息页](https://www.rfc-editor.org/info/rfc8633/)** · **[HTML 全文](https://www.rfc-editor.org/rfc/rfc8633.html)**  
   - 备份入口。  
3. **[Cisco · Use Best Practices for NTP](https://www.cisco.com/c/en/us/support/docs/availability/high-availability/19643-ntpm.html)**  
   - 经典 NTP 实践文；对照「时间是分析前提」。  
4. **[Cisco · IOS XR NTP 配置与监控要点](https://www.cisco.com/c/en/us/td/docs/iosxr/cisco8000/timing/b-timing-sync-config-guide-cisco8000/m-network-time-protocol.html)**  
   - 多源、认证、状态监控气质。  
5. **[CISA · Time Guidance for Network Operators / CIOs / CISOs（PDF）](https://www.cisa.gov/sites/default/files/publications/time_guidance_network_operators_cios_cisos_508.pdf)**  
   - 对时治理检查问句；对齐「要有对时策略与异常处置」。  
6. **[CAST / ORNL · Technical Bulletin 004（PDF）](https://cast.ornl.gov/downloads/CAST-Technical-Bulletin-004.pdf)**  
   - 对时监测与运维讨论；借监控偏移的重要性。  
7. **[Netverge · NTP Monitoring](https://netverge.com/blog/ntp-monitoring)**  
   - 偏移/抖动/reach 等一并看的白话。  
8. **[NTP FAQ · Troubleshooting](https://ntp.org/ntpfaq/NTP-s-trouble/)** · **[NTP 项目首页](https://www.ntp.org/)**  
   - 排障入口与项目门户。  
9. **[RFC 5905 · NTPv4](https://datatracker.ietf.org/doc/html/rfc5905)**  
   - 协议基础（选读）；不要求背字段。  
10. **[NIST · Using NTP: Introduction and Recommended Practices](https://www.nist.gov/publications/using-ntp-introduction-and-recommended-practices)**  
    - NIST 对时实践入口页。  
11. **[NIST Internet Time Service 服务器页](https://tf.nist.gov/tf-cgi/servers.cgi)**  
    - 公开时间源列表气质（本网是否外采另议）。  
12. **[ISA · Alarm management questions everyone asks](https://www.isa.org/intech-home/2020/march-april/features/alarm-management-questions-that-everyone-asks)**  
    - 告警管理生命周期白话；对照 N-告/N-治。**借精神，不背条款号。**  
13. **[ISA-18 委员会页](https://www.isa.org/standards-and-publications/isa-standards/isa-standards-committees/isa18)**  
    - 标准家族入口（了解用）。  
14. **[Emerson · Alarm Management By the Numbers（PDF）](https://www.emerson.com/is/content/emerson/en/corporate/news-and-events/articles/documents/alarm-management-by-the-numbers.pdf)**  
    - 风暴/速率类 KPI 直觉（过程工业语境，借「风暴要度量」）。  
15. **[IChemE · Alarm rationalisation metrics guidance（PDF）](https://www.icheme.org/media/17392/lc-0151_21-lead-process-safety-metrics-alarm-rationalisation-final.pdf)**  
    - 合理化与洪水定义气质；对照 N-风。  
16. **[Wikipedia · Alarm management](https://en.wikipedia.org/wiki/Alarm_management)** · **[IEC 62682](https://en.wikipedia.org/wiki/IEC_62682)**  
    - 名词地图；**不把百科当本网制度。**  
17. **[ETSI ES 202 336-2 · DC power monitoring information model（PDF）](https://www.etsi.org/deliver/etsi_ES/202300_202399/20233602/01.01.01_60/es_20233602v010101p.pdf)**  
    - 电信直流电源监控信息集气质（市电/整流/电池等）；**只借对象清单直觉，不背条款当 DMR ETSI。**  
18. **[DPS · Rectifier Monitoring via SNMP](https://www.dpstele.com/blog/rectifier-monitoring-snmp-alarms-dialer.php)** · **[Rectifier Monitoring](https://www.dpstele.com/rectifier-monitoring.php)** · **[Remote Battery Monitoring](https://www.dpstele.com/network-monitoring/remote-battery-monitoring-telecom-utility-sites.php)**  
    - 电信场景整流/电池远程监控白话（厂商博客；借对象与链路直觉）。  
19. **[Pandora FMS · SNMP traps 与 storm protection](https://pandorafms.com/manual/!current/en/documentation/pandorafms/monitoring/08_snmp_traps_monitoring)**  
    - trap 风暴保护参数气质；对照 N-风/N-治（制度抑制，非攻击）。  
20. **[Netdata · SNMP traps sizing](https://learn.netdata.cloud/docs/network-performance-monitoring/snmp-traps/sizing-and-capacity-planning)** · **[Alerts](https://learn.netdata.cloud/docs/network-performance-monitoring/snmp-traps/alerts)**  
    - 容量与告警侧补充。  
21. **[NetXMS · SNMP Traps 文档](https://docs.netxms.org/admin/dev/snmp/traps/)**  
    - 开源网管 trap 处理入口。  
22. **[Network Management Experts · SNMP Trap Design That Doesn't Flood Your NOC](https://networkmanagementexperts.com/knowledge/snmp-trap-design-noc/)**  
    - 「别把 NOC 灌爆」设计文；对照关联与限速精神。  
23. **[Wikipedia · Network Time Protocol](https://en.wikipedia.org/wiki/Network_Time_Protocol)** · **[Precision Time Protocol](https://en.wikipedia.org/wiki/Precision_Time_Protocol)** · **[UTC](https://en.wikipedia.org/wiki/Coordinated_Universal_Time)**  
    - 对时名词垫脚石。  
24. **[Wikipedia · SNMP](https://en.wikipedia.org/wiki/Simple_Network_Management_Protocol)** · **[SCADA](https://en.wikipedia.org/wiki/Supervisory_control_and_data_acquisition)** · **[RTU](https://en.wikipedia.org/wiki/Remote_terminal_unit)** · **[NOC](https://en.wikipedia.org/wiki/Network_operations_center)** · **[Telemetry](https://en.wikipedia.org/wiki/Telemetry)**  
    - 监控链路名词包。  
25. **[Wikipedia · UPS](https://en.wikipedia.org/wiki/Uninterruptible_power_supply)** · **[Rectifier](https://en.wikipedia.org/wiki/Rectifier)** · **[Battery](https://en.wikipedia.org/wiki/Battery_(electricity))** · **[Diesel generator](https://en.wikipedia.org/wiki/Diesel_generator)** · **[ATS](https://en.wikipedia.org/wiki/Automatic_transfer_switch)**  
    - 电源对象百科（指针回手册12）。  
26. **[Wikipedia · Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio)** · **[LMR](https://en.wikipedia.org/wiki/Land_mobile_radio_system)** · **[Two-way radio](https://en.wikipedia.org/wiki/Two-way_radio)**  
    - DMR/专网弱项补。  
27. **[DMR Association · Key Benefits](https://dmrassociation.org/dmr-key-benefits.html)** · **[Scanner School · Intro to DMR](https://www.scannerschool.com/introduction-to-dmr/)**  
    - 官方/白话入门。  
28. **[NIST SP 800-128（PDF）](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-128.pdf)** · **[NIST CSF](https://www.nist.gov/cyberframework)** · **[CISA Secure by Design](https://www.cisa.gov/resources-tools/resources/secure-by-design)** · **[CISA Best Practices](https://www.cisa.gov/topics/cybersecurity-best-practices)**  
    - 配置/检测/响应气质；监控异常要进响应，不是静音了事。  
29. **[Motorola Solutions · MOTOTRBO 入口](https://www.motorolasolutions.com/en_us/products/two-way-radios/mototrbo.html)** · **[Support](https://support.motorolasolutions.com/)**  
    - 查本网机型网管文档时用；本篇不绑定菜单课。  
30. **[Wikipedia · Configuration management](https://en.wikipedia.org/wiki/Configuration_management)** · **[Change management (ITSM)](https://en.wikipedia.org/wiki/Change_management_(ITSM))**  
    - 变更与配置名词；抑制规则变更也要可控。

**视频：**

31. **[Scanner School · What is DMR?（YouTube）](https://www.youtube.com/watch?v=aQX_JbTbXuY)**  
    - 双时隙入门弱项补；提醒监控/对时不改变 12.5 kHz/两槽物理。  
32. **[Scanner School · Why Digital Radio Sounds Like Robots（YouTube）](https://www.youtube.com/watch?v=-hLiTz7oSKE)**  
    - 数字悬崖/BER 直觉；倒换窗「突然差」别先骂同频。  
33. **[P25 vs DMR（YouTube）](https://www.youtube.com/watch?v=tsVFV_XTQw8)**  
    - 数字制式对比扫盲；避免把监控风暴说成「数字电台玄学」。

> **诚实说明**：没有找到「DMR 专网电源监控对时与告警风暴治理（含假绿拒签 + 三钟差禁秒级因果 + 根因关联 + 禁全静音交班制度 + 插页 N）」专项中文/公开视频教程；上面的视频与文档分别讲 NTP 实践、告警管理/合理化精神、电信直流监控对象、SNMP trap 风暴防护与 DMR 基础，需要你自己按本篇贴纸 N 与插页 R1–R8 把它们拼进网管交班包。`video_found=true`（通用 DMR 入门视频 + 文档侧 NTP/告警管理/直流监控），**非**专项「DMR NMS 告警风暴制度」教程。

**库内必回：** `学习推送/手册12_基站电源与后备切换交维.md`（本篇的物理母册 K）、`手册06_日志三联单深化.md`（对时/脱敏）、`手册07_覆盖与同频干扰分诊.md`（假 F / 禁加功率）、`手册09_话务与容量分诊.md`（假 H / 禁加信道）、`手册08_测试实验室最小闭环.md`（台架气质）、`手册10`/`手册13`（远端有源/井库）、`手册11`/`手册14`（写频账时钟）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子

- 贴纸 **N** 五子类：监 / 时 / 告 / 风 / 治。  
- 故事：消防中控室火警面板 + 各楼层钟没对时；先探头、再对钟、后认铃、末治风暴。  
- 八条硬规则；**假绿拒签**；**漂移禁秒级因果**；**禁全静音交班**。  
- 风暴先根因事件；倒换窗可挂 K，监控主贴 N。  
- 禁加功率/加信道掩盖；公开包脱敏 L3。

### 11.2 回库路径

```text
总索引.md
  └─ 集群 / Tier III → 运维手册
       ├─ 手册01–05（A–E）06（总单）07（F）08（G）09（H）10（I）11（J）12（K）13（L）14（M）
       └─ 本篇手册15（贴纸N + 插页N + 电源监控对时与告警风暴治理卡）
            └─ 回：手册12（母册）、06–09、10/13、11/14、加餐弱项
```

### 11.3 下一篇手册候选（本篇不写正文）

- **室分有源隔离与减敏台架专项**（手册08 G + 手册10 I 的加深）。  
- **口部切换与邻站泄漏治理**（覆盖边界 / 邻站）。  
- **大批量写频后金机基线漂移巡检**（手册11/14 的巡检册）。  
- **（可选）网管采集高可用与假绿演练剧本**（本篇 N-监 的演习加深）。

### 11.4 给带新人的三句话

> 假绿拒签；没有写清钟差，就没有秒级因果。  
> 风暴先找根因事件，禁止拆成二十个同频故事。  
> 全静音不是交班技能，加功率也不是灭火器。

### 11.5 运维一周里怎么用这篇（复印到周历）

```text
周一  默写 N 五子类 + 假绿拒签卡
周二  抽查 1 站采集非假绿 + 记三钟差
周三  演练脚本 C（全静音）与脚本 D（风暴拆单）
周四  对一份旧风暴单：有无 R6 根因
周五  对齐会：抑制窗例外是否合规；与 K 演练窗对齐
```

### 11.6 和弱项加餐的衔接

把 12.5 kHz / 4FSK / 30 ms 两槽背熟，你才说得清「监控与对时管心跳与证据钟，不改调制台阶」。有人要用加功率/加信道治铃或掉话时，回加餐 + 手册07/09/12。

### 11.7 一张图记住本篇（收工贴纸）

```text
        铃墙亮了 / 要下秒级结论 / 要交班
                      │
          ┌───────────┴───────────┐
          │ 采集非假绿？            │否 → 拒签（N-监）
          ▼
        三钟差写清？──否──▶ 禁秒级因果（N-时）
          │是
          ▼
        单铃语义/级别/动作清楚？──否──▶ 先 N-告 合理化
          │是
          ▼
        风暴？──是──▶ 标根因事件 → 关联抑制（N-风/N-治）
          │否
          ▼
        物理倒换相关？──可挂 K；监控主贴 N
          │
          ▼
        结案 + 脱敏 L3
        禁令：全静音交班；加功率/加信道；逐条拆射频病；假绿放行
```

---

## 12. 本篇检查清单（自学打勾）

- [ ] 能背 N 五子类并各举一个拒签/拒静音例子  
- [ ] 能画「消防中控室 + 楼层钟」链并指出五段  
- [ ] 能背八条硬规则  
- [ ] 能说明假绿、三钟差、根因事件三问  
- [ ] 能拒绝「全静音交班 / 假绿放行 / 漂移下秒级结论 / 风暴拆射频单 / 加功率压铃」  
- [ ] 会填插页 N 的 R1–R8  
- [ ] 会填《本网电源监控对时与告警风暴治理卡》封面与夜班五行  
- [ ] 能说明与手册12/06/07/09 的指针关系（不重写）  
- [ ] 自测 10 题过关  
- [ ] 知道 §10 诚实说明：无专项 DMR NMS 风暴制度视频，仅通用视频+文档  
- [ ] 弱项：12.5 kHz / 4FSK / 30 ms·60 ms 仍能口述  
- [ ] 公开分享前完成脱敏 L3 自检  

---

*手册15 · 电源监控对时与告警风暴治理 · 贴纸 N · 教学虚构 · 脱敏 L3 · 2026-10-16*
