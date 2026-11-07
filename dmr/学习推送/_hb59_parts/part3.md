## 6. 工作实例（12 则，教学虚构，L3）

1. **接地棒在想签准用**：运维称棒还在要签准用 → 查 BF1，无机房接地台账本期核对 → **拒签**；补 BF-地。  
2. **看着连着 / 口头连过当窗过**：外包称「看着连着 / 连过了」免窗页 → **拒签**；补 BF-等 主人/窗/方法/准用期。  
3. **AM 顶替 BF**：班长用 AM 天馈接地浪涌签顶本期机房等电位签 → **挂 R**；主贴仍 BF；**AM过≠BF过**。  
4. **AO / AW 顶替**：站务称漏水与列头末端过了等电位免做 → **拒签顶替**；AO≠BF、AW≠BF；漏水≠等电位；供电≠等电位。  
5. **N 绿免实测**：大屏监控绿，本期实测免 → **拒签**；N绿≠BF过；补 BF-验。  
6. **套邻站表**：外包拷邻站接地/等电位/SPD表改机房号 → **BF-验 拒签重测**；禁套。  
7. **功率战**：雷击/SPD告警，网优要抬功率 → **禁功率战**；先挂 N；缺秩序整改贴 BF；天馈侧另问 AM。  
8. **旁路SPD冒充**：外包旁路SPD消告警后要求准用 → **禁**；挂 N/R；禁签。  
9. **拆跨接冒充**：新人拆跨接「量一下」再冒充连好 → **禁**；挂整改；主贴 BF-治。  
10. **AD / AF / AS / BC 混签**：环境班称 AD 入库与 AF/AS/BC 供电过了，等电位免 → **拒签**；AD≠本期窗、供电≠等电位。  
11. **不安全带电违章**：外包未授权带电拧联接螺栓要求准用 → **禁**；挂 N/R；禁签。  
12. **泄密发群**：新人公开群贴真实汇流排号与SPD序列号 → **L3 违规**；脱敏重发；挂 BF-治。

### 6.1 实例对照表（再钉一次，教学）

| # | 触发原话 | 正确贴纸动作 | 错误动作（禁） |
|---|----------|--------------|----------------|
| 1 | 「棒在就能签」 | 补 BF-地；拒签无账 | 直接签准用 |
| 2 | 「看着连着 / 口头连过」 | 补 BF-等 | 免窗页 |
| 3 | 「AM 签顶」 | 挂 R；主贴 BF | 用 AM 顶 BF |
| 4 | 「AO/AW 过了免做」 | 边界勾选；主贴 BF | 用 AO/AW 顶 |
| 5 | 「N 绿免实测」 | 补 BF-验 | 免实测 |
| 6 | 「邻站表改号」 | BF-验 拒签重测 | 套票交差 |
| 7 | 「抬功率压告警」 | 挂 N；禁功率战 | 抬功率 |
| 8 | 「旁路SPD消告警」 | 挂 N/R；禁签 | 旁路后准用 |
| 9 | 「拆跨接冒充」 | 挂整改；禁 | 拆跨接冒充连好 |
| 10 | 「AD/AF/AS/BC 过了免」 | 边界勾选；主贴 BF | 混签顶替 |
| 11 | 「带电拧螺栓」 | 挂 N/R；禁 | 不安全带电违章 |
| 12 | 「汇流排/SPD编号发群」 | L3 脱敏 | 公开可还原编号 |

### 6.2 与 AM / AO / AW / AD / N 边界再对照（防写混）

```text
  天馈/塔脚/天馈侧SPD抽检          ──→  贴纸 AM（手册40）  ★AM≠BF
  漏水探测·汇流排探测              ──→  贴纸 AO（手册42）
  列头末端·油机市电·UPS旁路·机柜PUE ──→  贴纸 AW/AF/AS/BC
  备件仪表入库准用                ──→  贴纸 AD（手册31）
  机柜·汇流排·设备外壳·测点台账    ──→  贴纸 BF-地（本篇）
  联接螺栓·跨接线·等电位带·周期窗  ──→  贴纸 BF-等（本篇）
  机房侧/配电侧SPD与接地/等电位边界──→  贴纸 BF-涌（本篇；勾清分工；尤其AM≠BF）
```

---

## 7. 台账卡模板（《本网机房接地与等电位浪涌保护巡检交底台账卡》）

```text
╔══════════════════════════════════════════════════╗
║ 《本网机房接地与等电位浪涌保护巡检交底台账卡》·教学 ║
║ 贴纸：BF（地/等/涌/验/治）  相对期号：________   ║
║ 脱敏机房角色：________                            ║
╠══════════════════════════════════════════════════╣
║ 【地】机柜□ 汇流排/测点□ 设备外壳□ 等电位角色指针□ ║
║       棒在≠台账过□ 禁口头接地正常□ AM≠本机房内□ ║
║ 【等】主人________ 窗________ 方法/准用期________ ║
║       联接螺栓□ 跨接线□ 等电位带□ 周期窗□ AD指针□ ║
║       看着连着≠窗过□ 禁口头连过□                  ║
║ 【涌】边界窗________ 到场________                 ║
║       方法摘要（不写旁路SPD/拆跨接/带电违章步骤）________║
║       机房侧/配电侧SPD角色□                       ║
║       禁旁路SPD□ 禁拆跨接□ 禁带电违章□ 禁伪造表□ ║
║       AM/AO/AW/AF/AS/BC/AN/N分工勾清□ AD号________ ║
║ 【验】本期实测□ 禁套声明□ 会签________            ║
║       结论：□准用 □有条件整改 □拒签               ║
║ 【治/界】AM≠BF□ AO≠BF□ AW≠BF□ AF≠BF□ AS≠BF□ BC≠BF□ ║
║         AD≠本期窗□ AN≠交底□ N绿≠BF□ 环境侧不顶替□ ║
║         假绿挂R□ 风暴挂N□ 变更走J□ L3□           ║
║ 不适用：□无机房等电位路径或无机房侧SPD路径（书面） ║
╚══════════════════════════════════════════════════╝
```

> 使用说明：本卡挂插页 BF1–BF8；门限与顺序以本网制度、合同与 OEM 书面为准；**不在卡上填写可还原门限全文与真实汇流排/SPD/跨接编号全文**；无机房等电位路径或无机房侧SPD路径站点勾「不适用」，不得用本卡顶 AM，也不得用 AM 顶本卡。

### 7.1 台账卡填写口诀（教学）

> **地先账，等先窗，涌先法，验本期，治拒假绿。** 缺一格就停；会签才放。**AM≠BF 必须勾。**

### 7.2 拒签后允许做什么（白名单）

允许：补机房接地台账、补等电位窗、重开SPD边界窗、本期重测、挂 R/N、走 J、内部整改、L3 脱敏重发。  
禁止：假绿放行、用 AM/AO/AW/AD/N 顶替、套他站他期表、旁路SPD、拆跨接冒充、不安全带电违章、抬功率压告警、公开可还原汇流排/SPD编号。

---

## 8. 术语表（本篇约 18 词）+ 易错观念

| 术语 | 本篇用法（教学） |
|------|------------------|
| **机房接地台账** | 机柜/汇流排/设备外壳/等电位联接角色·测点入账；BF-地；**≠ AM 天馈侧台账** |
| **等电位联接** | Equipotential bonding；联接螺栓/跨接线/等电位带；有主有窗有方法 |
| **跨接线 / 联接螺栓** | Bonding jumper / bonding fastener；**看着连着≠窗过**；**禁拆跨接冒充** |
| **等电位带 / 汇流排** | Equipotential bar / ground bar；角色入账；编号脱敏 |
| **机房侧/配电侧 SPD** | Facility / distribution SPD；**≠ AM 天馈侧 SPD**；绿灯≠本期过 |
| **浪涌保护器（SPD）** | Surge Protective Device；有边界窗与方法；**禁旁路SPD** |
| **接地棒在** | 仅目视存在；**≠ 机房接地台账过、≠ 准用** |
| **假绿** | 无实测/无会签却显示通过；挂 R；≠ 放行 |
| **套票** | 套他站他期接地/等电位/SPD表；BF-验 拒签 |
| **旁路SPD** | 旁路浪涌保护器冒充可过；**本篇硬禁** |
| **拆跨接冒充** | 拆跨接线冒充已连好/已测过；**本篇硬禁** |
| **不安全带电违章** | 未授权不安全带电作业冒充可过；**本篇硬禁** |
| **功率战** | 用抬功率压接地/SPD告警；**禁**；先挂 N |
| **贴纸 BF** | 本篇主贴；地/等/涌/验/治五子类 |
| **AM ≠ BF** | 天馈接地浪涌 ≠ 机房接地等电位/机房侧SPD准用 |
| **AO ≠ BF** | 漏水探测 ≠ 等电位准用 |
| **AW ≠ BF** | 列头末端供电 ≠ 等电位过 |
| **AD ≠ BF** | 备件入库 ≠ 本期等电位/SPD窗 |
| **N ≠ BF** | 风暴秩序 ≠ 本期实测 |
| **脱敏 L3** | 禁真实站名/机房全称/汇流排·SPD·跨接编号全文/联系人 |

**易错观念（纠一次）**  
- 「接地棒在 = 准用」→ 错；要 BF-地台账 + 本期实测。  
- 「看着连着 / 口头连过 / 口头接地正常 = 窗过」→ 错；要 BF-等 主人窗方法。  
- 「SPD绿灯 = 本期过」→ 错；要 BF-涌边界方法 + BF-验。  
- 「AM 过 = BF 过」→ 错；天馈侧 ≠ 机房内。  
- 「AO 过 = 等电位过」→ 错；漏水 ≠ 等电位准用。  
- 「AW/AF/AS/BC 过 = 等电位过」→ 错；供电 ≠ 等电位。  
- 「AD 入库签 = 本期窗过」→ 错；备件入库 ≠ 本期等电位/SPD窗。  
- 「N 绿 = 本期实测过」→ 错；风暴绿 ≠ 交底准用。  
- 「旁路SPD / 拆跨接消告警 = 办法」→ 错；硬禁。  
- 「抬功率压SPD告警 = 救急」→ 错；禁功率战。

---

## 9. 自测（12 题）+ 参考答案

1. 贴纸 BF 五个子类是什么？口诀是哪一句？  
2. 「接地棒在就能签」违反哪条硬规则？属哪个子类？  
3. 八条硬规则里，哪一条要求等电位联接有主有窗有方法/准用期？  
4. AM 天馈接地浪涌过了，能不能顶本期 BF？为什么？  
5. AO 漏水过了，能不能免等电位准用？AW 列头末端过了呢？  
6. N 监控绿，能不能免本期接地/等电位/SPD实测？  
7. 套邻站接地/等电位/SPD表改机房号，应如何处置？  
8. 雷击/SPD告警时，能不能先抬功率？应挂什么？天馈侧还问谁？  
9. 「旁路SPD消告警后再签」允许吗？拆跨接冒充呢？带电拧螺栓呢？  
10. AD 备件入库签还在，能不能免本期等电位/SPD窗？AF/AS/BC 供电过了呢？  
11. 本站无机房等电位路径，BF 怎么处理？假绿放行应挂什么？主贴还是不是 BF？  
12. 弱项短补：DMR 信道宽、调制、时隙各是什么？告警窗禁什么？

### 参考答案

1. 地 / 等 / 涌 / 验 / 治；口诀：**接地有账，等电位有窗，浪涌有法，会签才放。**  
2. 规则1（机房接地台账钉死）；属 **BF-地**。  
3. 规则2。  
4. **不能**。AM ≠ BF；天馈侧接地浪涌过 ≠ 机房内接地与等电位/机房侧SPD过。  
5. **不能**。AO ≠ BF（漏水 ≠ 等电位准用）；AW ≠ BF（供电 ≠ 等电位）。  
6. **不能**。N 绿 ≠ BF 过；要有本期实测与会签。  
7. **BF-验 拒签重测**；禁套他站他期。  
8. **不能**抬功率；先挂 **N** 理风暴；缺秩序整改贴 **BF**；天馈侧另问 **AM**；**禁功率战**。  
9. **不允许**；禁旁路SPD；禁拆跨接冒充；禁不安全带电违章；挂 N/R，禁签准用。  
10. **不能**；AD 只支撑仪表/备件准用，不顶本期 BF 窗；AF/AS/BC ≠ BF，供电过 ≠ 等电位过。  
11. 书面勾「不适用」；不得用 BF 顶 AM，也不得用 AM 顶 BF。假绿挂 **R**；主贴仍 **BF**。  
12. **12.5 kHz** / **4FSK** / **2-slot TDMA**；告警窗 **禁功率战**。

---

## 10. 加深阅读与视频（均已用 curl / oEmbed 核对；以核验当时为准）

**本篇专项方法级阅读（机房接地 / 等电位联接 / 浪涌保护 SPD；借秩序，不替代本网 BF 签字；不教旁路SPD、不教拆跨接冒充、不教不安全带电违章）**  
1. **[Wikipedia · Equipotential bonding](https://en.wikipedia.org/wiki/Equipotential_bonding)**——等电位联接公开词条（借「等电位有联接秩序、看着连着≠合格」直觉；**不是**本网 BF 法定制度；**不发明条款号**）。  
2. **[Wikipedia · Earthing system](https://en.wikipedia.org/wiki/Earthing_system)**——接地系统公开词条（借「接地有系统、有测点角色」；**接地棒在≠台账过**）。  
3. **[Wikipedia · Surge protector](https://en.wikipedia.org/wiki/Surge_protector)** · **[Surge arrester](https://en.wikipedia.org/wiki/Surge_arrester)**——浪涌保护器 / 避雷器公开词条（借「SPD有分层、有维护秩序」；**绿灯≠本期过**；**禁旁路SPD**）。  
4. **[Wikipedia · Ground (electricity)](https://en.wikipedia.org/wiki/Ground_(electricity))** · **[Electrical bonding](https://en.wikipedia.org/wiki/Electrical_bonding)**——接地 / 电气联接公开词条（借「bonding 有跨接角色」；**口头连过≠窗过**；**禁拆跨接冒充**）。  
5. **[Wikipedia · Lightning](https://en.wikipedia.org/wiki/Lightning)** · **[Electromagnetic compatibility](https://en.wikipedia.org/wiki/Electromagnetic_compatibility)** · **[Residual-current device](https://en.wikipedia.org/wiki/Residual-current_device)** · **[Faraday cage](https://en.wikipedia.org/wiki/Faraday_cage)**——雷电 / EMC / 剩余电流 / 法拉第笼公开词条（借「浪涌与等电位有边界直觉」；对照 **AM≠BF**）。  
6. **[HSM University · Grounding, bonding, lightning and surge protection（数据中心配电课公开页）](https://www.hsmuniversity.org/us/course/dce-310-data-center-power-distribution/lesson-9-grounding-bonding-lightning-and-surge-protection)**——数据中心接地/联接/浪涌公开课页（借「机房有接地与SPD分层」；门限以本网书面为准；**不教旁路SPD/拆跨接/带电违章**）。  
7. **[DMR Association · Standards](https://www.dmrassociation.org/dmr-standards.html)** · **[首页](https://www.dmrassociation.org/)**——空中接口标准入口（**不规定**机房接地等电位台账）。  
8. **[Tait Radio Academy](https://www.taitradioacademy.com/)** · **[Hytera](https://www.hytera.com/)** · **[Motorola Solutions](https://www.motorolasolutions.com/)** · **[Sepura](https://www.sepura.com/)**——专网厂商公开入口。  
9. **[SRRC 公开入口](https://www.srrc.org.cn/)**——无线电型号核准公开入口（台站设备秩序指针；**不替代**本网 BF）。  
10. **[Schneider Electric · Data Centers 公开解决方案入口](https://www.schneider-electric.com/en/work/solutions/for-business/s4/data-center-and-networks-data-centers/)**——数据中心公开入口（借「机房供电与环境有分层」；机房接地等电位专项仍 BF；天馈侧回 AM）。  

**故事类比：医院手术室/ICU 等电位联接 / 数据中心 equipment bonding / facility SPD（只借直觉，不是台站法定依据）**  
11. **[Wikipedia · Operating room](https://en.wikipedia.org/wiki/Operating_room)** · **[Intensive care unit](https://en.wikipedia.org/wiki/Intensive_care_unit)** · **[Data center](https://en.wikipedia.org/wiki/Data_center)**——手术室/ICU/数据中心直觉（借「棒在≠准用、看着连着≠窗过、口头接地正常≠方法过、SPD绿灯≠本期过、AM过≠BF过、AO过≠BF过、AW过≠BF过、AD过≠本期窗过、N绿≠BF过」）。  
12. Wikipedia：[Digital mobile radio](https://en.wikipedia.org/wiki/Digital_mobile_radio) · [Land mobile radio system](https://en.wikipedia.org/wiki/Land_mobile_radio_system) · [Noise floor](https://en.wikipedia.org/wiki/Noise_floor)。

**国内无线电法规（台站秩序指针；无账乱签机房接地等电位不是法外）**  
13. **[《中华人民共和国无线电管理条例》（中国政府网）](https://www.gov.cn/zhengce/zhengceku/2016-11/25/content_5137687.htm)** · **[国务院公报版](https://www.gov.cn/gongbao/content/2016/content_5148745.htm)**。  
14. **[《无线电频率使用许可管理办法》（中国政府网）](https://www.gov.cn/zhengce/2022-08/23/content_5722706.htm)**。  
15. **[《地面无线电台（站）管理规定》（中国政府网）](https://www.gov.cn/zhengce/202310/content_6908889.htm)** · **[国务院公报 · 工信部令第60号](https://www.gov.cn/gongbao/content/2023/content_5745291.htm)**。

**ITU / 验收方法级**  
16. **[ITU-R SM.1753](https://www.itu.int/rec/R-REC-SM.1753/en)**。  
17. **[P25 Best Practice · Field Acceptance Tests](https://www.p25bestpractice.com/implementing/field-acceptance-tests/)** · **[Flowdit · SAT](https://flowdit.com/site-acceptance-test/)**——到站/现场合格与公开入口（合格步骤≠假绿）。

**视频（YouTube，已用 oEmbed 核验标题与频道）**  
18. **[Telco Grounding and Bonding Best Practices Explained](https://www.youtube.com/watch?v=20h-SJRalbM)**——电信接地与联接公开片（借「接地与bonding有巡检秩序」；**不是** BF 台账专项；**不教旁路SPD/拆跨接/带电违章**）。  
19. **[Panduit · 5 Steps to Implementing a Grounding and Bonding System](https://www.youtube.com/watch?v=KR5N1_xGA8k)**——接地与联接五步公开片（借「机柜/跨接/汇流排有联接角色」；**看着连着≠窗过**；门限以本网书面为准）。  
20. **[Basics of Lightning Protection and Earthing/Grounding | IEC 62305](https://www.youtube.com/watch?v=obkUNBH1xnY)**——防雷与接地公开片（借「外部防雷与内部SPD/等电位有分层」；**对照 AM≠BF**：外部/天馈侧直觉回 AM，机房内回 BF）。  
21. **[SPD – Surge Protective Devices – What Are They / How They Work](https://www.youtube.com/watch?v=CCZJ0CPOR2U)**——SPD 是什么/怎么工作公开片（借「SPD有类型与分流直觉」；**绿灯≠本期过**；**禁旁路SPD**；**不是** BF 台账专项）。  
22. **[A detailed look into the functionality of Surge Protection Devices](https://www.youtube.com/watch?v=33XBMj9jHHc)**——SPD 功能详解公开片（借「SPD限制过电压」；安装与门限以本网与 OEM 书面为准；**不教旁路**）。  
23. **[SPD Typ 1, Typ 2 und Typ 3 erklärt](https://www.youtube.com/watch?v=AfNUT8_epG8)**——SPD 类型分层公开片（借「SPD有分层」；机房侧/配电侧角色回 BF；天馈侧回 AM）。  
24. **[MPSCS · Site Maintenance Inspection and Preventative Maintenance](https://www.youtube.com/watch?v=4IRdxeXN1do)**——站点维护与记录（借「要巡要记」）。  
25. **[Engineered Vision · FAT and SAT Explained](https://www.youtube.com/watch?v=x7qNC6Rtp9I)** · **[Careers360 · FAT & SAT](https://www.youtube.com/watch?v=3aafLF9o0NA)**——出厂/到站合格直觉（回指：假绿≠会签）。  
26. **[Scanner School · What is DMR?](https://www.youtube.com/watch?v=aQX_JbTbXuY)**（弱项：时隙与数字话音）。  
27. **[Rohde & Schwarz · Understanding Spectrum Analyzers – ACLR](https://www.youtube.com/watch?v=mco_BJ1mjNo)**——频谱仪直觉；对照禁功率战。  
28. **[NATEsafety · How to Conduct Tower Inspections](https://www.youtube.com/watch?v=dFs4At6-hhU)** · **[Sunil Kashyap · How to perform site audit or RF audit](https://www.youtube.com/watch?v=7Awj0-rDfeA)**——巡检/审计通用视频（借「要巡要记」；**不是**旁路SPD/拆跨接/带电违章教条；塔侧接地直觉对照 AM，机房内对照 BF）。  
29. **[The Engineering Mindset · Data Center HVAC](https://www.youtube.com/watch?v=xBxyhxmhigc)** · **[Fundamentals of HVAC](https://www.youtube.com/watch?v=klggop60vlM)**——数据中心/HVAC 公开片（借「机房有分层交底」；接地等电位专项仍 BF）。

> **诚实说明**：没有找到「DMR 专网机房接地与等电位浪涌保护巡检交底台账（含贴纸 BF + 插页 BF1–BF8 + 医院手术室/ICU 或数据中心 equipment bonding / facility SPD 隐喻 + 拒签卡 + 与 AM/AO/AW/AD/N 分工 + AM≠BF）」的专项中文公开视频或制度文章；最贴题的是 **Wikipedia Equipotential bonding / Earthing system / Surge protector / Ground / Electrical bonding**、**HSM University 数据中心接地浪涌公开课页**、**Telco Grounding and Bonding + Panduit 5 Steps + IEC 62305 Lightning/Earthing + SPD How They Work + SPD functionality + SPD Typ1/2/3** 公开片，以及站点维护/FAT-SAT/DMR 基础视频。其余为国内无线电法规与 DMR/ITU 入口。需按贴纸 BF 与 BF1–BF8 拼进本网流程。`video_found=true`（电信接地联接片 + 接地联接五步片 + 防雷接地片 + SPD工作原理片 + SPD功能片 + SPD类型片 + 通用巡检/FAT-SAT/DMR），**非** BF 台账专项。部分厂商 SPD 产品子路径返回 403/重定向失败，本篇以已 200/oEmbed 通过的链接为准。任何「教旁路SPD / 拆跨接冒充 / 不安全带电违章 / 伪造接地等电位台账 / 抬功率压告警」的页面即使 200，本篇也**不引用**。

**库内必回：** 手册40（AM）、42（AO）、50（AW）、33（AF）、46（AS）、56（BC）、31（AD）、41（AN）、28（AA）、15（N）、44（AQ）、58（BE）、57（BD）、47（AT）、36（AI）、51（AX）、52（AY）、53（AZ）、48（AU）、55（BB）、54（BA）、49（AV）、45（AR）、34（AG）、43（AP）、37（AJ）、38（AK）、35（AH）、39（AL）、19（R）、06（脱敏）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子
- 贴纸 **BF** 五子类：地 / 等 / 涌 / 验 / 治——双字母续写在 BE 之后的第一张 **BF**，负责机房接地与等电位浪涌保护「台账清不清、等电位有没有窗、浪涌边界有没有法、本期过了没有」。  
- 口诀：**接地有账，等电位有窗，浪涌有法，会签才放。**  
- 故事：医院手术室/ICU 等电位联接与机房浪涌保护巡检（或数据中心 equipment bonding / equipotential bonding / facility SPD / ground bar）——棒在≠准用；看着连着≠窗过；口头接地正常≠方法过；SPD绿灯≠本期过。  
- 八条硬规则：**机房接地台账钉死**；**等电位联接有主有窗有方法/准用期**；**机房SPD与接地/等电位边界窗与方法钉死**；**本期实测禁套**；**会签才放行**；**禁顶替 AM/AO/AW/AF/AS/BC/AD/AN/AA/N/AQ/BE/BD/…，主贴 BF，假绿≠放行挂 R**；**异常风暴挂 N、变更走 J、禁功率战/旁路SPD/拆跨接冒充/不安全带电违章/伪造台账**；**脱敏 L3**。  
- **BF 不替代 AM，也不替代 AO，也不替代 AW，也不替代 AD，也不替代 N**：AM=天馈接地浪涌；AO=漏水汇排探测；AW/AF/AS/BC=供电链；AD=备件仪表准用；BF=机房接地与等电位/机房侧SPD准用。**AM ≠ BF；AO ≠ BF；AW ≠ BF；AD ≠ BF；N ≠ BF。**

### 11.2 下一篇手册候选（本篇不写正文）
- **机房精密空调过滤器压差与滤网更换专项交底台账**（与 AU 滤网压差气流、AI 温湿度、AD 备件、N 监控、AN 门禁咬合；适用于要单独钉滤网更换窗与压差准用的站点）  
- **机房冷却水泵组与冷凝水侧交底台账**（与 BA 冷冻水冷却塔、BD 冷冻水泵组定压补水、AO 漏水、AT 冷凝加湿、N 监控咬合；适用于要单独钉冷却水泵与冷凝水侧秩序的站点）  
- **机房柴油发电机日用/储油罐油位与泄漏巡检交底台账**（与 AF 油机市电、AV 油品净化加油、AR 油机房通风燃油、N 监控、AN 门禁咬合；适用于要单独钉油位/泄漏巡检秩序的站点）

### 11.3 给带新人的三句话
1. 机房接地不是棒在就能签：接地有账，本期核对钉死；**AM天馈侧≠本机房内**。  
2. 等电位不是看着连着就算过、浪涌不是绿灯就算过：主人窗方法准用期，边界书面方法，本期实测会签才算准用；禁旁路SPD、禁拆跨接冒充、禁不安全带电违章。  
3. 假绿挂 R；主贴 BF；AM/AO/AW/AD/N 不顶替；异常窗禁功率战禁旁路SPD；公开脱敏 L3。

### 11.4 一张图记住本篇（收工贴纸）
```text
  ┌────────── 贴纸 BF ──────────┐
  │ 地 机房接地台账钉死         │
  │ 等 等电位有主有窗有方法     │
  │ 涌 SPD边界窗·方法钉死       │
  │ 验 本期实测·禁套·会签       │
  │ 治 假绿顶替套票旁路SPD拆跨接功率战 │
  └────────────────────────────┘
    棒在≠准用 · 看着连着≠窗过 · 口头接地正常≠方法过 · SPD绿灯≠本期过 · 假绿≠准用
    AM≠BF（天馈接地浪涌 ≠ 机房接地等电位/机房侧SPD）
    AO≠BF（漏水 ≠ 等电位准用）
    AW≠BF（列头末端 ≠ 等电位）
    AF≠BF（油机市电 ≠ 等电位）
    AS≠BF（UPS旁路 ≠ 等电位；≠旁路SPD）
    BC≠BF（机柜PUE ≠ 等电位）
    AD≠BF（备件入库 ≠ 本期等电位/SPD窗）
    N≠BF（风暴秩序 ≠ 本期实测）
    BE≠BF（水质换罐 ≠ 接地等电位）
```

---

## 12. 本篇检查清单（自学打勾）
- [ ] 能背贴纸 BF 五子类与医院手术室/ICU 等电位联接或数据中心 equipment bonding / facility SPD / ground bar 故事  
- [ ] 能背口诀：接地有账，等电位有窗，浪涌有法，会签才放  
- [ ] 能背八条硬规则（机房接地台账钉死、等电位有主窗方法、SPD边界窗方法、本期实测、会签才放、禁顶替假绿挂R、禁功率战禁旁路SPD禁拆跨接禁带电违章挂N走J、L3）  
- [ ] 能分清 BF 与 AM / AO / AW / AF / AS / BC / AD / AN / N / BE / R / J 边界；尤其 **AM≠BF、AO≠BF、AW≠BF、AD≠BF、N≠BF**  
- [ ] 会填插页 BF1–BF8 与台账卡封面/地/等/涌/验/会签页  
- [ ] 会用拒签卡卡住无账、套票、顶替、假绿、旁路SPD、拆跨接冒充  
- [ ] 自测 12 题过关；知道 video_found=true 但是非 BF 台账专项  
- [ ] 回库用 L3 对一遍最近一次机房接地与等电位浪涌保护交底：台账、窗、方法、本期实测、会签、拒签项（无路径则勾不适用）  
- [ ] 弱项短补记得：12.5 kHz / 4FSK / 2-slot TDMA；告警窗禁功率战  
- [ ] 知道下一篇三个候选（精密空调过滤器压差与滤网更换 / 冷却水泵组与冷凝水侧 / 柴油发电机油位与泄漏巡检）尚未写正文  

---

*手册59 · 贴纸 BF · 2026-11-07 早间推送（Asia/Shanghai）· 教学用 · L3*
