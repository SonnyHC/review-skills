#欢迎大家，希望大家点点右上角Star

# Review Skills

面向生物医学材料综述的skill，帮助把分散文献组织成有明确问题、证据比较和转化分析的综述文章。

适用领域包括聚合物凝胶、水凝胶、可穿戴与植入式生物电子器件、肾脏健康、组织工程和药物递送。支持中文、英文和双语写作。

## 可以做什么

- 确定综述问题、范围与章节结构。
- 按机制、设计变量、应用和证据水平综合文献。
- 建立比较表、图件分工和信息层级。
- 修改目录式罗列、缺乏证据的声称及空泛展望。
- 检查科学逻辑、图表衔接和文稿导出版式。

## 安装到  Agent 全局

可以把仓库链接交给  Agent，并说明：

> 请把 https://github.com/SonnyHC/review-skills 中的 review-skills 安装到全局技能目录，保留完整的 SKILL.md、agents 和 references 文件夹。

也可以在终端安装：

```bash
mkdir -p "$HOME/.codex/skills"
git clone https://github.com/SonnyHC/review-skills.git "$HOME/.codex/skills/review-skills"
```

## 使用示例

```text
使用 review-skills，根据我提供的文献，设计“可注射水凝胶用于肾脏修复”的综述框架。
先明确综述问题、证据范围、章节逻辑以及图表分工。
```

```text
使用 review-skills 审查这段综述。重点检查机制解释、跨研究比较、证据边界和转化局限，
把原始研究结果、作者解释及未来研究建议分开。
```

```text
使用 review-skills 检查这篇综述的图表体系，找出重复图件、缺失的比较维度和信息层级问题。
```

## 文件结构

```text
SKILL.md
agents/openai.yaml
references/paper-study-notes.md
references/visual-layout-playbook.md
```

这是由说明文件组成的技能，无需配置专用 API key。检索文献、读取论文和编辑文稿时，需要运行它的智能体具备相应工具与文件访问权限。

