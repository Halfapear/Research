# VIKI-R 北邮组会 PPT 迭代 Prompt

目标：把论文 `VIKI-R: Coordinating Embodied Multi-Agent Cooperation via Reinforcement Learning` 做成北邮组会汇报 PPT。

必须遵守：

1. 先读论文与项目主页，提取“问题 -> benchmark -> 方法 -> 结果 -> 局限 -> 讨论”的汇报主线。
2. 优先参考用户指定模板 `北京邮电大学学术风PPT模板 01.pptx`：深绿色左右装饰栏、浅绿色上下边、网格纸背景、绿色标题线、绿色结论条。
3. 用户身份按北邮处理；不要使用泛化公司风、米色卡片风，也不要在用户指定模板时自行换成蓝白 BUPT 组会风。
4. 可加入固定美化背景：使用网上北邮甲子钟图片，处理为低饱和、低对比、强虚化、浅绿色遮罩的内容区底纹；背景必须很淡，不影响文字阅读。
5. 每页只能讲一个核心 claim，正文压缩到可讲述的短句；不要堆大段文字。
6. 每页必须有可展示的 proof object：论文图、流程图、指标条形图或结构化表。
7. 图文不得重叠，中文不得贴边、溢出或压线；导出后必须做 contact sheet 和布局检查。
8. 保留左屏讲稿思路：PPT 给老师看，文档给汇报人念；PPT 不塞完整段落。

推荐页序：

1. 封面：VIKI-R + 北邮计科院视觉元素。
2. 目录：研究背景、VIKI-Bench、VIKI-R 方法、实验与讨论。
3. 背景：多机器人协作的身体差异、视觉约束、并行执行。
4. VIKI-Bench：L1 / L2 / L3 三层接口。
5. 数据构建：templates -> GPT-4o -> checkers -> simulator -> human。
6. 方法：SFT warmup -> GRPO -> rewards。
7. 主结果：L1 强、L2 泛化难、L3 有改善。
8. 消融：step penalty 防止长计划作弊。
9. 训练观察：GRPO 放大已有能力，不是凭空创造能力。
10. 局限：sim-to-real、hierarchy、interpretability、cost。
11. 讨论：benchmark 是否真实、reward 是否可迁移、如何借鉴到云边研究。

验收标准：

- 11 页 PPTX 可打开。
- 每页渲染 PNG 预览，contact sheet 人眼检查。
- layout checker 为 0 error / 0 warning。
- PPTX 内 slide 数为 11，媒体文件非空。
- 输出文件命名清楚，例如 `VIKI-R_group_meeting_report_BUPT_iterated.pptx`。
