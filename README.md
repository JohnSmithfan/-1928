# 奉天1928

## 项目简介

《奉天1928》是一部多人协作创作的历史架空电子小说。

故事讲述张学良重生回到皇姑屯事件前半个月，凭借前世记忆，他做的第一件事，是保住父亲张作霖不被日军暗杀（第一个情节：救父）。随后，他远赴德国购买技术生产线（主线大情节），利用超前认知与工业资源，推动中国提前展开全面抗日准备，事件跨度从1928年抗日开局到1955年建国与重建。

## 项目目标

- 以多人协作方式，共同创作一部高质量的历史架空长篇电子小说
- 通过 Git 版本控制管理章节创作与修订历史
- 建立统一的写作规范与世界设定文档，保证文风一致

## 故事背景

- **书名**：《奉天1928》
- **题材**：历史架空 / 军事 / 工业建设 / 权谋
- **核心设定**：张学良重生，预知历史走向
- **时间跨度**：1928年 — 1955年
- **规划规模**：约 1008 章 × 每章约 4000 字 ≈ 400 万字（五卷，第1—1008章：第一卷1—88、第二卷89—288、第三卷289—591、第四卷592—743、第五卷744—1008）

## 故事简介

张学良重生至1928年皇姑屯事件前半个月，凭借对未来的记忆，
从救父开始，一步步改变东北乃至整个中国的命运。
时间跨度从1928年抗日到1955年建国与重建。

> 📖 完整剧情总纲请查看 [SYNOPSIS.md](./SYNOPSIS.md)

## 文件结构

```
奉天1928/
├── README.md              ← 项目介绍与参与方式
├── SYNOPSIS.md            ← 剧情总纲
├── STYLE-GUIDE.md         ← 写作风格
├── progress.md            ← 进度与规划（唯一；含「附一：总体规划」，原 PLAN.md 已并入并删除）
├── CHANGELOG.md           ← 变更日志
├── LICENSE                ← CC BY-NC-SA 4.0 协议
├── CONTRIBUTING.md        ← 写作协作规范 ＋ §12 文件卫生条例
├── CODE_OF_CONDUCT.md     ← 行为准则（注意是空格，非下划线）
├── SECURITY.md            ← 安全政策（凭据泄漏的上报渠道）
├── SUPPORT.md             ← 支持渠道与提问前自查
├── .gitignore             ← Git忽略规则
├── .gitattributes         ← 换行符口径（全库 LF）
├── .github/               ← Issue / PR 模板、CODEOWNERS
├── chapters/              ← 正文唯一存放目录（卷/幕/单章：`第NNN章 四字标题.md`）
├── characters/            ← 角色设定
├── worldbuilding/         ← 世界观设定（含 OUTLINE/ 五卷大纲，分卷权威源）
├── issues/                ← 卷/幕剧情讨论 Issue（每幕一个，附索引）
├── notes-personal/        ← 个人工作草稿（大纲拼接副本/设定草稿，非权威源）
└── _trash/                ← 唯一回收站（按用途+日期分子目录，附 MANIFEST.md）
```

> ⚠️ 根目录只许存在上面这些条目，多一个都判违规 —— 见 [CONTRIBUTING.md §12](./CONTRIBUTING.md) 文件卫生条例。

## 参与方式

1. 阅读 [CONTRIBUTING.md](./CONTRIBUTING.md) 了解协作规范（**含 §12 文件卫生条例**）
2. 阅读 [STYLE-GUIDE.md](./STYLE-GUIDE.md) 了解写作风格要求
3. 在 `.github/ISSUE_TEMPLATE/` 中认领章节或提出写作建议（四类模板：章节认领／设定勘误／创作建议／文件卫生）
4. 创建分支进行写作，提交 Pull Request 请求审校（模板见 [PULL_REQUEST_TEMPLATE.md](./.github/PULL_REQUEST_TEMPLATE.md)）
5. 审校通过后合并至主分支

### 提 Issue 前先看这里

| 你要做的事 | 用哪个模板 |
|---|---|
| 认领某一章 | [章节认领](./.github/ISSUE_TEMPLATE/章节认领.md) |
| 报告史实／设定／数字错误 | [设定勘误](./.github/ISSUE_TEMPLATE/设定勘误.md) |
| 提议情节／角色／支线 | [创作建议](./.github/ISSUE_TEMPLATE/创作建议.md) |
| 发现垃圾文件或格式污染 | [文件卫生](./.github/ISSUE_TEMPLATE/文件卫生.md) |
| 疑似凭据泄漏 | [SECURITY.md](./SECURITY.md)，**勿开公开 Issue** |

## 文件卫生（一句话）

仓库里出现**零字节文件、临时扫描产物、散落备份、根目录越界文件、脚本堆积、末尾无换行、换行符混杂、BOM、文件名异常、内容重复、`_trash/` 堆积**——任一项——都走同一条路：**出报告 → 确认 → 按报告改 → 复扫登记**。判定清单与五步流程见 [CONTRIBUTING.md §12](./CONTRIBUTING.md)，自查工具 python `.workbuddy/scripts/scan_hygiene.py`。

## 版权声明

本项目采用 Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) 协议开源。详见 LICENSE 文件。

## 联系方式

欢迎通过 GitHub Issues 参与讨论，或加入项目交流群获取最新动态。
