<!-- 手册11 投递 part3/3：§8–§12（术语·自测·外链·收束·检查清单） -->
> 上文：part1（§1–§3）+ part2（§4–§7）。本段收官。

## 8. 术语表（本篇约 28 词）+ 易错观念

| # | 术语 | 白话 | 易错 |
|---|------|------|------|
| 1 | 写频 / CPS | 用电脑读写电台配置的窗口与软件 | ≠ 随便改就能上线 |
| 2 | Codeplug | 机内配置「整本书」 | ≠ 可跨机型通刷 |
| 3 | 读出 / Read | 先把机内书拷出来 | 跳过=事故 |
| 4 | 写入 / Write | 把文件刷进机器 | 成功弹窗≠验证完成 |
| 5 | 备份 | 可打开、可回滚的上一版文件 | ≠ 「我记得」 |
| 6 | 现服 | 当前认可的配置版本 | 要与档案一致 |
| 7 | 上一版 | 书柜储备本 | 删了就无法回滚 |
| 8 | 金机 | 有档案的已知良好样机 | ≠ 随便好机 |
| 9 | 金机基线 | 档案号+日期+摘要+验证 | 会漂移 |
| 10 | 变更单 | 谁改什么的授权纸 | 「临时」也要单 |
| 11 | Hangtime | 通话后信道保持类定时 | 乱拧≠覆盖补丁 |
| 12 | 队列超时 | 排队/等待相关配置 | 改前要范围与回滚 |
| 13 | CC / 色码 | 身份门牌气质参数 | 写错→手册07 身份层气质 |
| 14 | 时隙 | 30 ms 两槽之一 | 写错→Grant有声类故障 |
| 15 | 鉴权相关参数 | 与鉴权开关/算法选择相关的配置类 | 写错→手册05 气质 |
| 16 | 样机验证 | 批量前的先写先验 | 不可用另一草稿顶替 |
| 17 | 回滚 | 刷回上一版并重验 | 失败稿上拧≠回滚 |
| 18 | 版本保留 N | 至少现服+若干历史 | N 由本网定 |
| 19 | 跨机型互写 | 不同机型文件通刷 | **禁止** |
| 20 | CPS 匹配 | 软件与机型/文件世代一致 | 不匹配就拒写 |
| 21 | 脱敏 L3 | 教学/公开去标识 | 禁真实频点个号密钥 |
| 22 | 贴纸 J | 写频/基线总类 | 须子类+证据 |
| 23 | J-备/基/变/验/回 | 五子类 | 可主+次 |
| 24 | 插页 J | R1–R8 证据页 | 无备份则弱 |
| 25 | 手册08 闭环 | 刺激→观察→判定→证据包 | 本篇只调用 |
| 26 | CM-2(3) 精神 | 保留先前配置以支持回滚 | **不背条款当 ETSI** |
| 27 | 文件哈希/标识 | 证明样机与批量同一文件 | 换草稿要重验 |
| 28 | 双钥匙直觉 | 写入与回滚确认可分离 | 不是真要两把金属钥匙 |

**易错观念十条**：

1. 「Write 成功 = 变更完成」→ 缺验证就不算完成。  
2. 「金机 = 能开机的好机」→ 要档案与验证。  
3. 「备份在微信里发过」→ 要可打开可回滚的归档。  
4. 「机型差不多可以通刷」→ 禁止。  
5. 「验失败再调调更快」→ 必须先回滚再新开单。  
6. 「Hangtime 拧大能治覆盖」→ 否；挂手册07/09。  
7. 「加功率顶写频事故」→ 禁止掩盖。  
8. 「历史版本占空间，删光」→ 书柜空了无法回滚。  
9. 「临时改不用开单」→ 临时最容易变永久债务。  
10. 「实验室 G 过就可以无视写频单」→ 现场批量文件可能不是同一哈希。

---

## 9. 自测（10 题）+ 参考答案

**题 1.** 贴纸 J 五个子类各用一句话说明；各举一个拒写/拒放行触发。

**题 2.** 为什么「空白 CPS 窗口直接 Write」是事故？正确顺序是什么？

**题 3.** 金机基线最低要有哪些字段？为什么「值班室能开机的那台」不够？

**题 4.** 「写后未验证 = 变更未完成」——验证最小包包含哪三类业务证明？

**题 5.** 验证失败时为什么必须回滚，而不是在失败稿上连续改？

**题 6.** 插页 J 的 R3、R4、R5、R6 各挡住哪种胡说？

**题 7.** 跨机型 codeplug 互写为什么禁止？写出后可能挂到哪些旧手册症状？

**题 8.** 如何用「图书馆版本卡」向新人解释「现服 / 上一版 / 草稿区」？

**题 9.** 手册08 金机对照与本篇 J-基 的关系？金机漂移时先做什么？

**题 10.** 列出封面拒写门槛至少五条（与 §7.1 对齐）。

### 参考答案

1. **J-备**读出备份；**J-基**金机档案制度；**J-变**变更单范围审批；**J-验**写后闭环验证；**J-回**失败回滚与版本保留。触发例：无备份；金机无档案；无单；未验要批量；上一版打不开。  
2. 空白写会覆盖机内唯一配置且无回滚源。顺序：Read→Save As→变更单→Edit→样机 Write→验证→过再批量。  
3. 档案号、日期、配置摘要、验证记录（及存放/上一版指针）。能开机≠已知良好未漂移。  
4. 登记（或等价附着）、Grant 有声、上下行可达；证据进包。  
5. 失败稿连续拧制造不可审计漂移；先回滚证明能回到绿，再新开单。  
6. R3 挡「无备份」；R4 挡「假金机」；R5 挡「无审批/跨机型」；R6 挡「写完不验」。  
7. 字段/能力不兼容，制造系统性幽灵故障；常表现为手册01 登记、02 Grant 无声、05 鉴权等气质。  
8. 现服=架上在用的书；上一版=柜台储备；草稿=编辑室未上架；新书没验完旧书不许扔。  
9. J-基 提供档案锚；手册08 用该锚做对照。漂移：隔离资格→上一版重刷→重验授牌。  
10. 无备份；无变更单/审批；跨机型；金机无档案/过期；未验要批量；拒回滚/上一版不可开；加功率或乱拧 Hangtime 掩盖；脱敏失败（答出≥5 条即可）。

---

## 10. 加深阅读与视频（均已用 curl 核对 HTTP 200；视频用 YouTube oEmbed 核对存在）

1. **[DMRhub · Codeplug backup: how not to lose your radio settings](https://dmrhub.ru/tech/en/bekap-codeplug)**  
   - 先读后存、命名与异地副本气质；对本篇 J-备 最直接。  
2. **[BridgeCom · How to Duplicate or Export the Codeplug on your DMR Radio](https://www.bridgecomsystems.com/blogs/bridgecom-official-blog/how-to-duplicate-or-export-the-codeplug-on-your-dmr-radio)**  
   - 复制/导出 codeplug 的操作气质（业余实践；专网按其 CPS 流程落地）。  
3. **[BTECH · Build a DMR 6X2 Code Plug（基础 codeplug 搭建）](https://baofengtech.com/build-a-dmr-6x2-code-plug-a-basic-code-plug-for-your-dmr-radio/)**  
   - 信道/区域/联系人等结构入门；提醒「结构懂了仍要备份与验证」。  
4. **[MO Digital Group · DMR Code Plugs Demystified（PDF）](https://modigitalgroup.org/wp-content/uploads/2025/02/DMR-Code-Plugs-Demystified-20250213.pdf)**  
   - Codeplug 概念拆解；适合写「配置摘要」字段时建立词汇。  
5. **[Amateur Radio Notes · Discovering DMR-3（PDF）](https://amateurradionotes.com/images2/12-dmr-3.pdf)**  
   - DMR 写频与实践笔记补充；当故事参考，**不当 ETSI 条文**。  
6. **[Motorola Solutions · APX Radio Management Fact Sheet（PDF）](https://aem-cloud-prod-cdn.motorolasolutions.com/content/dam/msi/docs/business/product_lines/apx/documents/apx_radio_management_fact_sheet.pdf)**  
   - 商用电台配置/车队管理产品气质：版本、仓库、部署——对照本篇「现服/上一版」制度，**不绑定品牌强制**。  
7. **[CSF Tools · NIST SP 800-53 Rev.5 CM-2(3) Retention of Previous Configurations](https://csf.tools/reference/nist-sp-800-53/r5/cm/cm-2/cm-2-3/)**  
   - 「保留先前配置以支持回滚」公开解释入口；**只借精神，不背条款当 ETSI**。  
8. **[ATO Pathways · NIST SP 800-53 CM-2.3 条目页](https://ato-pathways.com/catalogs/oscal/catalogs/NIST_SP-800-53_rev5_catalog:latest/items/cm-2.3)**  
   - 同上控制项的另一公开目录视图。  
9. **[NIST SP 800-53 Rev.5 全文（PDF）](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf)**  
   - 配置管理章节对照阅读；本篇不要求背诵。  
10. **[GSA · Configuration Management (CM) 政策 PDF](https://www.gsa.gov/system/files/Configuration-Management-%28CM%29-%5BCIO-IT-Security-01-05-Rev-6%5D.pdf)**  
    - 政府机构 CM 制度样例气质：基线、变更、记录。  
11. **[HCI ITIL · Service Transition · Configuration Management 章节](https://www.hci-itil.com/ITIL_v3/books/3_service_transition/service_transition_ch4_3.html)**  
    - ITIL 风基线/CI 直觉；把电台 codeplug 当成可配置项来管。  
12. **[Giva · ITIL Service Configuration Management / CMDB 基线介绍](https://www.givainc.com/resources/itil/service-configuration-management/)**  
    - 基线与配置库白话；辅助向领导解释「为什么要制度柜」。  
13. **[Wikipedia · Configuration management](https://en.wikipedia.org/wiki/Configuration_management)**  
    - CM 总览与术语地图。  
14. **[Scanner School · An Introduction to DMR](https://www.scannerschool.com/introduction-to-dmr/)**  
    - 双时隙与数字语音入门；提醒写频不改变 12.5 kHz/两槽物理。  
15. **[DMR Association · Key Benefits of DMR Technology](https://dmrassociation.org/dmr-key-benefits.html)**  
    - 官方白话：同带宽两路等；与弱项短补对齐。

**视频：**

16. **[How to Create a Digital Codeplug for Your Radio!（YouTube）](https://www.youtube.com/watch?v=ycoQc8SbKoY)**  
    - 数字 codeplug 创建入门（通用业余 CPS 气质，非专网回滚制度专项）。  
17. **[Amateur Radio & CPS Software A Beginner's Guide（YouTube）](https://www.youtube.com/watch?v=QOA_G7Q8hko)**  
    - CPS 软件新手向；配合本篇「先读后写」。  
18. **[Basic DMR Programming with RT Systems software（YouTube）](https://www.youtube.com/watch?v=w5xrH7urisU)**  
    - 第三方编程软件气质演示；强调仍要备份与机型匹配。  
19. **[Scanner School · What is DMR?（YouTube）](https://www.youtube.com/watch?v=aQX_JbTbXuY)**  
    - 双时隙入门；避免把写频事故说成「数字电台玄学」。  
20. **[Scanner School · Why Digital Radio Sounds Like Robots（YouTube）](https://www.youtube.com/watch?v=-hLiTz7oSKE)**  
    - 数字悬崖/BER 直觉；验证「有声」时的听感差别。

> **诚实说明**：没有找到「DMR 专网写频变更回滚与金机基线制度（含变更单 + 版本保留 + 金机档案 + 验失败强制回滚）」专项中文/公开视频教程；上面的视频分别讲 codeplug/CPS 入门与 DMR 基础，需要你自己按本篇贴纸 J 与插页 R1–R8 把它们拼进制度包。`video_found=true`（通用 CPS/codeplug 与 DMR 入门视频），非专项「DMR 写频变更回滚与金机基线制度」教程。

**库内必回：** `学习推送/手册06_日志三联单深化.md`（证据/脱敏）、`手册08_测试实验室最小闭环.md`（金机对照闭环）、`手册01_登记失败三问.md` / `手册02_Grant了没声.md` / `手册05_鉴权失败分诊.md`（坏写频症状指针）、`手册10_室分隧道覆盖交维清单.md`（I-交 金机基线存放）、`手册07_覆盖与同频干扰分诊.md` / `手册09_话务与容量分诊.md`（禁加功率/乱拧掩盖）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子

1. **写频有五张脸**：J-备 / J-基 / J-变 / J-验 / J-回。  
2. **先读后写**；无备份禁止写。  
3. **金机基线有档案**；不是随便好机。  
4. **写后未验证 = 变更未完成**。  
5. **验失败必须回滚**；再开新单。  
6. **书柜要有上一版**（CM-2(3) 精神，不背条款）。  
7. **禁跨机型互写**；禁加功率/乱拧 Hangtime 当补丁。  
8. **脱敏进仓**；公开材料去频点/个号/密钥。

### 11.2 回库路径

```text
总索引.md
  └─ 集群 / Tier III → 运维手册
       ├─ 手册01–05（A–E）06（总单）07（F）08（G）09（H）10（I）
       └─ 本篇手册11（贴纸J + 插页J + 写频变更回滚与金机基线制度卡）
            └─ 回：手册06–08、10 的 I-交、加餐弱项
```

### 11.3 下一篇手册候选（本篇不写正文）

- **基站电源与后备切换交维**（电源/油机/倒换引起的「假覆盖/假容量/假干扰」）。  
- **电梯井·地下车库专项**（手册10 I-覆 的加深专项册）。  
- **（可选）大批量写频作业与 OTAP/无线写频风险边界**（本篇 J 的批量与无线通道加深）。

### 11.4 给带新人的三句话

> 没备份、没变更单、没验证，就没有 Write。  
> 金机是带档案的校对样本，不是值班室碰巧能开机的那台。  
> 新书没验完，旧书不许扔；验失败先回滚。

### 11.5 运维一周里怎么用这篇（复印到周历）

```text
周一  默写 J 五子类 + 「无备份禁止写」卡
周二  抽查金机档案：过期？上一版可打开？
周三  对一次旧变更单：有无 R3 备份证明与 R6 验证表
周四  演练「验失败回滚」话术（对话 C）
周五  §6.5 对齐会；统计拒写/回滚单
```

### 11.6 和弱项加餐的衔接

把 12.5 kHz / 4FSK / 30 ms 两槽背熟，你才说得清「写频改的是账本，不是调制台阶」。有人要用写频加功率或乱拧 Hangtime 治覆盖/话务时，回加餐 + 手册07/09，而不是继续 Write。

### 11.7 一张图记住本篇（收工贴纸）

```text
        要改写频 / 动金机相关配置
                      │
          ┌───────────┴───────────┐
          │有变更单+审批？         │否 → 拒写（J-变）
          ▼
        读出并备份可打开？──否──▶ 拒写（J-备）
          │是
          ▼
        同机型且 CPS 匹配？──否──▶ 拒写（禁跨机型）
          │是
          ▼
        金机档案未过期？──否──▶ 先重锚（J-基）
          │是
          ▼
        样机写 + 验证（登记/有声/上下行）过？
          │否 ──▶ 回滚上一版（J-回）；关单；新开单
          │是
          ▼
        更新现服版本卡；旧现服入上一版架；再批量+抽检
        禁令：空白写；无验放行；失败不回滚；加功率/乱拧掩盖
```

---

## 12. 本篇检查清单（自学打勾）

- [ ] 能背 J 五子类并各举一个拒写/拒放行例子  
- [ ] 能画「图书馆版本卡」并指出现服/上一版/草稿区  
- [ ] 能背八条硬规则（先读后写……脱敏）  
- [ ] 能说明金机基线最低字段与漂移处置  
- [ ] 能拒绝「空白写 / 跨机型 / 无验批量 / 失败不回滚」  
- [ ] 会填插页 J 的 R1–R8  
- [ ] 会用 §7 封面拒写门槛 + 回滚剧本页做一次模拟变更  
- [ ] 知道验失败为何必须回滚再开新单  
- [ ] 知道本篇如何调用手册08 闭环、如何衔接手册10 I-交  
- [ ] 自测 10 题达标；回库重对至少 1 次写频/金机事件（L3）  
- [ ] 知道下一篇候选且**本篇未写它们的正文**  
- [ ] 外链打开过至少 3 个（含 1 个 codeplug 备份文 + 1 个 CM/基线文或 CPS 视频）

---

*推送说明：本篇为手册模式第 11 篇（非第 41 课）。主线是写频变更回滚与金机基线制度：贴纸 J 五子类、插页 J、图书馆版本卡故事、八条硬规则、现场映射、十例、制度卡模板、术语、自测与核验外链。硬禁令贯穿：不发明条款号、不写真实频点/个号/密钥/站名、不重写手册07/08/10 全文、禁跨机型互写、禁加功率/乱拧 Hangtime 掩盖、验失败必须回滚。读完应能向同事讲清「先证明能回滚再允许写、金机是带档案的校对样本、新书没验完旧书不许扔」。*
