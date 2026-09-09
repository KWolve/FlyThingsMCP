# CHANGELOG — FlyThings MCP Release

> 本仓库为 **FlyThings MCP 公开版**（基础控件/UI 开发能力），供普通开发者使用。
> 当前版本：**v0.27.13-open**（2026-09-09）。版本号与内部开发版同步，内容为公开裁剪集。

## v0.27.13-open (2026-09-09) — 公开版发布

**本仓库内容范围**：
- ✅ 基础 UI 控件知识（`knowledge/uicontrols/`，22 篇：Button/TextView/ListView/Window/SlideWindow/PageWindow/CameraView/VideoView/CircleBar/Diagram/EditText 等 JSON 字段与代码 API）
- ✅ 通用开发机制（`knowledge/devflow/`：工程配置 package.properties/EasyUI.cfg、自定义字库、自定义控件、原型流程、代码骨架等）
- ✅ MCP 工具全家桶：项目创建/布局转换/预览/依赖管理/规范校验/多语言 i18n/自动化测试
- ✅ 项目模板（`templates/` 多平台 HelloWord）

**不包含**：平台专用深度方案（MPP/DVR/UVC 类）、客户定制方案、内部调试工具与完整开发史（见内部版）。

## 使用

1. 按 `README.md` 安装 MCP Server（完全本地部署，内置向量检索，零远程依赖）
2. AI 工具接入后直接对话开发：创建工程 → 布局 → 代码 → 编译 → 部署
3. 知识检索 `flythings_search`：控件字段/API/坑位问法直接命中 `knowledge/`

## 版本记录（公开摘要）

- **v0.27.x**：基础控件知识持续沉淀（控件字段全集、代码 API、层级规则、图标规范、json 必写键）；工程配置机制（rotateScreen/字库）；i18n 多语言工具链；自动化测试工具
- **v0.26 及更早**：本地化检索（bge-small-zh）、工程工具链（fui/fun）、模板与项目规范成型
