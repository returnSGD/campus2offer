# 把经历变成证据

![Build PDF](https://github.com/returnSGD/campus2offer/actions/workflows/build.yml/badge.svg)

**计算机学生的四年规划与求职实战**（工作稿 v1.0）

> 把学习变成证据，把选择变成实验，把工作变成下一次选择的起点。

## 下载

- **最新编译版（PDF）**：[Releases · latest](https://github.com/returnSGD/campus2offer/releases/latest)
- 直链：`https://github.com/returnSGD/campus2offer/releases/latest/download/campus2offer-latest.pdf`

**仓库里不存 PDF。** 每次 `main` 有更新（包括合并 PR），CI 会重新编译并覆盖这个 release 的 PDF；想看旧版就翻 Releases 历史或 Actions 的 artifact。这样贡献者改 `.tex` 时不会和编译产物打架。
这本书写给计算机大类的高中生、本科生和应届生：从选专业、看培养方案、做第一个真实项目，到写简历、面试、选 offer、入职前九十天。它不承诺 offer，只提供一套更可靠的工作方式——**先把问题说清楚，做一个成本可承受的实验，进入真实环境，记录结果，再根据证据调整方向**。

## 这本书里有什么

- **14 章正文**：起点（专业、时间轴、分叉口）→ 能力（工程、刷题、协作、代表作）→ 求职（岗位、企业、简历、面试、秋招）→ 现实（钱、心态、信息、复盘）
- **7 个附录**：四类读者的行动路线、冷启动通信脚本库、项目卡与成果账本、术语表、主题索引、来源与参考文献、留言板
- **可填写的工具**：方向实验卡、JD 拆解表、Offer 权重表、项目卡、成果账本
- **带出处的数据**：毕业生规模、行业工资、软件业收入、青年失业率等，脚注给出原始发布与日期

## 怎么用这个仓库

| 目的一 | 看这里 |
|---|---|
| 直接读书 | [Releases · latest](https://github.com/returnSGD/campus2offer/releases/latest)（PDF 由 CI 自动发布） |
| 改书稿 | [把经历变成证据-初稿.tex](./把经历变成证据-初稿.tex)（XeLaTeX + ctexbook） |
| 参与贡献 | [CONTRIBUTING.md](./CONTRIBUTING.md) |
| 看改动记录 | [编辑说明.md](./编辑说明.md) |
| 改了内容要同步什么 | [维护指南.md](./维护指南.md) |

## 本地编译

需要 TeX Live 或 MiKTeX（含 XeLaTeX 与 ctex），中文字体为 SimSun / Times New Roman：

```bash
xelatex 把经历变成证据-初稿.tex
xelatex 把经历变成证据-初稿.tex   # 第二遍生成目录
```

## 欢迎 PR 的东西

- 真实、脱敏的案例（踩坑、复盘、面试追问）
- 简历 Before / After
- 项目拆解、README 模板、压测与评测脚本
- 岗位与公司的公开信息整理
- 事实核对：数据过期、口径错误、链接失效

不要提交：广告、课程推销、未经授权的他人内容、无法追溯来源的数字。

## 许可

- 文字内容：[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)（署名—非商业性使用—相同方式共享）
- 代码片段：MIT

## 联系

- X：[@sundayai_](https://x.com/sundayai_)
- 邮箱：sunday.xu@ttcadvisory.com
