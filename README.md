# 𝒃𝒂𝒃𝒚（@Jsforbaby）脚本 / 插件 / 模块汇总

Telegram 频道 [𝒃𝒂𝒃𝒚](https://t.me/Jsforbaby)（21K 订阅）作者公开的脚本、插件、模块整理版。
上游仓库：[ios151/Rewrite](https://github.com/ios151/Rewrite)、[Yu9191/Rewrite](https://github.com/Yu9191/Rewrite)。

- **整理规则**：以较新的 `ios151/Rewrite`（最后提交 2026-10-27）为基准，`Yu9191/Rewrite`（2026-09-17）内容为其子集，同名同用途取新版本；同一功能的脚本与二进制分属不同目录，均单独保留。
- **结构**：`surge/`、`loon/`、`qx/`、`egern/`、`stash/` 按平台存放，`scripts/` 按应用分组，`ipa/dmg/`、`dylib/` 见文末说明。
- **更新时间**：2026-11-11
- **收录数**：Surge 模块 32 · Loon 插件 0 · QX 重写 4 · Egern 10 · Stash 5 · 脚本 236

## 目录

```
├── surge/          Surge 模块（.sgmodule）
├── loon/           Loon 插件（.plugin）
├── qx/             Quantumult X 重写（.conf）
├── egern/          Egern 模块（.lpx）
├── stash/          Stash 片段（.snippet）
├── scripts/        脚本（.js / .mjs，按应用分组）
│   └── itunes/     App Store 收据类脚本
├── ipa/dmg/        安装包目录（本仓库不托管，见说明）
├── dylib/          注入库目录（本仓库不托管，见说明）
└── 其他/           BoxJS 订阅、视频源等附属配置
```

链接格式：`https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/<目录>/<文件名>`

## Surge 模块（32）

直接添加到 Surge：模块 → 添加模块 → 粘贴下方链接。

| 文件 | 用途 | 大小 |
|---|---|---|
| [AGC.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/AGC.sgmodule) | AGC · AGC解锁会员1-17 | 274 B |
| [AppraveTask.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/AppraveTask.sgmodule) | AppRaven 邀请助手 · 自动注册小号并填写 AppRaven 邀请码。 | 585 B |
| [CADReader.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/CADReader.sgmodule) | CAD快速看图 · CAD快速看图 | 354 B |
| [carrot.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/carrot.sgmodule) | Carrot解锁订阅 · 需要试用或者订阅到期 | 271 B |
| [ins.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/ins.sgmodule) | ins社区 · ins | 599 B |
| [IPPure.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/IPPure.sgmodule) | IPPure Panel · 显示 IPPure 欺诈分数、IP 信息以及当前节点名称。参考StashNetworks | 588 B |
| [kd.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/kd.sgmodule) | 快对答案 · 快对答案获取 | 272 B |
| [klx.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/klx.sgmodule) | 看理想VIP解锁 · 解锁看理想VIP会员功能，免费脚本请勿贩卖 | 655 B |
| [KuGou.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/KuGou.sgmodule) | 酷狗音乐会员解锁 · 解锁酷狗音乐会员功能，包括VIP歌曲、无损音质、去广告、皮肤等 | 12.3 KB |
| [KuWoTask.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/KuWoTask.sgmodule) | 酷我音乐签到 · 酷我音乐自动签到、领金币、抽奖等任务 | 905 B |
| [lanjiyin.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/lanjiyin.sgmodule) | 蓝基因医学 · 20250126最新 | 309 B |
| [linearitcurve.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/linearitcurve.sgmodule) | linearitcurve · linearitcurve解锁订阅 | 213 B |
| [lovekey.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/lovekey.sgmodule) | Lovekey键盘 · 无限制使用 更新2026-10-11 | 602 B |
| [MGSP.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/MGSP.sgmodule) | 咪咕视频 · 伟人 | 759 B |
| [MJTV.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/MJTV.sgmodule) | 麦咭TV · 麦咭TV | 478 B |
| [pear.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/pear.sgmodule) | Pear视频解析 · 会员视频解析，支持选择播放器（支持BoxJS配置） | 2.6 KB |
| [pluginhub.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/pluginhub.sgmodule) | 适配可莉插件中心 · 支持可莉插件中心的插件给Surge使用; 非Loon用户切勿反馈插件任何问题，尊重原创; 使用前请先添加ScriptHub模块. 插件中心网址 | 793 B |
| [Reven.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/Reven.sgmodule) | Revenuecat · Revenuecat | 636 B |
| [RRSP.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/RRSP.sgmodule) | 人人视频 · 频道获取每日最新Token..UMID | 654 B |
| [skbz.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/skbz.sgmodule) | 时空壁纸 · 获取会员图片 | 323 B |
| [speedtest.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/speedtest.sgmodule) | Speedtest 广告vip & 净化 · 去广告会员权益，移除广告，需登录 | 473 B |
| [TgRedirect.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/TgRedirect.sgmodule) | Telegram跳转 · 将  重定向到你选择的客户端（tg/sg/turrit/ime/ng/lingo | 533 B |
| [tlsm.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/tlsm.sgmodule) | 套路SM VIP解锁 · 播放完整视频；SenPlayer 下载 | 512 B |
| [TOPlt.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/TOPlt.sgmodule) | Topluntan · Topluntan | 555 B |
| [xfbs.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/xfbs.sgmodule) | xfbs · xfbs | 428 B |
| [YuRedirect.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/YuRedirect.sgmodule) | Yu9191 → ios151 链接重定向 · 旧号 Yu9191 已迁移至 ios151，访问 raw / github 旧路径时自动 302 到新号 | 653 B |
| [yyjy1.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/yyjy1.sgmodule) | yyjy1 · yyjy1 | 282 B |

**1808/**

| 文件 | 用途 | 大小 |
|---|---|---|
| [1808.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/1808/1808.sgmodule) | 1808.online · 解锁会员视频 | 505 B |

**huangdouduanju/**

| 文件 | 用途 | 大小 |
|---|---|---|
| [huangdou.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/huangdouduanju/huangdou.sgmodule) | 黄豆短剧VIP解锁 · VIP解锁 + 去广告 + 完整播放（浏览器直接观看） | 1.7 KB |

**itunes/**

| 文件 | 用途 | 大小 |
|---|---|---|
| [bbaabbyy.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/itunes/bbaabbyy.sgmodule) | bbaabbyy · bbaabbyy | 310 B |
| [xgn.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/itunes/xgn.sgmodule) | xgn · xgn | 291 B |

**moshi/**

| 文件 | 用途 | 大小 |
|---|---|---|
| [moshi-pro.sgmodule](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/surge/moshi/moshi-pro.sgmodule) | Moshi · 4.2.0 买断永久 Pro（需 patched jsbundle） | 432 B |

## Loon 插件（0）

Loon → 插件 → 添加插件，链接同上。

> 上游 Loon 插件共 2 个，均为 18+ 应用专用，未收录，故本目录为空。

（暂无）

## Quantumult X 重写（4）

QX 重写 / 规则引用。

（暂无）

**BiliBili/**

| 文件 | 用途 | 大小 |
|---|---|---|
| [BiliBiliDailyBonus.conf](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/qx/BiliBili/BiliBiliDailyBonus.conf) | — | 203 B |

**huangdouduanju/**

| 文件 | 用途 | 大小 |
|---|---|---|
| [huangdou.conf](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/qx/huangdouduanju/huangdou.conf) | 黄豆短剧VIP解锁 · VIP解锁 + 去广告 + 完整播放（浏览器直接观看） | 1.3 KB |

**moshi/**

| 文件 | 用途 | 大小 |
|---|---|---|
| [moshi-pro.conf](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/qx/moshi/moshi-pro.conf) | — | 281 B |

**wuyouyunpan/**

| 文件 | 用途 | 大小 |
|---|---|---|
| [wuyouyunpan.conf](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/qx/wuyouyunpan/wuyouyunpan.conf) | — | 203 B |

## Egern 模块（10）

Egern 模块导入。

| 文件 | 用途 | 大小 |
|---|---|---|
| [AppraveTask.lpx](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/egern/AppraveTask.lpx) | AppRaven 邀请助手 · 自动注册小号并填写 AppRaven 邀请码。安装后请点击插件配置填写参数。 | 660 B |
| [CADReader.lpx](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/egern/CADReader.lpx) | CAD快速看图 · CAD快速看图 | 417 B |
| [KuWoTask.lpx](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/egern/KuWoTask.lpx) | 酷我音乐签到 · 酷我音乐自动签到、领金币、抽奖等任务 | 928 B |
| [lovekey.lpx](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/egern/lovekey.lpx) | Lovekey键盘 · 更新日期2026-10-11 | 686 B |
| [pear.lpx](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/egern/pear.lpx) | Pear视频解析 · 会员视频解析，支持选择播放器（支持BoxJS配置） | 2.4 KB |
| [RRSP.lpx](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/egern/RRSP.lpx) | 人人视频4K嗅探 · 自动抓取人人视频4K播放地址，并调用外部播放器。 | 991 B |
| [tlsm.lpx](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/egern/tlsm.lpx) | 套路SM VIP解锁 · 播放完整视频 SenPlayer 下载 | 466 B |
| [YuRedirect.lpx](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/egern/YuRedirect.lpx) | Yu9191 → ios151 链接重定向 · 旧号 Yu9191 已迁移至 ios151，访问 raw / github 旧路径时自动 302 到新号 | 640 B |

**huangdouduanju/**

| 文件 | 用途 | 大小 |
|---|---|---|
| [huangdou.lpx](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/egern/huangdouduanju/huangdou.lpx) | 黄豆短剧VIP解锁 · VIP解锁 + 去广告 + 完整播放（浏览器直接观看） | 1.7 KB |

**moshi/**

| 文件 | 用途 | 大小 |
|---|---|---|
| [moshi-pro.lpx](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/egern/moshi/moshi-pro.lpx) | Moshi · 4.2.0 买断永久 Pro（需 patched jsbundle） | 403 B |

## Stash 片段（5）

Stash 覆写片段。

| 文件 | 用途 | 大小 |
|---|---|---|
| [taoluyingshi.snippet](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/stash/taoluyingshi.snippet) | 套路影视VIP解锁 · 绕过积分墙直接播放，支持SenPlayer下载 | 410 B |
| [tlsm.snippet](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/stash/tlsm.snippet) | 套路SM VIP解锁@ios151 · 绕过 60 秒预览，注入完整视频与 SenPlayer 下载 | 721 B |
| [YuRedirect.snippet](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/stash/YuRedirect.snippet) | Yu9191 → ios151 链接重定向 · 旧号 Yu9191 已迁移至 ios151，访问 raw / github 旧路径时自动 302 到新号 | 639 B |

**huangdouduanju/**

| 文件 | 用途 | 大小 |
|---|---|---|
| [huangdou.snippet](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/stash/huangdouduanju/huangdou.snippet) | 黄豆短剧VIP解锁 · VIP解锁 + 去广告 + 完整播放（浏览器直接观看） | 1.3 KB |

**huangguoduanju/**

| 文件 | 用途 | 大小 |
|---|---|---|
| [huangguo.snippet](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/stash/huangguoduanju/huangguo.snippet) | 黄果短剧去广告 · 去广告（播放跳转/轮播/横幅/贴片） | 444 B |

## 脚本（JS / MJS）（236）

按原仓库用途分组；同名同用途保留新版本。

| 文件 | 用途 | 大小 |
|---|---|---|
| [1998.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/1998.js) | 1998 解锁全课程全资料 | 2.3 KB |
| [52ywy.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/52ywy.js) | 夜未央 | 16.0 KB |
| [65kan.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/65kan.js) | * 密钥部分来自 @xzxxn7 | 14.9 KB |
| [ABCLearning.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/ABCLearning.js) | ABCLearning | 4.7 KB |
| [adblockpro.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/adblockpro.js) | adblockpro 10.7.5 | 4.9 KB |
| [AGC.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/AGC.js) | * | 961 B |
| [aidcj.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/aidcj.js) | Ai大藏经 | 337 B |
| [aimirror.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/aimirror.js) | * AI Mirror | 64.3 KB |
| [AppRaven.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/AppRaven.js) | AppRaven | 560 B |
| [AppRavenTask.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/AppRavenTask.js) | — | 164.9 KB |
| [AppraveTask.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/AppraveTask.js) | 脚本名称: AppRaven 邀请助手 (Module版) | 194.7 KB |
| [aymy.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/aymy.js) | 哎呀漫鸭 | 40.3 KB |
| [BHpro.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/BHpro.js) | ************************************ | 1.2 KB |
| [BodyOk.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/BodyOk.js) | BodyOk 4.1.9 | 1.3 KB |
| [BookRclass.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/BookRclass.js) | * bookrclass | 8.0 KB |
| [bqwz.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/bqwz.js) | * | 5.4 KB |
| [bsxm.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/bsxm.js) | rewrite_local | 319 B |
| [bszw.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/bszw.js) | * 笔神作文 | 6.2 KB |
| [cad.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/cad.js) | rewrite_local | 184.9 KB |
| [CamScanner.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/CamScanner.js) | ************************************ | 4.1 KB |
| [carrot.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/carrot.js) | * CARROTWeathe | 25.2 KB |
| [carrot2.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/carrot2.js) | — | 5.1 KB |
| [chsj.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/chsj.js) | * 插画世界 | 477 B |
| [Clipboard.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/Clipboard.js) | * Clipboard | 10.5 KB |
| [damaopeilian.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/damaopeilian.js) | * 大猫ai练琴 | 8.5 KB |
| [damaopeilian2.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/damaopeilian2.js) | — | 4.8 KB |
| [Documents.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/Documents.js) | Documents | 13.2 KB |
| [dtk.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/dtk.js) | q | 799 B |
| [dtpk.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/dtpk.js) | * | 10.2 KB |
| [DuetDisplay.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/DuetDisplay.js) | ‎Duet Display 2.18 | 606 B |
| [dydsk.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/dydsk.js) | 大渔大师课 | 850 B |
| [dzyj.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/dzyj.js) | app：地址预警 | 469 B |
| [emmo.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/emmo.js) | * Emmo日记 | 438 B |
| [feel.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/feel.js) | * feelFlow | 1.4 KB |
| [feelFlow.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/feelFlow.js) | * feelFlow | 1.4 KB |
| [felo.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/felo.js) | — | 5.7 KB |
| [felock.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/felock.js) | 7.18 | 7.3 KB |
| [forest.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/forest.js) | forest | 1.2 KB |
| [fqzm.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/fqzm.js) | 番茄助眠 | 177.7 KB |
| [FTzhongwenwang.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/FTzhongwenwang.js) | ***************************** | 785 B |
| [genpix.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/genpix.js) | * 软件名称: GenPix | 20.1 KB |
| [GTP4o.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/GTP4o.js) | GTP4o | 650 B |
| [GTP4ohd.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/GTP4ohd.js) | — | 182 B |
| [gzm.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/gzm.js) | * 歌者盟 | 936 B |
| [Handy.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/Handy.js) | * | 8.2 KB |
| [hulashaoeryy.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/hulashaoeryy.js) | 呼啦少儿英语 | 508 B |
| [ins.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/ins.js) | ins社区 | 144.5 KB |
| [insck.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/insck.js) | — | 518 B |
| [iTunes.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/iTunes.js) | ************************************ | 29.3 KB |
| [jgty.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/jgty.js) | * 激光投影 | 658 B |
| [Jieluoxuan.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/Jieluoxuan.js) | 解螺旋 | 27.1 KB |
| [kanlixiang.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/kanlixiang.js) | — | 178.4 KB |
| [kaoshibao.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/kaoshibao.js) | rewrite_local | 6.0 KB |
| [kaoyanxcx.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/kaoyanxcx.js) | ***************************** | 9.7 KB |
| [kaoyaoshi.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/kaoyaoshi.js) | 考药狮 | 1.9 KB |
| [kd.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/kd.js) | "},timeout:r};this.post(n,(t,e,a)=>s(a))}).catch(t=>this.logErr(t))}loaddata(){if(!this.is | 10.0 KB |
| [kdf.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/kdf.js) | * 看东方 | 12.5 KB |
| [kugou.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/kugou.js) | 01-10 | 27.3 KB |
| [KuGougainianban.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/KuGougainianban.js) | ************************************************ | 8.3 KB |
| [kugouksong.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/kugouksong.js) | * | 5.9 KB |
| [kugouv5.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/kugouv5.js) | — | 129.6 KB |
| [kuwotask.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/kuwotask.js) | * 原作者 @mcdasheng688 @General74110 | 41.8 KB |
| [lanjiyin.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/lanjiyin.js) | * 蓝基因医学 | 155.5 KB |
| [LectMate.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/LectMate.js) | * 有道留学听课宝 | 147.4 KB |
| [LittleFox.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/LittleFox.js) | rewrite_local | 10.1 KB |
| [lovekey.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/lovekey.js) | * | 10.6 KB |
| [luping.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/luping.js) | 抖音快手直播录屏 | 23.1 KB |
| [lwj.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/lwj.js) | * 朗文家 | 5.8 KB |
| [m3u.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/m3u.js) | * 看东方 M3U源 | 231.8 KB |
| [mgspck.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/mgspck.js) | 伟人咪咕视频 只是适配代理工具 | 30.6 KB |
| [mh.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/mh.js) | 1.添加脚本 | 2.5 KB |
| [mimo.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/mimo.js) | * mimo | 6.1 KB |
| [mjtv.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/mjtv.js) | * 麦咭TV | 7.9 KB |
| [mlxx.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/mlxx.js) | * 美丽修行 | 2.2 KB |
| [mohe.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/mohe.js) | 魔核 | 19.0 KB |
| [msb.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/msb.js) | 马士兵 | 797 B |
| [mxshm.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/mxshm.js) | 漫小肆韓漫 | 682 B |
| [mxy.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/mxy.js) | * | 182.0 KB |
| [NBshiyanshi.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/NBshiyanshi.js) | * NB实验室 | 19.3 KB |
| [nihaixiazydq.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/nihaixiazydq.js) | 倪海厦中医大全 | 906 B |
| [Not.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/Not.js) | rewrite_local | 1002 B |
| [one.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/one.js) | * 软件名称: One·一个 | 12.9 KB |
| [One1222.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/One1222.js) | * 软件名称: o*N （一个） | 216.0 KB |
| [one2jj.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/one2jj.js) | * one2jj | 23.2 KB |
| [one_daily_task.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/one_daily_task.js) | 每天晚上9点提示你是否戒色？ | 214.5 KB |
| [PDFexpert.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/PDFexpert.js) | 项目名称：PDF点睛 | 21.3 KB |
| [peak.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/peak.js) | * Peak | 5.5 KB |
| [pear.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/pear.js) | * | 180.0 KB |
| [pitaya.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/pitaya.js) | * 火龙果 | 889 B |
| [plpl.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/plpl.js) | * | 146.9 KB |
| [pptds.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/pptds.js) | * PPT大师 | 6.9 KB |
| [prompt3.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/prompt3.js) | Prompt3 | 1.8 KB |
| [PSExpress.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/PSExpress.js) | PSExpress 23.49.1 | 6.0 KB |
| [PureLibro.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/PureLibro.js) | ***************************** | 1.9 KB |
| [RavenTask.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/RavenTask.js) | // AppRaven 14‑Day Premium (QX / Surge / Loon) | 671 B |
| [Revenuecat.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/Revenuecat.js) | ************************************ | 11.0 KB |
| [rjdd.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/rjdd.js) | rewrite_local | 158.6 KB |
| [RRSP.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/RRSP.js) | * @name RRTV 4K | 166.6 KB |
| [RSA.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/RSA.js) | ! JSEncrypt v2.3.0    */ | 165.7 KB |
| [rwmm.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/rwmm.js) | 哎呀漫鸭 | 22.1 KB |
| [SDvpn.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/SDvpn.js) | * 赛盾VPN | 23.2 KB |
| [sgbl.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/sgbl.js) | 时光伴侣 | 1.3 KB |
| [sgvpn.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/sgvpn.js) | * 松过VPN | 23.1 KB |
| [simplypiano.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/simplypiano.js) | simplypiano | 5.0 KB |
| [sj100.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/sj100.js) | * 试卷100 | 5.3 KB |
| [skbz.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/skbz.js) | "},timeout:r};this.post(n,(t,e,a)=>s(a))}).catch(t=>this.logErr(t))}loaddata(){if(!this.is | 9.7 KB |
| [speedtest.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/speedtest.js) | — | 1.4 KB |
| [super.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/super.js) | * 超级应用锁 | 480 B |
| [taoluyingshi.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/taoluyingshi.js) | 套路影视 | 14.6 KB |
| [TgRedirect.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/TgRedirect.js) | * | 2.5 KB |
| [ticaiku.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/ticaiku.js) | * | 13.6 KB |
| [tlsm.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/tlsm.js) | name.toLowerCase(); · 套路SM (tlsm.one) VIP 解锁 | 9.3 KB |
| [tlsm.surge.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/tlsm.surge.js) | "},timeout:o};this.post(n,(e,t,i)=>s(i))}).catch(e=>this.logErr(e))}loaddata(){if(!this.is | 14.0 KB |
| [TOPlt.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/TOPlt.js) | rewrite_local | 98.2 KB |
| [tzsp.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/tzsp.js) | rewrite_local | 170.9 KB |
| [vpn.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/vpn.js) | Eric | 13.7 KB |
| [vpssp.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/vpssp.js) | — | 7.1 KB |
| [wallhaven.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/wallhaven.js) | * wallhaven | 10.1 KB |
| [wk.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/wk.js) | * 万康人体解剖 | 411 B |
| [WM4K.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/WM4K.js) | — | 396 B |
| [wpxz.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/wpxz.js) | * | 1.0 KB |
| [wpyx.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/wpyx.js) | * 王派医学 | 139.3 KB |
| [wxcode.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/wxcode.js) | 提取 code | 1.4 KB |
| [wyux.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/wyux.js) | * 外研u学 | 80.6 KB |
| [wyzjh.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/wyzjh.js) | * 我要做计划 | 6.0 KB |
| [xbfn.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/xbfn.js) | — | 51.2 KB |
| [xbl.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/xbl.js) | 小伴龙 | 451 B |
| [xdsxy.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/xdsxy.js) | * 行动商学院 | 5.7 KB |
| [xfbs.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/xfbs.js) | * | 146.1 KB |
| [xgvpn.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/xgvpn.js) | * 西瓜加速器 | 26.9 KB |
| [xiaohuli.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/xiaohuli.js) | * | 17.5 KB |
| [xmjsq.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/xmjsq.js) | 小明计算器 | 162.4 KB |
| [xt.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/xt.js) | * 炫图ai画图 | 17.3 KB |
| [xt2.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/xt2.js) | "},timeout:r};this.post(n,(t,e,a)=>s(a))}).catch(t=>this.logErr(t))}loaddata(){if(!this.is | 9.7 KB |
| [xt3.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/xt3.js) | 实际不用改这么多 | 789 B |
| [yangtao.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/yangtao.js) | * 樱桃PLUS | 151.2 KB |
| [yjt.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/yjt.js) | * 易截图2 | 547 B |
| [ypjj.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/ypjj.js) | * 音频剪辑 | 611 B |
| [yxpl.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/yxpl.js) | * 音熊陪练 | 5.7 KB |
| [yyfysq.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/yyfysq.js) | * 粤语翻译神器 | 1.5 KB |
| [yyjy1.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/yyjy1.js) | * | 678 B |
| [zimuquan.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/zimuquan.js) | 字母圈 | 343.6 KB |
| [zjsg.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/zjsg.js) | * 指尖时光 | 1.7 KB |
| [zuimeibizhi.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/zuimeibizhi.js) | 最美壁纸 | 48.2 KB |
| [zyb.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/zyb.js) | * 作业帮 | 7.8 KB |

**1808/**（2 个）

| 文件 | 用途 | 大小 |
|---|---|---|
| [fake.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/1808/fake.js) | — | 262 B |
| [page.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/1808/page.js) | — | 2.7 KB |

**AD/**（1 个）

| 文件 | 用途 | 大小 |
|---|---|---|
| [maiduidui.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/AD/maiduidui.js) | — | 776 B |

**BiliBili/**（1 个）

| 文件 | 用途 | 大小 |
|---|---|---|
| [BiliBili.Modified.response.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/BiliBili/BiliBili.Modified.response.js) | * | 33.9 KB |

**KDF/**（2 个）

| 文件 | 用途 | 大小 |
|---|---|---|
| [kandonfang.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/KDF/kandonfang.js) | — | 701 B |
| [video-parser.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/KDF/video-parser.js) | * 看东方 | 22.6 KB |

**huangdouduanju/**（1 个）

| 文件 | 用途 | 大小 |
|---|---|---|
| [huangdou.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/huangdouduanju/huangdou.js) | huangdou.js - Build 2026-09-07 12:11:48 */ | 107.7 KB |

**itunes/**（82 个）

| 文件 | 用途 | 大小 |
|---|---|---|
| [1001.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/1001.js) | 1001 | 10.2 KB |
| [3Dscanner.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/3Dscanner.js) | 3D scanner | 10.2 KB |
| [6fzyy.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/6fzyy.js) | 6分钟英语 | 15.3 KB |
| [Again.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Again.js) | Again 最简洁的阅读器 | 10.2 KB |
| [Ailinghui.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Ailinghui.js) | Ai灵绘 2.1.1 | 10.2 KB |
| [baiban.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/baiban.js) | * 白板 | 10.5 KB |
| [bbaabbyy.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/bbaabbyy.js) | bbaabbyy | 10.4 KB |
| [bizhi.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/bizhi.js) | 壁纸 4.5.4 | 10.2 KB |
| [BodyTune.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/BodyTune.js) | BodyTune 2.1.1 | 10.1 KB |
| [bs.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/bs.js) | bs | 10.2 KB |
| [CamTranslator.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/CamTranslator.js) | * Cam Translator | 10.5 KB |
| [CapyMood.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/CapyMood.js) | CapyMood 1.1.0 | 10.3 KB |
| [celiangyuan.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/celiangyuan.js) | 测量员Pro | 10.2 KB |
| [chatbotai.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/chatbotai.js) | * Chatbotai | 19.1 KB |
| [cwd.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/cwd.js) | 宠物岛 | 10.2 KB |
| [daanjl.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/daanjl.js) | * | 10.2 KB |
| [Dictionary.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Dictionary.js) | * Dictionary & Translator | 10.6 KB |
| [dingdangdaiban.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/dingdangdaiban.js) | 叮当代办 | 10.2 KB |
| [ECG.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/ECG.js) | ECG+ | 10.2 KB |
| [EWA.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/EWA.js) | EWA-轻松学习英语阅读 | 10.3 KB |
| [gqjp.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/gqjp.js) | * 钢琴简谱 | 10.3 KB |
| [guangyingxiutu.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/guangyingxiutu.js) | 光影修图 2.5 | 10.2 KB |
| [hsfxq.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/hsfxq.js) | 鼾声分析器 | 10.3 KB |
| [Iam.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Iam.js) | * | 10.3 KB |
| [Impresso.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Impresso.js) | * ‎Impresso | 10.5 KB |
| [Jiazigu.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Jiazigu.js) | 架子鼓 | 10.1 KB |
| [JisuanqiAir.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/JisuanqiAir.js) | ‎计算器 Air 5.1.0 | 10.3 KB |
| [jrxy.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/jrxy.js) | 今日抽烟 | 10.2 KB |
| [jzxd.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/jzxd.js) | 驾照学典 | 10.1 KB |
| [lunwenjun.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/lunwenjun.js) | 论文君 | 10.2 KB |
| [Mindllama.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Mindllama.js) | * Mindllama | 10.4 KB |
| [moguixiangji.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/moguixiangji.js) | 魔鬼相机 3.996 | 10.3 KB |
| [Mondly.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Mondly.js) | Mondly 7.1.13 | 10.2 KB |
| [Morse.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Morse.js) | Morse | 10.1 KB |
| [Motivation.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Motivation.js) | * | 10.3 KB |
| [NYFM.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/NYFM.js) | NYFM 1.5.2 | 10.2 KB |
| [OfflineMusicPlayer.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/OfflineMusicPlayer.js) | Offline Music Player | 10.1 KB |
| [onesec.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/onesec.js) | * one sec | 10.5 KB |
| [pdfpro.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/pdfpro.js) | Pdf prl | 10.2 KB |
| [pdfReaderfree.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/pdfReaderfree.js) | PDf Reader Free | 10.4 KB |
| [PicPro.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/PicPro.js) | PicPro 3.1.8 | 10.2 KB |
| [PicsLeap.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/PicsLeap.js) | PicsLeap 2.1.5 | 10.2 KB |
| [pollykann.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/pollykann.js) | 小鹦看看 | 10.2 KB |
| [PolyGit.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/PolyGit.js) | * PolyGit | 10.5 KB |
| [PrettyUp.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/PrettyUp.js) | PrettyUp 6.8.2 | 10.4 KB |
| [ProFit.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/ProFit.js) | ProFit | 10.2 KB |
| [pthxx.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/pthxx.js) | 普通话学习 | 10.2 KB |
| [Ptime.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Ptime.js) | Ptime 1.5.0 | 10.2 KB |
| [qianbihua.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/qianbihua.js) | * | 10.3 KB |
| [Retake.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Retake.js) | Retake | 10.3 KB |
| [RitmoVideo.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/RitmoVideo.js) | RitmoVideo 2.4.0 | 9.3 KB |
| [RSBJ.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/RSBJ.js) | 人生笔记 | 10.3 KB |
| [RZJThb.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/RZJThb.js) | R&Z阶梯绘本 | 10.1 KB |
| [ShellBean.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/ShellBean.js) | — | 43 B |
| [shoton.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/shoton.js) | SHOT ON | 10.2 KB |
| [shudu.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/shudu.js) | 数独 3.8.0 | 10.2 KB |
| [Side.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Side.js) | Side p照片的 | 10.2 KB |
| [smartgym.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/smartgym.js) | smartgym 7.2.6 | 10.4 KB |
| [SnapEdit.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/SnapEdit.js) | * ‎SnapEdit | 10.5 KB |
| [songsterr.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/songsterr.js) | Songsterr 7.1.0 | 10.2 KB |
| [sparkai.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/sparkai.js) | * wkmusic | 10.4 KB |
| [spxz.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/spxz.js) | 视频下载 | 10.3 KB |
| [sssmjc.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/sssmjc.js) | 时尚素描教程 | 10.2 KB |
| [StandByUs.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/StandByUs.js) | StandByUs | 10.3 KB |
| [Storybeat.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Storybeat.js) | Storybeat 4.9.2 | 10.1 KB |
| [sunally.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/sunally.js) | * sunally | 10.5 KB |
| [tubepod.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/tubepod.js) | TubePod | 10.2 KB |
| [typeon.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/typeon.js) | TypeOn翻译 | 10.2 KB |
| [Unidream.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Unidream.js) | * Unidream | 10.6 KB |
| [vllo.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/vllo.js) | Vllo | 10.3 KB |
| [wkmusic.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/wkmusic.js) | * wkmusic | 10.5 KB |
| [wmyx.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/wmyx.js) | 完美影像 5.1.7 | 10.4 KB |
| [xgn.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/xgn.js) | 同作者 | 10.1 KB |
| [Xk.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/Xk.js) | 星空 12.0.2 | 10.3 KB |
| [xqjs.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/xqjs.js) | 象棋js | 10.3 KB |
| [yytt.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/yytt.js) | yytt | 10.2 KB |
| [yyxw.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/yyxw.js) | 英语新闻 | 10.2 KB |
| [yyyj.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/yyyj.js) | 英语演讲 | 10.2 KB |
| [yzqnw.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/yzqnw.js) | ************************************ | 1.3 KB |
| [zhouzhouji.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/zhouzhouji.js) | 周周记 | 10.3 KB |
| [ztqs.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/ztqs.js) | 真题全刷 | 10.1 KB |
| [zyjh.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/itunes/zyjh.js) | 中医精华 | 10.1 KB |

**moshi/**（1 个）

| 文件 | 用途 | 大小 |
|---|---|---|
| [moshi-pro.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/moshi/moshi-pro.js) | — | 18.2 KB |

**wuyouyunpan/**（1 个）

| 文件 | 用途 | 大小 |
|---|---|---|
| [vip_static.js](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/scripts/wuyouyunpan/vip_static.js) | — | 499 B |

## 其他（附属配置）

BoxJS 订阅等附属文件，非模块主体，按需取用。

| 文件 | 说明 | 大小 |
|---|---|---|
| [boxjs订阅.json](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/其他/配置/boxjs订阅.json) | 频道脚本的 BoxJS 订阅入口 | 1.5 KB |
| [PearVideo.boxjs.json](https://raw.githubusercontent.com/qmq123181/Jsforbaby/main/其他/配置/PearVideo.boxjs.json) | 梨视频 BoxJS 配置 | 21.8 KB |

## ipa / dmg 与 dylib

频道内的 `*.ipa`、`*.dmg`、`*.dylib` 属于第三方应用的安装包与破解注入库（含对商业 App 的授权绕过），**本仓库不转存、不镜像**，只保留目录占位。需要时请回到原频道对应帖子自取，风险与合规由使用者自负。

## 未收录内容

- **成人 / 18+ 站点相关脚本与模块**（约 12 组应用，含同名衍生版本）— 不纳入本汇总。
- 上游仓库中的构建中间产物（`dist/`、`src/`、`package.json`）、`.zip` 压缩包、以及含 token / 登录态 / 收据的明文文件（`onetoken*`、`peartoken`、`fqzm.txt`、`rr.txt`、`Not.txt` 等）— 属于凭据或隐私数据，一律剔除。
- 重复用途：同一应用同平台存在多份时只保留较新的一份，其余未收录。

## 第三方内容与致谢

- 上游作者：[𝒃𝒂𝒃𝒚 频道](https://t.me/Jsforbaby) · [ios151](https://github.com/ios151) · [Yu9191](https://github.com/Yu9191)
- 部分脚本沿用原作者的二次来源（fmz200 广告拦截合集、Script-Hub 转换、BoxJS 等），版权归原作者所有。
- 姊妹项目：[qmq123181/fkikelee](https://github.com/qmq123181/fkikelee)（可莉插件整理版）。

## 更新记录

- 2026-11-11：首次建立，收录上游 2026-11-11 前内容；剔除成人站群、破解二进制与凭据文件。
