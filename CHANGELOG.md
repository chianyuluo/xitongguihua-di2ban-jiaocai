# 更新日志

遵循 [语义化版本](https://semver.org/lang/zh-CN/)。

## [0.2.1] - 2026-10-17

### 修正
- `02-siyaosu-coach.md` 重命名为 `02-siyaosu-framework-coach.md`，与 frontmatter `name` 及文档引用一致。
- `LICENSE` 换为 CC BY-NC-SA 4.0 官方全文（GitHub 可正确识别，原为 `NOASSERTION`）。

## [0.2.0] - 2026-10-17

### 新增
- **12 个教练模块**（`coaches/`），统一六段式：R 原文锚点 / I 考生卡点 / A1 正确过程 / A2 反例库 / E 分层追问 / B 边界。
  - `01-mcq-diagnoser` 选择题诊断
  - `02-siyaosu-framework-coach` 四要素框架
  - `03-process8-coach` 服务 8 过程
  - `04-lifecycle-coach` 服务生命周期 5 阶段
  - `05-planning-method-coach` 规划方法选型
  - `06-security-coach` 等保 2.0 与安全规划
  - `07-case-finding-coach` 案例找错
  - `08-case-calculation-coach` 案例计算
  - `09-essay-material-builder` 论文素材
  - `10-essay-framework-diagnoser` 论文框架诊断
  - `11-study-route-planner` 备考路线
  - `12-mistake-attribution-log` 错题归因
- `INDEX.md` 技能地图与触发速查。
- `examples/` 3 个"输入→输出"示例。
- `.github/workflows/release.yml`：打 tag 自动打包 zip/.skill。
- `LICENSE`（CC BY-NC-SA 4.0）。

### 变更
- `SKILL.md` 增加教练路由与"常见坑（Gotchas）"。
- `README.md` 重写：30 秒看懂、安装方式、教练清单。

## [0.1.0] - 2026-10-17

### 新增
- 24 章知识框架（`chapters/`）。
- `SKILL.md` 主索引；`cheatsheet.md`、`glossary.md`、`patterns.md`。
- 考纲/考频/必背/陷阱/策略等支撑文件。
- 初版 README 与版权声明。
