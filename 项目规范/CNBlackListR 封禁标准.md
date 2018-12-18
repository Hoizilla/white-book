# 综述
- 机器人包含两个级别的，0（严重）会被踢出（如果群组[开启](https://github.com/CNBlackListR/white-book/blob/master/使用说明.md)了 `AutoKick`），1（警告）只是提示群主需要注意
- 群主可以选择遇到 Spam 时只是警告（`/soamenable BlackList`），或者是给予机器人权限并[开启](https://github.com/CNBlackListR/white-book/blob/master/使用说明.md) `AutoKick`
- 所有 Spam 证据将会放在频道 [@CNBlackListEvidence](https://t.me/CNBlackListEvidence)；理由将会放在频道 [@CNBlackListR](https://t.me/CNBlackListR)
- 所有判断将会避免偏向性，所有判决将会尽量在群组 [@CNBlackListRChat](https://t.me/CNBlackListRChat) 放出讨论
- 如果您被封禁，但是认为判决有误，请通过申诉机器人 [@CNBlackListRTicketBot](https://t.me/CNBlackListRTicketBot) 进行申诉并给出较为详细的理由。


# 判断规则

1. 所有群组如果没有特殊标明，默认视作接受群组 / 频道链接广告。除了群发（详见第三条）以外其他不处理。
2. 默认认为所有群组类型为 SFW，除非另有说明。处理在 SFW 群组里散布 R15/R18 论坛、群组、频道等链接及图片、视频、GIF 等媒体文件的情况。等级设定为 0
3. 不受众多群组欢迎的判断：在5种不同话题的群组，超过10个群组，同时群成员大于 200 人的群组被移出，将会被标记为不受欢迎的用户，等级为 0
4. 对于 * 散布 * 的最低阈值定义为 3 个群组。辅助规定：包含链接（aff，其他群组 / 频道）的消息，在讨论话题不相关 / 在规定禁止推广的群组出现，消息反复出现并不定期刷屏。在最低阈值达到并满足任意一辅助规定将会被直接判定 Spam
5. 处理伪造他人身份的情况，如果被伪造用户如果存在相应的 Telegram 账户则给出警告。如果被仿冒者要求项目对这位用户执行封禁，项目将会在考虑影响情况的严重程度过后再处理（实例见 假Breakwa11 事件）
6. 除特别恶劣事件（例如单单因为有人损害了自己的利益而跑到多于 5 个群故意破坏他人正常声誉，实例见 `@Fengyun` 事件），本项目不处理个人或团体意见不合的情况。
7. 本项目在处理 “政治经济” 相关群组成员的任何冲突事件时，如果范围仅在相关讨论群组内则不会处理。如果范围扩大将会避免给出任何级别为 0 的处理，只会给出提示性消息（级别为 1 的消息）给各个群主参考。出现扩散群发则将相关群组排除计数后按照第三条处理。
8. Halal（清真）判断，可参见[这里](https://wfjsw.gitbooks.io/tgcn-groupindex-reference/plugin_antihalal.html)。默认将会自动提示并尝试删除（如果给予权限并开启功能）。


# 处罚时长
- 条例 2，3，4 所述情况封禁时间限制在 1 小时 - 3 个月
- 条例 5，6 所述情况封禁时间限制在 3 个月 - 3 年
- 条例 8 所述情况封禁为永久  

群组创建者或管理员可随时使用 `/soamdisable BlackList` 关闭此警告 / 封禁（AutoKick）功能。

**启用该功能并授予机器人管理员权限即视为同意上述策略。**

（对应的，使用 `/soamenable BlackList (AutoKick)` 重新开启）

更多意见您可以随时加入群组 ([@CNBlackListRChat](https://t.me/CNBlackListRChat)) 讨论。
