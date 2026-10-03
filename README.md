# achievements

本仓库用于点亮 GitHub 个人主页成就徽章（Achievements）。

当前进度（等级门槛来自 GitHub 官方社区讨论 #209029）：

| 成就 | 等级门槛 | 当前进度 |
|------|----------|----------|
| Quickdraw | 5 分钟内关闭 issue / PR（无等级） | ✅ 已达成，徽章已显示 |
| Yolo | 合并无评审 PR（无等级） | ✅ 条件已满足，等官方发放 |
| Pull Shark | 2 / 16 / 128 / 1024 个合并 PR | ✅ 130 个 → 银级 |
| Galaxy Brain | 2 / 8 / 16 / 32 个采纳答案 | ✅ 33 个 → 金级 |
| Pair Extraordinaire | 1 / 10 / 24 / 48 个联合署名合并 | 铜级以下，需他人配合 |

实现方式：

- Quickdraw：issue #1 开启 3 秒后关闭
- Yolo：PR #2 无评审直接合并
- Pull Shark：`notes/` 下每个里程碑 PR 对应一个小文件，全部 squash 合并
- Galaxy Brain：Q&A 分类的 Discussions 自问自答并采纳（只有 Q&A 分类支持采纳答案）

无法自助完成的成就：

- **Star Gazer**：单个仓库 16 / 128 / 512 / 4096 星，只能靠真实项目攒星
- **Public Sponsor**：需要通过 GitHub Sponsors 真实赞助
- **Pair Extraordinaire 高等级**：需要其他 GitHub 账号的联合署名提交
- **Heart On Your Sleeve / Open Sourcerer**：官方内部测试中，暂不可获得
- **Arctic Code Vault / Mars 2020**：历史限定，已无法获得

> 注：徽章发放为异步任务，通常几分钟到几小时内到账，可在个人主页查看。
