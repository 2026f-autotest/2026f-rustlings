# Rustlings 接入验证

2026-09-15，北京时间。

## 来源与题目

使用 [LearningOS/2026s-rustling-classroom-template](https://github.com/LearningOS/2026s-rustling-classroom-template) 的提交 `ade06927b84603689356bde886616dd40d3265de`。全部 `exercises/`、`info.toml`、`Cargo.toml` 和 `Cargo.lock` 与上游一致，共 110 题，每题 1 分。

原始模板已经完成前 30 题，本地全量评测实测 30/110；本次没有将验证仓库新增的解答放回模板。

评测运行器只调整了临时产物目录，以及构建脚本成功时输出原始测试结果的行为；继续调用上游的编译、测试、Clippy 和 Cargo 构建脚本逻辑。

## 自动领取

- [真实领取申请](https://github.com/2026f-autotest/enroll/issues/14)。
- [自动建仓运行](https://github.com/2026f-autotest/enroll/actions/runs/34924114984)：成功。
- [学员配置检查](https://github.com/2026f-autotest/2026f-rustlings-Alayfolk64/actions/runs/34924133737)：成功，`STUDENT_GITHUB=Alayfolk64`，组织课程凭证可读取。
- 机器人回复正式仓库、邀请及配置检查链接，并自动关闭申请。

## 真实解答、评测和排行榜

学员仓库：[2026f-rustlings-Alayfolk64](https://github.com/2026f-autotest/2026f-rustlings-Alayfolk64)。

提交 `5981c928c09b8e5d37a7e655ff0474bf0ba32e93` 实际完成以下五题：

| 题目 | 评测模式 |
| --- | --- |
| `structs1` | 单元测试，3 项测试通过 |
| `strings1` | 编译并运行 |
| `clippy1` | Clippy 检查并运行 |
| `tests7` | 构建脚本设置环境变量，1 项测试通过 |
| `tests8` | 构建脚本设置条件编译，1 项测试通过 |

[真实 push 触发的评测运行](https://github.com/2026f-autotest/2026f-rustlings-Alayfolk64/actions/runs/34924284081) 完整执行 110 题，35 题通过、75 题未通过，总分 **35/110**。评测作业耗时 52 秒，独立上传作业耗时 10 秒。

还有题目未完成，因此评测作业按规则标红；上传作业成功，日志确认 `OpenCamp accepted the score (result=1).`，成绩文件记录 `upload.status=accepted`。通过公开排行榜查询接口读回 `Alayfolk64` 的成绩为 **35 分**，与 CI 结果一致。

## 自动化检查

- 模板身份校验、评分适配、领取备用入口和上传状态等 22 项测试通过：[云端运行](https://github.com/2026f-autotest/2026f-rustlings/actions/runs/34924037275)。
- 领取入口 35 项测试通过：[云端运行](https://github.com/2026f-autotest/enroll/actions/runs/34924070001)。
- 模板只有维护者 `Alayfolk64` 拥有写入权限，没有分配团队写权限。

本次是功能验证，未进行大规模并发压力测试。
