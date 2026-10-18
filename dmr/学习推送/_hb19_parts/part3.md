## 8. 术语表（本篇约 28 词）+ 易错观念

| 术语 | 一句话 |
|------|--------|
| **采集链** | 从探头/轮询到入库再到值班屏的整条「眼睛」路径 |
| **采集角色标签** | 主/备采集的可审计身份名（脱敏，非真实主机名强制公开） |
| **对象清单** | 本网规定「采什么」的版本化列表 |
| **心跳** | 采集仍活着的周期信号 |
| **超时** | 超过多久无成功拍视为僵死候选 |
| **最近成功拍** | 最后一次有效采集时间戳气质 |
| **主备 / 双路** | 两路采集冗余；要可切换 |
| **切换窗** | 书面批准的主↔备切换验证时段 |
| **脑裂** | 双主同时写/互刷，视图分裂 |
| **假绿** | 采集已死或静默缺口，屏仍正常/全绿 |
| **静默缺口** | 中间缺拍无人告警 |
| **死人手柄** | 正常时应持续「报到」的告警；停报到反而要响（精神借用） |
| **合成探测** | 主动探针证明链路/采集未静默（精神借用） |
| **假绿演练** | 故意断一路证铃会响、屏会变 |
| **演练窗** | 演练的书面起止、范围、中止 |
| **会响证据** | 演练中铃响或变色的可审计记录（L3） |
| **监控已就绪** | 交维用语；本篇规定须过 R 门槛 |
| **HA 完成** | 高可用完成；无切换验证不得宣称 |
| **值班屏** | 网管大屏；绿≠可靠 |
| **贴纸 R** | 本篇主贴纸：采/备/绿/演/治 |
| **插页 R** | R1–R8 填写页 |
| **三联单** | 手册06 证据单；本篇主贴 R |
| **脱敏 L3** | 教学/公开最高脱敏；禁真实站名频点个号密钥网管地址 |
| **叠挂 N** | 对时/风暴气质次挂 |
| **叠挂 K** | 电源倒换窗次挂 |
| **叠挂 Q** | 配置漂移；与假绿分清 |
| **叠挂 G** | 台架验证气质 |
| **加功率叙事** | 用抬功率假装治好监控盲；本篇禁止 |

**易错观念**

| 错 | 对 |
|----|----|
| 大屏绿 = 监控可靠 | 先证心跳、主备、演练 |
| 有两台采集机 = HA | 要切换验证与脑裂治理 |
| 假绿演练 = 故意搞破坏不专业 | 专业的是书面窗 + 会响证据 |
| 监控看不见 = 干扰 | 先 R，再 F |
| 配置漂移 = 采集假绿 | Q ≠ R |
| 倒换演练 = 假绿演练 | K 不顶替 R-演 |
| 静音交班 = 消假绿 | 更危险；指针 N |
| 采集 HA 改变 12.5 kHz/两槽 | 不改变 RF 物理 |

---

## 9. 自测（10 题）+ 参考答案

1. 贴纸 R 五个子类各是什么？各用一句话。  
2. 为什么「值班屏全绿」不能直接签「监控已就绪」？  
3. 八条硬规则里，哪一条禁止用加功率掩盖「监控看不见」？  
4. 有双采集但从没做过切换窗验证，能否签 HA 完成？依据哪条规则？  
5. 假绿的定义是什么？发现后动作是什么？  
6. 假绿演练最小包至少含哪几项？  
7. 演练窗如何与 N、K 叠挂？主贴是谁？  
8. 插页 R1–R8 里，哪几行不过必须拒签「监控就绪」？哪几行不过禁签交维（演练）？  
9. 配置漂移（Q）与采集假绿（R）如何一句话分清？  
10. 公开材料能否写真实网管地址？本篇脱敏要求是什么？

### 参考答案

1. **R-采** 身份与心跳；**R-备** 主备切换与脑裂禁令；**R-绿** 假绿定义与探测；**R-演** 演练剧本与会响；**R-治** 拒签与 L3。  
2. 全绿可能是假绿；须过采集身份、主备（若宣称 HA）、假绿探测与演练账。  
3. **规则2**。  
4. **不能**；**规则3**（及脑裂时 **规则7**）。  
5. 采集僵死/断链/静默缺口而屏仍绿；**拒签/拒放行（规则4）**，先修探测。  
6. 书面窗、范围、注入动作、期望（会响/变色）、中止、证据、结果与恢复。  
7. 可挂 N（风暴/对时）、K（电源倒换）；**采集 HA 与假绿剧本主贴 R（规则6）**。  
8. **R2/R4** 不过禁「监控就绪」；宣称 HA 时 **R3** 空也禁；交维要可靠时 **R6/R7** 空禁签（规则5）。  
9. Q=柜台货相对金机漂；R=探头/采集僵死屏却绿。  
10. **不能**；公开/教学 **L3**，禁真实站名/频点/个号/密钥/网管地址（规则8）。

---

## 10. 加深阅读与视频（均已用 curl 核对 HTTP 200；视频用 YouTube oEmbed 核对存在）

1. **[Zabbix · Proxy concept](https://www.zabbix.com/documentation/current/en/manual/concepts/proxy)**  
   - 代理采集/分布式气质；对照 R-采/R-备「谁采、备路」。**只借精神，不绑定厂商。**  
2. **[Zabbix · Distributed monitoring](https://www.zabbix.com/documentation/current/en/manual/distributed_monitoring)**  
   - 分布式监控与多节点气质；对照「备机要够得着对象、切换可测」。  
3. **[LibreNMS · High Availability](https://docs.librenms.org/Support/High-Availability/)**  
   - 开源网管 HA 组件直觉（库/缓存/轮询）；借「采集要冗余」。  
4. **[LibreNMS · Distributed Poller](https://docs.librenms.org/Extensions/Distributed-Poller/)**  
   - 分布式轮询扩展；对照多路采集气质，不抄架构当本网法规。  
5. **[VictoriaMetrics · vmagent High-Availability Examples](https://victoriametrics.com/blog/vmagent-high-availability-examples/)**  
   - 双采集刮取 + 去重精神；对照脑裂/双写要治理（规则7）。  
6. **[VictoriaMetrics · K8s HA monitoring guide](https://docs.victoriametrics.com/guides/k8s-ha-monitoring-via-vm-cluster/)**  
   - 复制与去重开关气质；只借「双写要去重」。  
7. **[Thanos · Querier / HA deduplication](https://thanos.io/tip/components/query.md/)**  
   - HA 副本去重填坑精神；对照双采集视图一致。  
8. **[Prometheus · Overview](https://prometheus.io/docs/introduction/overview/)**  
   - 拉取式监控地图；借「有目标、有刮取、有告警」链条。  
9. **[Prometheus · Alerting rules](https://prometheus.io/docs/prometheus/latest/configuration/alerting_rules/)**  
   - 告警规则基础；对照假绿要有规则可响。  
10. **[ilert · Prometheus heartbeat example](https://docs.ilert.com/alerting/heartbeat-monitoring/prometheus-heartbeat-example)**  
    - 心跳/死人手柄接法气质；对照 R-绿「停报到要响」。  
11. **[PromLabs · End-to-end watchdog alerts](https://training.promlabs.com/training/monitoring-and-debugging-prometheus/metrics-based-meta-monitoring/end-to-end-watchdog-alerts/)**  
    - Watchdog 端到端精神；对照假绿探测。  
12. **[Principles of Chaos Engineering](https://principlesofchaos.org/)**  
    - 混沌工程原则：稳态、假设、注入、验证；对照 R-演书面窗。  
13. **[Microsoft Learn · Chaos engineering overview](https://learn.microsoft.com/en-us/azure/chaos-studio/chaos-studio-chaos-engineering-overview)**  
    - 混沌演练与假设验证气质；借「先稳态、再注入、要观察」（不绑定云厂商菜单）。  
14. **[Gremlin · How to run a GameDay](https://www.gremlin.com/community/tutorials/how-to-run-a-gameday)**  
    - GameDay 角色与观察；对照演练分工，不绑定工具。  
15. **[FDAI · Chaos Game Day Runbook](https://dotnetpower.github.io/fdai/runbooks/chaos-game-day/)**  
    - 书面窗、中止、缺样本=失败精神；对照 R-演最小包。  
16. **[NIST SP 800-137 · ISCM（PDF）](https://nvlpubs.nist.gov/nistpubs/legacy/sp/nistspecialpublication800-137.pdf)**  
    - 持续监控策略与采集—分析—响应循环；**只借精神，不背当 ETSI。**  
17. **[NIST CSRC · SP 800-137 条目](https://csrc.nist.gov/pubs/sp/800/137/final)**  
    - 官方入口。  
18. **[NIST RMF · Monitor Step](https://csrc.nist.gov/Projects/risk-management/about-rmf/monitor-step)**  
    - 监控步骤结果清单；对照「监控要持续有策略」。  
19. **[CISA · Guidance for SIEM and SOAR Implementation](https://www.cisa.gov/resources-tools/resources/guidance-siem-and-soar-implementation)**  
    - 采集/检测/响应平台选型气质；借「要有可见性」，不抄清单当 DMR 法规。  
20. **[Grafana · Synthetic monitoring](https://grafana.com/docs/grafana-cloud/testing/synthetic-monitoring/)**  
    - 合成监测气质；对照 R-绿「主动证明链路未静默」（不绑定云账号）。  
21. **[CISA · Cybersecurity Best Practices](https://www.cisa.gov/topics/cybersecurity-best-practices)**  
    - 检测与响应入口集。  
22. **[CISA · Secure by Design](https://www.cisa.gov/resources-tools/resources/secure-by-design)**  
    - 设计期就考虑可观测/失败可见气质。  
23. **[Wikipedia · FCAPS](https://en.wikipedia.org/wiki/FCAPS)**  
    - 故障/配置/计费/性能/安全管理地图；对照「监控属 F/P 气质」。**不背百科当制度。**  
24. **[Wikipedia · Network monitoring](https://en.wikipedia.org/wiki/Network_monitoring)** · **[Network management](https://en.wikipedia.org/wiki/Network_management)** · **[NOC](https://en.wikipedia.org/wiki/Network_operations_center)**  
    - 名词垫脚石。  
25. **[Wikipedia · SNMP](https://en.wikipedia.org/wiki/Simple_Network_Management_Protocol)** · **[Telemetry](https://en.wikipedia.org/wiki/Telemetry)** · **[Heartbeat (computing)](https://en.wikipedia.org/wiki/Heartbeat_%28computing%29)**  
    - 采集与心跳名词。  
26. **[Wikipedia · High availability](https://en.wikipedia.org/wiki/High_availability)** · **[Failover](https://en.wikipedia.org/wiki/Failover)** · **[Split-brain (computing)](https://en.wikipedia.org/wiki/Split-brain_%28computing%29)**  
    - HA/切换/脑裂；对照 R-备 规则7。  
27. **[Wikipedia · Chaos engineering](https://en.wikipedia.org/wiki/Chaos_engineering)** · **[Fault injection](https://en.wikipedia.org/wiki/Fault_injection)** · **[Netflix Chaos Monkey（GitHub）](https://github.com/Netflix/chaosmonkey)**  
    - 演练精神名词包；Chaos Monkey 仅借「故意失败」史话，不照搬公有云工具。  
28. **[Wikipedia · Dead man's switch](https://en.wikipedia.org/wiki/Dead_man%27s_switch)** · **[Watchdog timer](https://en.wikipedia.org/wiki/Watchdog_timer)** · **[Synthetic monitoring](https://en.wikipedia.org/wiki/Synthetic_monitoring)**  
    - 死人手柄/看门狗/合成监测隐喻；对照 R-绿。  
29. **[ITU · M.3010 Principles for a TMN（条目）](https://www.itu.int/rec/T-REC-M.3010)**  
    - 电信管理网原则入口；**只借 TMN 精神，不发明 DMR ETSI 条款。**  
30. **[ITU · M.3400 TMN management functions（条目）](https://www.itu.int/rec/T-REC-M.3400)**  
    - TMN 管理功能集入口；借 FCAPS 气质。  
31. **[ITU · M.3000 Overview of TMN Recommendations](https://www.itu.int/rec/T-REC-M.3000)**  
    - TMN 建议综述入口。  
32. **[RFC 3411 · SNMP Architecture](https://datatracker.ietf.org/doc/html/rfc3411)** · **[RFC 3418 · MIB-II](https://datatracker.ietf.org/doc/html/rfc3418)**  
    - SNMP 架构与基础 MIB；选读，不要求背 OID。  
33. **[NIST CSF](https://www.nist.gov/cyberframework)** · **[NIST SP 800-53r5（PDF）](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf)**  
    - 检测/响应与监控控制气质；不背条款当 ETSI。  
34. **[DMR Association · Key Benefits](https://dmrassociation.org/dmr-key-benefits.html)** · **[Scanner School · Intro to DMR](https://www.scannerschool.com/introduction-to-dmr/)**  
    - 官方/白话入门；提醒采集 HA 不改变 12.5 kHz/两槽。  
35. **[Wikipedia · Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio)** · **[Land mobile radio system](https://en.wikipedia.org/wiki/Land_mobile_radio_system)** · **[Two-way radio](https://en.wikipedia.org/wiki/Two-way_radio)**  
    - DMR/专网弱项补。  
36. **[Motorola Solutions · MOTOTRBO 入口](https://www.motorolasolutions.com/en_us/products/two-way-radios/mototrbo.html)** · **[Support](https://support.motorolasolutions.com/)**  
    - 查本网机型网管文档入口；本篇不绑定菜单课。  
37. **[Pandora FMS · SNMP traps monitoring](https://pandorafms.com/manual/!current/en/documentation/pandorafms/monitoring/08_snmp_traps_monitoring)**  
    - trap 与风暴保护气质；指针回手册15 N-风。  
38. **[NetXMS · SNMP Traps](https://docs.netxms.org/admin/dev/snmp/traps/)**  
    - 开源网管 trap 处理入口。  
39. **[Wikipedia · Observability](https://en.wikipedia.org/wiki/Observability)** · **[Site reliability engineering](https://en.wikipedia.org/wiki/Site_reliability_engineering)**  
    - 可观测/SRE 地图；借「失败要可见」。  
40. **[Google SRE Book · Monitoring Distributed Systems（公开章）](https://sre.google/sre-book/monitoring-distributed-systems/)**  
    - 监控症状 vs 原因、告警要可行动精神；对照假绿与演练。  
40b. **[Icinga 2 · Distributed Monitoring](https://icinga.com/docs/icinga-2/latest/doc/06-distributed-monitoring/)**  
    - 开源分布式监控拓扑气质；对照多路采集。  
40c. **[Prometheus · Alerting best practices](https://prometheus.io/docs/practices/alerting/)**  
    - 告警要可行动、避免噪声；对照假绿要响、风暴要治（指针 N）。  
40d. **[Google SRE Workbook · Monitoring](https://sre.google/workbook/monitoring/)**  
    - 监控实践续篇；借「症状导向」精神。  
40e. **[Microsoft · Chaos engineering in Azure Well-Architected](https://learn.microsoft.com/en-us/azure/architecture/framework/resiliency/chaos-engineering)**  
    - 韧性框架中的混沌演练位置；对照书面窗与假设。

**视频：**

41. **[Scanner School · What is DMR?（YouTube）](https://www.youtube.com/watch?v=aQX_JbTbXuY)**  
    - 双时隙入门弱项补；提醒采集/假绿演练不改变物理台阶。  
42. **[Scanner School · Why Digital Radio Sounds Like Robots（YouTube）](https://www.youtube.com/watch?v=-hLiTz7oSKE)**  
    - 数字悬崖/BER；「突然差」别先骂同频，先问监控是否假绿。  
43. **[P25 vs DMR（YouTube）](https://www.youtube.com/watch?v=tsVFV_XTQw8)**  
    - 数字制式对比扫盲；避免把采集故障说成「数字电台玄学」。  
44. **[Prometheus Monitoring Tutorial for Beginners（YouTube）](https://www.youtube.com/watch?v=h4Sl21AKiDg)**  
    - 通用拉取监控入门气质；自己按贴纸 R 映射到本网采集链。  
45. **[What is Chaos Engineering? | Principles of Chaos（YouTube）](https://www.youtube.com/watch?v=3CNNhK9JTDk)**  
    - 混沌工程入门；对照假绿演练「故意断一路」精神，不照搬公有云工具。

> **诚实说明**：没有找到「DMR 专网网管采集高可用与假绿演练（含双采集切换验证 + 假绿拒签 + 书面演练窗证会响 + 脑裂禁令 + 插页 R）」专项中文/公开制度视频；上文为双采集/HA 去重、持续监控、Game Day/混沌演练、死人手柄/合成监测精神与 DMR 基础，需按贴纸 R 与 R1–R8 拼进网管交班包。`video_found=true`（通用视频 + NMS/HA/演练文档），**非**专项「DMR NMS 假绿演练制度」教程。

**库内必回：** `学习推送/手册15_电源监控对时与告警风暴治理.md`（N 母册；假绿气质/对时/风暴）、`手册12_基站电源与后备切换交维.md`（K；倒换窗可挂）、`手册06_日志三联单深化.md`（脱敏/证据）、`手册08_测试实验室最小闭环.md`（G 台架气质）、`手册18_金机基线漂移巡检.md`（Q；漂移≠采集假绿）、`手册07_覆盖与同频干扰分诊.md` / `手册09_话务与容量分诊.md`（禁加功率/加信道）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子

- 贴纸 **R** 五子类：采 / 备 / 绿 / 演 / 治。  
- 故事：机场塔台双雷达 + 值班屏全绿演练。  
- 八条硬规则；**先证心跳非假绿**；**无主备/无切换禁签就绪**；**假绿拒签**；**无演练禁签交维**；**脑裂禁当 HA**；**禁加功率掩盖看不见**。  
- 主贴 R，可挂 N/K/G/Q；N 过 ≠ R 过；Q ≠ R。  
- 公开包脱敏 L3。

### 11.2 回库路径

```text
  现场「监控就绪 / 全绿 / 看不见」
       │
       ├─ 本篇手册19（贴纸R + 插页R + 采集HA与假绿演练卡）
       ├─ 指针手册15 N（对时/风暴）
       ├─ 指针手册12 K（倒换窗）
       ├─ 指针手册18 Q（漂移分清）
       └─ 排除 R 后再挂 F/H/A–E；禁加功率叙事
```

### 11.3 下一篇手册候选（本篇不写正文）

- **邻频协调与边界联测制度**  
- **干扰投诉分诊与证据链**  
- （可选）其他未写专题：按现场债排序  

### 11.4 给带新人的三句话

1. 值班屏一直绿，先问采集心跳和假绿演练账，再谈空口。  
2. 有两台采集机不等于高可用——要切换验证，还要防脑裂。  
3. 看不见禁止加功率；假绿演练不是捣乱，是交维门槛。

### 11.5 运维一周里怎么用这篇（复印到周历）

| 日 | 动作 |
|----|------|
| 一 | 抽查插页 R2/R3 是否空 |
| 二 | 心跳/最近成功拍抽检 |
| 三 | 脑裂/双写治理跟进 |
| 四 | 假绿演练窗排期或复盘 |
| 五 | 与 N/K 交维包对齐 |
| 六/日 | 夜班 15 分钟节奏；演练债写入交班 |

### 11.6 和弱项加餐的衔接

采集 HA 与假绿演练 **不改** 12.5 kHz / 4FSK / 30 ms / 60 ms。加功率治「看不见」= 认错病；回加餐 + 本篇规则2。

### 11.7 一张图记住本篇（收工贴纸）

```text
  ┌────────── 贴纸 R ──────────┐
  │ 采 谁采·采什么·心跳超时   │
  │ 备 主备切换·禁脑裂         │
  │ 绿 僵死仍绿=假绿拒签       │
  │ 演 断一路·书面窗·证会响   │
  │ 治 无演练禁签·L3·禁加功率 │
  └────────────────────────────┘
     塔台双雷达 · 屏绿≠可靠
```

### 11.8 十分钟给领导的电梯演讲

> 监控交维不能只看大屏绿。我们要证明：谁在采、主备切得动、假绿探得到、定期故意断一路铃会响。做不到就不签「监控已就绪」。加功率解决不了眼睛瞎。制度贴纸叫 R，和以前的对时风暴 N、电源倒换 K、金机漂移 Q 分工清楚。

### 11.9 和手册15 / 12 / 18 同时爆发时怎么分工

| 现象主导 | 主贴 | 次挂 |
|----------|------|------|
| 采集僵死/无演练/脑裂 | **R** | N |
| 铃墙风暴/对时乱 | **N** | R（先排除假绿） |
| 市电倒换物理 | **K** | R/N |
| 抽检配置漂 | **Q** | R（若同时假绿） |

---

## 12. 本篇检查清单（自学打勾）

- [ ] 能背贴纸 R 五子类与机场塔台双雷达故事  
- [ ] 能背八条硬规则（含禁加功率、假绿拒签、无演练禁签、脑裂禁 HA）  
- [ ] 会填插页 R1–R8 与演练最小包  
- [ ] 能分清 R 与 N、K、Q、G 的主次挂  
- [ ] 会用六则对话脚本拒签「全绿交维」「加功率治看不见」  
- [ ] 夜班 15 分钟与 40 分钟演练节奏能复印  
- [ ] 10 题自测过关  
- [ ] 知道 §10 诚实说明：无专项中文 DMR 假绿演练制度视频，仅通用视频+文档  
- [ ] 回库用 L3 重对一次本网采集/假绿/演练事件  
- [ ] 弱项：采集 HA 不改变 12.5 kHz / 两槽物理  

---

*手册19 · 网管采集高可用与假绿演练剧本 · 学习推送 · 2026-10-18 09:52 +08:00*
