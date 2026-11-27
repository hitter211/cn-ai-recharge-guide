# Gemini 4 四款模型（Neon / Carbon / Hydrogen / Argon）选择手册：档位对照与开通验证

> 本文更新于 **2026 年 11 月 27 日**。Google 七周连发四款 Gemini 4 模型，名字全是化学元素，订阅列表一变再变。本文是仓库版操作手册：四款怎么选、你的订阅能用哪款、12 月 1 日的价格节点，以及开通前的验证清单。利益相关照旧披露：作者自营订阅充值服务（时差商店），文中非官方。更完整的长文版在官网 [Gemini 4 四款模型怎么选](https://www.shichangstore.com/guide/gemini-4-models/)。

## 一、四款模型速查表（2026-11-24 口径）

| 模型 | 发布 | 定位 | API 价（$/M in/out） | 订阅门槛 | 现状 |
|---|---|---|---|---|---|
| Hydrogen（氢） | 11-12 | 快、日常、免费档 | 1.50 / 7.50 | 人人可用，Plus $4.99 起 | 在售 |
| Neon（氖） | 11-18 | 中坚：编程+分析 | 3.00 / 15.00 | Pro $19.99 / Ultra | 在售 |
| Carbon（碳） | 10-28 | 旗舰，最难最长任务 | 11-30 前 2/10 促销，**12-1 起 4/20** | **仅 Ultra** | 在售 |
| Argon（氩） | 9-30 | 本世代首款 | 12-1 起 4/20 | **已从订阅列表隐去** | 仅 API |

统一规格：约 1M tokens 上下文（输入/思考/输出共享）、相同工具能力。差别只在思考档默认值、单价、订阅门槛。

**四句话记住**：Hydrogen 人人可用；Neon 是 Pro 的主力（AA 指数最高档 61 分，反超 Carbon 的 60 和 Opus 5.5 的 59）；Carbon 只有 Ultra 能点；Argon 已被 Neon 静默替换（无公告，仅帮助页体现）。

## 二、按你的订阅对号入座

| 你的档位 | 能点到 | 建议 |
|---|---|---|
| 免费 | Hydrogen（限量） | 先试能力，够用不升级 |
| Plus $4.99 | Hydrogen 为主 | 轻量高频主力 |
| Pro $19.99 | Hydrogen + **Neon** | Neon 是主力；重难题忍到 Ultra 或走 API |
| Ultra $99.99/$199.99 | + **Carbon** | 难题 Carbon、日常 Neon |
| API 开发者 | 四款全可选 | 11 月内 Carbon 促销最低；12 月起性价比排序 Hydrogen > Neon > Carbon/Argon |

## 三、三个容易踩的坑

1. **别按元素名猜强弱。** 原子序数、发布顺序、能力排序互相对不上；官方没解释命名。氢≠最弱（它是速度王），氩≠最强（它已退场）。
2. **别把促销价当永久价。** Carbon/Argon 的 $2/$10 是 11 月 30 日前的促销，12 月 1 日起 $4/$20。API 批量调用卡这个窗口。
3. **别信 Krypton。** 11-14 的"氪"爆料已被发帖人自己证伪（测的其实是高推理档 Hydrogen）；Helium（氦）有 TIER_HELIUM 代码线索和 DeepMind 预告视频，但未官宣。看到"Helium/Krypton 发布"先核日期信源。

## 四、开通前验证清单（订阅侧）

1. 确认账号地区与订阅档位——Pro 只能点到 Neon，别被"给你开 Carbon"的话术带走（做不到，档位是 Google 侧控制的）
2. 订阅到账后在 App 模型列表实测：Pro 应见 Neon，Ultra 应见 Carbon；**点不到先等 24 小时再找卖家**，Google 侧档位同步有延迟
3. 模型分数对比只看大致先后（各家思考档位口径不一致），选型用你自己的 20 条真实请求实测
4. 走代充的，付款前核验卖家口碑与售后规则，六条判断标准见 [代充靠谱吗](https://www.shichangstore.com/guide/daichong-kaopu-ma/)
5. 全档位价格与年付折算见 [Gemini 会员多少钱一个月](https://www.shichangstore.com/guide/gemini-duoshaoqian/)；开通流程与防坑见 [Gemini 代充怎么开通](https://www.shichangstore.com/guide/gemini-daichong/)

## 五、Argon 专节：首款模型退场的验证要点（A1 簇）

Argon 是四款里唯一"从有到无"的，单独列一节，完整时间线见 [Gemini Argon 退场时间线与验证清单](gemini-argon.md)。本节只留可操作的要点：

1. **判断订阅状态**：Pro / Ultra 订阅里没有 Argon = 正常（11-18 起被 Neon 替换），不需要找卖家"修复"。
2. **API 计价核对**：11 月内 $2 / $10（促销），12-1 起 $4 / $20；账单对不上价先怀疑渠道。
3. **存量迁移三步**：盘点模型名与调参 → Neon 回归对比 → 算 12 月后用量账（Neon $3 / $15 更便宜更强，迁移纯收益）。
4. **话术免疫**：订阅侧已无此模型，"Argon 订阅内部价 / 带 Argon 的号"一律按话术处理。

## 六、Hydrogen 专节：免费档与生图的验证要点（H1 簇）

Hydrogen 是四款里唯一带免费档的，"免费"也因此成了话术高发区。完整长文见官网 [Gemini Hydrogen 免费吗：免费额度、生图与订阅说明](https://www.shichangstore.com/guide/gemini-hydrogen-mianfei/)，本节只留可操作的验证要点：

1. **两条免费路径分开验**：API 免费档只面向开发者（AI Studio / API key）；普通用户看 App——免费 Google 账号能在模型列表点到 Hydrogen 才算数，点不到先核对账号状态与地区，别急着找卖家。
2. **量上限别写死**：免费配额官方口径是可以随时调整、不做另行通知，任何写死具体数字的攻略都按过期信息处理；自己的重置节奏以实测为准。
3. **生图验证三步**：App 里选中 Hydrogen → 发一条生图请求 → 记下当天成功张数。免费档生图有量上限，"无限量生图"类宣传一律按话术处理。
4. **开源辟谣**：Google 未开放模型权重，看到"Hydrogen 开源下载 / 权重打包"直接按误导信息处理。
5. **没有"Hydrogen 会员"可订**：它是模型档不是产品——免费可用、Plus（$4.99）主力、Pro/Ultra 包含；模型名后面接"内部价 / 专属通道"的按话术处理。
6. **对 Argon 的替代关系**：轻量场景 Hydrogen（$1.50/$7.50 常态价 + 免费档）全面占优；Argon 只剩 API 且 12 月 1 日起 $4/$20（见上文 Argon 专节）。

## 七、复测记录

- 2026-11-24：对照 Google Cloud 官方文档（Gemini 4 model family 四款规格）、官方博客与帮助页订阅行、Artificial Analysis 指数 v5.0.1（Neon 61 / Carbon 60 / Hydrogen 54 / Opus 5.5 59）、第三方单任务实测（Neon $6.44 vs Carbon $7.76）交叉核对；四款发布日期与 API 价以官方 changelog 为准
- Argon 从订阅列表隐去的结论来自官方帮助页当前状态（11-19 起多源一致）；API 无弃用通知，以官方 changelog 为准
- 2026-11-26：新增第五节 Argon 专节（呼应官网 Argon 详解页上线），事实未变化；Argon 订阅行仍为"已被 Neon 替换"，定价页促销窗口仍标至 11-30
- 2026-11-27：新增第六节 Hydrogen 专节（呼应官网 Hydrogen 免费页上线），事实未变化；免费档与生图口径同 11-24 核对结果，免费配额仍以官方页面实时标注为准
- 模型列表"可能随时调整且不另行通知"（官方原话），本文按月复核，下次复核 2026-12-05（覆盖 Carbon 涨价节点）

## 八、FAQ

1. **Pro 订阅能用 Neon 吗？** 能，Neon 门槛就是 Pro/Ultra，Pro 在 App 直接可点。
2. **Carbon 只有 Ultra 能用吗？** 是，Pro 点不到；需要 Carbon 级能力只能升级或走 API。
3. **Neon 和 Carbon 哪个强？** 最高档 Neon 61 略超 Carbon 60，且快约三倍、更便宜；日常默认档两者约打平（60）。多数场景选 Neon。
4. **Hydrogen 免费是真的吗？** API 唯一有免费档的，App 端免费用户和 Plus 都能用，有量上限；支持生图。展开版见官网 [Hydrogen 免费页](https://www.shichangstore.com/guide/gemini-hydrogen-mianfei/)。
5. **Argon 怎么不见了？** 11-18 被 Neon 静默替换，App 已不可用，仅 API 在售；已接 API 的程序短期无需迁移。
6. **谁该升级 Ultra？** 确实每天处理最难最长任务、且必须用 Carbon 的人；只为模型名好看而升级是浪费。

---

*相关文档：[Gemini Argon 退场时间线与验证清单](gemini-argon.md) · [Gemini 国内充值指南](gemini-chongzhi.md) · [代充为什么便宜](daichong-weishenme-pianyi.md) · [充值防坑与账号安全](recharge-safety.md)*
