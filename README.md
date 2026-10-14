# 数学科研演示技能 · Math Research Presentations

帮助 AI 助手把数学研究讲清楚：从问题和障碍出发，解释机制与方法，再用有明确含义的证明或实验支持结论。

它不是固定的幻灯片模板，也不是科研结果生成器。适用于 Beamer、PowerPoint 或其他可编辑演示格式；不强制机构、作者、字号、页数、配色或排版工具。

## 能做什么

- 规划整场报告的论证顺序、逐页作用和讲述时间。
- 把定理的假设、结论、关键证明步骤和适用范围讲清楚。
- 区分严格结论、渐近分析、数值观察和待验证的解释。
- 在展示实验结果前定义数学问题，并准确解释误差、成本和失败情况。
- 处理 PDF 批注、保留修改依据，核对布局、导航、引用与讲稿。
- 通过试讲式检查发现缺失定义、跳步和重复内容。

示例重点是 **PPT 的编辑过程**：同一素材如何从过载页面变成有承接的两页、从孤立的图变成可解释的比较、从重复结尾变成有证据的收束。数学只作载体，不用一份新的数学讲义代替修改示范。详见 [修改前后对照](examples/before-after.md)。

## 文件与示例

| 文件 | 用途 |
|---|---|
| [SKILL.md](SKILL.md) | AI 助手读取的主规则 |
| [references/mathematical-argument.md](references/mathematical-argument.md) | 定理、证明、渐近规律与公式核对 |
| [references/numerical-evidence.md](references/numerical-evidence.md) | 数值实验的设置、误差和公平比较 |
| [references/revision-and-delivery.md](references/revision-and-delivery.md) | 批注修改、呈现、检查与公开发布 |
| [examples/](examples/README.md) | 独立编写的改前/改后示例、Beamer 源码、PDF 和讲稿 |

## 使用方式

将本仓库作为名为 `math-research-presentation` 的技能目录，放入你的 AI 助手所支持的技能位置。不同工具的安装位置可能不同；本仓库不自动修改任何本机设置。在支持命名技能调用的环境中，可这样请求：

```text
请用 $math-research-presentation 帮我整理这份数学报告。
听众了解基础数值分析，报告 20 分钟。请保留 Beamer 格式，
先检查论证顺序，再完成修改，并给出中文讲稿。
```

也可以直接让助手阅读 `SKILL.md`，再提供论文或幻灯片。

其他常用请求：

```text
只审阅，不改文件：哪些实验回答了不同的问题，哪些可以合并？
```

```text
把这份定理型报告改成 15 分钟版本，保留假设与关键证明思路。
将不影响后续论证的技术细节移入备份页。
```

```text
根据这份已保存批注的 PDF 修改对应源码。
不要把已删除的文字重新放进结论或讲稿。
```

## 原则与可配置项

科研准确性优先于叙事包装。内部停止不等于独立准确性；漂亮的图不替代明确的问题定义；成功的局部测试不等于整个方法已经验证。

个人偏好应由使用者另行提供，例如语言、配色、导航、讲稿和时长。本公开版本不包含任何人的私人偏好档案、对话记录、机构身份或未发表研究数据。示例使用独立写出的标准数学问题，没有复制私人演示文件。

本技能不会自动运行新的科研实验、创建后台任务或获得额外发布权限。实际排版与编译需要对应工具；示例 PDF 可直接阅读，源码编译方式见示例说明。

## English overview

This skill helps an assistant create, revise, and review mathematical research talks. It emphasizes dependency-driven exposition, explicit assumptions, meaningful proof sketches, interpretable numerical evidence, and verification of the delivered artifact. It preserves the user's format and does not require a fixed visual theme or another skill.

The examples are independent educational constructions, not anonymized research measurements. No personal conversation history or unpublished project data is included.

## License

MIT. See [LICENSE](LICENSE). The license covers the original files in this repository; it does not grant rights to third-party material supplied in future presentations.
