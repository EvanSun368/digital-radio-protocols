<!-- 手册12 投递 part3/3：§8–§12 -->
> 上文：part1（§1–§3）、part2（§4–§7）。

## 8. 术语表（本篇约 30 词）+ 易错观念

| # | 词 | 一句话 | 易错 |
|---|----|--------|------|
| 1 | 市电 | 进户交流主供 | 有电压 ≠ 质量合格 |
| 2 | 整流 | 交流变直流并浮充电池 | 模块退出仍可能「有一点电」 |
| 3 | −48 V 直流厂 | 电信常见直流母线气质 | 极性/接地按本网规范，不发明 |
| 4 | 浮充 | 电池长期在线维持 | 浮充「看起来正常」≠ 能放电 |
| 5 | 蓄电池组 | 市电掉后的短桥 | 老化靠抽检，不靠名牌 |
| 6 | UPS | 不间断电源；双转换桥接气质 | 与油机兼容要联调 |
| 7 | 双转换 | 先整流再逆变，负载常吃逆变器 | 不是所有 UPS 都双转换 |
| 8 | 油机/柴油机 | 长时后备发电 | 有油机 ≠ 会自启 |
| 9 | 启动电池 | 专伺油机点火 | 与通信电池不是同一块 |
| 10 | ATS | 自动转换开关 | 要验切与回切 |
| 11 | 防误启延时 | 避免毛刺就启动油机 | 延时内闪断可能「不切油机」 |
| 12 | 回切 | 市电稳后回到主供 | 回切失败常被漏写 |
| 13 | 粘连 | 开关机构卡在某一侧 | 交维必须暴露 |
| 14 | walk-in | UPS 对油机缓加载气质 | 硬加载可能拒收 |
| 15 | 拒收油机 | UPS 判断油机 V/f 不合格 | 表现为反复电池放电 |
| 16 | N+1 整流 | 多一块冗余模块 | 无冗余时单模块退出即放电 |
| 17 | 低压断开 | 护电池的阈值气质 | 到点掉负载 = 「突然全死」 |
| 18 | 告警静音 | 铃不响 | 不等于消缺 |
| 19 | 倒换窗口 | 切/回切附近数十秒～数分钟 | 可出现假空口病 |
| 20 | 假覆盖 | 电源病外表像弱覆盖 | 禁加功率 |
| 21 | 假干扰 | 电源抖外表像同频 | 先对时 |
| 22 | 假容量 | 掉站造成话务假坏 | 先电源 |
| 23 | 贴纸 K | 电源/后备总类 | 须子类+证据 |
| 24 | 插页 K | R1–R8 | 无剧本则弱 |
| 25 | K-交 | 边界责任 | 口头不算 |
| 26 | 金机抽检 | 倒换后业务证明 | 调用 G，不重写 |
| 27 | 对时 | 电源日志与网管对齐 | 手册06 五要素 |
| 28 | 脱敏 L3 | 教学/公开仓 | 禁真实站名频点 |
| 29 | 带条件放行 | 非关键尾巴有时限责任人 | 倒换未演不可带条件 |
| 30 | 电源对齐会 | 周会抽插页 K 与反例 | 不等于已经交维 |

**易错观念（钉死）**：

- 「有市电电压」≠ 交维完成。  
- 「有油机」≠ 停电能活。  
- 「告警安静」≠ 健康。  
- 「倒换抖一下」≠ 先判同频。  
- 「加功率」≠ 电源药。

---

## 9. 自测（10 题）+ 参考答案

**题 1.** 贴纸 K 五个子类各用一句话说明；各举一个拒签/拒放行触发。  
**题 2.** 画出「ICU + 备用发电机」链：市电、整流、电池/UPS、油机、ATS、告警、交维边界各在哪。  
**题 3.** 八条硬规则默写（大意正确即可）。  
**题 4.** 为何「只测电压」必须拒签？R5 缺什么？  
**题 5.** 倒换顺序：先撑、再唤、后切、稳了再回——对应哪些设备？  
**题 6.** 插页 K 的 R1、R5、R6、R7 各挡住哪种胡说？  
**题 7.** 假覆盖 / 假干扰 / 假容量 各举一例电源真因；错误处置是什么？  
**题 8.** 倒换窗短时登记失败，为何主贴 K 而不是直接手册01 结案？  
**题 9.** 告警静音在什么条件下可以暂时存在？交维前要怎样？  
**题 10.** 下一篇候选你记住哪两个？本篇写了它们正文吗？

### 参考答案

1. K-市市电整流；K-备电池UPS油机；K-切倒换回切；K-告告警禁长期静音；K-交边界。触发见表 2.4。  
2. 见 §2.1 ASCII；告警=铃，交维=交接班清单。  
3. 见 §4.1 八条。  
4. 未证明切/回切与业务；R5 空。  
5. 撑=电池/UPS；唤=油机；切=ATS；回=回切市电。  
6. R1 挡「大概晚上」；R5 挡「电压OK就行」；R6 挡「直接协议玄学」；R7 挡「静音当消缺」。  
7. 欠压掉远端；倒换窗BER跳；多站间歇掉电。错：加功率/扫同频一周/加信道。  
8. 症状可挂01，主因在电源窗；先K后协议。  
9. 须时限+审批+责任人；交维前必须恢复铃并验证到达。  
10. 电梯井·地下车库专项；可选 OTAP/大批量写频等。**本篇未写正文。**

---

## 10. 加深阅读与视频（均已用 curl 核对 HTTP 200；视频用 YouTube oEmbed 核对存在）

1. **[Electronics Guide · Power Systems for Communications](https://www.electronicsguide.net/systems-and-technologies/communication-electronics/infrastructure-and-support-systems/power-systems-for-communications/)**  
   - 电信电源总览：−48 V、整流浮充、电压窗气质；对本篇 K-市/K-备 最直接。  
2. **[Telecom Wiki · DC Plants 工程指南（PDF，IA）](https://telecom.wiki/download/attachments/819658/790-100-654MP_IA.pdf)**  
   - 整流 N+1、充电因子等厂站工程直觉；**只借精神，不背条款当 ETSI**。  
3. **[Telecom Wiki · DC Power Plants（PDF，IB）](https://telecom.wiki/download/attachments/819658/790-100-654MP_IB.pdf)**  
   - 与上互补的整流冗余与维护备件气质。  
4. **[ITU-T · White Paper on Lithium Batteries for Telecom Sites（PDF）](https://www.itu.int/en/ITU-T/studygroups/2025-2028/05/Documents/Reports/2025-03-WhitePaper-LithiumBatteries-TelecomSites.pdf)**  
   - 电信站电池作为「能量守护」的公开白皮书；对照 K-备 安全与运维意识。  
5. **[Vertiv / Battcon · Telecommunications VRLA Battery Maintenance, Testing and Replacement（PDF）](https://www.vertiv.com/48dd3b/globalassets/documents/battcon-static-assets/2000/telecommunications---vrla-battery-maintenance-testing-and-replacement.pdf)**  
   - VRLA 维护与测试程序气质；提醒「浮充看起来正常 ≠ 能放电」。  
6. **[Wikipedia · Automatic transfer switch](https://en.wikipedia.org/wiki/Automatic_transfer_switch)**  
   - ATS 总览与术语地图。  
7. **[Wikipedia · Uninterruptible power supply](https://en.wikipedia.org/wiki/Uninterruptible_power_supply)**  
   - UPS 拓扑入门；对照双转换桥接直觉。  
8. **[Wikipedia · Rectifier](https://en.wikipedia.org/wiki/Rectifier)**  
   - 整流基础；帮助新人分清「交流入口」与「直流母线」。  
9. **[Wikipedia · Diesel generator](https://en.wikipedia.org/wiki/Diesel_generator)**  
   - 油机后备总览；配合「有油机 ≠ 会自启」。  
10. **[Wikipedia · VRLA battery](https://en.wikipedia.org/wiki/VRLA_battery)**  
    - 阀控铅酸电池术语；对照站用电池保养对话。  
11. **[Wikipedia · Float voltage](https://en.wikipedia.org/wiki/Float_voltage)**  
    - 浮充电压概念；避免「有浮充电压就当作满健康」。  
12. **[ZTA Power · How UPS and Diesel Generator Work Together（ATS 集成指南）](https://www.ztapower.com/blog/how-ups-and-diesel-generator-work-together-ats-wiring-system-integration-guide_b97)**  
    - 市电→UPS 桥接→油机→ATS 时序白话；对本篇剧本页最友好。  
13. **[EVICO · Double-Conversion UPS: Topology & Transfer Time](https://www.evicopower.com/blog/double-conversion-uninterruptible-power-supply/)**  
    - 双转换「近似零切换到电池」直觉；区分待机/在线互动型。  
14. **[PowerWadi · UPS Generator Compatibility](https://powerwadi.com/ups-generator-compatibility/)**  
    - UPS 拒收油机、walk-in、反复充放的现场compat 说明。  
15. **[Voltenertec · Standby Generator and UPS Coordination](https://voltenertec.com/en/standby-generator-ups-coordination-backup-time-en/)**  
    - 电池续航要覆盖「启动失败重试 + 拒收间隔」；对 K-备 续航谈话有用。  
16. **[NetEngineerLab · Generator + UPS Transfer & Ride-Through Planner](https://netengineerlab.com/tools/generator-ups-transfer-ride-through-planner/)**  
    - 把失电→桥接→启机→ATS→稳定变成可度量时间线；提醒不能替代现场剧本。  
17. **[Critical Energy · UPS, ATS and Generator: The Blackout Power Chain](https://critical-energy.net/ups-ats-generator-blackout-power-chain/)**  
    - 停电功率链总图气质；适合带新人。  
18. **[NFPA · An Overview of NFPA 110](https://www.nfpa.org/news-blogs-and-articles/blogs/2023/01/23/an-overview-of-nfpa-110)**  
    - 应急/备用电源标准公开概述；**只借「要测试、要转换设备」精神，不背条款当 ETSI**。  
19. **[Curtis Power · NFPA 110 Transfer Switch Equipment](https://www.curtispowersolutions.com/nfpa-110-transfer-switch-equipment)**  
    - 转换开关在应急电源里的角色白话。  
20. **[Cummins · Power Topic · Transfer Switch（PDF）](https://incal.cummins.com/www/literature/technicalpapers/PT-7016-P1-TransferSwitch-en.pdf)**  
    - 厂商技术文：转换开关与系统配合；作工程阅读，不绑定品牌强制。

**视频：**

21. **[Eaton PSEC · Automatic transfer switch (ATS) fundamentals（YouTube）](https://www.youtube.com/watch?v=yjphp4SBkSA)**  
    - ATS 监压、延时、切到油机、回切的标准讲解（通用电力，非 DMR 专项）。  
22. **[Generac automatic transfer switch explained, demo（YouTube）](https://www.youtube.com/watch?v=rT_3JYZS9Mg)**  
    - ATS 演示气质；帮助新人「看见」阀门动作。  
23. **[Scanner School · What is DMR?（YouTube）](https://www.youtube.com/watch?v=aQX_JbTbXuY)**  
    - 双时隙入门弱项补；提醒电源病不改变 12.5 kHz/两槽物理。  
24. **[Scanner School · Why Digital Radio Sounds Like Robots（YouTube）](https://www.youtube.com/watch?v=-hLiTz7oSKE)**  
    - 数字悬崖/BER 直觉；倒换窗「假干扰」听感对照。  
25. **[ABB · Automatic transfer switch technology & drives（PDF 技术说明）](https://library.e.abb.com/public/eb7aa78b2327401b9525fd28d46512a9/Technical_Note_178_AutomaticTransferSwitch_Technology_Drives.pdf)**  
    - ATS 技术说明补充阅读（文档，非视频；列入加深包）。  
26. **[DMR Association · Key Benefits of DMR Technology](https://dmrassociation.org/dmr-key-benefits.html)**  
    - 官方白话弱项补；与频谱短补对齐。  
27. **[Scanner School · An Introduction to DMR](https://www.scannerschool.com/introduction-to-dmr/)**  
    - 文文入门；避免把电源事故说成「数字电台玄学」。

> **诚实说明**：没有找到「DMR 专网站电源与后备切换交维（含市电→油机 ATS 剧本 + 假覆盖/假干扰/假容量分诊 + 插页拒签）」专项中文/公开视频教程；上面的视频与文档分别讲 ATS/UPS/油机协调、电信直流厂与电池维护、以及 DMR 基础，需要你自己按本篇贴纸 K 与插页 R1–R8 把它们拼进交维包。`video_found=true`（通用 ATS/UPS/油机与 DMR 入门视频），非专项「DMR 基站电源交维」教程。

**库内必回：** `学习推送/手册06_日志三联单深化.md`（对时/脱敏）、`手册07_覆盖与同频干扰分诊.md` / `手册09_话务与容量分诊.md`（假 F/假 H 禁加功率）、`手册08_测试实验室最小闭环.md`（倒换后业务抽检）、`手册01_登记失败三问.md` / `手册02_Grant了没声.md`（倒换窗次挂）、`手册10_室分隧道覆盖交维清单.md`（远端电源边界）、`手册11_写频变更回滚与金机基线制度.md`（别误伤金机锚）、`加餐_频率带宽与调制解调.md`。

---

## 11. 收束：你今天带走什么；下一篇候选

### 11.1 带走的钉子

- 贴纸 **K** 五子类：市 / 备 / 切 / 告 / 交。  
- 故事：基站 = ICU 监护仪；电源链 = 供氧 + 呼吸机 + 备用发电机 + 铃 + 交接班。  
- 交维必演：**市电→后备→回切**。  
- 八条硬规则；禁加功率掩盖闪断假干扰。  
- 倒换窗可挂 A/B/F/H，**主贴 K**。

### 11.2 回库路径

```text
总索引.md
  └─ 集群 / Tier III → 运维手册
       ├─ 手册01–05（A–E）06（总单）07（F）08（G）09（H）10（I）11（J）
       └─ 本篇手册12（贴纸K + 插页K + 基站电源与后备切换交维卡）
            └─ 回：手册06–11、加餐弱项
```

### 11.3 下一篇手册候选（本篇不写正文）

- **电梯井·地下车库专项**（手册10 I-覆 的加深专项册）。  
- **（可选）大批量写频作业与 OTAP/无线写频风险边界**（手册11 J 的批量与无线通道加深）。  
- **（可选）电源监控对时与告警风暴治理**（本篇 K-告 的加深册）。

### 11.4 给带新人的三句话

> 只测电压，就没有交维。  
> 铃不能不响；倒换必须演切与回切。  
> 电源在抖时，加功率不是药，协议玄学也不是第一结案词。

### 11.5 运维一周里怎么用这篇（复印到周历）

```text
周一  默写 K 五子类 + 「未演倒换禁止签」卡
周二  抽查一站：告警静音？燃油？启动电池？
周三  对一份旧交维包：有无 R5 时序
周四  演练脚本 B（假干扰）与脚本 C（静音）
周五  §6.5 对齐会；统计拒签与闪断事件
```

### 11.6 和弱项加餐的衔接

把 12.5 kHz / 4FSK / 30 ms 两槽背熟，你才说得清「电源改的是电，不是调制台阶」。有人要用加功率治闪断假干扰时，回加餐 + 手册07/09。

### 11.7 一张图记住本篇（收工贴纸）

```text
        要交维 / 遇闪断掉站 / 倒换窗怪病
                      │
          ┌───────────┴───────────┐
          │关键告警是否静音？      │是 → 拒签/先恢复铃（K-告）
          ▼
        有倒换剧本时序？──否──▶ 拒签（K-切）
          │是
          ▼
        电池/UPS/油机能力可证明？──否──▶ 拒签（K-备）
          │是
          ▼
        市电/整流现状可读？──否──▶ 先补测（K-市）
          │是
          ▼
        边界书面？──否──▶ 拒签（K-交）
          │是
          ▼
        业务抽检；症状可挂 A/B/F/H，主贴 K
        禁令：只测电压；静音当消缺；加功率掩盖；电源病写成协议玄学
```

---

## 12. 本篇检查清单（自学打勾）

- [ ] 能背 K 五子类并各举一个拒签例子  
- [ ] 能画「ICU + 备用发电机」链并指出五段  
- [ ] 能背八条硬规则  
- [ ] 能说明市电→后备→回切顺序直觉  
- [ ] 能拒绝「只测电压 / 长期静音 / 加功率掩盖」  
- [ ] 会填插页 K 的 R1–R8  
- [ ] 会用 §7 封面拒签门槛 + 倒换剧本页 + 边界责任页做一次模拟交维  
- [ ] 知道假覆盖/假干扰/假容量如何主贴 K  
- [ ] 知道倒换窗如何次挂手册01/02/07/09 而不改主贴  
- [ ] 自测 10 题达标；回库重对至少 1 次电源/倒换事件（L3）  
- [ ] 知道下一篇候选且**本篇未写它们的正文**  
- [ ] 外链打开过至少 3 个（含 1 个 ATS/UPS 文 + 1 个电信直流/电池文或 ATS 视频）

---

*推送说明：本篇为手册模式第 12 篇（非第 41 课）。主线是基站电源与后备切换交维：贴纸 K 五子类、插页 K、医院 ICU+备用发电机故事、八条硬规则、现场映射、十例、交维卡模板、术语、自测与核验外链。硬禁令贯穿：不发明条款号、不写真实频点/个号/密钥/站名、不重写手册07–11 全文、禁加功率掩盖、倒换窗症状可挂 A/B/F/H 但主贴 K。读完应能向同事讲清「交维必须演市电→后备→回切、铃不能不响、电源在抖时先贴 K」。*
