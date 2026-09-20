# 机场推荐 2026｜Clash机场 / 节点订阅与科学上网实测

[![last commit](https://img.shields.io/github/last-commit/OpenNetCN/clash?label=last%20update)](https://github.com/OpenNetCN/clash/commits/main)
[![stars](https://img.shields.io/github/stars/OpenNetCN/clash?style=flat)](https://github.com/OpenNetCN/clash/stargazers)
[![issues](https://img.shields.io/github/issues/OpenNetCN/clash)](https://github.com/OpenNetCN/clash/issues)

📅 **内容最后更新：2026年09月20日**

> ℹ️ **近期阶段说明：** 机场入口和客户端要求仍会变化，第一次购买优先月付或季付，并以官网结算页与当前公告为准。

还在找 **稳定机场**？现在的关键不是“名单越长越好”，而是先看 **线路证据、使用限制和自己的实际场景**。

这不是一份机场大全。从 2022 年至今我长期自费订阅、对比过 **40+ 家** 机场，主要看晚高峰、AI 工具、流媒体、入口维护和售后响应。先用下面四项确定方向，再看对应评测和购买限制。

<a id="quick-pick"></a>

## 🔥 30 秒选机场（先看这个）

先锁定 1 家主选，最多再留 1 家备用。四家的定位不同，不需要只按排名购买。

| 你的需求 | 首选 | 入门套餐（流量 / 周期） | 为什么 | 下一步 |
| --- | --- | --- | --- | --- |
| 🏆 第一次买长期主力 / AI + 流媒体都要 | **BoostNet** | 200G / ¥49/月 | 自研客户端 + 三网直连 IEPL，综合使用更省心 | [看评测](#boostnet) · [立即注册](https://tw.boostqz.com/?path=register&code=kKMFirlm) |
| 💎 老牌旗舰 / 稳定性优先 / 通用客户端 | **WgetCloud** | 200G/月，约 ¥79/月起 | 老牌高端机场，极致稳定，客服响应快，支持 Clash 等通用客户端，覆盖节点齐全 | [看评测](#wgetcloud) · [立即注册（需外网）](https://invite.wgetcloud.ltd/auth/register?code=kVJQPh) |
| 🌤 年付省心 / 家庭多设备 | **青云梯** | 每月 60G / ¥96/年 | 老牌 IPLC 专线，适合长期低成本使用 | [看评测](#qingyunti) · [立即注册](https://realvtest.qytvipaff.cc/register?aff=zcIlh0VY) |
| 🤖 原生 / 高质量 IP / IDE 登录稳定 | **TNTCloud** | 110G / ¥20/月 | IPLC 专线 + 高质量出口，适合专项 AI 与登录场景 | [看评测](#tnt) · [立即注册](https://tanu095.tntvipaff.cc/#/register?code=7MPbfr89) |

<a id="client-tip"></a>

📖 如果需要查看更多机场信息，请直接跳转到 [精选机场深度评测（2026 最新）](#top7) 章节。

📡 想确认近期节点状态，可以查看 [每日节点可用性观测](#daily-check)。

📌 有外网环境的用户，也可以访问 [https://gptvpnhelper.com/](https://gptvpnhelper.com/) 查看排版和测速图更完整的网页版。

💡 **建议 Star 仓库并收藏书签。** 机场价格、入口地址和推荐顺序会持续变化，后续以顶部更新时间和正文说明为准。

### 🧩 主力 + 备用怎么配

一主一备是性价比最高的配置：主力扛日常，备用只在主力波动时顶上，不用买大流量。

| 组合 | 主力负责 | 备用负责 |
| --- | --- | --- |
| **BoostNet + 悠兔** | BoostNet 扛全部日常 | 悠兔顶晚高峰视频和主力波动期 |
| **BoostNet + TNTCloud** | BoostNet 扛综合场景 | TNTCloud 专供 IDE 登录、API 调用等敏感出口 |
| **悠兔 + 银河云** | 悠兔扛高码率视频 | 银河云年付兜底，成本压到最低 |
| **青云梯 + 银河云** | 青云梯做家庭年付主用 | 银河云做低价第二条 |
| **唯兔云 + TNTCloud** | 唯兔云覆盖东南亚等业务地区 | TNTCloud 补高质量出口 |

> 💡 两条都先月付跑两周，确认本地表现后再把主力那条转年付，备用那条保持最低档即可。

### ⚠️ 五个最常见的买错方式

- **第一次买就上三年付 / 永久套餐** —— 你还没验证过本地运营商的表现。先月付或季付，跑通了再谈长期。
- **只是临时查点资料，却买了高价年付** —— 短测用月付或季付就够，预算实在低就看 [银河云](#yinheyun)。
- **主要用 ChatGPT / Claude / Cursor，却图省钱用免费机场** —— 来路不明的节点在 AI 平台这边风控最严。综合主力看 [BoostNet](#boostnet) / [悠兔](#youtu)，专项出口补 [TNTCloud](#tnt)。
- **做 TikTok / 跨境业务，只按最低价挑** —— 这类场景先确认目标地区有没有节点、账号登录地区对不对，价格是最后一个变量。
- **团队办公刚需，只比套餐单价** —— 真正决定成本的是设备限制、客服响应速度和退款规则。

🧭 想直接看结论，跳到 [个人快速推荐清单](#person)。  
🧑‍🎓 第一次配置，先看 [3 分钟从零开始科学上网教程](#study)。  
⚠️ 想先看避坑建议，直接跳到 [购买建议与风险提醒](#risk)。

---

### 🧪 这份名单是怎么筛出来的

从 2022 年至今长期自费订阅，对比过 40+ 家，当前只保留七家。判断依据按权重排下来是：

1. **稳定性（最高权重）** —— 晚高峰 `20:00-22:00` 是否频繁掉线、入口失效后多久恢复、订阅是否容易失效。不看白天跑分截图。
2. **AI 工具** —— ChatGPT / Claude / Copilot / Cursor 能不能稳定登录、长时间对话、连续开发调用，而不只是"网页能打开"。
3. **流媒体** —— YouTube 4K/8K、Netflix、Disney+、TikTok 能否稳定播放。
4. **线路与出口** —— IEPL / IPLC / 中转质量、出口 IP 质量、热门地区覆盖。
5. **套餐透明度**（中）—— 价格、流量、设备限制、退款规则写没写清楚。
6. **售后响应**（中）—— 节点、客户端、套餐、入口问题能不能闭环。

其中第 1 项有可复现的数据支撑：[每日节点可用性观测](#daily-check) 每天跑一次连通性探测并提交一次 commit，历史快照可以直接翻仓库提交记录。其余维度靠长期使用观察，不做数字化。

> 📌 不同地区、运营商、设备和时间段都会影响实际体验。样本不足的新机场暂不展示评分。购买前仍需核对结算页价格、官方公告和当前客户端要求。

> ⚠️ **网络环境特别说明（省墙）**  
> 如果你遇到“所有节点都不可用”，除了机场本身问题，也可能是本地网络、运营商或地区策略导致。遇到这种情况，先更新订阅、切换入口或联系机场客服确认，不要只看单个测速截图下结论。

---

## 📚 目录

1. [30 秒选机场（先看这个）](#quick-pick)
2. [按需求直接选：我的个人推荐](#person)
3. [每日节点可用性观测](#daily-check)
4. [精选机场深度评测](#top7)
5. [七大精选机场对比表格](#top9-table)
6. [网页版与单项测评入口](#web-entry)
7. [新手教程：3 分钟从零开始科学上网](#study)
8. [客户端配置与订阅（GitHub 专区）](#config)
   - [全平台客户端下载](#clients)
   - [Clash / Mihomo 配置模板](#clash-config)
   - [Shadowrocket / sing-box / v2rayN 订阅导入](#client-config)
   - [线路与协议术语对照表](#glossary)
9. [如何挑选靠谱机场？2026 避坑指南](#choose)
10. [什么是机场？](#ssssr)
11. [购买建议与风险提醒](#risk)
12. [免责声明](#免责声明)
13. [机场 vs VPN：哪个好用？](#vs)
14. [常见问题 FAQ](#faq)
15. [最新国外新闻速览](#daily-news)
16. [常用网站推荐](#listweb)
17. [反馈与贡献](#contribute)

---

<a id="person"></a>

## ✨ 按需求直接选：我的个人推荐

如果只按“实际购买决策”来分，我会把当前推荐压缩成下面几类。这里不重复堆参数，具体测速、套餐和使用细节继续看后面的深度评测。

| 需求场景 | 优先选择 | 备选/补充 | 购买建议 |
| --- | --- | --- | --- |
| AI + 流媒体综合主力 | [BoostNet](#boostnet) | [WgetCloud](#wgetcloud) | BoostNet 默认看 200G/月；更看重老牌稳定性和通用客户端可选 WgetCloud |
| 稳定性优先 / 团队办公 | [WgetCloud](#wgetcloud) | [BoostNet](#boostnet) | 老牌旗舰，支持通用客户端，200G/月基础档，价格以官网结算页为准 |
| 长期主用 / 晚高峰视频 | [悠兔](#youtu) | [BoostNet](#boostnet) | 悠兔默认看 300G/月，想先试线路可从 150G/月开始 |
| 年付省心 / 家庭多设备 / 老牌稳定长期用 | [青云梯](#qingyunti) | [银河云](#yinheyun) | 更适合想长期年付、省心使用和多设备一起用的用户 |
| ChatGPT / Claude / Cursor / IDE 登录 | [BoostNet](#boostnet) | [TNTCloud](#tnt) | 先保证综合稳定，再按需补专项出口 |
| TikTok / 跨境电商 / 多区域业务 | [唯兔云](#weituyun) | [TNTCloud](#tnt) | 先确认目标地区节点和账号场景，不要只看最低价 |
| 预算优先 / 年付备用 | [银河云](#yinheyun) | [青云梯](#qingyunti) | 低预算可以年付备用；更看重老牌稳定和家庭多设备再看青云梯 |


> 🛡️ **作者补充：** `BoostNet / 悠兔 / WgetCloud` 价格确实稍贵一点，但今年 4 月那波对机场的集中打击里，它们的**恢复能力是我观察到最强的**——基本很快就恢复可用，客服也全程能联系上，不会出现「机场用不了、客服又失联」的情况。愿意为稳定多花一点的用户，这三家更让人安心。

---

<a id="daily-check"></a>

## 📡 每日节点可用性观测

| 机场名称 | 测试客户端 | 最后检查日期 | 服务状态 | 总节点数量 | 可用节点数量 | 可用节点比例 | 历史可用节点比例 | 稳定性 |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | --- |
| [BoostNet](#boostnet) | 官方客户端 | 2026-09-20 | 可用 | 45 | 44 | 97.78% | 94.76% | 高 |
| [悠兔](#youtu) | 官方客户端 | 2026-09-20 | 可用 | 51 | 45 | 88.24% | 93.00% | 高 |
| [TNTCloud](#tnt) | 官方客户端 | 2026-09-20 | 可用 | 50 | 50 | 100.00% | 98.57% | 高 |
| [青云梯](#qingyunti) | 官方客户端 | 2026-09-20 | 可用 | 61 | 61 | 100.00% | 98.83% | 高 |
| [银河云](#yinheyun) | 官方客户端 | 2026-09-20 | 可用 | 34 | 34 | 100.00% | 98.11% | 高 |
| [唯兔云](#weituyun) | 官方客户端 | 2026-09-20 | 可用 | 73 | 65 | 89.04% | 92.56% | 高 |
| [WgetCloud](#wgetcloud) | Clash Verge | 2026-09-20 | 可用 | 29 | 29 | 100.00% | 100.00% | 高 |

#### 📈 这份数据是怎么来的

- **检测方式：** 本地定时任务逐个拉取订阅，对每个节点做 HTTP 连通性探测（`http://www.gstatic.com/generate_204`），统计返回 204 的比例。
- **"可用节点比例"** 是当次检测的快照；**"历史可用节点比例"** 是累计均值，后者更能反映一家机场的长期稳定性。
- **检测环境：** 单一地区、单一运营商、固定时间点。**它不等于你本地的表现** —— 同一家机场在不同省份、不同运营商、不同时段的结果可能差别很大。
- **只看连通性，不看速度。** 节点"可用"不代表"跑得快"，带宽和晚高峰表现请看各家评测段落里的实测图。

---

<a id="top7"></a>

## 🏆 精选机场深度评测（2026 最新）

> 本次评测从超过 **40+ 热门机场服务商**中精挑细选，当前保留七款覆盖不同使用场景的机场。名单涵盖综合主力、多国家与家宽 IP、高端 IEPL、平价主力和低价备用；具体表现仍需结合本地网络与实际节点判断。

这些机场均经过实测或长期观察，主流节点通常可用于 ChatGPT、YouTube、Netflix 等常见平台访问，并具备相对较好的连接稳定性和流媒体适配能力；具体表现仍以实际节点、平台风控和本地网络为准。

🧭 无论你的需求是“高稳定性办公场景”、还是“流媒体刷剧党”，或是“低价备用应急”，这份清单都为你准备好了对应的优选方案。

<a id="boostnet"></a>

### 1. ⚡ BoostNet — 综合主力首推，自研客户端，三网直连 IEPL

**综合评分 9.6 / 10**｜三网直连 IEPL · Anytls · 香港 HGC 落地 · 2024 年运营

- **适合谁：** 想少折腾、直接上一条长期主力线的中高强度用户，`AI + 流媒体 + 远程办公` 一起用最合适
- **不适合：** 预算极低、只偶尔用一下的轻度用户（看 [银河云](#yinheyun)）
- **为什么排第 1：** 不是某一项最极端，而是「客户端省心 + 综合稳定 + AI/流媒体都能打 + 客服响应快」结合得最好
- **核心参数：** Anytls 协议｜全球 5+ 地区 30+ 节点（企业档 10+ 地区 40+ 节点，以实际订阅为准）｜常规 5 台设备 / 企业档 30 台｜支付宝 · 微信
- **客户端：** Windows / Mac / 安卓一键客户端，以官方服务文档为准
- **怎么买：** 日常主力优先 **200G/月（¥49）**；多设备 **400G/月（¥79）**；重度 **1000G/月（¥129）** ｜ 👉 [立即注册 BoostNet](https://tw.boostqz.com/?path=register&code=kKMFirlm)

| 套餐 | 价格 | 每月流量 | 手动重置 | 备注 |
| --- | ---: | ---: | ---: | --- |
| 每月20G流量套餐 | ¥200 / 年 | 20GB | ¥17 / 次 | 轻量套餐 |
| **200G流量套餐** | **¥49 / 月** | 200GB | ¥50 / 次 | 爆款，日常主力优先 |
| 400G流量套餐 | ¥79 / 月 | 400GB | ¥80 / 次 | 多设备 / 偏重度 |
| 1000G流量套餐 | ¥129 / 月 | 1000GB | ¥130 / 次 | 重度 |
| 企业团队套餐 | ¥388 / 月 | 1500GB | ¥388 / 次 | 30 台设备，全球 10+ 地区 40+ 节点 |

> 🔄 **重置规则：** 每月购买日免费重置，几号买下月几号过期；提前用完需单独买重置包。
>
> ⚠️ **购买前必看：** 禁止共享他人使用；**仅限中国大陆，新疆不可用，境外不可用**；禁 BT / P2P / PT；**不提供退款**。

> 🔗 **立即注册：** [BoostNet](https://tw.boostqz.com/?path=register&code=kKMFirlm)
> 💰 **价格口径：** 以官网结算页最终显示为准（套餐按 2026-04-28 整理）

📖 完整测速图、解锁实测与使用细节 → [BoostNet 机场测评](https://gptvpnhelper.com/boostnet/)

---

<a id="wgetcloud"></a>

### 2. 💎 WgetCloud — 老牌旗舰，稳定性优先，支持通用客户端

**综合评分 9.5 / 10**｜广州 BGP → IEPL 专线 · 自研控制面板 · 2021 年成立

- **适合谁：** 团队办公、内容创作、把稳定性放在首位的用户，以及需要 Clash 等通用客户端的人
- **不适合：** 只想要最低价、日常轻度使用的用户（看 [青云梯](#qingyunti) / [银河云](#yinheyun)）
- **当前态度：** 质量认可，但年付门槛高，**除团队办公和高预算刚需外不建议普通用户优先买**
- **核心参数：** Trojan 主协议 + Shadowsocks（路由器兼容）｜当前监测 29 节点覆盖五大洲｜全节点 Full-Cone UDP｜按档 3 / 4 / 5 个在线 IP｜工单 + 邮件，平均回复 1-3 小时
- **客户端：** 支持 Clash 等通用客户端（七家里唯一不受官方客户端口径限制的）
- **怎么买：** 想控制预算从 **基础专线服务（约 ¥79/月）** 起步；AI 与远程协作更重看 **优质专线服务** ｜ 👉 [立即注册 WgetCloud（需外网环境）](https://invite.wgetcloud.ltd/auth/register?code=kVJQPh)

| 套餐 | 价格 | 核心配置 | 峰值带宽 / 连接数 | 适合谁 |
| --- | ---: | --- | --- | --- |
| 基础专线服务 | 约 ¥79 / 月 | 200G / 30 天重置，3 个在线 IP | 200Mbps / 300 | 入门，日常主力 |
| 优质专线服务 | 约 ¥89 / 月 | 250G / 30 天重置，4 个在线 IP | 300Mbps / 800 | AI、远程协作更重 |
| 精品专线服务 | 约 ¥99 / 月 | 270G / 30 天重置，5 个在线 IP，全球五大洲节点 | 500Mbps / 1500 | 商务、内容创作，含 SLA |

> 📌 **注册入口需要外网环境**，没有可用连接时点击可能打不开。优质 / 精品档支持智能负载均衡。

> 🔗 **立即注册：** [WgetCloud（需外网环境）](https://invite.wgetcloud.ltd/auth/register?code=kVJQPh)
> 💰 **价格口径：** 约 ¥79/月起，以官网结算页最终显示为准

📖 2026-08-10 的 32 节点测速、各平台解锁比例与长测记录 → [WgetCloud 机场测评](https://gptvpnhelper.com/wgetcloud/)

---

<a id="youtu"></a>

### 3. 🐰 悠兔机场 — 长期主用优先，高端 IEPL 专线，多入口中转更稳

**综合评分 9.5 / 10**｜广东电信入口 → 高端 IEPL + 多入口双层加密隧道 · 2022 年运营

- **适合谁：** 想买一条能长期主用、晚高峰依旧稳定的 IEPL 主力线，YouTube / Netflix / ChatGPT / TikTok 高频用户
- **不适合：** 只想挑一条最省心的综合主力、完全不想研究线路差异的人（先看 [BoostNet](#boostnet)）
- **核心参数：** Shadowsocks（不支持 SSR）｜50+ 节点多落地多入口，覆盖港日新美台等主流地区（以实际订阅为准）｜默认 1x 倍率，可切 2x 专线节点｜全节点 UDP｜默认 5 台设备 / 团体档 20 台｜支付宝 · 微信
- **使用限制：** 仅限中国内地；**新疆、港澳台及境外不可用**；禁 SMTP、封 22 端口；不适合 BT / P2P / PT
- **客户端：** 优先官方客户端；通用客户端通常可用，以官网当前支持列表为准（详见 [顶部统一说明](#client-tip)）
- **怎么买：** 试线路优先 **150G/月（¥39）**；当主力优先 **300G/月（¥59）**；重度优先 **500G/月（¥79）** ｜ 👉 [立即注册悠兔（线路1）](https://tw.youtu1.com/?path=register&code=erkQTmbM) ｜ [备用（线路2）](https://tw.youtunice.com/?path=register&code=erkQTmbM)

| 套餐 | 流量 / 周期 | 月付 | 其他周期 | 重置 |
| --- | --- | ---: | --- | ---: |
| 入门首选 | 150G / 月 | ¥39 | 年付 ¥400 | ¥40 / 次 |
| **每月300G** | 300G / 月 | **¥59** | 季 ¥160 / 半年 ¥310 / 年 ¥500 | ¥60 / 次 |
| 每月500G | 500G / 月 | ¥79 | 季 ¥220 / 半年 ¥420 / 年 ¥800 | ¥80 / 次 |
| 每月1000G | 1000G / 月 | ¥119 | - | ¥120 / 次 |
| 轻量年包 | 200G / 年 | - | ¥199 / 年 | 用完续费，不走重置包 |
| 轻量季度包 | 50G / 月 | - | ¥79 / 季 | ¥26 / 次 |
| 团体套餐 | 1500G / 月 | ¥366 | - | 最多 20 台设备 |

> ✅ 所有个人套餐线路和速度一致，主流套餐均支持 GPT、Netflix、Disney+ 和 UDP。

> 🔗 **立即注册：** [悠兔（线路1）](https://tw.youtu1.com/?path=register&code=erkQTmbM) ｜ [备用（线路2）](https://tw.youtunice.com/?path=register&code=erkQTmbM)
> 💰 **价格口径：** 以官网结算页最终显示为准（套餐按 2026-04-28 整理）

📖 2026-04-27 晚高峰 8K HDR 零丢帧实测、多区域测速与解锁图 → [悠兔机场测评](https://gptvpnhelper.com/youtu/)

---

<a id="qingyunti"></a>

### 4. 🌤 青云梯 — 稳定运营 7 年老牌机场，性价比 IPLC 专线，年付 ¥8/月

**综合评分 9.3 / 10**｜企业级 IPLC 专线 · 智能负载均衡 · 2019 年 11 月开业

- **适合谁：** 想找老牌稳定、省心年付、多设备全家用，同时希望 AI / 流媒体都覆盖的人
- **核心优势：** 稳定运营 7 年 + 企业级 IPLC + 智能负载均衡（按本地网络自动分配最优入口），年付 ¥96 起
- **核心参数：** Shadowsocks｜80+ 全专线节点覆盖 17+ 地区（港台日新马美韩泰印尼菲越英德法土巴阿）｜三网优化｜不限系统、支持多设备｜支付宝 · 微信 · USDT｜真人客服实时在线
- **客户端：** 当前特殊时期直接用官方客户端，`Clash / Shadowrocket / V2rayN / Stash` 旧订阅暂不作主方案（详见 [顶部统一说明](#client-tip)）
- **怎么买：** 轻度 / 备用优先 **青云·诀（¥96/年）**；中度主力优先 **VIP1（150GB/月）**；多设备 / 重度优先 **VIP2（300GB/月）** ｜ 👉 [立即注册青云梯](https://realvtest.qytvipaff.cc/register?aff=zcIlh0VY)

| 套餐 | 每月流量 | 月付 | 季付 | 年付 |
| --- | --- | ---: | ---: | ---: |
| **青云·诀** | 60GB | - | - | **¥96（≈¥8/月）** |
| 青云·VIP1 | 150GB | ¥25 | ¥67 | ¥240（≈¥20/月） |
| 青云·VIP2 | 300GB | ¥45 | ¥121 | ¥432（≈¥36/月） |
| 青云·VIP3 | 600GB | ¥85 | ¥229 | ¥916（≈¥76/月） |

> 🔗 **立即注册：** [青云梯（年付 ¥96 / 60G）](https://realvtest.qytvipaff.cc/register?aff=zcIlh0VY)
> 💰 **价格口径：** 以官网结算页最终显示为准

📖 测速图与更完整的线路说明 → [青云梯机场测评](https://gptvpnhelper.com/qingyunti/)

---

<a id="tnt"></a>

### 5. 🔥 TNTCloud — 更看重原生 IP 与专线出口时可看，IPLC 专线，海外团队运营

**综合评分 9.2 / 10**｜IPLC 全专线 · Trojan · 原生 / 高质量 IP · 2024 年成立

- **适合谁：** 已明确需要原生 / 高质量 IP、IDE 登录或专项出口的 ChatGPT / Claude / Copilot / Gemini 深度用户
- **核心优势：** IPLC 全专线 + 原生出口，适合登录验证、长期会话、跨境后台；多节点 TLS RTT < 50ms
- **核心参数：** Trojan｜香港×10、台湾×10、新加坡×10、日本×10、美国×10、德国×1｜不限速、不限倍率、**不限设备数**｜支付宝 · 微信 · U 转账
- **客户端：** **暂不支持** `Clash / Clash Meta / Sing-box / Shadowrocket` 直接导入，请用官网官方客户端（详见 [顶部统一说明](#client-tip)）
- **怎么买：** 轻度优先 **VIP1（110GB）**；专项使用优先 **VIP2（220GB）**；多设备 / 重度优先 **VIP3（440GB）** ｜ 👉 [立即注册 TNTCloud](https://tanu095.tntvipaff.cc/#/register?code=7MPbfr89)

| 套餐 | 流量 / 月 | 价格 | 说明 |
| --- | --- | ---: | --- |
| 季付限量包 | 60GB × 3 月 | ¥30 / 季 | 超低月均，轻量首选 |
| VIP1（轻量） | 110GB | ¥20 / 月 | 日常上网 + 流媒体 |
| **VIP2（中量）** | 220GB | **¥40 / 月** | 主力推荐 |
| VIP3（高量） | 440GB | ¥80 / 月 | 多设备 + 高画质 |
| VIP4（巨量） | 1100GB | ¥160 / 月 | 重度或多人共享 |
| 定制套餐 | 独享 / 定制 | ¥680 / 月 | 专线独享，支持定向功能 |

> 🔗 **立即注册：** [TNTCloud](https://tanu095.tntvipaff.cc/#/register?code=7MPbfr89)
> 💰 **价格口径：** 以官网结算页最终显示为准

📖 测速图与出口质量实测 → [TNTCloud 机场测评](https://gptvpnhelper.com/tntcloud/)

---

<a id="weituyun"></a>

### 6. 🐰 唯兔云 — 2025 新晋 IPLC 专线，SS2022 协议，TikTok / 电商 / 多区域业务专项可看

**综合评分 9.1 / 10**｜IPLC 全专线 · SS2022 · 东南亚节点丰富 · 2025 年运营

- **适合谁：** 明确需要 TikTok 运营、跨境电商、直播带货、东南亚与多区域业务节点，同时兼顾 AI / 流媒体的人
- **核心优势：** IPLC + SS2022，节点不只盯港日美新，还覆盖东南亚五国、印度、韩国及部分欧美
- **核心参数：** SS2022｜港台日美新 + 东南亚五国 + 印度 + 韩国 + 部分欧美（以面板实际订阅为准）｜**无倍率、不限速、不限设备数**｜支付宝 · 微信 · USDT｜多人客服轮班 + 海外技术团队
- **客户端：** 暂不建议用 `Clash / 小火箭 / Shadowrocket / Sing-box`，按官网知识库的官方客户端与导入方式操作。iPhone 用户没有外区账号可直接联系官方获取 iOS 安装指引（详见 [顶部统一说明](#client-tip)）
- **怎么买：** 试水优先 **100GB（月付 ¥14.9）**；当主力优先 **200GB（月付 ¥29.9）**；多设备 / TikTok / 电商运营优先 **500GB（月付 ¥59.9）** ｜ 👉 [立即注册唯兔云](https://realvpn.v2yunvipaff.com/#/?code=5LVpl8Mh)

| 套餐 | 流量 / 月 | 月付 | 季付 | 年付 |
| --- | --- | ---: | ---: | ---: |
| 轻量年付小包 | 45GB | - | - | ¥79.9（≈¥6.7/月） |
| 标准版 | 100GB | ¥14.9 | ¥40.9 | ¥142.9 |
| **进阶版** | 200GB | **¥29.9** | ¥80.9 | ¥286.9 |
| 高流量版 | 500GB | ¥59.9 | ¥161.9 | ¥547.9 |
| 重度版 | 1000GB | ¥119.9 | ¥323.9 | ¥1150.9 |
| 不限时流量包 | 500GB | - | - | 首次 ¥340，续费 9 折 |

> 🔗 **立即注册：** [唯兔云](https://realvpn.v2yunvipaff.com/#/?code=5LVpl8Mh)
> 💰 **价格口径：** 以官网结算页最终显示为准

> ℹ️ 唯兔云暂时没有单独测评页，完整测速图与实测记录见网页版对应段落 → [唯兔云（网页版）](https://gptvpnhelper.com/#weituyun)

---

<a id="yhy"></a>
<a id="yinheyun"></a>

### 7. 🌌 银河云 Galaxy — 年付爆款 ¥98，Trojan 专线，节点丰富

**综合评分 8.9 / 10**｜全线 IEPL 专线 · Trojan · 新加坡团队 · 2023 年 6 月上线

- **适合谁：** 预算优先、希望用较低年付成本获得 IEPL 专线和多设备支持的长期用户，以及家庭共享场景
- **核心优势：** 年付 ¥98 起（每天约 0.27 元）即可用 IEPL 专线，**不限设备数**，支持退款
- **核心参数：** Trojan｜香港×10、台湾×5、新加坡×5、日本×5、美国×5、马来西亚×2、越南×2、菲律宾×2、泰国×2、英国×2、阿根廷×2、土耳其×2｜支付宝 · 微信 · USDT（USDT / VX 联系官网客服）
- **客户端：** 当前优先官方客户端，`Clash / Shadowrocket / Sing-box` 暂不作主方案（详见 [顶部统一说明](#client-tip)）
- **怎么买：** 极低预算长期优先 **年付轻量包（¥98/年）**；中度长期优先 **行星套餐（200GB/月）**；重度优先 **恒星套餐（400GB/月）** ｜ 👉 [立即注册银河云](https://realvtest.galaxyvipaff01.cc/register?aff=tcOd0ob7)

| 套餐 | 流量 / 月 | 月付 | 季付 | 半年付 | 年付 | 两年付 | 三年付 |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: |
| **年付轻量包** | 50GB | - | - | - | **¥98** | - | - |
| 星尘套餐 | 100GB | ¥18 | ¥49 | ¥92 | ¥173 | ¥302 | ¥389 |
| 行星套餐 | 200GB | ¥35 | ¥95 | ¥179 | ¥336 | ¥588 | ¥756 |
| 恒星套餐 | 400GB | ¥70 | ¥189 | ¥357 | ¥672 | ¥1176 | ¥1512 |
| 星系套餐 | 800GB | ¥140 | ¥378 | ¥714 | ¥1344 | ¥2352 | ¥3024 |
| 永久不限时套餐 | 1000GB | - | - | - | - | - | ¥680（一次性） |

> ℹ️ 实际稳定性仍要看本地运营商和晚高峰节点表现。

> 🔗 **立即注册：** [银河云](https://realvtest.galaxyvipaff01.cc/register?aff=tcOd0ob7)
> 💰 **价格口径：** 以官网结算页最终显示为准

📖 测速图与节点分布实测 → [银河云机场测评](https://gptvpnhelper.com/yinheyun/)

---

<a id="七大精选机场对比表格按推荐优先级排序"></a>
<a id="top9-table"></a>

## 📊 七大精选机场对比表格（按推荐优先级排序）

| 定位 | 机场名称          | 协议          | 接入方式       | 起始价格         | AI 友好度       | 流媒体友好度     | 设备限制  | 适合场景       |
| --- | ------------- | ----------- | ---------- | ------------ | ------------ | ---------- | ----- | ---------- |
| 综合主力首选 | **BoostNet**  | Anytls | 三网直连 IEPL  | ¥49起（200G/月） | 强（多数节点可用）    | 强（多数节点解锁）  | 常规 5 台 / 企业 30 台 | 默认先看的 AI + 流媒体综合主力 |
| 长期主用首选 | **悠兔**       | Shadowsocks | 高端 IEPL + 多入口中转 | ¥39起（150G/月） | 强（主流平台可用） | 强（主流平台可用） | 默认 5 台 | 更看重 IEPL、高峰视频和长期持有 |
| 老牌年付优选 | **青云梯**       | Shadowsocks | IPLC 专线    | ¥8/月（年付¥96）  | 强（主流节点可用） | 强（主流节点可用） | 不限    | 年付省心 / 家庭多设备 |
| 专项出口优选 | **TNTCloud**  | Trojan      | IPLC 全专线   | ¥20起         | 强（原生/高质量 IP） | 强（主流平台覆盖较全） | 不限    | 原生 IP / IDE 登录 / 出口偏好 |
| 业务场景优选 | **唯兔云**       | SS2022      | IPLC 全专线   | ¥14.9起（另有¥79.9/年） | 强（主流平台覆盖较全） | 强（主流平台覆盖较全） | 不限    | 电商 / TikTok / 多区域业务 |
| 低预算年付优选 | **银河云**       | Trojan      | IEPL 专线    | ¥18起（年付¥98）  | 强（主流平台覆盖较全） | 强（主流平台覆盖较全） | 不限    | 预算优先 / 年付备用 |
| 老牌旗舰稳定主力 | **WgetCloud** | | Trojan/SS   | BGP+IEPL   | 约 ¥79/月起 | 强（优质/精品更强） | 强（优质/精品更强） | 3-5台  | 团队办公 / 高预算稳定性刚需 |

想看更具体的「场景 → 首选 + 备选 + 预算」搭配，可以直接回到上面的 [个人快速推荐清单](#person)。

<a id="web-entry"></a>

## 🔗 网页版入口

本页 README 已包含完整主内容，不需要跳转。如果你已经有可用节点，网页版的排版、测速图和移动端阅读体验更完整：

**[gptvpnhelper.com](https://gptvpnhelper.com/)** — 各机场单项测评页的入口也在上面每家评测块末尾的 📖 链接里（唯兔云暂无单独页面）。

> 📌 没有可用外网环境时这些链接可能打不开，继续往下看 [新手教程](#study) 即可。

---

<a id="study"></a>

## 🚀 新手必看：3 分钟从零开始科学上网

完全零基础也能跟着走完。下载和配置的细节都在 [客户端配置与订阅](#config) 一章，这里只讲主流程。

### 第一步：选机场并注册

| 机场 | 特点 | 价格 | 跳转 |
| --- | --- | --- | --- |
| ⚡ **BoostNet** | 综合主力首推 | ¥49/月起 | [看评测](#boostnet) |
| 🐰 **悠兔** | 长期主用优先 | ¥39/月起 | [看评测](#youtu) |
| 🌤 **青云梯** | 长期年付主力 | ¥96/年起 | [看评测](#qingyunti) |
| 🐰 **唯兔云** | 多区域业务专线 | ¥14.9/月起 | [看评测](#weituyun) |

注册 → 邮箱 + 密码 → 选套餐支付 → 登录后台找到**订阅链接**（形如 `https://example.com/api/v1/client/subscribe?token=xxxxxxxx`）。

> ⚠️ **订阅链接等于账号钥匙，不要分享给任何人**，也不要贴进群聊、Issue 或截图里。

### 第二步：装客户端

原则：**机场有官方客户端就优先用官方的**，需要自定义分流时再上通用客户端。

👉 全平台下载地址、内核对照见 [📦 全平台客户端下载](#clients)。

**iOS 按这个顺序判断：**

1. **先看你买的那家机场的使用说明支持哪些客户端** —— 这一步决定后面所有选择，各家不一样，不要跨家照搬。
2. **机场已接入 Nextin** → 直接用 Nextin。免费，填机场给的**识别码**再输入你在该机场的账号密码就能拿到节点，省掉付费和复制订阅链接两步。识别码每家不同，看机场自己的说明。
3. **机场没接入 Nextin、但给订阅链接** → Shadowrocket 或 Stash，都要付费，按 [订阅导入说明](#client-config) 操作。
4. **机场明确要求用官方客户端**（当前 [TNTCloud](#tnt) / [青云梯](#qingyunti) / [银河云](#yinheyun) / [唯兔云](#weituyun) 属于这种）→ 按官方指引来，别先去折腾通用客户端。

> 📱 iOS 三个客户端都需要 **美区 / 港区 / 台区 / 新区 Apple ID**，国区商店搜不到，Nextin 免费也省不掉这步。没有外区账号就直接联系机场客服要 iOS 安装指引。
>
> **切换 Apple ID：** App Store（不是"设置"）→ 右上角头像 → 拉到底退出登录 → 登录外区账号 → 下载 → 装完再切回自己的账号。

### 第三步：导入订阅并连接

1. 打开客户端 → 找到"订阅 / 配置" → 添加 → 粘贴订阅链接 → 保存
2. 点"更新订阅"，等节点列表加载出来
3. 选节点：日常用 🇭🇰 香港（延迟低）｜ChatGPT 用 🇺🇸 美国｜Netflix 日区用 🇯🇵 日本
4. 开启代理开关，代理模式保持**规则 / 智能分流**
5. 右键节点可以测速，优先选延迟 < 100ms 的

各客户端的具体操作差异见 [Nextin / Shadowrocket / sing-box / v2rayN 订阅导入](#client-config)。

### 第四步：测试是否成功

| 测试站 | 目的 | 成功标志 |
| --- | --- | --- |
| [Google](https://www.google.com) | 基础连通 | 能打开搜索 |
| [ChatGPT](https://chat.openai.com) | AI 工具 | 能进对话界面 |
| [YouTube](https://www.youtube.com) | 视频 | 能播放 |
| [ip.sb](https://ip.sb) | 出口 IP | 显示国外 IP |

打不开就依次排查：客户端是否已启动 → 是否选了节点 → 订阅链接对不对 → 换个节点试。

### 🆘 常见问题快速解决

| 问题 | 原因 | 解决 |
| --- | --- | --- |
| 💔 打不开 GitHub | DNS 污染 | 换节点，或清 DNS 缓存（配置见 [Clash 配置模板](#clash-config) 的 `dns` 段） |
| 🐌 速度慢 | 节点拥堵 | 测速后选延迟最低的 |
| ⚠️ ChatGPT 不可用 | 出口 IP 被判定 | 换美国或台湾节点，AI 分组建议手动固定节点 |
| 🔄 频繁断线 | 节点不稳 | 换节点，长期不稳就换机场 |
| 🚫 提示订阅无效 | 链接过期或填错 | 重新登录机场后台复制 |
| 🌐 国内网站也走代理 | 规则模式没开或规则顺序写反 | 切回规则模式，规则写法见 [Clash 配置模板](#clash-config) |

### 🔒 几条使用习惯

- 不要用代理登录银行 / 支付宝，让它们走直连
- 敏感账号开两步验证
- 不要长期只用一个节点
- 不要分享订阅链接，容易被滥用导致限速甚至封号

---

<a id="config"></a>

## 🛠 客户端配置与订阅（GitHub 专区）

> 📌 这一章是 README 独有内容，网页版没有。如果你已经买好机场、只想拿到能直接用的配置，从这里开始看就够了。
>
> 🔐 **订阅链接等于你的账号凭证，不要发到群里、Issue 里或任何公开位置。** 下文所有示例中的 `YOUR_SUBSCRIPTION_URL` 都需要替换成你自己的订阅地址。

<a id="clients"></a>

### 📦 全平台客户端下载

优先用机场官方客户端（见各家评测段落）；需要自定义分流规则时，再用下面的通用客户端。

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
| Windows 64 位 | `xxx-x64-setup.exe`（32 位选 `ia32`，不确定就右键"此电脑"→属性看系统类型） |
| macOS Apple Silicon | `xxx-aarch64.dmg`；Intel 芯片选 `xxx-x64.dmg` |
| Android | 最新版本的 `xxx-arm64-v8a-release.apk` |

> 🍎 macOS 提示"无法打开"：系统设置 → 隐私与安全性 → 点"仍要打开"。
> 🤖 Android 需要先开启"允许安装未知来源应用"。

> 📱 **iOS 选哪个：** 先看机场的使用说明支持哪些客户端。已接入 Nextin 的直接用 Nextin（免费，识别码 + 机场账号密码接入）；没接入再看 Shadowrocket / Stash，这两个都要付费。三者都需要海外 Apple ID。
>
> ⚠️ 当前 `TNTCloud / 青云梯 / 银河云 / 唯兔云` 建议优先使用官方客户端，不要按旧教程优先折腾通用客户端。`悠兔` 也更建议先用官方客户端。具体以官网当前列出的支持客户端和版本为准。

---

<a id="clash-config"></a>

### ⚙️ Clash / Mihomo 配置模板

下面是一份可以直接改用的 `config.yaml` 骨架，适用于 mihomo（Clash.Meta）内核及基于它的客户端（Clash Verge Rev / ClashX Meta / FlClash / OpenClash）。

绝大多数机场都提供 Clash 订阅链接，客户端导入后会自动生成节点和分组。**只有在你要自定义分流规则时才需要手写配置**。

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

# ---- DNS：防污染的关键，不要省略 ----
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
  nameserver:               # 国内域名解析
    - https://dns.alidns.com/dns-query
    - https://doh.pub/dns-query
  fallback:                 # 国外域名解析，走代理更干净
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

按用途分组，比把所有流量丢进同一个组要稳得多 —— AI 工具对 IP 质量敏感，流媒体对区域敏感，两者的最优节点往往不是同一个。

```yaml
proxy-groups:
  - name: "🚀 节点选择"
    type: select
    use: [airport]
    proxies: ["♻️ 自动选择", DIRECT]

  - name: "♻️ 自动选择"
    type: url-test           # 按延迟自动选最快节点
    use: [airport]
    url: http://www.gstatic.com/generate_204
    interval: 300
    tolerance: 50

  - name: "🤖 AI 工具"
    type: select             # AI 服务建议手动固定节点，频繁换 IP 容易触发风控
    use: [airport]
    proxies: ["🚀 节点选择"]

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

#### 几个容易踩的坑

| 现象 | 常见原因 | 处理方向 |
| --- | --- | --- |
| 节点能连、网页打不开 | DNS 没配 `fake-ip` 或 `fallback` 缺失 | 补全上面的 `dns` 段 |
| ChatGPT / Claude 提示地区不可用 | 出口 IP 被判定为机房 IP 或共享过度 | 在「🤖 AI 工具」组里手动固定一个节点，别用自动选择 |
| 国内网站也走了代理 | 规则顺序写反，`MATCH` 之前没有 `GEOIP,CN` | 保持 `RULE-SET` → `GEOIP` → `MATCH` 的顺序 |
| 订阅更新后分组消失 | 客户端覆盖了本地配置 | 用客户端的「覆写 / Merge」功能，不要直接改自动生成的文件 |
| 规则集拉不下来 | jsDelivr 被干扰 | 换 `https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/` 前缀 |

---

<a id="client-config"></a>

### 📲 Shadowrocket / sing-box / v2rayN 订阅导入

#### Nextin（星拓，iOS / iPadOS / Apple TV）

**通用客户端**，不是哪一家机场的专属 App。基于 Clash Meta 内核，覆盖 Apple 全平台，**下载免费**（App 内有积分类内购），相比 Shadowrocket / Stash 少了一道付费门槛。

> 📱 **下载需要海外 Apple ID**（美区 / 港区 / 台区 / 新区均可），国区 App Store 搜不到。这一步对新手来说通常比装 App 本身更麻烦，先准备好账号再往下走。

两种接入方式：

1. **识别码 + 账号密码** —— **每家机场的识别码不一样**，在对应机场的使用说明里找。填入识别码后，再输入你**在这家机场的账号和密码**，Nextin 会自动拉取订阅和节点，全程不用手动复制订阅链接。对新手最省事。
2. **订阅链接** —— 机场没提供识别码时用这个。首页直接粘贴订阅地址即可，它也兼容 Shadowrocket 格式的订阅链接。

接入后允许系统的 VPN 配置权限，代理模式保持"规则"，再选节点连接。

> ℹ️ 支持 VLESS / Reality、AnyTLS、Trojan、VMess、Shadowsocks / SSR、Hysteria2、TUIC、Masque 等协议。App Store 上 Mac 版标注为 "Designed for iPad, Not verified for macOS"，macOS 建议仍用 Clash Verge Rev 或 ClashX Meta。
>
> ⚠️ 识别码和具体步骤以你所在机场官网 / 客服当前给出的说明为准，各家不通用。提示识别码无效，通常是填错或该机场没有提供，改用订阅链接导入即可。识别码方式需要在 Nextin 里填机场面板的账号密码，介意的话直接用订阅链接。

#### Shadowrocket（iOS）

1. 复制机场提供的订阅链接。
2. 打开 Shadowrocket → 右上角 `+` → 类型选择 **Subscribe**。
3. URL 粘贴订阅链接，备注随意填 → 保存。
4. 回到首页下拉刷新，节点列表会自动拉取。
5. 首页顶部开关打开，选一个节点即可。

> 需要分流的话：`配置` → 选中当前配置 → 编辑，规则写法与 Clash 不同，按 Shadowrocket 自己的 `RULE-SET` 语法填。

#### sing-box

sing-box 通常直接导入机场提供的 sing-box 订阅（如果机场支持）。需要手写时，出站片段大致长这样：

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
      "outbounds": ["节点A", "节点B"],
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

> 图形客户端（Hiddify / NekoBox）可以直接粘订阅链接，不需要手写 JSON。手写只在自建或调试时才有必要。

#### v2rayN（Windows）

1. 主界面 → `订阅` → `订阅设置`。
2. 新增一条，备注填机场名，地址填订阅链接。
3. 确定后 → `订阅` → `更新订阅（不经过代理）`。
4. 节点列表出现后，右键某个节点 → `设为活动服务器`。
5. 任务栏图标右键 → `系统代理` → `自动配置系统代理`。

> v2rayN 从 6.x 起支持 Xray 与 sing-box 双内核，如果某类协议连不上，先在 `设置` 里换一下内核再试。

---

<a id="glossary"></a>

### 📖 线路与协议术语对照表

买机场时最常见的看不懂的词，一张表说清楚。

| 术语 | 含义 | 对你意味着什么 |
| --- | --- | --- |
| **直连** | 国内直接连到境外落地服务器 | 成本低、价格便宜；晚高峰容易抖动 |
| **中转** | 国内先进中转服务器，再转发到落地 | 比纯直连稳，质量取决于中转节点的带宽 |
| **IEPL** | 运营商提供的跨境专线（以太网私用专线） | 不走公网出口，晚高峰稳定性明显更好，价格更贵 |
| **IPLC** | 国际专线电路，端到端点对点专线 | 与 IEPL 同属专线，延迟低、抗封锁强，成本最高 |
| **BGP 中转** | 用 BGP 多线机房做中转 | 三网兼容性好，适合不知道自己是哪个运营商的用户 |
| **落地 IP** | 你在境外网站眼里的出口 IP | 决定能不能解锁流媒体和 AI 服务，比速度更重要 |
| **原生 IP** | 归属地与机房所在地一致的住宅/商用 IP | 流媒体和 AI 服务判定更宽松，通常单独加价 |
| **广播 IP** | 机房把 IP 段广播到其他地区 | 便宜，但更容易被判定为代理 |
| **Shadowsocks** | 老牌轻量加密代理协议 | 速度快、兼容性最好，特征相对明显 |
| **SS2022** | Shadowsocks 2022 版加密规范 | 抗重放、抗主动探测更强，需要新版客户端 |
| **Trojan** | 伪装成 HTTPS 流量的协议 | 特征不明显，适合封锁较严的环境 |
| **VMess / VLESS** | V2Ray 系协议，VLESS 是无加密层的轻量版 | VLESS + Reality 组合当前较流行 |
| **Hysteria2** | 基于 QUIC 的协议 | 弱网和高丢包环境下表现好，但流量消耗偏大 |
| **AnyTLS** | 较新的 TLS 伪装协议 | 抗封锁方向的新选择，需客户端支持 |
| **倍率** | 某节点消耗流量的系数 | `0.5x` 表示用 1G 只扣 0.5G，`3x` 则相反，买之前一定要看 |
| **fake-ip** | Clash 的 DNS 处理模式 | 不配它容易出现"能连上但打不开网页" |

---

<a id="choose"></a>

## ❓ 如何挑选靠谱机场？2026 避坑指南 + 5 大核心指标

第一次买机场最容易踩的坑不是"买贵了"，而是**只看低价、不看线路、不看晚高峰、不看 AI 解锁质量**。这一章给的是可以直接照着筛的方法。

### 🚦 先按用途定方向，别一上来比价格

| 主要用途 | 优先看的指标 | 更适合的线路 | 购买建议 |
| --- | --- | --- | --- |
| 🤖 ChatGPT / Claude / Gemini / Copilot / Cursor | 线路质量、出口 IP、晚高峰稳定性 | IEPL / IPLC、原生 IP、家宽 IP | 先月付，确认 AI 稳定再年付 |
| 🎬 Netflix / Disney+ / YouTube / TikTok | 流媒体解锁、地区覆盖、晚高峰带宽 | IEPL / IPLC / 优质中转，热门地区节点 | 选明确标注解锁能力的 |
| 💼 远程办公 / 会议 / GitHub / API 调用 | 丢包率、晚高峰延迟、售后响应 | IEPL / IPLC / 稳定 BGP 中转 | 不要用只支持年付的新机场做主力 |
| 💰 轻度使用 / 备用线路 | 月付门槛、基础解锁、性价比 | 普通中转 / BGP 中转 | 预算可低，但别贪"9.9 包年" |

### ⏱ 60 秒筛选顺序

1. **看用途** —— AI、流媒体、办公，还是低价备用。
2. **看线路** —— 优先 IEPL / IPLC，其次优质 BGP 中转，最后普通中转。
3. **看晚高峰** —— 重点是 `19:30-23:00` 的真实表现，不看白天峰值截图。
4. **看解锁** —— 区分"网页能打开"和"Copilot / Cursor / API 长时间稳定使用"。
5. **看价格** —— 月付能接受、可验证、售后能联系，再谈年付。

### 📋 5 大核心指标

#### 1️⃣ 线路架构（最重要，占 30%）

| 线路类型 | 延迟 | 稳定性 | 价格 | 适合人群 |
| --- | --- | --- | --- | --- |
| 🏆 **IEPL / IPLC 专线** | < 50ms | ⭐⭐⭐⭐⭐ | ¥30-120/月 | 办公、AI 重度 |
| 🥈 **BGP 中转** | 50-150ms | ⭐⭐⭐⭐ | ¥20-60/月 | 日常上网、流媒体 |
| 🥉 **普通中转** | 100-200ms | ⭐⭐⭐ | ¥10-30/月 | 轻度、备用 |
| ⚠️ **公网直连** | 不稳定 | ⭐⭐ | ¥5-15/月 | 不建议做主力 |

> 🚩 只反复写"秒开""企业级网络"却不写具体线路类型的，默认谨慎看待。线路名词看不懂可以对照 [术语表](#glossary)。

#### 2️⃣ 晚高峰表现（25%）

用户最集中的时段是 `19:30-23:00`，这个时段的数据才接近真实体验。看机场有没有公开晚高峰测速图而不是只放白天峰值；看公告区最近 7-30 天有没有持续反馈和处理动作；判断标准用"能不能连续用 30 分钟以上"，而不是单次跑分。

> 🚩 白天很快、晚高峰大幅掉速；Speedtest 数字漂亮但 ChatGPT / Netflix / GitHub 实际很差。

#### 3️⃣ 解锁能力与出口 IP（20%）

| 场景 | 更理想的出口条件 | 合格标准 |
| --- | --- | --- |
| ChatGPT / Claude / Gemini 网页版 | 原生 IP / 家宽 IP / 干净出口 | 能稳定登录、长时间对话，较少触发风控 |
| Copilot / Cursor / OpenAI · Anthropic API | 稳定出口 + 低风控 + 晚高峰可用 | 连续开发调用稳定，不频繁掉认证 |
| Netflix / Disney+ / YouTube Premium | 原生 IP + 解锁能力 | 能稳定播放，目标地区内容库正常 |
| TikTok / Instagram / X | 非大陆出口 + 地区匹配 | 正常浏览、登录、发布和切区 |

> 🚩 "网页能打开"不等于"长期稳定可用"，Copilot / Cursor / API 场景要单独验证。数据中心 IP 便宜但更容易被识别。

#### 4️⃣ 品牌口碑与售后（15%）

看运营时长和持续更新记录、有没有公告频道 / TG 群 / 工单 / 邮件、有没有备用域名和应急通知方式、出问题时是公开说明还是直接失联。

> 🚩 上线很短却大力卖年付或终身套餐；只留一个充值入口；官网经常打不开又没有备用渠道。

#### 5️⃣ 套餐灵活性与成本（10%）

| 考察点 | 好机场 ✅ | 差机场 ❌ |
| --- | --- | --- |
| 支付周期 | 支持月付 / 季付 / 年付，或对临时收紧有清晰公告 | 新站一上来只支持年付 |
| 设备限制 | 不限或 ≥ 3 台 | 限制 1 台 |
| 流量重置 | 每月重置 | 不重置，用完就没 |
| 支付方式 | 支付宝 / 微信 / USDT | 只支持加密货币 |
| 试用退款 | 支持试用或退款 | 不支持 |

### 🎯 100 分快速评估表

| 维度 | 分值 | 检查什么 |
| --- | ---: | --- |
| 线路架构 | 30 | 是否明确标注 IEPL / IPLC / BGP，专线还是中转说得清不清楚 |
| 晚高峰表现 | 25 | `19:30-23:00` 是否稳定，测速与真实使用是否一致 |
| 解锁能力 / 出口 IP | 20 | ChatGPT / Claude / Copilot / Netflix / TikTok 是否明确说明可用 |
| 口碑 / 售后 / 应急 | 15 | 公告、TG 群、客服、备用官网、持续更新记录 |
| 套餐灵活性 / 成本 | 10 | 月付、试用、设备数、流量规则是否透明 |

**80 分以上**可作主力候选；**60-79 分**只做备用并先月付；**60 分以下**不建议长期买，更不要一上来年付。

### ⚠️ 这两类机场别碰

**🚫 免费机场** —— 通常严重限速（1-3 Mbps，晚高峰几乎不可用）、频繁掉线，还存在注入广告、追踪记录甚至窃取账号的风险。**不要用免费机场登录银行 / 支付宝、访问公司内网或企业邮箱、注册和长期登录 AI 账号。** 预算低就看 [银河云](#yinheyun) 这类信息透明、门槛也低的正规选择。

**🚫 ¥9.9 包年这类超低价** —— 一台香港 VPS 加 1000GB CN2 带宽的月成本就在 ¥700 左右，卖 ¥9.9/年需要 840 个用户才回本，只能靠超售维持，结果就是限速、IP 污染、随时跑路。合理区间：入门 ¥15-30/月，中端 ¥30-80/月，高端专线 ¥80-150/月。

### 💡 正确的省钱策略

| 方案 | 月均成本 | 适合谁 |
| --- | --- | --- |
| 🎁 利用试用期 | ¥0 | 新手、短期使用 |
| 📦 年付套餐 | ¥8-15/月 | 确定长期使用 |
| 🤝 合租分摊 | ¥10-30/月 | 与朋友 / 家人共享 |
| 🎯 按需购买 | ¥15-30/月 | 轻度用户，选小流量套餐 |
| 🔄 主力 + 备用 | ¥30-50/月 | 稳定需求，两家互补 |

顺序是：先选支持月付或试用的验证自己的场景 → 连续稳定用 1-2 周 → 再考虑年付。有生产力需求的尽量留一条备用线。

> 👉 已经确定需求就直接看 [个人推荐清单](#person)；想看套餐和测速细节看 [精选机场深度评测](#top7)。

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

## 购买建议与风险提醒（如何防跑路/规避封锁）

1. **第一次购买，大多数机场优先月付 / 季付**：先用短周期验证你所在地区、运营商、常用节点和 AI / 流媒体场景是否正常。
2. **不要迷信“绝对稳定”宣传**：没有任何一家机场能在所有地区、所有时段、所有运营商下都表现完全一致。谁还在高调承诺“永不拔线”“100% 稳”，谁就更值得警惕。
3. **主力线和备用线最好分开准备**：至少保留两家不同线路、不同协议的机场，遇到地区波动、入口失效或临时维护时才能快速切换。
4. **紧盯公告和入口变化**：Telegram / 邮件渠道发布的“入口变更”“节点迁移”“临时维护”要及时处理；套餐周期、价格和可购买状态以结算页和公告为准。
5. **订阅链接不要外传，账号规则要看清**：很多机场禁止共享、限制异常登录或频繁重置，违规后可能直接封号或限速。
6. **合法合规**：严禁利用机场从事任何违法活动，否则账号冻结、追责风险自负。

---

## 免责声明

本文所有数据基于公开测速、实际体验与用户反馈，仅作学习交流，不构成任何法律或投资建议。在任何情况下，作者不对因使用本仓库信息而导致的直接或间接损失承担责任。请各位务必遵守当地法律法规，合理合规使用科学-上网服务。

> 科学-上网，先科学，后上网；愿你我都能自由、安全、快速地拥抱世界知识。

---

<a id="vs"></a>

## 机场 vs VPN：哪个好用？

| 维度 | VPN | 机场 |
| --- | --- | --- |
| 节点数量 | 3-10 条主流出口 | 30-200+ 全球线路 |
| 分流能力 | 全局或分应用（少数支持） | 域名 / 端口 / IP 分流、规则自定义、链式代理 |
| 速度上限 | 受单机带宽和用户量限制 | 取决于机场总带宽投入与线路等级 |
| 价格 | 2-12 USD/月 | 5-120 CNY/月，高中低档全覆盖 |
| 协议 | OpenVPN / WireGuard 等 | SS / VMess / Trojan / Hysteria2 等并存，可混用 |
| 解锁 | Netflix 仅部分，AI 服务看官方策略 | 通常针对流媒体和 AI 做适配，实际以节点和平台风控为准 |

**怎么选：** 国内封锁环境下 VPN 连接本身就常出问题，延迟也更高；优点是国外大厂不太会跑路。机场的自由度和专线延迟明显更好，对开发者、跨境电商、内容创作者和流媒体重度用户来说通常是更优选，代价是要自己挑服务商、承担跑路风险——所以本页才花这么大篇幅讲怎么筛（见 [避坑指南](#choose)）。

协议和线路名词看不懂见 [术语对照表](#glossary)。

---

<a id="faq"></a>

## ❓ 常见问题 FAQ

### 1. 第一次买，到底选哪家？

想少研究线路细节、直接买一条 `AI 工具 + 流媒体 + 日常办公` 都能覆盖的综合主力 → [BoostNet](#boostnet)，默认从 200G/月开始。更看重 IEPL 线路质量、晚高峰 YouTube / Netflix 表现和长期持有 → [悠兔](#youtu)，默认看 300G/月，想低门槛测试先从 150G/月开始。

### 2. 应该月付、季付还是年付？

第一次买建议先月付或季付。先验证你所在地区、运营商、常用设备和 ChatGPT / Claude / YouTube / Netflix 等场景都正常，再考虑长期套餐。

### 3. ChatGPT / Claude / Cursor 选哪家？

综合主力先看 [BoostNet](#boostnet) 或 [WgetCloud](#wgetcloud)；更看重高端 IEPL 和晚高峰视频表现看 [悠兔](#youtu)；对原生或高质量出口、IDE 登录更敏感时补看 [TNTCloud](#tnt)。具体可用性以节点和平台风控为准。

配置上还有一点容易忽略：AI 工具的代理分组建议**手动固定节点**，不要用自动选择，频繁换 IP 更容易触发风控。写法见 [Clash 配置模板](#clash-config)。

### 4. TikTok / 跨境电商选哪家？

优先看 [唯兔云](#weituyun)，它更强调东南亚、印度、韩国及部分欧美节点覆盖，适合多区域业务和账号运营。需要更高质量专项出口时搭配 [TNTCloud](#tnt)。这类场景不要只看价格，先确认目标地区节点、账号登录地区和平台风控表现。

### 5. 官方客户端、Clash、Nextin 怎么选？

[WgetCloud](#wgetcloud) 支持 Clash 等通用客户端；其他几家优先按官网当前说明使用官方客户端。iOS 上如果机场已接入 Nextin，它免费且用识别码 + 机场账号密码就能接入，是当前门槛最低的通用客户端方案。需要自定义规则时再确认订阅格式和客户端版本是否兼容，详见 [客户端配置与订阅](#config)。

### 6. 下单前最应该核对什么？

套餐周期、每月流量、设备限制、客户端要求、退款规则和最终结算金额。价格一律以官网结算页为准。

### 7. 买了不能用，先排查什么？

按顺序来：

1. 是否用了机场当前推荐的官方客户端
2. 是否更新过订阅、换过香港 / 日本 / 新加坡 / 美国等不同节点
3. 是否看过官网公告、入口变更和客户端版本要求
4. 是否只在某个设备或某个本地网络下不可用
5. 仍不可用就带上设备、系统、运营商和报错截图联系客服

能连上但网页打不开，多半是 DNS 问题，见 [Clash 配置模板](#clash-config) 的 `dns` 段。**不要只凭一个节点、一张测速图或一次失败就判断整家机场不可用。**

### 8. 怎么防止机场跑路？

优先选有官网、公开测速、活跃 TG 群的服务商。新机场优先月付或季付；老牌机场因公告临时关闭短周期时，也要先确认自己确实需要长期主力再决定要不要上年付。

本页推荐的几家大多已有一定运营周期，TNTCloud、唯兔云这类新晋专线文中都标注了上线时间。更偏向长运营周期的，重点看 2019 年 11 月开业的 [青云梯](#qingyunti)，或 2022 年开业的 [悠兔](#youtu)。

> 📖 概念类问题（机场是什么、和 VPN 什么区别、免费机场能不能用、支持哪些平台）分别见 [什么是机场](#ssssr)、[机场 vs VPN](#vs)、[避坑指南](#choose) 和 [全平台客户端下载](#clients)。

---

<a id="daily-news"></a>

## 🌍 最新国外新闻速览（自动更新）

新闻速览已拆分到独立文件，定时任务会继续更新最近 10 条国外新闻标题与原文链接：[`daily-news.md`](./daily-news.md)。

---

<a id="listweb"></a>

## 🌐 连通之后：常用海外资源

按这个仓库的读者画像挑的，偏开发和 AI 工具，不收录成人内容站点。

### 🤖 AI 工具

| 站点 | 说明 | 出口要求 |
| --- | --- | --- |
| [ChatGPT](https://chat.openai.com) | OpenAI 对话与 API 控制台 | 对 IP 质量敏感，建议固定节点 |
| [Claude](https://claude.ai) | Anthropic 对话，长上下文场景常用 | 同上，频繁换 IP 容易触发验证 |
| [Google AI Studio](https://aistudio.google.com) | Gemini 模型调试与 API key | 需非大陆出口 |
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
