# 如何使用创赛 Deck Preset

## 场景

参加竞赛 / 黑客松 / 创新赛 / 创业路演时，快速生成 10-12 页 PPT。

## 步骤

### 1. 准备项目信息

- 项目名
- Slogan（一句话价值主张，<= 15 字）
- 团队 / 学校
- 技术栈
- 核心功能（2-3 个）
- 创新点（3 个）
- 竞品（2-3 个）
- 演示截图（3-5 张）
- 数据成果（用户数 / 性能提升）
- 市场空间（TAM / SAM / SOM）
- 商业模式
- 路线图（3-6-12 个月）
- 团队照片 + 联系方式

### 2. 用 ppt-master 生成

把 presets/competition-deck-preset.md 喂给 ppt-master，说：

"基于此 preset 生成一个创赛 PPT，项目名 ___, Slogan ___, 团队 ___"

ppt-master 会按 11 页结构生成 PPTX 文件。

### 3. 手动填充内容

按 P1-P11 结构，把项目信息填充到对应页面。

### 4. 按视觉风格统一配色

- 主色：#1a1a2e（背景）+ #ef5350（强调）
- 辅色：#42a5f5（蓝）/ #66bb6a（绿）/ #ffa726（橙）
- 字体：思源黑体 / 微软雅黑
- 图表：用 visualization-mcp v0.2.0 生成

### 5. 按 checklist 逐项检查

见 presets/competition-deck-preset.md 的"参赛前 checklist"部分。

### 6. 演练

- 8 分钟演练 3 遍以上
- Q&A 预案 3 个问题

## 常见问题

### Q: 我的项目不适合 11 页结构怎么办？

A: 按实际内容删减页面，保持叙事逻辑（问题 -> 方案 -> 演示 -> 前景 -> 团队）。

### Q: 如何添加自己的 logo？

A: 在 P1（封面）和 P11（团队）添加 logo，保持视觉一致性。

### Q: 如何添加动效？

A: 建议不要添加动效（避免分散注意力），专注内容。

### Q: 如何导出 PDF？

A: 用 PowerPoint / WPS 导出 PDF，确保字体嵌入。

## 配套工具

- **visualization-mcp v0.2.0**: 生成 K 线 / 决策树 / combo 图（与视觉风格对齐）
- **ppt-master**: AI 驱动的 PPT 生成工作流

---

**Author**: RuiChencc
**Version**: 1.0.0
