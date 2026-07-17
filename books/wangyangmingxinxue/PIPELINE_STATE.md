# 蒸馏流水线状态

- [x] 阶段 0：整书理解
- [x] 阶段 0 用户确认
- [x] 阶段 1：五类候选提取
- [x] 阶段 1.5：三重验证
- [x] 阶段 1.5 用户轻确认
- [x] 阶段 2：RIA++ skills 构造
- [x] 阶段 3：交叉链接与词典
- [x] 阶段 4：压力测试
- [x] 阶段 5：精华文
- [x] 阶段 5：安装到项目 `.codex/skills/`

## 当前状态

流水线完成：6 个 skills 已通过独立盲测，并已安装到项目 `.codex/skills/`。

## 输入与审计

- 源文件：`wangyangmingxinxuesanbuzou/王阳明心学入门三步走（度阴山）.epub`
- 已转换文本：`/tmp/wangyangmingxinxuesanbuzou.txt`（约 519 千字；临时重建文件）
- 输出范围：全书方法论，覆盖修心、决策、领导、处事；传记与史料仅作案例和边界证据。

## 下一步

后续可用 `test-prompts.json` 接入 darwin-skill 做自动进化。
