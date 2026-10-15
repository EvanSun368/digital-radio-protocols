
## 8. 术语表（本篇约 30 词）+ 易错观念

| # | 词 | 一句话 | 易错 |
|---|----|--------|------|
| 1 | 电梯井道 | 轿厢垂直运行的井筒 | 有电梯 ≠ 有射频路径 |
| 2 | 轿厢 | 金属罐笼；门开关改衰减 | 门开数据 ≠ 门关真实 |
| 3 | 厅门 | 每层井道门区域 | 厅门有信号 ≠ 轿厢内有 |
| 4 | 泄漏同轴/辐射电缆 | 沿线「漏」信号的馈线 | 图纸有 ≠ 已装且通 |
| 5 | 厅门天线 | 层站侧耦合进轿厢的天线 | 一副大堂天线 ≠ 全井覆盖 |
| 6 | 门开/门关对照 | 同点开关门两次测量 | 可选项心态 = 拒签 |
| 7 | 中运行走测 | 升降过程中连续测 | 只停层测 ≠ 运动剧本 |
| 8 | 地下车库 | 厚混凝土+钢筋屏蔽空间 | 地面站「漏下来」不可靠 |
| 9 | 坡道 | 进出车库的行驶过渡 | 静止测点代替不了行驶 |
| 10 | 法拉第笼气质 | 金属壳体屏蔽 | 轿厢/钢筋车库常见 |
| 11 | 层间黑洞 | 井道某段无有效耦合 | 易被「随机掉话」掩盖 |
| 12 | 猎站/重选毛刺 | 运动中短时换站失败 | 先查扇区边界与路径 |
| 13 | 扇区边界 | 两覆盖区交缝 | 穿过井道/坡道很危险 |
| 14 | 满车抽测 | 车库有车占用时再测 | 空车库绿图骗人 |
| 15 | 远端单元 | 有源室分末端 | 掉电像覆盖玄学（挂 K） |
| 16 | 点位表 | 设计该测该装清单 | 缺电梯车库=先天盲 |
| 17 | 金机梯子 | 能量→SYNC→身份→BER→业务 | 不用公网 LTE 代替 |
| 18 | 假覆盖 | 结构盲外表像弱覆盖 | 禁加功率 |
| 19 | 假干扰 | 门关/升降毛刺像同频 | 先门对照 |
| 20 | 假容量 | 盲区造成话务假坏 | 先结构 |
| 21 | 贴纸 L | 电梯井/地下车库总类 | 须子类+证据 |
| 22 | 插页 L | R1–R8 | 无门对照则弱 |
| 23 | L-交 | 边界责任 | 口头不算 |
| 24 | 室分商 | 楼宇 DAS/泄漏实施方 | 不等于 DMR 信源方 |
| 25 | 信源方 | DMR 基站/核心侧 | 边界要切开写 |
| 26 | 对时 | 走测与投诉与网管对齐 | 手册06 |
| 27 | 脱敏 L3 | 教学/公开仓 | 禁真实楼名频点 |
| 28 | 带条件放行 | 非关键尾巴有时限责任人 | 门关未测不可带条件 |
| 29 | 对齐会 | 周会抽插页 L 与反例 | 不等于已经交维 |
| 30 | I-覆 加深 | 本篇相对手册10 的定位 | 走廊过 ≠ 本篇过 |

**易错观念（钉死）**：

- 「走廊有信号」≠ 电梯/车库交维完成。  
- 「门开有信号」≠ 门关可用。  
- 「有电梯井」≠ 有射频路径。  
- 「加功率」≠ 井道/车库药。  
- 「手册10 签过」≠ 本专项可免。

---

## 9. 自测（10 题）+ 参考答案

**题 1.** 贴纸 L 五个子类各用一句话说明；各举一个拒签/拒放行触发。  
**题 2.** 画出「矿井罐笼 + 地下矿层」链：井道、厅门、轿厢门、车库层、坡道、边界各在哪。  
**题 3.** 八条硬规则默写（大意正确即可）。  
**题 4.** 为何「只测走廊」必须拒签？R5/R6 缺什么？  
**题 5.** 门开/门关对照为什么强制？只开门测会漏掉什么？  
**题 6.** 插页 L 的 R1、R3、R5、R6 各挡住哪种胡说？  
**题 7.** 假覆盖 / 假干扰 / 假容量 各举一例井道或车库真因；错误处置是什么？  
**题 8.** 升降窗短时登记失败，为何主贴 L 而不是直接手册01 结案？  
**题 9.** 手册10 的 I-覆 与本篇 L 是什么关系？走廊交维过能否代替本篇？  
**题 10.** 下一篇候选你记住哪两个？本篇写了它们正文吗？

### 参考答案

1. L-井井道路径；L-库车库层/坡道；L-门门开闭衰减；L-切运动猎站；L-交边界。触发见表 2.4。  
2. 见 §2.1 ASCII；边界=分包合同。  
3. 见 §4.1 八条。  
4. 未证明井道/车库与门/运动；R5 门对照、R6 运动剧本空。  
5. 勤务常门关；只开门测会漏金属笼衰减与「门缝耦合」假象。  
6. R1 挡「大概下午」；R3 挡「图纸有就行」；R5 挡「开门测过了」；R6 挡「停层测过了」。  
7. 井道无路径；门关 BER 跳；早高峰罐笼窗掉话。错：加功率/扫同频一周/加信道。  
8. 症状可挂01，主因在结构窗；先L后协议。  
9. 本篇是 I-覆 加深专项；走廊过不能代替井道/车库剧本。  
10. 大批量写频与 OTAP 风险边界；电源监控对时与告警风暴治理等。**本篇未写正文。**

---

## 10. 加深阅读与视频（均已用 curl 核对 HTTP 200；视频用 YouTube oEmbed 核对存在）

1. **[Hytera · Filling Coverage Gaps in Garages, Tunnels, High-Rises](https://www.hytera.com/en/connect/blog/filling-coverage-gaps-in-garages-tunnels-and-high-rise-interiors)**  
   - 车库/隧道/高层盲区与泄漏馈线、分布天线选型白话；对本篇 L-库 / L-井 最直接。  
2. **[Resolution Wireless · Parking Garage DAS Planning](https://www.resolutionwireless.com/underground-parking-garage-das-planning/)**  
   - 地下车库混凝土+钢筋屏蔽、逐层勘测与验收气质；对照 L-库。  
3. **[Wireless-Nets · How to Provide Coverage Inside Elevators](https://wireless-nets.com/resources/tutorials/covering_elevators.html)**  
   - 电梯金属衰减、厅门侧天线与泄漏同轴利弊；强调门关与井道协调（Wi-Fi 文，借结构直觉，不当 DMR 条文）。  
4. **[香港机电工程署 · 升降机电讯覆盖指引 Circular 6/2024（PDF）](https://www.emsd.gov.hk/filemanager/tc/content_806/Circular_6_2024_Guideline_on_Provision_of_Telecommunications_Service_Coverage_to_Lifts.pdf)**  
   - 井道布线与电梯设备分隔、安全协调公开指引；**只借「要协调电梯维保、保持净距」精神，不背条款当 ETSI**。  
5. **[RFS · RADIAFLEX Installation Guideline（PDF）](https://www.rfstechnologies.com/pictures/rfs%20technologies/installation%20instrctions/radiaflex_installation_guideline_version-a-12-2024_optimized.pdf)**  
   - 辐射电缆安装指南，含垂直井道安装章节气质；作工程阅读，不绑定品牌强制。  
6. **[AMTA / MCF · Design Guidelines for DAS（Draft PDF）](https://amta.org.au/wp-content/uploads/2024/10/MCF-Design-Guidelines-for-Distributed-Antenna-Systems-Draft-2.0-IBC-Workgroup-11092024-1.pdf)**  
   - 楼宇核心与电梯井覆盖、扇区边界避免不当切换等设计讨论；对照 L-切。  
7. **[Anritsu · Testing Distributed Antenna Systems（DAS）Application Note PDF](https://dl.cdn-anritsu.com/en-us/test-measurement/files/Application-Notes/Application-Note/11410-00887A.pdf)**  
   - 室分回波/DTF/插损/PIM 与走测气质；接手册10 最小测试包。  
8. **[Rohde & Schwarz · Testing Passive Networks in DAS（White Paper PDF）](https://scdn.rohde-schwarz.com/ur/pws/dl_downloads/pdm/cl_brochures_and_datasheets/white_paper/5216_2053_52/Testing_Passive_Networks_wp_en_5216-2053-52_v0200.pdf)**  
   - 被动室分分支测试与走测前功率准确；适合写交维包规范。  
9. **[Rohde & Schwarz · Measurements on Leaky Feeders](https://www.rohde-schwarz.com/uk/applications/measurements-on-leaky-feeders_230850-1534464.html)**  
   - 泄漏电缆测量话题入口。  
10. **[VIAVI · DAS Deployment Overview（Application Note PDF）](https://www.viavisolutions.com/en-us/literature/das-deployment-overview-streamlined-approaches-das-deployments-application-notes-en.pdf)**  
    - 部署与验收：扫线、噪底、走测流程总览。  
11. **[TRS · IBS Testing Pocket Guide Part 1（PDF）](https://cms.trsrentelco.com/sites/default/files/resources-pdfs/In_Building_Systems_Testing_Pocket_Guide_Part_1.pdf)**  
    - 室内系统测试口袋书；明确 CW 走测对车场、升降井等场景的重要性。  
12. **[Anritsu · Cable and Antenna Analyzer Measurement Guide PDF](https://dl.cdn-anritsu.com/en-us/test-measurement/files/Manuals/Measurement-Guide/10580-00241F.pdf)**  
    - 回波/DTF 测量指南公开参考（不绑定逐步厂商课）。  
13. **[Wikipedia · Distributed antenna system](https://en.wikipedia.org/wiki/Distributed_antenna_system)**  
    - DAS 总览与术语地图。  
14. **[Wikipedia · Leaky feeder](https://en.wikipedia.org/wiki/Leaky_feeder)**  
    - 泄漏馈线/隧道与受限空间百科入口。  
15. **[Wikipedia · Faraday cage](https://en.wikipedia.org/wiki/Faraday_cage)**  
    - 理解轿厢金属笼与钢筋车库屏蔽气质。  
16. **[Wikipedia · Handover](https://en.wikipedia.org/wiki/Handover)**  
    - 切换/重选概念垫脚石；对照 L-切（蜂窝文，借直觉）。  
17. **[Wikipedia · Standing wave ratio](https://en.wikipedia.org/wiki/Standing_wave_ratio)** · **[Passive intermodulation](https://en.wikipedia.org/wiki/Passive_intermodulation)**  
    - VSWR 与 PIM 定义级复习。  
18. **[Wikipedia · Radio propagation](https://en.wikipedia.org/wiki/Radio_propagation)**  
    - 传播与阻挡总览；帮助新人理解「混凝土层数」不是玄学。  
19. **[DMR Association · Key Benefits of DMR Technology](https://dmrassociation.org/dmr-key-benefits.html)**  
    - 官方白话弱项补；与频谱短补对齐。  
20. **[Scanner School · An Introduction to DMR](https://www.scannerschool.com/introduction-to-dmr/)**  
    - 文文入门；避免把井道事故说成「数字电台玄学」。

**视频：**

21. **[Keysight FieldFox · Episode 78: Leaky Feeder Testing using FieldFox CAT mode（YouTube）](https://www.youtube.com/watch?v=1-V7xqUAAGY)**  
    - 泄漏电缆 CAT/DTF 操作气质演示（通用仪表课，非 DMR 电梯专项）。  
22. **[How to Perform a Return Loss Sweep for RF Cable & Antenna Testing（YouTube）](https://www.youtube.com/watch?v=f7tzYk9ELh4)**  
    - 回波/Return Loss 扫线入门。  
23. **[Scanner School · What is DMR?（YouTube）](https://www.youtube.com/watch?v=aQX_JbTbXuY)**  
    - 双时隙入门弱项补；提醒结构病不改变 12.5 kHz/两槽物理。  
24. **[Scanner School · Why Digital Radio Sounds Like Robots（YouTube）](https://www.youtube.com/watch?v=-hLiTz7oSKE)**  
    - 数字悬崖/BER 直觉；门关「突然卡」与模拟「渐渐差」的差别。

> **诚实说明**：没有找到「DMR 专网电梯井·地下车库专项交维（含门开/门关对照 + 中运行升降 + 车库每层/坡道剧本 + 插页拒签）」专项中文/公开视频教程；上面的视频与文档分别讲泄漏电缆测试、室分验收、电梯/车库覆盖工程与 DMR 基础，需要你自己按本篇贴纸 L 与插页 R1–R8 把它们拼进交维包。`video_found=true`（通用 DAS/泄漏/室内覆盖与 DMR 入门视频），非专项「DMR 电梯井/车库交维」教程。

**库内必回：** `学习推送/手册10_室分隧道覆盖交维清单.md`（本篇的母册 I）、`手册07_覆盖与同频干扰分诊.md`（假 F）、`手册08_测试实验室最小闭环.md`（金机）、`手册06_日志三联单深化.md`（对时/脱敏）、`手册09_话务与容量分诊.md`（假 H）、`手册01_登记失败三问.md` / `手册02_Grant了没声.md`（运动窗次挂）、`手册11_写频变更回滚与金机基线制度.md`、`手册12_基站电源与后备切换交维.md`（远端电源）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子

- 贴纸 **L** 五子类：井 / 库 / 门 / 切 / 交。  
- 故事：大楼 = 矿井；电梯 = 罐笼；车库 = 地下矿层；坡道 = 矿车通道。  
- 交维必做：**厅门 + 门开/门关 + 中运行 + 车库每层 + 坡道**。  
- 八条硬规则；禁加功率掩盖井道/车库黑洞。  
- 症状可挂 F/I/A/B，**主贴 L**。

### 11.2 回库路径

```text
总索引.md
  └─ 集群 / Tier III → 运维手册
       ├─ 手册01–05（A–E）06（总单）07（F）08（G）09（H）10（I）11（J）12（K）
       └─ 本篇手册13（贴纸L + 插页L + 电梯井·地下车库专项交维卡）
            └─ 回：手册06–12、加餐弱项；母册手册10
```

### 11.3 下一篇手册候选（本篇不写正文）

- **大批量写频作业与 OTAP/无线写频风险边界**（手册11 J 的批量与无线通道加深）。  
- **电源监控对时与告警风暴治理**（手册12 K-告 的加深册）。  
- **（可选）其它**：例如室分有源隔离与减敏台架专项、口部切换与邻站泄漏治理等（按现场痛点再排）。

### 11.4 给带新人的三句话

> 只测走廊，就没有电梯/车库交维。  
> 门关对照与中运行是强制项，不是麻烦项。  
> 井道在黑洞时，加功率不是药，协议玄学也不是第一结案词。

### 11.5 运维一周里怎么用这篇（复印到周历）

```text
周一  默写 L 五子类 + 「未测井道/车库禁止签」卡
周二  抽一部电梯：门开/门关各一次
周三  对一份旧交维包：有无 R5/R6
周四  演练脚本 C（加功率）与脚本 D（边界）
周五  §6.5 对齐会；统计电梯/车库投诉与拒签
```

### 11.6 和弱项加餐的衔接

把 12.5 kHz / 4FSK / 30 ms 两槽背熟，你才说得清「井道/车库改的是路径与衰减，不是调制台阶」。有人要用加功率治电梯黑洞时，回加餐 + 手册07/09/10。

### 11.7 一张图记住本篇（收工贴纸）

```text
        要交维 / 遇电梯或车库怪病
                      │
          ┌───────────┴───────────┐
          │ 点位表含井道与车库？    │否 → 拒签（L-井/L-库/L-交）
          ▼
        门开/门关对照做过？──否──▶ 拒签（L-门）
          │是
          ▼
        中运行升降 + 坡道行驶做过？──否──▶ 拒签（L-切）
          │是
          ▼
        路径可指认（泄漏/厅门/分支）？──否──▶ 先补测（L-井/L-库）
          │是
          ▼
        边界书面？──否──▶ 拒签（L-交）
          │是
          ▼
        业务抽检；症状可挂 F/I/A/B，主贴 L
        禁令：只测走廊；只开门测；加功率掩盖；结构病写成协议玄学
```

---

## 12. 本篇检查清单（自学打勾）

- [ ] 能背 L 五子类并各举一个拒签例子  
- [ ] 能画「矿井罐笼 + 地下矿层」链并指出五段  
- [ ] 能背八条硬规则  
- [ ] 能说明厅门→门开/门关→中运行→车库/坡道→边界的顺序直觉  
- [ ] 能拒绝「只测走廊 / 只开门测 / 加功率掩盖」  
- [ ] 会填插页 L 的 R1–R8  
- [ ] 会用 §7 封面拒签门槛 + 门/运动剧本页 + 边界责任页做一次模拟交维  
- [ ] 知道假覆盖/假干扰/假容量如何主贴 L  
- [ ] 知道运动窗如何次挂手册01/02/07/09/10 而不改主贴  
- [ ] 自测 10 题达标；回库重对至少 1 次电梯/车库事件（L3）  
- [ ] 知道下一篇候选且**本篇未写它们的正文**  
- [ ] 外链打开过至少 3 个（含 1 个电梯或车库文 + 1 个 DAS/泄漏文或视频）

---

*推送说明：本篇为手册模式第 13 篇（非第 41 课）。主线是电梯井·地下车库专项交维：贴纸 L 五子类、插页 L、矿井罐笼+地下矿层故事、八条硬规则、现场映射、十例、交维卡模板、术语、自测与核验外链。硬禁令贯穿：不发明条款号、不写真实频点/个号/密钥/楼名、不重写手册07–12 全文、禁加功率掩盖、症状可挂 F/I/A/B 但主贴 L。读完应能向同事讲清「交维必须做门开/门关与中运行、只测走廊不算数、井道在黑洞时先贴 L」。*
