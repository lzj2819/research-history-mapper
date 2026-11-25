# Research History Mapper 使用说明

## 技能内容

- `SKILL.md`：技能入口、触发描述、七阶段总览和通用规则。
- `references/workflow.md`：各阶段的详细操作。
- `references/encoding.md`：8 类属性、矩阵、节点和演化关系。
- `references/experiment-and-evidence.md`：Experiment Skeleton、实验级缓存、统一 ID 与证据记录。
- `references/mpa.md`：Bibliometrix、Pajek/mpaR、SPC/SPLC 与双网络对照。
- `references/offline-display.md`：离线地图、热力图、论文卡、回链和性能验收。
- `references/evidence-and-reading.md`：证据核查与分层阅读。
- `assets/`：范围说明、登记表、演化边、实验骨架、证据、裁决、展示快照和报告模板。

## 安装

将 `research-history-mapper/` 整个目录复制到个人或项目的 `.claude/skills/` 下，保持 `SKILL.md` 位于该目录根部。

## 示例调用

- “请用 research-history-mapper 梳理强化学习在能源交易中的完整发展历史，输出中文报告、研究矩阵和骨干演化边。”
- “帮我搞懂图神经网络用于材料发现的来龙去脉，区分方法继承与普通基线比较。”
- “从近年的代表论文倒推，再从理论源头正推，整理这个研究方向的起源、分叉、融合、争议和研究空白。”

## 推荐输入

提供研究对象、核心任务、语种、截止日、可用数据库、已有文献目录和期望输出。缺少信息时，技能会先建立透明的范围协议，再推进检索和证据整理。
