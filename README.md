# 机场推荐 2026｜Clash机场 / 节点订阅与科学上网实测

[![last commit](https://img.shields.io/github/last-commit/OpenNetCN/clash?label=last%20update)](https://github.com/OpenNetCN/clash/commits/main)
[![stars](https://img.shields.io/github/stars/OpenNetCN/clash?style=flat)](https://github.com/OpenNetCN/clash/stargazers)
[![issues](https://img.shields.io/github/issues/OpenNetCN/clash)](https://github.com/OpenNetCN/clash/issues)

📅 **内容最后更新：2026年09月21日**

本页面向寻找 **稳定机场、Clash机场、节点订阅与 AI 工具连接方案** 的用户，整理七家机场的购买门槛、客户端限制和配置方法。科学上网、魔法上网或梯子服务是否适合你，先看常用设备与目标平台，再比较价格。

> **资料日期：** 套餐核对日期见各品牌摘要，节点观测和测速截图另列日期。顶部更新时间表示文章修订时间，不代表所有价格与客户端政策都已在当天复核。

<a id="quick-pick"></a>

## 🔥 30 秒选机场（先看这个）

先选一家验证自己的场景。下表列出四种常见需求，其余场景见 [个人推荐](#person)。价格为本文资料记录，付款前核对当前结算金额。

| 你的需求 | 先看哪家 | 套餐与实付参考 | 点击前确认 | 下一步 |
| --- | --- | --- | --- | --- |
| 综合日常主力：AI + 流媒体 + 办公 | **BoostNet** | 200GB/月，¥49/月 | 支持官方客户端及 Clash 等通用客户端；新疆及境外不可用；不退款 | [看限制](#boostnet) · [查看套餐并注册](https://tw.boostqz.com/?path=register&code=kKMFirlm) |
| 需要 Clash 等通用客户端 / 高预算办公 | **WgetCloud** | 200GB/30天，记录价 ¥237/季（折合 ¥79/月） | 注册入口需外网；季付记录不代表可月付 | [看限制](#wgetcloud) · [查看套餐并注册（需外网）](https://invite.wgetcloud.ltd/auth/register?code=kVJQPh) |
| 年付轻量 / 家庭多设备 | **青云梯** | 60GB/月，¥96/年（折合 ¥8/月） | 此档仅年付；只支持官方客户端，购买前确认设备支持 | [看限制](#qingyunti) · [查看套餐并注册](https://realvtest.qytvipaff.cc/register?aff=zcIlh0VY) |
| 补充专项出口 / IDE 登录场景 | **TNTCloud** | 试线路 110GB/月 ¥20；专项主用 220GB/月 ¥40 | 只支持官方客户端；出口需按目标平台验证 | [看限制](#tnt) · [查看套餐并注册](https://tanu095.tntvipaff.cc/#/register?code=7MPbfr89) |

<a id="client-tip"></a>

> **先确认设备，再付款：** **WgetCloud、BoostNet、悠兔均支持 Clash 等通用客户端；BoostNet、悠兔也提供官方客户端。青云梯、银河云、唯兔云、TNTCloud 当前只支持官方客户端。** 具体支持的系统、通用客户端名称与版本，以及安装或导入方式，请按对应官网说明操作。

🧭 [按场景选](#person) · [七家选购摘要](#top7) · [节点观测](#daily-check) · [新手上手](#study) · [购买前检查](#risk)

<a id="web-entry"></a>

📌 更多品牌详评与图文教程见 [gptvpnhelper.com 网页版](https://gptvpnhelper.com/)（需可用的外网连接）。

<details>
<summary>🧩 需要连续办公时，怎样准备主力与备用</summary>

先验证主力线，再按中断成本决定是否加备用。选择两家不代表底层线路一定独立；遇到主力故障时，备用是否仍能连接需要实际验证。

| 组合 | 主力用途 | 备用或补充用途 |
| --- | --- | --- |
| BoostNet + 悠兔 | 综合日常 | 主力波动时切换，分别测试晚高峰表现 |
| BoostNet + TNTCloud | 综合日常 | 按需验证 IDE 登录与专项出口 |
| 悠兔 + 银河云 | 高频视频与办公 | 年付轻量包做备用 |
| 青云梯 + 银河云 | 家庭多设备 | 第二家低流量备用 |
| 唯兔云 + TNTCloud | 多区域业务 | 补充目标地区或出口选择 |

优先用各家提供的短周期档测试。青云·诀和银河云轻量包本身仅年付，若先买同品牌月付档，需另行核对线路权限是否相同，不能把月付测试视为对年付档的完整验证。

</details>

<details>
<summary>🧪 推荐依据与证据范围</summary>

从 2022 年起长期自费订阅、对比过 40+ 家机场，目前保留七家。选择时关注常用设备兼容性、晚高峰连续使用、目标平台访问、付款条件和故障处理记录。

- **套餐与限制：** 依据已有官网资料整理，核对日期见各品牌；当前可售套餐仍需查看结算页。
- **使用观察：** 品牌摘要附适合场景、限制与实测截图，长篇分析见对应网页；单次测速只代表当时环境。
- **节点观测：** 仅展示已有快照中的节点数与可用比例，不据此推算全天在线率或平台解锁率。

推荐理由以对应场景、使用记录和购买限制为依据，便于按自己的需求核对。

</details>

## 📚 目录

1. [30 秒选机场](#quick-pick)
2. [按需求直接选：个人推荐](#person)
3. [每日节点可用性观测](#daily-check)
4. [七家机场选购摘要](#top7)
5. [七家套餐与限制对比](#top9-table)
6. [新手上手：先确认设备，再注册连接](#study)
7. [客户端配置与订阅（GitHub 专区）](#config)：[客户端下载](#clients) · [Mihomo 配置](#clash-config) · [订阅导入](#client-config) · [术语表](#glossary)
8. [选购核对清单](#choose)
9. [什么是机场](#ssssr)
10. [购买建议与风险提醒](#risk)
11. [免责声明](#免责声明)
12. [机场与 VPN 对比](#vs)
13. [FAQ](#faq)
14. [常用海外资源](#listweb)
15. [反馈与贡献](#contribute)

---

<a id="person"></a>

## ✨ 按需求直接选：我的个人推荐

这里补充速选表未展开的场景。需要先确认客户端、地区和预算，推荐顺序不代表每一家都适合所有人。

| 需求场景 | 优先选择 | 备选/补充 | 购买建议 |
| --- | --- | --- | --- |
| AI + 流媒体综合主力 | [BoostNet](#boostnet) | [WgetCloud](#wgetcloud) | BoostNet 默认看 200G/月；更看重老牌稳定性、需要 Clash 等通用客户端时可选 WgetCloud |
| 稳定性优先 / 团队办公 | [WgetCloud](#wgetcloud) | [BoostNet](#boostnet) | 支持 Clash 等通用客户端；基础档记录价 ¥237/季，200GB/30天；团队需核对在线 IP 与共享条款 |
| 长期主用 / 晚高峰视频 | [悠兔](#youtu) | [BoostNet](#boostnet) | 悠兔默认看 300G/月，想先试线路可从 150G/月开始 |
| 年付省心 / 家庭多设备 / 老牌稳定长期用 | [青云梯](#qingyunti) | [银河云](#yinheyun) | 更适合想长期年付、省心使用和多设备一起用的用户 |
| ChatGPT / Claude / Cursor / IDE 登录 | [BoostNet](#boostnet) | [TNTCloud](#tnt) | 先保证综合稳定，再按需补专项出口 |
| TikTok / 跨境电商 / 多区域业务 | [唯兔云](#weituyun) | [TNTCloud](#tnt) | 先确认目标地区节点和账号场景，不要只看最低价 |
| 预算优先 / 年付备用 | [银河云](#yinheyun) | [青云梯](#qingyunti) | 银河云作为第二家年付备用候选，并非最低价；只比预算与流量时也应比较青云梯和唯兔云轻量档 |


> **历史观察：** 在作者跟踪的 2026 年 4 月故障期间，BoostNet、悠兔和 WgetCloud 的恢复及客服联系情况相对较好。本页未附足以横向排名的完整恢复时长记录，这段观察不构成后续可用性或客服响应承诺。

---

<a id="daily-check"></a>

## 📡 每日节点可用性观测

以下为 2026-09-20 的已有观测快照，按摘要顺序排列。

| 机场 | 记录所列客户端 | 观测日期 | 总节点 | 可用节点 | 当次可用比例 |
| --- | --- | --- | ---: | ---: | ---: |
| [BoostNet](#boostnet) | 官方客户端 | 2026-09-20 | 45 | 44 | 97.78% |
| [WgetCloud](#wgetcloud) | Clash Verge | 2026-09-20 | 29 | 29 | 100.00% |
| [悠兔](#youtu) | 官方客户端 | 2026-09-20 | 51 | 45 | 88.24% |
| [青云梯](#qingyunti) | 官方客户端 | 2026-09-20 | 61 | 61 | 100.00% |
| [TNTCloud](#tnt) | 官方客户端 | 2026-09-20 | 50 | 50 | 100.00% |
| [唯兔云](#weituyun) | 官方客户端 | 2026-09-20 | 73 | 65 | 89.04% |
| [银河云](#yinheyun) | 官方客户端 | 2026-09-20 | 34 | 34 | 100.00% |

<details>
<summary>📈 怎样理解这份快照</summary>

- 当次可用比例 = 可用节点数 ÷ 本次统计的总节点数，四舍五入到两位小数；节点总数不等于每个套餐都能使用的节点数。
- 当前表格未附完整的地区、运营商、测试时段、客户端版本、探测目标、超时与重试记录，不能据此复现实测，也不能比较所有人的实际体验。
- 既有历史均值没有同时列出起始日期、有效样本数与聚合算法，暂不展示，也不据此给出“稳定性高”的评级。
- 连通快照不代表全天在线率、速度、AI 登录成功率或流媒体解锁率。带日期的测速截图见各品牌摘要末尾链接。

</details>

---

<a id="top7"></a>

## 🏆 七家机场选购摘要

每家先看适合人群、推荐依据和限制，再核对套餐。本页保留代表性测速与解锁截图，完整评测另见品牌页。

> **图片怎么读：** 日期以图内时间为准，均为历史单次样本；地区、运营商、带宽、线程和测试工具不同，不能仅凭峰值横向排名。“解锁”是工具探测标签，不保证实际账号或全部功能可用。图内旧域名、客户端提示、协议及倍率需与当前官网说明区分；节点列表前几行也可能是套餐信息别名，不能直接按行数推算独立节点数。

<a id="boostnet"></a>

### 1. ⚡ BoostNet — 综合主力首推，自研客户端，三网直连 IEPL

**最近核对记录：** 套餐 2026-04-28；客户端支持情况 2026-09-21 确认；本次未复核结算页。

三网直连 IEPL · AnyTLS · 香港 HGC 落地 · 2024 年运营

- **适合谁：** 想少折腾、直接上一条长期主力线的中高强度用户，需要同时使用 `AI + 流媒体 + 远程办公`
- **不适合：** 预算极低、只偶尔用一下的轻度用户（看 [银河云](#yinheyun)）
- **主要依据：** 官方客户端减少手动配置步骤，200GB 月付档适合先验证综合日常需求；已有使用记录覆盖 AI、流媒体与办公场景
- **核心参数：** AnyTLS 协议｜全球 5+ 地区 30+ 节点（企业档 10+ 地区 40+ 节点，以实际订阅为准）｜常规 5 台设备 / 企业档 30 台｜支付宝 · 微信
- **客户端：** 支持 Clash 等通用客户端，也提供 Windows / macOS / Android 官方客户端；具体客户端版本和导入方式按官网说明操作
- **怎么买：** 日常主力优先 **200G/月（¥49）**；多设备 **400G/月（¥79）**；重度 **1000G/月（¥129）** ｜ 👉 [查看套餐并注册 BoostNet](https://tw.boostqz.com/?path=register&code=kKMFirlm)

| 套餐 | 价格 | 每月流量 | 手动重置 | 备注 |
| --- | ---: | ---: | ---: | --- |
| 每月20G流量套餐 | ¥200 / 年 | 20GB | ¥17 / 次 | 轻量套餐 |
| **200G流量套餐** | **¥49 / 月** | 200GB | ¥50 / 次 | 日常主力优先 |
| 400G流量套餐 | ¥79 / 月 | 400GB | ¥80 / 次 | 多设备 / 偏重度 |
| 1000G流量套餐 | ¥129 / 月 | 1000GB | ¥130 / 次 | 重度 |
| 企业团队套餐 | ¥388 / 月 | 1500GB | ¥388 / 次 | 30 台设备，全球 10+ 地区 40+ 节点 |

> 🔄 **重置规则：** 已有资料记载每月按购买日重置流量；套餐有效期按所买周期计算。提前用完需另购重置包，具体重置日期以面板为准。
>
> ⚠️ **购买前必看：** 禁止共享他人使用；**仅限中国大陆，新疆不可用，境外不可用**；禁 BT / P2P / PT；**不提供退款**。

**📷 测速样本｜2026-07-03 12:04（CST）**

图内标注广西移动 2Gbps，展示不同地区节点的延迟与下载速度，部分节点明显较慢。这是白天样本，不能用于推断晚高峰表现；点击图片可查看原图。

<a href="https://img.petnooko.com/2026/07/fa2bf196c0881c0eca4d96518d1e4f33.webp"><img src="https://img.petnooko.com/2026/07/fa2bf196c0881c0eca4d96518d1e4f33.webp" alt="BoostNet 测速样本，2026-07-03，广西移动 2Gbps" width="520" /></a>

<details>
<summary>查看解锁记录｜2026-07-01</summary>

图内标注佛山移动 500Mbps；Netflix、Disney+、TikTok 等列同时存在成功、失败或 N/A 结果，应逐节点看目标平台。图中旧客户端提示不代表当前规则，当前支持情况见本节客户端说明。

<a href="https://img.petnooko.com/2026/07/6720b911653a171fe3b7d57777ae6f6d.webp"><img src="https://img.petnooko.com/2026/07/6720b911653a171fe3b7d57777ae6f6d.webp" alt="BoostNet 平台解锁探测记录，2026-07-01" width="900" /></a>

</details>

> 🔗 **查看套餐并注册：** [BoostNet](https://tw.boostqz.com/?path=register&code=kKMFirlm)
> 💰 **价格口径：** 以上为 2026-04-28 套餐记录，以官网结算页最终显示为准

📖 完整评测与使用细节 → [BoostNet 机场测评](https://gptvpnhelper.com/boostnet/)

---

<a id="wgetcloud"></a>

### 2. 💎 WgetCloud — 老牌旗舰，稳定性优先，支持通用客户端

**最近核对记录：** 季付套餐 2026-08-01；客户端支持情况 2026-09-21 确认；本次未复核结算页。

广州 BGP → IEPL 专线 · 自研控制面板 · 2021 年成立

- **适合谁：** 团队办公、内容创作、把稳定性放在首位的用户，以及需要 Clash 等通用客户端的人
- **不适合：** 只想要最低价、日常轻度使用的用户（看 [青云梯](#qingyunti) / [银河云](#yinheyun)）
- **主要依据：** 支持 Clash 等通用客户端，有带日期的测速记录；品牌页 2026-08-01 资料记载已恢复季付。适合明确需要客户端灵活性并能接受季付实付门槛的人
- **核心参数：** Trojan 主协议 + Shadowsocks（路由器兼容）｜当前监测 29 节点覆盖五大洲｜UDP 类型需逐节点核对（下方样本含 FullCone 与 Unknown）｜按档 3 / 4 / 5 个在线 IP｜工单 + 邮件，响应时间以实际工单为准
- **客户端：** 支持 Clash 等通用客户端，导入格式和版本按官网说明确认
- **怎么买：** 想控制预算从 **基础专线服务（记录价 ¥237/季，折合 ¥79/月）** 起步；AI 与远程协作更重看 **优质专线服务** ｜ 👉 [查看套餐并注册 WgetCloud（需外网环境）](https://invite.wgetcloud.ltd/auth/register?code=kVJQPh)

| 套餐 | 价格 | 核心配置 | 峰值带宽 / 连接数 | 适合谁 |
| --- | ---: | --- | --- | --- |
| 基础专线服务 | ¥237 / 季（折合 ¥79/月） | 200G / 30 天重置，3 个在线 IP | 200Mbps / 300 | 入门，日常主力 |
| 优质专线服务 | ¥267 / 季（折合 ¥89/月） | 250G / 30 天重置，4 个在线 IP | 300Mbps / 800 | AI、远程协作更重 |
| 精品专线服务 | ¥297 / 季（折合 ¥99/月） | 270G / 30 天重置，5 个在线 IP，全球五大洲节点 | 500Mbps / 1500 | 商务、内容创作；SLA 范围和赔付需查条款 |

> 📌 **注册入口需要外网环境**，没有可用连接时点击可能打不开。优质 / 精品档支持智能负载均衡。

**📷 测速样本｜2026-08-10 09:35（CST）**

图中香港、日本等地区有较快的样本，也有新加坡、日本等节点速度偏低的记录。测试环境未在图内完整注明，不能与其他品牌截图直接比较；点击图片可查看原图。

<a href="https://img.petnooko.com/2026/08/9922aa40f9ea86da3ea2ba347f89e64c.webp"><img src="https://img.petnooko.com/2026/08/9922aa40f9ea86da3ea2ba347f89e64c.webp" alt="WgetCloud 节点测速样本，2026-08-10" width="720" /></a>

<details>
<summary>查看 AI 与流媒体探测记录｜2026-08-10</summary>

同日探测结果因节点和平台不同而异，例如部分香港节点的 OpenAI 标为“仅 APP”、Claude 标为“失败”。这些标签属于当次探测结果，不等于账号登录、长会话或所有功能均已验证。

<a href="https://img.petnooko.com/2026/08/9ccf39901853ffadb886561bcd3d3f69.webp"><img src="https://img.petnooko.com/2026/08/9ccf39901853ffadb886561bcd3d3f69.webp" alt="WgetCloud AI 与流媒体探测记录，2026-08-10" width="900" /></a>

</details>

> 🔗 **查看套餐并注册：** [WgetCloud（需外网环境）](https://invite.wgetcloud.ltd/auth/register?code=kVJQPh)
> 💰 **价格口径：** 以上为品牌页 2026-08-01 季付资料，折合月价不代表支持月付。当前售卖周期与结算价尚待重新核对，下单前以官网为准。

📖 完整评测与更多测试说明 → [WgetCloud 机场测评](https://gptvpnhelper.com/wgetcloud/)

---

<a id="youtu"></a>

### 3. 🐰 悠兔机场 — 长期主用优先，高端 IEPL 专线，多入口中转更稳

**最近核对记录：** 套餐 2026-04-28；客户端支持情况 2026-09-21 确认；本次未复核结算页。

广东电信入口 → 高端 IEPL + 多入口双层加密隧道 · 2022 年运营

- **适合谁：** 想买一条能长期主用、晚高峰依旧稳定的 IEPL 主力线，YouTube / Netflix / ChatGPT / TikTok 高频用户
- **不适合：** 需要境外接入、SSH 默认 22 端口或未经允许共享账号的用户
- **主要依据：** IEPL 与多入口方案，150GB 月付档可用于初次验证；300GB 档适合已确认线路表现的高频用户
- **核心参数：** Shadowsocks（不支持 SSR）｜50+ 节点多落地多入口，覆盖港日新美台等主流地区（以实际订阅为准）｜默认 1x 倍率，可切 2x 专线节点｜全节点 UDP｜个人档默认 5 台设备 / 团体档 20 台（共享权限按条款）｜支付宝 · 微信
- **使用限制：** 仅限中国内地；**新疆、港澳台及境外不可用**；禁 SMTP、封 22 端口；不适合 BT / P2P / PT；个人套餐禁止共享，团体权限另查条款
- **客户端：** 支持 Clash 等通用客户端，也提供官方客户端；具体客户端版本和导入方式按官网说明操作（详见 [顶部统一说明](#client-tip)）
- **怎么买：** 试线路优先 **150G/月（¥39）**；当主力优先 **300G/月（¥59）**；重度优先 **500G/月（¥79）** ｜ 👉 [查看套餐并注册悠兔（线路1）](https://tw.youtu1.com/?path=register&code=erkQTmbM) ｜ [备用（线路2）](https://tw.youtunice.com/?path=register&code=erkQTmbM)

| 套餐 | 流量 / 周期 | 月付 | 其他周期 | 重置 |
| --- | --- | ---: | --- | ---: |
| 入门首选 | 150G / 月 | ¥39 | 年付 ¥400 | ¥40 / 次 |
| **每月300G** | 300G / 月 | **¥59** | 季 ¥160 / 半年 ¥310 / 年 ¥500 | ¥60 / 次 |
| 每月500G | 500G / 月 | ¥79 | 季 ¥220 / 半年 ¥420 / 年 ¥800 | ¥80 / 次 |
| 每月1000G | 1000G / 月 | ¥119 | - | ¥120 / 次 |
| 轻量年包 | 200G / 年 | - | ¥199 / 年 | 用完续费，不走重置包 |
| 轻量季度包 | 50G / 月 | - | ¥79 / 季 | ¥26 / 次 |
| 团体套餐 | 1500G / 月 | ¥366 | - | 最多 20 台设备 |

> **套餐说明：** 已有资料记载个人套餐线路权限一致，支持 UDP；实际速度与平台访问需按节点验证，不将相同线路权限理解为相同测速结果。

**📷 测速样本｜2026-07-03 12:25（CST）**

图内标注广西移动 2Gbps，能看到不同地区和倍率线路的速度差异。这是白天样本，不作为晚高峰视频结论；点击图片可查看原图。

<a href="https://img.petnooko.com/2026/07/b78f6f7bad6cdb780b2c862f654f5be6.webp"><img src="https://img.petnooko.com/2026/07/b78f6f7bad6cdb780b2c862f654f5be6.webp" alt="悠兔测速样本，2026-07-03，广西移动 2Gbps" width="460" /></a>

图中协议标为 AnyTLS，部分线路标有 2.5x 倍率，与上方既有 Shadowsocks / 2x 资料不同；当前协议和倍率需按实际订阅核对。

<details>
<summary>查看解锁记录｜2026-07-01</summary>

图内标注佛山移动 500Mbps，展示 Netflix、Disney+、OpenAI 等平台的逐节点探测结果，包含失败和 N/A。图中旧客户端提示仅保留作历史记录，当前支持情况见本节说明。

<a href="https://img.petnooko.com/2026/07/75d3ea2e7b8b399f069362706c978621.webp"><img src="https://img.petnooko.com/2026/07/75d3ea2e7b8b399f069362706c978621.webp" alt="悠兔平台解锁探测记录，2026-07-01" width="900" /></a>

</details>

> 🔗 **查看套餐并注册：** [悠兔（线路1）](https://tw.youtu1.com/?path=register&code=erkQTmbM) ｜ [备用（线路2）](https://tw.youtunice.com/?path=register&code=erkQTmbM)
> 💰 **价格口径：** 以上为 2026-04-28 套餐记录，以官网结算页最终显示为准

📖 更多图文与 2026-04-27 晚高峰视频记录（与上图为不同批次） → [悠兔机场测评](https://gptvpnhelper.com/youtu/)

---

<a id="qingyunti"></a>

### 4. 🌤 青云梯 — 2019 年开业，IPLC 专线，轻量档 ¥96/年

**最近核对记录：** 客户端支持情况 2026-09-21 确认；套餐核对日期未记录，本次未复核结算页。

企业级 IPLC 专线 · 智能负载均衡 · 2019 年 11 月开业

- **适合谁：** 想找老牌稳定、省心年付、多设备全家用，同时希望 AI / 流媒体都覆盖的人
- **主要依据：** 2019 年 11 月开业，提供 IPLC 与多设备方案；青云·诀适合确认使用需求后的轻量年付
- **限制：** 青云·诀不提供月付；多设备不等于可任意合租，设备上限、共享和退款规则需核对当前条款
- **核心参数：** Shadowsocks｜80+ 全专线节点覆盖 17+ 地区（港台日新马美韩泰印尼菲越英德法土巴阿）｜三网优化｜支持多设备，系统兼容性按官方客户端列表｜支付宝 · 微信 · USDT｜客服在线时段以官网为准
- **客户端：** 当前只支持官方客户端，不支持 Clash 等通用客户端；安装方式按官网说明操作（详见 [顶部统一说明](#client-tip)）
- **怎么买：** 轻度 / 备用优先 **青云·诀（¥96/年）**；中度主力优先 **VIP1（150GB/月）**；多设备 / 重度优先 **VIP2（300GB/月）** ｜ 👉 [查看套餐并注册青云梯](https://realvtest.qytvipaff.cc/register?aff=zcIlh0VY)

| 套餐 | 每月流量 | 月付 | 季付 | 年付 |
| --- | --- | ---: | ---: | ---: |
| **青云·诀** | 60GB | - | - | **¥96（≈¥8/月）** |
| 青云·VIP1 | 150GB | ¥25 | ¥67 | ¥240（≈¥20/月） |
| 青云·VIP2 | 300GB | ¥45 | ¥121 | ¥432（≈¥36/月） |
| 青云·VIP3 | 600GB | ¥85 | ¥229 | ¥916（≈¥76/月） |

<details>
<summary>查看历史测速与解锁样本｜2025-10-29</summary>

**测试日期以图内时间为准：2025-10-29 16:16（CST）。** 图中同时列出速度及部分平台探测结果，含失败、未知和无速度记录。该样本较旧，仅供了解历史测试情况，不代表当前节点或解锁状态。

<a href="https://img.petnooko.com/2026/06/e069f62470a4d54c91bedf415794123a.webp"><img src="https://img.petnooko.com/2026/06/e069f62470a4d54c91bedf415794123a.webp" alt="青云梯历史测速与平台探测记录，图内日期 2025-10-29" width="900" /></a>

</details>

> 🔗 **查看套餐并注册：** [青云梯（¥96/年，每月 60GB）](https://realvtest.qytvipaff.cc/register?aff=zcIlh0VY)
> 💰 **价格口径：** 以上为已有资料价格，以官网结算页最终显示为准

📖 测速图与更完整的线路说明 → [青云梯机场测评](https://gptvpnhelper.com/qingyunti/)

---

<a id="tnt"></a>

### 5. 🔥 TNTCloud — 更看重原生 IP 与专线出口时可看，IPLC 专线，海外团队运营

**最近核对记录：** 客户端支持情况 2026-09-21 确认；套餐核对日期未记录，本次未复核结算页。

IPLC 全专线 · Trojan · 原生 / 高质量 IP · 2024 年成立

- **适合谁：** 已明确需要原生 / 高质量 IP、IDE 登录或专项出口的 ChatGPT / Claude / Copilot / Gemini 深度用户
- **主要依据：** IPLC 与不同地区出口可用于专项场景对照；“原生 IP”不等于住宅 IP，也不保证平台放行
- **限制：** 必须接受当前官方客户端方案；业务账号先验证目标地区和连续会话，多人共享及退款另查条款
- **核心参数：** Trojan｜香港×10、台湾×10、新加坡×10、日本×10、美国×10、德国×1｜不限速、不限倍率、**不限设备数**｜支付宝 · 微信 · U 转账
- **客户端：** 当前只支持官方客户端，不支持 Clash 等通用客户端；安装方式按官网说明操作（详见 [顶部统一说明](#client-tip)）
- **怎么买：** 轻度优先 **VIP1（110GB）**；专项使用优先 **VIP2（220GB）**；多设备 / 重度优先 **VIP3（440GB）** ｜ 👉 [查看套餐并注册 TNTCloud](https://tanu095.tntvipaff.cc/#/register?code=7MPbfr89)

| 套餐 | 流量 / 月 | 价格 | 说明 |
| --- | --- | ---: | --- |
| 季付限量包 | 60GB × 3 月 | ¥30 / 季 | 超低月均，轻量首选 |
| VIP1（轻量） | 110GB | ¥20 / 月 | 日常上网 + 流媒体 |
| **VIP2（中量）** | 220GB | **¥40 / 月** | 主力推荐 |
| VIP3（高量） | 440GB | ¥80 / 月 | 多设备 + 高画质 |
| VIP4（巨量） | 1100GB | ¥160 / 月 | 重度使用；共享须核对条款 |
| 定制套餐 | 独享 / 定制 | ¥680 / 月 | 专线独享，支持定向功能 |

<details>
<summary>查看历史测速与解锁样本｜2026-01-18</summary>

图内时间为 2026-01-18 10:04（CST），标注陕西联通 1Gbps。速度与平台探测结果需分开看，例如部分 Netflix 结果为“未知”，部分 Disney+ 结果为“失败”。该图仅作历史样本，不代表近期晚高峰或当前解锁表现。

<a href="https://img.petnooko.com/2026/01/5e4f9e11b7e226cc9d679b0e7fbbd882.webp"><img src="https://img.petnooko.com/2026/01/5e4f9e11b7e226cc9d679b0e7fbbd882.webp" alt="TNTCloud 历史测速与平台探测记录，2026-01-18" width="900" /></a>

</details>

> 🔗 **查看套餐并注册：** [TNTCloud](https://tanu095.tntvipaff.cc/#/register?code=7MPbfr89)
> 💰 **价格口径：** 以上为已有资料价格，以官网结算页最终显示为准

📖 测速图与出口质量实测 → [TNTCloud 机场测评](https://gptvpnhelper.com/tntcloud/)

---

<a id="weituyun"></a>

### 6. 🐰 唯兔云 — 2025 新晋 IPLC 专线，SS2022 协议，TikTok / 电商 / 多区域业务专项可看

**最近核对记录：** 客户端支持情况 2026-09-21 确认；套餐核对日期未记录，本次未复核结算页。

IPLC 全专线 · SS2022 · 东南亚节点丰富 · 2025 年运营

- **适合谁：** 明确需要 TikTok 运营、跨境电商、直播带货、东南亚与多区域业务节点，同时兼顾 AI / 流媒体的人
- **主要依据：** IPLC + SS2022 与东南亚等地区覆盖，方便先按目标业务地区筛选节点
- **限制：** 节点地区覆盖不等于 TikTok 发布、直播或店铺账号一定可用；付款前确认官方客户端、共享与退款规则
- **核心参数：** SS2022｜港台日美新 + 东南亚五国 + 印度 + 韩国 + 部分欧美（以面板实际订阅为准）｜**无倍率、不限速、不限设备数**｜支付宝 · 微信 · USDT｜多人客服轮班 + 海外技术团队
- **客户端：** 当前只支持官方客户端，不支持 Clash 等通用客户端；按官网知识库操作。iPhone 用户没有外区账号可联系官方获取 iOS 安装指引（详见 [顶部统一说明](#client-tip)）
- **怎么买：** 试水优先 **100GB（月付 ¥14.9）**；当主力优先 **200GB（月付 ¥29.9）**；多设备 / TikTok / 电商运营优先 **500GB（月付 ¥59.9）** ｜ 👉 [查看套餐并注册唯兔云](https://realvpn.v2yunvipaff.com/#/?code=5LVpl8Mh)

| 套餐 | 流量 / 月 | 月付 | 季付 | 年付 |
| --- | --- | ---: | ---: | ---: |
| 轻量年付小包 | 45GB | - | - | ¥79.9（≈¥6.7/月） |
| 标准版 | 100GB | ¥14.9 | ¥40.9 | ¥142.9 |
| **进阶版** | 200GB | **¥29.9** | ¥80.9 | ¥286.9 |
| 高流量版 | 500GB | ¥59.9 | ¥161.9 | ¥547.9 |
| 重度版 | 1000GB | ¥119.9 | ¥323.9 | ¥1150.9 |

**一次性流量包（不属于年付套餐）：** 既有资料列出不限时 500GB、首次 ¥340；500GB 为整包总流量，不是每月配额。有效期、重置和续费价格以结算页为准。

<details>
<summary>查看测速样本｜2026-07-22</summary>

图内时间为 2026-07-22 11:47（CST），标注珠海联通 9Gbps、32 线程，不能与其他带宽环境的截图直接比较。图中既有较快记录，也有多条零速度记录；这是一张测速图，不包含平台解锁验证。

图中协议标为 VLESS，与上方既有 SS2022 资料不同；当前协议需向官网核对，不能据此推断支持 Clash 等通用客户端。

<a href="https://img.petnooko.com/2026/08/74dbedc4bd12fee92c761a47950d2e9d.webp"><img src="https://img.petnooko.com/2026/08/74dbedc4bd12fee92c761a47950d2e9d.webp" alt="唯兔云测速样本，2026-07-22，含零速度节点记录" width="900" /></a>

</details>

> 🔗 **查看套餐并注册：** [唯兔云](https://realvpn.v2yunvipaff.com/#/?code=5LVpl8Mh)
> 💰 **价格口径：** 以上为已有资料价格，以官网结算页最终显示为准

> ℹ️ 唯兔云暂时没有单独测评页，完整测速图与实测记录见网页版对应段落 → [唯兔云（网页版）](https://gptvpnhelper.com/#weituyun)

---

<a id="yhy"></a>
<a id="yinheyun"></a>

### 7. 🌌 银河云 Galaxy — ¥98/年轻量备用，Trojan / IEPL

**最近核对记录：** 客户端支持情况 2026-09-21 确认；套餐核对日期未记录，本次未复核结算页。

全线 IEPL 专线 · Trojan · 新加坡团队 · 2023 年 6 月上线

- **适合谁：** 预算优先、希望用较低年付成本获得 IEPL 专线和多设备支持的长期用户，以及需要为多台自用设备准备备用连接的用户
- **主要依据：** 50GB/月的年付轻量档可作为第二家备用候选；按现有记录并非七家最低年付价，应结合本地表现选择
- **限制：** 轻量档仅年付；资料提及退款，但申请时限、用量门槛与扣费规则未完整记录，付款前确认，不视为无条件退款
- **核心参数：** Trojan｜香港×10、台湾×5、新加坡×5、日本×5、美国×5、马来西亚×2、越南×2、菲律宾×2、泰国×2、英国×2、阿根廷×2、土耳其×2｜支付宝 · 微信 · USDT（USDT / VX 联系官网客服）
- **客户端：** 当前只支持官方客户端，不支持 Clash 等通用客户端；安装方式按官网说明操作（详见 [顶部统一说明](#client-tip)）
- **怎么买：** 低流量备用可看 **年付轻量包（¥98/年）**；中度长期优先 **行星套餐（200GB/月）**；重度优先 **恒星套餐（400GB/月）** ｜ 👉 [查看套餐并注册银河云](https://realvtest.galaxyvipaff01.cc/register?aff=tcOd0ob7)

| 套餐 | 每月流量 | 月付 | 季付 | 年付 |
| --- | --- | ---: | ---: | ---: |
| **年付轻量包** | 50GB | - | - | **¥98** |
| 星尘套餐 | 100GB | ¥18 | ¥49 | ¥173 |
| 行星套餐 | 200GB | ¥35 | ¥95 | ¥336 |
| 恒星套餐 | 400GB | ¥70 | ¥189 | ¥672 |
| 星系套餐 | 800GB | ¥140 | ¥378 | ¥1344 |

<details>
<summary>其他周期与一次性流量包（已有价格记录）</summary>

| 套餐 | 半年付 | 两年付 | 三年付 |
| --- | ---: | ---: | ---: |
| 星尘套餐 | ¥92 | ¥302 | ¥389 |
| 行星套餐 | ¥179 | ¥588 | ¥756 |
| 恒星套餐 | ¥357 | ¥1176 | ¥1512 |
| 星系套餐 | ¥714 | ¥2352 | ¥3024 |

另有一次性 1000GB 流量包，记录价 ¥680，原套餐名“永久不限时套餐”。1000GB 是整包总流量，不是月配额；“不限时”不代表服务永久存续，具体有效期和使用条件以条款为准。

</details>

<details>
<summary>查看历史测速与解锁样本｜2026-01-18</summary>

图内时间为 2026-01-18 10:16（CST），标注辽宁移动 1Gbps。各地区速度及解锁结果有差异，部分平台显示失败或未知。该图仅作历史参考，不代表当前节点列表或近期晚高峰表现。

<a href="https://img.petnooko.com/2026/01/9890c60caa8e3fb3fd16659dd7983c88.webp"><img src="https://img.petnooko.com/2026/01/9890c60caa8e3fb3fd16659dd7983c88.webp" alt="银河云历史测速与平台探测记录，2026-01-18" width="900" /></a>

</details>

> 🔗 **查看套餐并注册：** [银河云](https://realvtest.galaxyvipaff01.cc/register?aff=tcOd0ob7)
> 💰 **价格口径：** 以上为已有资料价格，以官网结算页最终显示为准

📖 测速图与节点分布实测 → [银河云机场测评](https://gptvpnhelper.com/yinheyun/)

---

<a id="七大精选机场对比表格按推荐优先级排序"></a>
<a id="top9-table"></a>

## 📊 七家套餐与限制对比（与摘要顺序一致）

用于核对付款门槛和客户端兼容性。以下均为已有资料记录，当前是否可售以结算页为准。

| 机场 | 协议 / 接入 | 默认先看套餐 | 客户端口径 | 设备 / 关键限制 |
| --- | --- | --- | --- | --- |
| **BoostNet** | AnyTLS / 三网直连 IEPL | 200GB/月，¥49/月 | 官方客户端及 Clash 等通用客户端 | 常规 5 台，企业 30 台；禁止共享；新疆及境外不可用；不退款 |
| **WgetCloud** | Trojan、SS / BGP + IEPL | 200GB/30天，记录价 ¥237/季（折合 ¥79/月） | 支持 Clash 等通用客户端 | 基础/优质/精品分别 3/4/5 个在线 IP，不能直接换算为设备数；注册需外网 |
| **悠兔** | Shadowsocks / IEPL + 多入口 | 试线路 150GB/月 ¥39；主力 300GB/月 ¥59 | 官方客户端及 Clash 等通用客户端 | 个人档 5 台、禁止共享；新疆、港澳台及境外不可用；封 22 端口 |
| **青云梯** | Shadowsocks / IPLC | 60GB/月，¥96/年 | 只支持官方客户端 | 多设备，具体上限与共享权限查条款；轻量档仅年付 |
| **TNTCloud** | Trojan / IPLC | 试线路 110GB/月 ¥20；专项主用 220GB/月 ¥40 | 只支持官方客户端 | 资料标注不限设备，共享权限另查 |
| **唯兔云** | SS2022 / IPLC | 试线路 100GB/月 ¥14.9；主力 200GB/月 ¥29.9 | 只支持官方客户端 | 资料标注不限设备；目标地区与业务功能需分别验证 |
| **银河云** | Trojan / IEPL | 备用 50GB/月 ¥98/年；月付可看 100GB/月 ¥18 | 只支持官方客户端 | 资料标注不限设备；退款条件需确认；轻量档仅年付 |

“不限设备”不等于允许多人合租。青云梯与唯兔云另有不同门槛的轻量方案，银河云的定位是备用候选，不是全表最低价。

---

<a id="study"></a>

## 🚀 新手上手：先确认设备，再注册连接

### ① 付款前确认支持方式

到选中机场的官网查看当前使用说明，确认你的系统、地区、客户端与套餐限制。需要 iOS、Linux、路由器或 Clash 自定义规则时尤其要先确认，见 [客户端统一说明](#client-tip)。

iOS 用户先确认机场推荐哪种安装与接入方式：官方要求使用专用方案时按指引操作；明确支持 Nextin 时再用识别码登录；支持通用订阅时才考虑 Shadowrocket / Stash。下载与海外 App Store 账号说明集中在 [客户端章节](#clients)。

### ② 注册并核对实付金额

从 [速选表](#quick-pick) 或所选品牌摘要中的“查看套餐并注册”进入，设置独立密码。确认**付款周期、实际支付金额、流量重置方式、退款与共享条款**后再下单。折合月价不表示支持月付。

### ③ 按官网支持方式连接

| 官网提供的方式 | 连接步骤 |
| --- | --- |
| 官方客户端账号登录 | 从官网指定来源安装 → 登录机场账号 → 更新节点 → 选择节点并连接 |
| 官方明确支持 Nextin 识别码接入 | 按本机场说明填写识别码与账号 → 加载节点 → 允许系统 VPN 配置并连接 |
| 官方明确支持通用订阅 | 复制相应客户端格式的订阅 → 导入 → 更新 → 选择节点 → 开启代理 |

使用规则或智能分流模式。重要账号尽量固定在经验证可用的地区与出口；另备可用节点，故障时再切换。低延迟只是参考，还要测试连续会话、丢包和实际吞吐。具体导入步骤见 [订阅导入](#client-config)。

> 🔐 订阅链接与账号密码都属于凭证，不要发到群聊、Issue 或公开截图。没有订阅入口时先问客服，不要套用其他机场教程。

### ④ 验证自己的用途

| 检查项 | 怎样验证 |
| --- | --- |
| 基础连接 | Google 等目标网站可正常加载，确认代理已生效 |
| AI 工具 | 在平台支持的地区测试登录、连续对话或 IDE 调用；网页能打开不代表所有功能可用 |
| 视频 | 播放所需地区内容，连续观察缓冲与清晰度；别只看测速数字 |
| 出口 | 使用 IP 查询服务确认出口地区，与客户端所选节点及实际用途对应 |

失败时按 [FAQ 排查顺序](#faq) 检查客户端、订阅、规则和网络，不要立即重复购买。银行、支付等不需要代理的业务保持直连，敏感账号开启两步验证。

---

<a id="config"></a>

## 🛠 客户端配置与订阅（GitHub 专区）

> 📌 这里提供配置参考。先确认机场允许通用订阅及目标客户端；仅提供官方接入的服务不能直接套用这些示例。
>
> 🔐 **订阅链接等于你的账号凭证，不要发到群里、Issue 里或任何公开位置。** 下文所有示例中的 `YOUR_SUBSCRIPTION_URL` 都需要替换成你自己的订阅地址。

<a id="clients"></a>

### 📦 全平台客户端下载

优先使用机场当前指定的客户端。下面列出通用工具供已确认兼容的用户选择，下载前核对系统架构、维护状态和机场支持版本。

| 平台 | 推荐客户端 | 内核 | 下载地址 |
| --- | --- | --- | --- |
| Windows | Mihomo Party | mihomo | [GitHub Releases](https://github.com/mihomo-party-org/mihomo-party/releases) |
| Windows | Clash Verge Rev | mihomo | [GitHub Releases](https://github.com/clash-verge-rev/clash-verge-rev/releases) |
| Windows | v2rayN | Xray / sing-box | [GitHub Releases](https://github.com/2dust/v2rayN/releases) |
| macOS | Clash Verge Rev | mihomo | [GitHub Releases](https://github.com/clash-verge-rev/clash-verge-rev/releases) |
| macOS | ClashX Meta | mihomo | [GitHub Releases](https://github.com/MetaCubeX/ClashX.Meta/releases) |
| iOS / iPadOS | **Nextin（星拓）**（免费下载，含内购；需外区 Apple ID） | mihomo | [App Store](https://apps.apple.com/us/app/nextin/id6754002454) |
| iOS / iPadOS | Shadowrocket（付费，需外区 Apple ID） | 自研 | [App Store](https://apps.apple.com/us/app/shadowrocket/id932747118) |
| iOS / iPadOS | Stash（付费，Clash 配置兼容） | 自研 | [App Store](https://apps.apple.com/app/id1596063349) |
| Android | FlClash | mihomo | [GitHub Releases](https://github.com/chen08209/FlClash/releases) |
| Android | Clash Meta for Android | mihomo | [GitHub Releases](https://github.com/MetaCubeX/ClashMetaForAndroid/releases) |
| Android | NekoBox for Android | sing-box | [GitHub Releases](https://github.com/MatsuriDayo/NekoBoxForAndroid/releases) |
| Android / 桌面 | Hiddify | sing-box | [GitHub Releases](https://github.com/hiddify/hiddify-next/releases) |
| Linux / 服务器 | mihomo 内核 | mihomo | [GitHub Releases](https://github.com/MetaCubeX/mihomo/releases) |
| Linux / 桌面 | sing-box | sing-box | [GitHub Releases](https://github.com/SagerNet/sing-box/releases) |
| 路由器（OpenWrt） | OpenClash | mihomo | [GitHub 项目页](https://github.com/vernesong/OpenClash) |
| Apple TV / Vision Pro | Nextin（星拓） | mihomo | [App Store](https://apps.apple.com/us/app/nextin/id6754002454) |

**下载时选哪个文件：**

| 平台 | 选这个 |
| --- | --- |
| Windows | 按系统架构选 x64 或 ARM64 安装包；32 位系统需先确认项目是否仍提供 ia32 版本 |
| macOS Apple Silicon | `xxx-aarch64.dmg`；Intel 芯片选 `xxx-x64.dmg` |
| Android | 最新版本的 `xxx-arm64-v8a-release.apk` |

> 🍎 macOS 拦截安装时，先核对下载来源和提示原因；确认是可信发布包的开发者验证提示后，再按系统指引处理。
> 🤖 Android 安装官网提供的 APK 时，按系统提示临时允许对应来源安装，装好后可关闭该权限。

> 📱 **iOS：** 先按机场支持列表选工具。Nextin 免费下载、含内购，是否需要付费功能看实际接入方式；Shadowrocket / Stash 为付费工具。App Store 是否可下载以及价格以账号地区为准，国区通常不提供这些应用。没有所需地区账号，付款前先向机场确认可行安装方式。
>
> 切换商店账号只在 App Store 内操作，下载来源以官网和应用商店为准；不要把陌生账号登录到系统 iCloud。Nextin 的识别码与订阅用法见 [导入说明](#client-config)。

---

<a id="clash-config"></a>

### ⚙️ Clash / Mihomo 配置模板

下面的三段 YAML 合并后构成一份 mihomo 配置示例，适用于兼容的客户端。需替换订阅地址、确认版本与格式，并验证规则集可以下载；不是所有机场链接都能作为 `proxy-providers` 输入。

如果官网提供完整配置，通常直接导入即可。只有需要自定义分流时才考虑下面的示例。修改前备份现用配置；节点供应配置需符合 mihomo 支持的 provider 格式。

<details>
<summary>展开 Mihomo 配置骨架、代理分组与规则（三段合并使用）</summary>

#### 基础骨架

```yaml
# ---- 基础设置 ----
port: 7890                 # HTTP 代理端口
socks-port: 7891           # SOCKS5 代理端口
mixed-port: 7892           # 混合端口（推荐只用这个）
allow-lan: false           # 是否允许局域网其他设备连接
mode: rule                 # rule / global / direct
log-level: info
external-controller: 127.0.0.1:9090

# ---- DNS 示例：fake-ip 是一种可选模式 ----
dns:
  enable: true
  ipv6: false
  enhanced-mode: fake-ip
  fake-ip-range: 198.18.0.1/16
  fake-ip-filter:
    - "*.lan"
    - "localhost.ptlogin2.qq.com"
  default-nameserver:
    - 223.5.5.5
    - 119.29.29.29
  nameserver:               # 主解析器，不是严格的国内域名分流
    - https://dns.alidns.com/dns-query
    - https://doh.pub/dns-query
  fallback:                 # 备用解析器；此处不保证 DNS 请求经代理发送
    - https://1.1.1.1/dns-query
    - https://dns.google/dns-query
  fallback-filter:
    geoip: true
    geoip-code: CN

# ---- 订阅：替换成你自己的订阅链接 ----
proxy-providers:
  airport:
    type: http
    url: "YOUR_SUBSCRIPTION_URL"
    interval: 3600          # 每小时更新一次节点
    path: ./providers/airport.yaml
    health-check:
      enable: true
      url: http://www.gstatic.com/generate_204
      interval: 300
```

#### 代理分组

按用途分组可分别选择出口。AI 与流媒体的地区和连接需求不同，分组本身不保证稳定性。

```yaml
proxy-groups:
  - name: "🚀 节点选择"
    type: select
    use: [airport]
    proxies: ["♻️ 自动选择", DIRECT]

  - name: "♻️ 自动选择"
    type: url-test           # 按探测延迟选择节点，不代表下载速度最快
    use: [airport]
    url: http://www.gstatic.com/generate_204
    interval: 300
    tolerance: 50

  - name: "🤖 AI 工具"
    type: select             # AI 服务建议手动固定节点，频繁换 IP 容易触发风控
    use: [airport]
    # 导入后在此组手动选择一个具体节点，不经自动选择组

  - name: "🎬 流媒体"
    type: select
    use: [airport]
    proxies: ["🚀 节点选择"]

  - name: "🐟 漏网之鱼"
    type: select
    proxies: ["🚀 节点选择", DIRECT]
```

#### 规则集与分流规则

`rule-providers` 使用社区维护的规则集，免去手工维护几千条域名：

```yaml
rule-providers:
  reject:
    type: http
    behavior: domain
    url: "https://cdn.jsdelivr.net/gh/Loyalsoldier/clash-rules@release/reject.txt"
    path: ./ruleset/reject.yaml
    interval: 86400
  proxy:
    type: http
    behavior: domain
    url: "https://cdn.jsdelivr.net/gh/Loyalsoldier/clash-rules@release/proxy.txt"
    path: ./ruleset/proxy.yaml
    interval: 86400
  direct:
    type: http
    behavior: domain
    url: "https://cdn.jsdelivr.net/gh/Loyalsoldier/clash-rules@release/direct.txt"
    path: ./ruleset/direct.yaml
    interval: 86400
  private:
    type: http
    behavior: domain
    url: "https://cdn.jsdelivr.net/gh/Loyalsoldier/clash-rules@release/private.txt"
    path: ./ruleset/private.yaml
    interval: 86400
  cncidr:
    type: http
    behavior: ipcidr
    url: "https://cdn.jsdelivr.net/gh/Loyalsoldier/clash-rules@release/cncidr.txt"
    path: ./ruleset/cncidr.yaml
    interval: 86400
  lancidr:
    type: http
    behavior: ipcidr
    url: "https://cdn.jsdelivr.net/gh/Loyalsoldier/clash-rules@release/lancidr.txt"
    path: ./ruleset/lancidr.yaml
    interval: 86400

rules:
  # --- AI 工具：放在最前面，优先级最高 ---
  - DOMAIN-SUFFIX,openai.com,🤖 AI 工具
  - DOMAIN-SUFFIX,chatgpt.com,🤖 AI 工具
  - DOMAIN-SUFFIX,oaistatic.com,🤖 AI 工具
  - DOMAIN-SUFFIX,oaiusercontent.com,🤖 AI 工具
  - DOMAIN-SUFFIX,anthropic.com,🤖 AI 工具
  - DOMAIN-SUFFIX,claude.ai,🤖 AI 工具
  - DOMAIN-SUFFIX,githubcopilot.com,🤖 AI 工具
  - DOMAIN-SUFFIX,copilot.github.com,🤖 AI 工具
  - DOMAIN-SUFFIX,cursor.com,🤖 AI 工具
  - DOMAIN-SUFFIX,cursor.sh,🤖 AI 工具
  - DOMAIN-SUFFIX,generativelanguage.googleapis.com,🤖 AI 工具
  - DOMAIN,gemini.google.com,🤖 AI 工具

  # --- 流媒体 ---
  - DOMAIN-SUFFIX,netflix.com,🎬 流媒体
  - DOMAIN-SUFFIX,nflxvideo.net,🎬 流媒体
  - DOMAIN-SUFFIX,disneyplus.com,🎬 流媒体
  - DOMAIN-SUFFIX,disney-plus.net,🎬 流媒体
  - DOMAIN-SUFFIX,tiktokv.com,🎬 流媒体
  - DOMAIN-SUFFIX,tiktokcdn.com,🎬 流媒体
  - DOMAIN-SUFFIX,spotify.com,🎬 流媒体
  - DOMAIN-SUFFIX,max.com,🎬 流媒体

  # --- 通用规则集 ---
  - RULE-SET,private,DIRECT
  - RULE-SET,reject,REJECT
  - RULE-SET,direct,DIRECT
  - RULE-SET,proxy,🚀 节点选择
  - RULE-SET,lancidr,DIRECT,no-resolve
  - RULE-SET,cncidr,DIRECT,no-resolve
  - GEOIP,CN,DIRECT
  - MATCH,🐟 漏网之鱼
```

</details>

导入后先在「🤖 AI 工具」组选择具体节点，再验证平台访问。规则只覆盖列出的域名及社区规则集，不保证覆盖某项服务的所有请求；需要时结合客户端日志补充。

#### 几个容易踩的坑

| 现象 | 常见原因 | 处理方向 |
| --- | --- | --- |
| 节点能连、网页打不开 | 系统代理、DNS、路由或节点出口异常 | 先查代理是否生效、解析是否成功及连接日志；再按原因调整，不必强制使用 fake-ip |
| AI 平台提示地区或访问受限 | 出口地区、IP 信誉、账号状态或平台策略 | 核对平台支持地区与报错；在允许使用的地区验证后固定具体节点 |
| 国内网站也走了代理 | 全局模式、规则缺失或先匹配到代理规则 | 检查连接日志实际命中的规则，将需要的直连规则放在兜底规则之前 |
| 订阅更新后分组消失 | 客户端覆盖了本地配置 | 用客户端的「覆写 / Merge」功能，不要直接改自动生成的文件 |
| 规则集拉不下来 | jsDelivr 被干扰 | 换 `https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/` 前缀 |

---

<a id="client-config"></a>

### 📲 Nextin / Shadowrocket / sing-box / v2rayN 订阅导入

#### Nextin（星拓，iOS / iPadOS / Apple TV）

Nextin 是通用客户端，免费下载、含内购。是否适配你的机场，以及所需功能是否收费，以机场说明与应用当前版本为准。下载条件见 [客户端表](#clients)。

1. **官网提供识别码：** 使用本机场给出的识别码，按其指引填写机场账号密码，加载节点。
2. **官网明确支持订阅导入：** 使用官网提供的兼容订阅格式；不要把任意客户端链接都视为可互换。

允许系统 VPN 配置权限，选择规则模式与节点后连接。识别码无效时先核对来源或联系客服；只有机场明确开放订阅时才改用链接导入。不要向来源不明的 App 输入账号凭证。

#### Shadowrocket（iOS）

1. 复制机场提供的订阅链接。
2. 打开 Shadowrocket → 右上角 `+` → 类型选择 **Subscribe**。
3. URL 粘贴订阅链接，备注随意填 → 保存。
4. 回到首页下拉刷新，节点列表会自动拉取。
5. 首页顶部开关打开，选一个节点即可。

> 需要分流的话：`配置` → 选中当前配置 → 编辑，规则写法与 Clash 不同，按 Shadowrocket 自己的 `RULE-SET` 语法填。

#### sing-box

sing-box 通常直接导入机场提供的 sing-box 订阅（如果机场支持）。下面仅演示出站片段，缺少入站、DNS 和路由设置，不能单独当作完整配置运行。字段兼容性需按所用 sing-box 版本核对：

<details>
<summary>展开 sing-box 出站片段</summary>

```json
{
  "outbounds": [
    {
      "type": "selector",
      "tag": "proxy",
      "outbounds": ["auto", "direct"],
      "default": "auto"
    },
    {
      "type": "urltest",
      "tag": "auto",
      "outbounds": ["节点A"],
      "url": "http://www.gstatic.com/generate_204",
      "interval": "5m"
    },
    {
      "type": "trojan",
      "tag": "节点A",
      "server": "example.com",
      "server_port": 443,
      "password": "YOUR_PASSWORD",
      "tls": { "enabled": true, "server_name": "example.com" }
    },
    { "type": "direct", "tag": "direct" }
  ]
}
```

</details>

使用图形客户端时，优先导入其明确支持的订阅格式；只有自建或调试时才需要手写 JSON。

#### v2rayN（Windows）

1. 主界面 → `订阅` → `订阅设置`。
2. 新增一条，备注填机场名，地址填订阅链接。
3. 更新订阅；入口可直连时选“不经过代理”，必须经代理访问时使用已有可用连接更新。
4. 节点列表出现后，右键某个节点 → `设为活动服务器`。
5. 任务栏图标右键 → `系统代理` → `自动配置系统代理`。

> v2rayN 从 6.x 起支持 Xray 与 sing-box 双内核，协议无法使用时，先核对所选内核及版本是否支持，再检查节点配置和报错。

---

<a id="glossary"></a>

### 📖 线路与协议术语对照表

买机场时最常见的看不懂的词，一张表说清楚。

| 术语 | 含义 | 对你意味着什么 |
| --- | --- | --- |
| **直连** | 客户端直接连接目标代理服务器 | 表现取决于网络路径；品牌所说“三网直连入口”不等于整条链路走公网 |
| **中转** | 请求经过中转服务器再到出口 | 质量取决于路径、带宽、负载与维护 |
| **IEPL / IPLC** | 以太网专线 / 国际专用电路服务 | 线路标签不能单独证明带宽或晚高峰体验，距离也会影响延迟 |
| **BGP 中转** | 使用多线网络接入的中转方案 | 需测试自己运营商的实际路径与拥堵情况 |
| **落地 IP** | 目标网站看到的代理出口地址 | 地区、信誉与共享情况会影响平台访问，但不是唯一因素 |
| **原生 IP** | 行业中常指登记或地理识别地区与实际出口地区相符的 IP，用法不统一 | 不等于住宅 IP，不保证平台放行；需核对具体含义和检测方法 |
| **住宅 / 数据中心 IP** | 按网络归属和用途划分的出口类型 | 与“原生”不是同一维度，平台可能结合账号、地区和行为判断 |
| **广播 IP** | 行业内常用于描述跨地区使用的 IP 地址段，并非严格统一的分类 | 地址登记地区与地理数据库识别可能不同，不能据此直接判断是否可用 |
| **Shadowsocks / SS2022** | 加密代理协议及其后续规范 | SS2022 需要兼容的客户端与服务端，协议名不代表带宽 |
| **Trojan** | 使用 TLS 传输的代理协议 | 需要相应客户端与证书配置，不能承诺不会被识别 |
| **VMess / VLESS** | 常见代理协议，VLESS 本身不提供加密层 | 安全性与兼容性需结合 TLS / REALITY 等具体传输配置判断 |
| **Hysteria2** | 基于 QUIC 的代理协议 | 表现取决于 UDP 可用性、丢包及带宽配置 |
| **AnyTLS** | 基于 TLS 的代理协议 | 客户端、内核与服务端必须兼容 |
| **倍率** | 节点消耗配额的系数 | 0.5x 表示传输 1GB 按 0.5GB 计费，3x 则按 3GB；核对面板规则 |
| **fake-ip** | DNS 返回合成地址并由代理映射域名的一种模式 | 是可选方案；兼容性需实测，不是网页可访问的必要条件 |

---

<a id="choose"></a>

## ❓ 选购核对清单：把宣传变成可验证的问题

先确认自己的设备与用途，再用下表核对。线路名称、运营年限和节点数量都不能代替本地测试。

| 需求 | 重点验证 | 不能只凭什么下结论 |
| --- | --- | --- |
| AI / IDE / API | 平台支持地区、登录、连续会话与请求成功情况 | 网页可打开、“原生 IP”标签 |
| 视频 | 所需内容库、实际播放清晰度、晚高峰缓冲 | 单次峰值带宽、低延迟 |
| 办公 | 会议、上传、丢包、客户端兼容与故障处理渠道 | 专线名称、在线率宣传 |
| 轻度备用 | 首次实付、有效期、配额与重置条件 | 折合月价、所谓“永久” |

### 🔎 五项买前核对

| 项目 | 需要查到的内容 | 查不到时怎么处理 |
| --- | --- | --- |
| 线路与地区 | 入口、出口地区、套餐权限；最好有带日期的样本 | 只当待验证信息，不据此推断速度 |
| 常用时段 | 自己常用时间的连续播放、会话与传输表现 | 先选可承受的短周期，不凭白天截图买长期 |
| 平台访问 | 目标账号与功能的实际结果，地区与 IP 是否合适 | 注册前询问限制，购买后逐项验证 |
| 售后与应急 | 可联系的客服、公告、备用入口与故障处理记录 | 找不到处理渠道时谨慎付款 |
| 套餐条款 | 付款周期、流量、设备/IP 上限、共享和退款条件 | 先问清；“不退款”是风险条件，不等于服务必然差 |

### 💰 怎样比较真实成本

- **月付与年付：** 比较首次实付和承担的周期，不用折合月价冒充月付门槛。
- **周期包与流量包：** 前者核对重置日期；后者核对总流量和有效期。不重置不等于套餐不合理。
- **设备与共享：** 不限设备不代表可以合租；BoostNet 禁止共享，悠兔个人档也有共享限制。
- **试用与退款：** 只有官网明确提供才纳入决策，确认申请期限、扣费和已用流量条件。
- **备用线：** 先核算两家实际合计费用，确认不同故障下能否切换；按实际需要选择备用流量档。

### ⚠️ 免费与超低价服务怎样看

来源不明、没有可核对条款或缺少维护渠道的服务，不适合承载重要账号和持续办公。付费本身也不能证明隐私或稳定性。不要安装来历不明的客户端、证书或忽略浏览器安全警告。

比较低价方案时，先看配额、限制、维护与故障记录，再判断预付金额和使用条件是否可接受。付款前的统一检查见 [购买建议](#risk)。

---

<a id="ssssr"></a>

## ✈️ 什么是"机场"？

已经知道的可以跳过这一章。

**机场** 是基于 Shadowsocks、V2Ray、Trojan 等协议搭建的代理订阅服务。叫"机场"是因为用户像选航班一样，从订阅里挑不同国家和地区的节点。一句话：**机场 = 提供多节点、多地区、多协议的科学上网订阅服务**。

它的链路是这样的：

```text
你的设备 → 入口服务器 → 中转/专线通道 → 落地节点 → 目标网站
```

- **入口链路** —— 把请求接进机场系统，入口稳不稳决定你能不能先连上
- **中转 / 专线** —— `IEPL`、`IPLC`、`BGP 中转` 等，决定延迟、抗波动和晚高峰表现
- **落地节点** —— 决定出口 IP 质量，直接影响 ChatGPT、Claude、Netflix、TikTok 的解锁表现

这三段里任何一段出问题都会体感变差，所以排查时也要按这个顺序想。各类线路和协议的区别见 [术语表](#glossary)，和 VPN 的差异见 [机场 vs VPN](#vs)。

典型用途：AI 工具与编程（ChatGPT / Claude / Copilot / Cursor）、流媒体解锁（Netflix / Disney+ / YouTube / TikTok）、远程办公（GitHub / Docker Hub / Figma / Notion / Google Workspace）、跨境业务（TikTok / Shopify / Amazon / 广告投放）、多设备统一分流。

---

<a id="risk"></a>

## ⚠️ 购买建议与风险提醒

1. **第一次购买，大多数机场优先月付 / 季付**：先用短周期验证你所在地区、运营商、常用节点和 AI / 流媒体场景是否正常。
2. **不要迷信“绝对稳定”宣传**：没有任何一家机场能在所有地区、所有时段、所有运营商下都表现完全一致。谁还在高调承诺“永不拔线”“100% 稳”，谁就更值得警惕。
3. **按中断成本决定是否准备备用**：对连续办公有要求时，可准备第二家并测试故障切换。不同品牌或协议不代表底层线路一定独立。
4. **紧盯公告和入口变化**：Telegram / 邮件渠道发布的“入口变更”“节点迁移”“临时维护”要及时处理；套餐周期、价格和可购买状态以结算页和公告为准。
5. **订阅链接不要外传，账号规则要看清**：很多机场禁止共享、限制异常登录或频繁重置，违规后可能直接封号或限速。
6. **合法合规**：严禁利用机场从事任何违法活动，否则账号冻结、追责风险自负。

---

<a id="免责声明"></a>

## 📌 免责声明

内容依据已有公开资料、使用记录与用户反馈整理。套餐、入口和客户端政策可能变化，截图仅代表对应日期与环境；作者不保证未来可用性、平台访问或退款结果。购买前自行核对条款，并遵守所在地法律法规。

---

<a id="vs"></a>

## 🔎 机场与 VPN：按具体服务比较

| 维度 | 商用 VPN 常见形态 | 机场订阅常见形态 |
| --- | --- | --- |
| 接入方式 | 官方应用，部分支持标准协议配置 | 官方客户端或订阅导入，按服务商支持方式选择 |
| 分流 | 取决于应用和系统，有的支持分应用或规则 | 通用客户端通常可自定义规则，官方方案可能有限制 |
| 地区与节点 | 数量与覆盖因产品和套餐而异 | 同样受套餐权限、维护与节点地区影响 |
| 表现 | 看本地连接、路径、负载和维护 | 同样需要测试；“专线”标签不代表任何地区都低延迟 |
| 费用与售后 | 核对首次实付、续费、退款及设备条款 | 核对周期、流量倍率、共享与退款条款 |

选购时比较具体产品与本地体验，不按类别判断谁一定更快、更安全或不会停服。开发者若需要自定义分流，优先确认客户端和订阅格式；希望一键使用则先确认官方应用支持自己的设备。

---

<a id="faq"></a>

## ❓ 常见问题 FAQ

### 1. 第一次买，到底选哪家？

综合日常先看 [BoostNet](#boostnet) 的 200GB 月付档。需要 Clash 等通用客户端时，BoostNet、悠兔和 [WgetCloud](#wgetcloud) 都可选；偏高预算办公、能接受季付实付门槛时再重点看 WgetCloud；想先用月付验证 IEPL 与晚高峰视频表现，看 [悠兔](#youtu) 的 150GB 档，确认需求后再考虑 300GB 档。付款前先核对设备和地区限制。

### 2. 应该月付、季付还是年付？

第一次买建议先月付或季付。先验证你所在地区、运营商、常用设备和 ChatGPT / Claude / YouTube / Netflix 等场景都正常，再考虑长期套餐。

### 3. ChatGPT / Claude / Cursor 选哪家？

综合主力先看 [BoostNet](#boostnet) 或 [WgetCloud](#wgetcloud)；更看重高端 IEPL 和晚高峰视频表现看 [悠兔](#youtu)；对原生或高质量出口、IDE 登录更敏感时补看 [TNTCloud](#tnt)。具体可用性以节点和平台风控为准。

配置上还有一点容易忽略：AI 工具的代理分组建议**手动固定节点**，不要用自动选择，频繁换 IP 更容易触发风控。写法见 [Clash 配置模板](#clash-config)。

### 4. TikTok / 跨境电商选哪家？

优先看 [唯兔云](#weituyun)，它更强调东南亚、印度、韩国及部分欧美节点覆盖，适合多区域业务和账号运营。需要更高质量专项出口时搭配 [TNTCloud](#tnt)。这类场景不要只看价格，先确认目标地区节点、账号登录地区和平台风控表现。

### 5. 官方客户端、Clash、Nextin 怎么选？

[WgetCloud](#wgetcloud)、[BoostNet](#boostnet)、[悠兔](#youtu) 均支持 Clash 等通用客户端，BoostNet 和悠兔也提供官方客户端。青云梯、银河云、唯兔云、TNTCloud 当前只支持官方客户端。iOS 上若机场明确支持 Nextin，可按其识别码或订阅指引接入；App 免费下载、含内购，下载地区和功能费用另行核对。需要自定义规则时再确认订阅格式和客户端版本是否兼容，详见 [客户端配置与订阅](#config)。

### 6. 下单前最应该核对什么？

套餐周期、每月流量、设备限制、客户端要求、退款规则和最终结算金额。价格一律以官网结算页为准。

### 7. 买了不能用，先排查什么？

按顺序来：

1. 是否用了机场当前明确支持的客户端和版本
2. 是否更新节点列表或订阅，并测试过适合目标平台的其他节点
3. 是否看过官网公告、入口变更和客户端版本要求
4. 是否只在某个设备或某个本地网络下不可用
5. 仍不可用就带上设备、系统、运营商和报错截图联系客服

能连上但网页打不开，还需检查系统代理、规则命中、DNS 与节点出口，见 [配置排障](#clash-config)。**不要只凭一个节点、一张测速图或一次失败就判断整家机场不可用。**

### 8. 怎样降低服务停运的损失？

运营记录和公开联系渠道可用于了解维护情况，但不能排除停运风险。控制预付金额和周期，保存购买与条款记录；确实需要连续使用时，准备并测试第二条连接。不要把长期运营、热闹群聊或“永久套餐”当作保障。

> 📖 概念类问题（机场是什么、和 VPN 什么区别、免费机场能不能用、支持哪些平台）分别见 [什么是机场](#ssssr)、[机场 vs VPN](#vs)、[避坑指南](#choose) 和 [全平台客户端下载](#clients)。

---

<a id="daily-news"></a>

**附加阅读：国外新闻速览**

新闻速览已拆分到独立文件，定时任务会继续更新最近 10 条国外新闻标题与原文链接：[`daily-news.md`](./daily-news.md)。

---

<a id="listweb"></a>

## 🌐 连通之后：常用海外资源

下面按开发、AI 与信息检索用途整理入口。

### 🤖 AI 工具

| 站点 | 说明 | 出口要求 |
| --- | --- | --- |
| [ChatGPT](https://chatgpt.com) | OpenAI 对话服务 | 对 IP 质量敏感，建议固定节点 |
| [Claude](https://claude.ai) | Anthropic 对话，长上下文场景常用 | 同上，频繁换 IP 容易触发验证 |
| [Google AI Studio](https://aistudio.google.com) | Gemini 模型调试与 API key | 需核对服务支持地区与账号条件 |
| [GitHub Copilot](https://github.com/features/copilot) | IDE 内代码补全 | IDE 登录对出口质量更敏感 |
| [Cursor](https://cursor.com) | AI 编辑器 | 同上 |
| [Hugging Face](https://huggingface.co) | 模型与数据集托管 | 拉大模型权重时吃带宽 |

### 👨‍💻 开发与包管理

| 站点 | 说明 |
| --- | --- |
| [GitHub](https://github.com) ｜ [GitLab](https://gitlab.com) | 代码托管 |
| [Docker Hub](https://hub.docker.com) ｜ [ghcr.io](https://github.com/features/packages) | 镜像仓库，pull 大镜像时建议走高带宽节点 |
| [npm](https://www.npmjs.com) ｜ [PyPI](https://pypi.org) ｜ [crates.io](https://crates.io) | 包仓库 |
| [Stack Overflow](https://stackoverflow.com) | 问答 |
| [MDN](https://developer.mozilla.org) | Web 标准文档 |
| [Cloudflare](https://dash.cloudflare.com) ｜ [Vercel](https://vercel.com) | 部署与 CDN 控制台 |

### 🔍 搜索与信息

[Google](https://www.google.com) ｜ [DuckDuckGo](https://duckduckgo.com)（不追踪）｜ [Reddit](https://www.reddit.com) ｜ [Hacker News](https://news.ycombinator.com) ｜ [Google Scholar](https://scholar.google.com)

### 📺 流媒体与社交

[YouTube](https://www.youtube.com) ｜ [Netflix](https://www.netflix.com) ｜ [Disney+](https://www.disneyplus.com) ｜ [Twitch](https://www.twitch.tv) ｜ [TikTok](https://www.tiktok.com) ｜ [X](https://x.com) ｜ [Instagram](https://www.instagram.com)

> 💡 不同站点对出口的要求不一样：AI 服务看 IP 质量，流媒体看地区，包仓库看带宽。分场景走不同代理分组的写法见 [Clash 配置模板](#clash-config)。

---

<a id="contribute"></a>

## 🤝 反馈与贡献

这份榜单靠持续的实测和反馈维护。遇到下面这些情况，欢迎开 Issue：

| 情况 | 请附上 |
| --- | --- |
| 某家机场节点大面积不可用 | 机场名、你的省份与运营商、出现时间、受影响的节点地区 |
| 官网入口打不开 / 换域名了 | 旧入口、你看到的新入口来源（官网公告 / TG 频道） |
| 套餐价格或流量与本文不符 | 结算页截图或链接、查看时间 |
| 客户端要求变了 | 机场名、官网当前列出的支持客户端 |
| 文中链接失效、锚点跳不动 | 章节名或行号 |

> ⚠️ **提 Issue 时不要贴订阅链接、账号密码或任何包含 token 的 URL。** 订阅链接等于账号凭证，贴出来等于把账号送人。需要说明节点情况时，描述地区和数量即可。

如果这份内容帮你少踩了坑，点个 ⭐ Star 让它能被更多人搜到。价格、入口和推荐顺序会持续变化，Star 之后可以在 [提交记录](https://github.com/OpenNetCN/clash/commits/main) 里看到每次更新改了什么。

---
