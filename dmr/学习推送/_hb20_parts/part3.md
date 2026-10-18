
## 6. 工作实例（8 个厚例，均教学虚构、已脱敏到 L3）

### 例 1 · 「隔壁新开信道无通知」→ S-协 / S-测
- **现象**：边界区 BER 两周内变差，本网无任何变更。  
- **排除**：本网金机正常（Q）、口部无变化（P）；频谱偏侧能量（F-邻 指纹）。  
- **贴法**：主 S-协，次 S-测 + F-邻。  
- **动作**：书面询问；补变更通知；四态联测；③ 态确认乙侧外溢 → 协商经批准的方向 / 下倾调整，复测。  
- **禁令**：联测前不得在投诉单写「恶意干扰」。

### 例 2 · 「共址新增未算互调」→ S-邻
- **现象**：铁塔新增另一家两部发射机，本网中继上行偶发噪底抬升。  
- **排除**：衰减器 3:1 指纹（手册07 F-互）；道号偏移筛查：(2a−b) 命中本网接收频点。  
- **贴法**：主 S-邻，次 F-互 / O。  
- **动作**：撤回共址「无异议」；与对方及铁塔方协调频率组合或滤波 / 隔离（走站务规程与批复）。  
- **禁令**：不得以本网加功率「顶过去」。

### 例 3 · 「功率战」→ S-治 + 规则2
- **现象**：两家在边界区先后各自抬功率，边界越来越差，投诉互指。  
- **贴法**：主 S-治。  
- **动作**：双方回到许可参数；协调书补外溢上限（S-界）；四态联测定基线；争议上报。  
- **禁令**：功率、天线、台址都是许可事项——私改本身就违规（条例第三十八条）。

### 例 4 · 「单方自测当验收」→ S-测
- **现象**：新站开通验收材料只有我方 20 点路测。  
- **贴法**：主 S-测。  
- **动作**：拒签边界验收；排 S6 窗；点位补「远我近他」点与共址接收口。  
- **禁令**：签字代替四态不算过。

### 例 5 · 「迁栅格」→ S-邻 / S-协
- **现象**：邻单位通知从 12.5 kHz 迁 6.25 kHz 栅格。  
- **贴法**：主 S-邻，次 S-协。  
- **动作**：按「比第一邻道还近」核算；迁移后四态复测（规则7）；台账更新版本。  
- **禁令**：沿用旧联测结论。

### 例 6 · 「洞口串台」→ P 还是 S
- **现象**：隧道口听到「隔壁站」。  
- **排除**：查台账：那个站属于邻单位，不是本网。  
- **贴法**：主 S-界，次 P（本网口部切换窗要配合调整）。  
- **动作**：与邻单位联测洞口外溢；本网口部按手册17 调参。  

### 例 7 · 「私自挪到空频点」→ S-治
- **现象**：有人把一个受扰信道改到「扫频看着空」的频点。  
- **贴法**：主 S-治，次 J（写频变更单）。  
- **动作**：立即回退到许可频点；走正规改频申请。  
- **禁令**：「看着空」≠ 没人用——可能是别家低占空比的许可信道。

### 例 8 · 「公开报告泄露」→ S-治
- 联测总结截图含真实频点、站名、坐标、联系人 → 撤回；按 L3 重写（道号偏移、角色标签、相对刻度）（规则8）。

---

## 7. 《本网邻频协调与边界联测卡》模板

### 7.1 封面 · 拒签门槛（贴网优 / 验收台）
```text
  ┌──── 本网邻频协调与边界联测卡 · 封面 ────┐
  │  缺以下任一项 → 禁止签开通 / 扩容 / 改参 / 边界验收： │
  │  □ 邻居台账（角色·制式·间隔·联系人角色·协调书版本）   │
  │  □ 频率关系（相对道号偏移；共址/近址/混栅格标注）       │
  │  □ 兼容核算（ACP/ACS/阻塞/互调候选，算到接收频点）     │
  │  □ 边界线 + 外溢上限 + 经批准的控制手段                 │
  │  □ 双方四态联测 + 对时 + 互签（有效期内）               │
  │  □ 结案无功率战 / 私改叙事；脱敏 L3                     │
  └──────────────────────────────────────────┘
```

### 7.2 邻居台账页（S-协）
| 邻居角色标签 | 制式 | 信道间隔 | 与本网关系（相对） | 联系人角色 | 协调书版本 | 变更通知时限 | 最近联测日期 |
|--------------|------|----------|--------------------|------------|------------|--------------|--------------|
| 邻单位乙 | | 12.5 / 6.25 | 第一邻道 / 共址 / 混栅格 | | | | |

### 7.3 联测四态记录页（S-测）
| 点位（脱敏） | ① 双静 噪底 | ② 甲发乙静 | ③ 甲静乙发 | ④ 双发 BER / 互调道 | 金机号 | 双方签字 |
|--------------|-------------|------------|------------|---------------------|--------|----------|
| 边界-01 | | | | | | |
| 远我近他-01 | | | | | | |
| 共址接收口 | | | | | | |

---

## 8. 术语表（本篇约 17 词）+ 易错观念

| 术语 | 一句话 |
|------|--------|
| **信道间隔** | 相邻两条车道中心的距离；DMR 为 12.5 kHz（国内也有 6.25 kHz 栅格） |
| **占用带宽** | 信号主体实际占的宽度；国无办附件1：12.5 kHz 间隔时 ≤ 8.5 kHz |
| **混栅格** | 12.5 与 6.25 kHz 栅格并存，中心不一定对齐 |
| **共址 / 近址** | 同塔同机房 / 相距很近的两家台站 |
| **dBc** | 比载波低多少 dB；−60 dBc = 百万分之一 |
| **邻道功率 ACP** | 发射机漏进邻道的功率（裙边） |
| **瞬态邻道功率** | 发射开 / 关瞬间漏进邻道的功率；限值更宽松 |
| **邻道选择性 ACS** | 接收机在邻道强信号下仍能解对本道的能力 |
| **阻塞 / 减敏** | 强信号把接收前端顶饱、灵敏度下降 |
| **互调 IMD** | 多个强信号混出新频率；三阶 2f1−f2 |
| **保护比** | 有用信号需比干扰高出的 dB 数 |
| **OCR** | 频率偏移下的合成抑制（发射裙边 + 接收选择性） |
| **远近效应** | 有用信号远而弱、邻道信号近而强 |
| **边界线 / 外溢上限** | 服务区分界与越界信号的约定上限 |
| **四态联测** | 双静 / 甲发乙静 / 甲静乙发 / 双发 |
| **功率战** | 双方互相抬功率，双输 |
| **脱敏 L3** | 教学 / 公开最高脱敏；禁真实频点站名单位联系人坐标 |

**易错观念**

| 错 | 对 |
|----|----|
| 邻频不是同频，没事 | 近处第一邻道可能比远处同频更凶（远近效应） |
| 我的设备达标，问题在对方 | ACP 与 ACS 合效果谁差谁说了算；要联测 |
| 自己跑一圈就是边界验收 | 必须双方同窗四态互签 |
| 被压了就开大 | 功率战双输；功率是许可事项 |

---

## 9. 自测（10 题）+ 参考答案

1. 贴纸 S 五个子类各是什么？各用一句话。  
2. 「12.5 kHz 信道」和「占用带宽 ≤ 8.5 kHz」是什么关系？两边的「路肩」有什么用？  
3. −60 dBc 大约是多少分之一？为什么共址时仍可能出事？  
4. 发射邻道功率（ACP）和接收邻道选择性（ACS）为什么必须一起看？  
5. 按 SM.337 思路，减小干扰有哪四个旋钮？哪个旋钮本篇禁止你单方面去拧？  
6. 两部发射机在 +2 道、+5 道，三阶互调产物落在哪？  
7. 四态联测是哪四态？② 态能回答什么问题？  
8. 什么叫远近效应？它对联测点位有什么要求？  
9. 洞口听到「隔壁站」，什么时候贴 P，什么时候主贴 S？  
10. 对方迁到 6.25 kHz 栅格，你要做哪三件事？公开记录怎么写？

### 参考答案
1. **S-协** 邻居台账与协调书；**S-邻** 邻频兼容核算；**S-界** 边界线与外溢上限；**S-测** 双方四态联测；**S-治** 拒签、禁功率战与私改、争议上报、L3。  
2. 车道 12.5 kHz，车身（信号主体）≤ 8.5 kHz（国无办附件1）；路肩给裙边与滤波留余量，减少漏进隔壁。  
3. 百万分之一；但发射功率大、两家天线贴得近时，剩下的百万分之一仍远高于对方接收灵敏度（§4.2）。  
4. 干扰的合效果由两者共同决定，谁差谁说了算；单边达标不能证明可共存（§4.3）。  
5. 降低干扰方发射、拉开距离、拉开频率、提高有用信号；**单方面抬自己功率 / 私自挪频**被禁止（规则2）——改频、改功率都须走许可变更。  
6. (2×2−5) = **−1 道**，(2×5−2) = **+8 道**。  
7. 双静 / 甲发乙静 / 甲静乙发 / 双发；② 态回答「甲的外溢进乙多少」。  
8. 有用信号远而弱、邻道信号近而强；点位必须包括「对方站附近、本网覆盖边缘」与共址接收口。  
9. 隔壁站属本网 → P；属别家网 → 主贴 S，本网口部要配合调参时次挂 P（规则6）。  
10. 更新台账（S-协）、按比第一邻道还近核算（S-邻）、迁移后四态复测（规则7）；公开只写道号偏移、角色标签、相对刻度（L3）。

---

## 10. 加深阅读与视频（均已用 curl 核对 HTTP 200；视频用 YouTube oEmbed 核对存在）

**标准与 DMR 本体（看原文，别背本篇转述）**
1. **[ETSI EN 300 113 V3.1.1（PDF）](https://www.etsi.org/deliver/etsi_en/300100_300199/300113/03.01.01_60/en_300113v030101p.pdf)**——§7.4 邻道/隔道功率、§8.6 邻道选择性、§8.8 互调响应抑制、§8.9 阻塞。  
2. **[ETSI EN 300 113-1 V1.5.1（PDF）](https://www.etsi.org/deliver/etsi_en/300100_300199/30011301/01.05.01_60/en_30011301v010501p.pdf)**——TS 102 361-1 引用的旧版分册。  
3. **[ETSI TS 102 361-1 V2.7.1（PDF）](https://www.etsi.org/deliver/etsi_TS/102300_102399/10236101/02.07.01_60/ts_10236101v020701p.pdf)**——§10.1 物理层通用参数；本地 `01-空中接口/`。  
4. **[ETSI TR 102 398 V1.5.1（PDF）](https://www.etsi.org/deliver/etsi_TR/102300_102399/102398/01.05.01_60/tr_102398v010501p.pdf)**——§5.1.4、§5.2、§10.2.3；参考文献列 CEPT T/R 25-08。本地 `00-入门/`。  
5. **[DMR Association · DMR Standards](https://www.dmrassociation.org/dmr-standards.html)**

**ITU / 欧洲协调方法（借方法，不抄门限）**
6. **[ITU-R SM.337 条目](https://www.itu.int/rec/R-REC-SM.337/en)** · **[SM.337-6 PDF](https://www.itu.int/dms_pubrec/itu-r/rec/sm/R-REC-SM.337-6-200810-I!!PDF-E.pdf)** · **[SM.337-6 目录](https://www.itu.int/dms_pubrec/itu-r/rec/sm/R-REC-SM.337-6-200810-I!!TOC-HTM-E.htm)**——频率与距离间隔。  
7. **[ITU-R SM.329](https://www.itu.int/rec/R-REC-SM.329/en)**（杂散域无用发射）· **[ITU-R SM.1541](https://www.itu.int/rec/R-REC-SM.1541/en)**（带外域无用发射）· **[ITU-R P.1546](https://www.itu.int/rec/R-REC-P.1546/en)**（30 MHz–4 000 MHz 点对面预测）。  
8. **[ITU 无线电规则](https://www.itu.int/pub/R-REG-RR)** · **[ITU-R 第1研究组（频谱管理）](https://www.itu.int/en/ITU-R/study-groups/rsg1/Pages/default.aspx)** · **[ITU 国家频谱管理手册](https://www.itu.int/pub/R-HDB-21)**。  
9. **[CEPT ECC · 专业陆地移动无线电专题](https://www.cept.org/ecc/topics/private-professional-land-mobile-radio)**（CEPT 文档库核验超时，未单列）。  
10. **[HCM Agreement 正文（PDF，RSGB 转载）](https://thersgb.org/publications/governmental/hcm-main-text.pdf)**——欧洲跨境协调协定，借方法。

**国内法规与通知（以官方原文为准）**
11. **[国无办〔2025〕1号 通知（工信部）](https://www.miit.gov.cn/jgsj/wgj/wjfb/art/2025/art_31a0765b521e4dc493262188aea65618.html)** · **[含附件 PDF（北京市政府转载）](https://www.beijing.gov.cn/zhengce/zhengcefagui/qtwj/202505/W020250508533710250422.pdf)**——第八、十五条；附件1 技术要求。  
12. **[《中华人民共和国无线电管理条例》](https://www.gov.cn/zhengce/zhengceku/2016-11/25/content_5137687.htm)**  
13. **[《无线电频率使用许可管理办法》](https://www.gov.cn/zhengce/2022-08/23/content_5722706.htm)**。  
14. **[《边境地区地面无线电业务频率国际协调规定》（工信部）](https://www.miit.gov.cn/jgsj/wgj/bmgz/art/2021/art_e99e6576549f491bb2a36ff971114191.html)** · **[国务院公报版](https://www.gov.cn/gongbao/content/2017/content_5210512.htm)**  
15. **[工信部标准信息问答 · 无线电干扰是怎样分类的？](https://bzxx.miit.gov.cn/bzxx/problem/detail?id=4FFC66BB85204DE3953EBB50B82C2645)**（需浏览器 JS）。  
16. **[APCO · Radio Frequency Management](https://www.apcointl.org/spectrum-management/)**——只借「协调人」角色概念。

**测量与站点工程（厂商教程，只借原理）**
17. **[R&S · Understanding ACLR](https://www.rohde-schwarz.com/us/products/test-and-measurement/analyzers/signal-and-spectrum-analyzers/understanding-adjacent-channel-leakage-ratio-aclr_258371.html)** · **[R&S · Channel Power Measurements（视频页）](https://www.rohde-schwarz.com/us/knowledge-center/videos/understanding-channel-power-measurements_251220-1513229.html)**。  
18. **[Keysight · Making an ACP Measurement](https://helpfiles.keysight.com/csg/89600B/Webhelp/Subsystems/gui/content/markers_acpr_makacprmeas.htm)**。  
19. **[Tait · When and where to use a duplexer](https://www.taitcommunications.com/en/about-us/news/2014/05/13/when-and-where-to-use-a-duplexer)** · **[Tait · Interference-free RF site design](https://www.taitcommunications.com/en/about-us/news/tait-talks-a-tait-engineer-is-sharing-his-extensive-expertise-on-ensuring-interference-free-rf-site-design)**  
20. **[Shure · What is Intermodulation?](https://www.shure.com/en-gb/insights/what-is-intermodulation)**  
21. **[Anritsu · LMR Master Basics（视频门户）](https://video-test-measurement.anritsu.com/en-us/detail/videos/land-mobile-radio/video/6166764567001/anritsu-site-master-spectrum-master-and-lmr-master-basics?autoStart=true)**。

**弱项补（频率与带宽 / 窄带化）**
22. **[Scanner School · AM, FM, Narrowband & Wideband FM](https://www.scannerschool.com/am-fm-sideband-narrowband-fm-and-wideband-fm/)** · **[Scanner School · Intro to DMR](https://www.scannerschool.com/introduction-to-dmr/)** · **[Electronics Notes · FM sidebands & bandwidth](https://www.electronics-notes.com/articles/radio/modulation/frequency-modulation-fm-sidebands-bandwidth.php)**。  
23. **[EMCI · Why Does Narrowbanding Matter?](https://www.emciwireless.com/our-blog/what-is-narrowbanding/)** · **[Motorola Solutions · What is Narrowbanding?（视频页）](https://video.motorolasolutions.com/detail/video/1187545050001)**。  
24. **Wikipedia 名词垫脚石**：[Adjacent-channel interference](https://en.wikipedia.org/wiki/Adjacent-channel_interference) · [Co-channel interference](https://en.wikipedia.org/wiki/Co-channel_interference) · [Intermodulation](https://en.wikipedia.org/wiki/Intermodulation) · [Passive intermodulation](https://en.wikipedia.org/wiki/Passive_intermodulation) · [Selectivity (radio)](https://en.wikipedia.org/wiki/Selectivity_%28radio%29) · [Frequency coordination](https://en.wikipedia.org/wiki/Frequency_coordination)。

**视频（YouTube oEmbed 均 200）**
25. **[R&S · Understanding Spectrum Analyzers – ACLR](https://www.youtube.com/watch?v=mco_BJ1mjNo)** · **[R&S · Getting Started with the FSW – ACLR](https://www.youtube.com/watch?v=vr_4dKYmF1g)**  
26. **[Shure · What is Intermodulation?](https://www.youtube.com/watch?v=IrlyAei02_o)** · **[electronics unmessed · Mystery of Intermodulation (EP131c)](https://www.youtube.com/watch?v=Ahlw4jVjnxY)**  
27. **[Wireless Workbench 6 · Introduction to Frequency Coordination](https://www.youtube.com/watch?v=k7qjqPOZC3E)** · **[Practical Show Tech · Basics of Frequency Coordination](https://www.youtube.com/watch?v=pWbdpMRS32M)** · **[SoundBase · Cleaner RF Coordination](https://www.youtube.com/watch?v=dKczj33QKkA)**——借「先扫、再算互调、再分配」顺序。  
28. **[BearCom · Narrowbanding Tutorial](https://www.youtube.com/watch?v=7ZFM9WwneSc)** · **[BridgeCom · Narrowband vs Wideband](https://www.youtube.com/watch?v=gYGV7J4QrmU)** · **[Scanner School · Secret of Bandwidth (Lesson 3)](https://www.youtube.com/shorts/Md32WlReUP8)**  
29. **[Scanner School · What is DMR?](https://www.youtube.com/watch?v=aQX_JbTbXuY)** · **[Scanner School · Why Digital Radio Sounds Like Robots](https://www.youtube.com/watch?v=-hLiTz7oSKE)** · **[Scanner School · P25 vs DMR](https://www.youtube.com/watch?v=tsVFV_XTQw8)** · **[Tait Radio Academy · P25 Phase 1 vs Phase 2](https://www.youtube.com/watch?v=lt3F1xgNB4I)**

> **诚实说明**：没有找到「DMR 专网邻频协调与边界联测制度（含邻居台账 + 兼容核算 + 双方四态联测 + 插页 S）」的专项中文 / 公开制度视频；上文视频为 ACLR 测量、互调、无线话筒频率协调、窄带化与 DMR 基础的**通用**内容，需按贴纸 S 与 S1–S8 拼进本网流程。`video_found=true`（通用），**非**专项。Ofcom（英国）与 FCC / eCFR（美国）相关协调页面从核验环境返回 403 或访问校验页，**未列入**；B 站相关射频课程返回 412，亦未列入。

**库内必回：** 手册07（F 诊断）、16（O）、17（P）、18（Q 金机）、15（N 对时）、06（脱敏）、11（J 变更单）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子
- 贴纸 **S** 五子类：协 / 邻 / 界 / 测 / 治。  
- 故事：相邻两家 KTV 共用一堵墙 + 物业陪同隔墙试唱。  
- 八条硬规则：**先证邻居台账**；**禁功率战与私自挪频**；**无书面协调禁签**；**单方自测禁签**；**共址近址混栅格未核算禁签**；**主贴 S 可挂 F/P/O/Q/N**；**变更先通知后复测**；**争议上报、L3**。  
- 弱项：12.5 kHz 车道、≤ 8.5 kHz 车身、−60 dBc = 百万分之一；ACP 与 ACS 谁差谁说了算。

### 11.2 回库路径
现场「边界变差 / 共址新增 / 对方投诉 / 迁栅格」→ 本篇（贴纸 S + 插页 S + 联测卡）→ 诊断指针手册07 F → 自家侧 O / P → 金机 Q、对时 N → 争议交无线电管理机构；全程禁功率战。

### 11.3 下一篇手册候选（本篇不写正文）
- **干扰投诉分诊与证据链**（向主管部门 / 对方单位投诉时，证据怎么组织、怎么脱敏、怎么不越权）  
- **频率许可变更与台站执照台账**（功率 / 天线 / 台址 / 信道变更与 J 写频单、S 协调书三账对齐）  
- （可选）**重大保障临时频率与联测窗**（临时设台、48 小时报告类要求与本网保障预案的衔接）

### 11.4 给带新人的三句话
1. 边界变差，先问邻居变没变，再问是本道中心还是偏一侧。  
2. 邻频不是没事——近处第一邻道可能比远处同频更凶。  
3. 被压了不许开大；一起到边界上四态联测，谈不拢找主管部门。

### 11.5 一张图记住本篇（收工贴纸）
```text
  ┌────────── 贴纸 S ──────────┐
  │ 协 邻居台账·协调书·通知   │
  │ 邻 同/邻/混栅格·ACP/ACS   │
  │ 界 边界线·外溢上限         │
  │ 测 双方同窗·四态·互签     │
  │ 治 禁功率战·禁私改·L3     │
  └────────────────────────────┘
    隔墙 KTV · 一起试唱才算数
```

### 11.6 十分钟给领导的电梯演讲
> 边界问题一家解决不了：认清邻居、算清隔墙、上限写进协调书、和对方四态联测并互签；做不到不签开通和验收。抬功率只会引发功率战，频率功率都是许可事项；谈不拢交主管部门。贴纸 S，与 F / P / O 分工清楚。

---

## 12. 本篇检查清单（自学打勾）
- [ ] 能背贴纸 S 五子类与隔墙 KTV 故事  
- [ ] 能背八条硬规则（含禁功率战、单方自测禁签、混栅格核算、变更先通知）  
- [ ] 会用 dB 表换算 −60 dBc，能说清 ACP 与 ACS 的合效果  
- [ ] 会用道号偏移算三阶互调候选，并算到接收频点  
- [ ] 10 题自测过关  
- [ ] 知道 §10 诚实说明：无专项中文 DMR 邻频协调视频，仅通用视频 + 文档  
- [ ] 回库用 L3 重对一次本网边界 / 共址事件  

---

*手册20 · 邻频协调与边界联测制度 · 学习推送 · 2026-10-18 18:52 +08:00*
