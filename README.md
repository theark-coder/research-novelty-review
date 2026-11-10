# Research Novelty Review

一个用于 Codex 的中文 Skill，通过文献对照评估论文想法或技术方案的创新性，识别新增贡献、关键问题和验证路径。

## 功能

- 比较最接近研究的问题设定、核心方法、假设及贡献。
- 分别评估创新性、研究价值与技术可行性。
- 区分文献结论、分析推断和待验证假设。
- 分别分析模块贡献、模块间关系及整体任务贡献，为拟主张的差异提出直接比较实验。
- 对关键问题提出可执行、成本合理的改进建议。

## 安装

在 Codex 中输入：

```text
$skill-installer 从以下 GitHub 目录安装 Skill：
https://github.com/theark-coder/research-novelty-review/tree/main/skills/research-novelty-review
```

也可以下载本仓库，将 `skills/research-novelty-review` 文件夹复制到目标项目的 `.agents/skills/` 目录中，保持 `research-novelty-review/SKILL.md` 的结构。

## 使用

```text
$research-novelty-review 评估下面的论文想法：

研究问题：希望解决什么问题？
核心方法：准备采用什么机制？
预期新增贡献：相比已有研究，希望推进什么？
已知相关论文：标题或链接（可选）。
```

粗略想法也可以作为输入，评估时会说明尚待澄清或验证的部分。

## 输出

1. 当前判断及证据支持程度。
2. 最接近的工作、论文链接及其关系。
3. 问题设定、核心机制、假设和新增贡献的对照。
4. 影响结论的关键问题及改进建议。
5. 下一步推导、实验或检索建议。
6. 与现有证据相符的贡献表述。

## 使用条件

这是一个以指令为主的 Skill。完整文献评估需要运行环境具备联网检索和论文阅读能力，可获取资料的范围会影响评估结论。资料有限时，应说明证据范围并据此限定判断。

## 反馈与贡献

欢迎通过 Issues 或 Pull Requests 提交使用反馈、可公开的测试案例和改进建议。

## 许可证

MIT License，详见 [LICENSE](LICENSE)。
